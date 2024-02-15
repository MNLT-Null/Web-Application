# Web-Application
Projekt i implementacja aplikacji webowej do sprzedaży biletóww kinie lub teatrze. | Розробка та впровадження веб-аплікації для продажу квитків у кіно чи театр.

# KINO|FILMBUY

## start service

```
docker compose up
``` 
*requires Windows Docker Desktop or manual installation. Download: https://docs.docker.com/desktop/install/windows-install/

## mongoDB (my custom database for application)

* dump db (save db)
    ```
    ./.internal/mongo_tools/mongodump.exe -d kino_db -o db
    ```
* restore/import db (load db)
    ```
    ./.internal/mongo_tools/mongorestore.exe -d kino_db db/kino_db
    ```
