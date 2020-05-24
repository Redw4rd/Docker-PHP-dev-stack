# PHP dev Stack Docker konténerekben

Az alábbi példa konfig futtatása esetén egy működőképes PHP fejlesztői környezet lesz elérhető. 

### Modulok
* Nginx
* PHP 7.4-FPM
* Mysql 8
* PHPMyAdmin

#Fejlesztői környezet elindítása:

Első dolgunk egy `web` elnevezésű alhálózat létrehozása melyet az alábbi paranccsal érhetünk el: `docker network create web`. 
Futassuk a gyökérben lévő Docker konfigurációs fájlt `docker-compose up -d`

### TODO
* vhost autómatizálás
* Környezet méretének csökkentése (alpine)