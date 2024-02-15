# Web-Application
Projekt i implementacja aplikacji webowej do sprzedaży biletóww kinie lub teatrze. | Розробка та впровадження веб-аплікації для продажу квитків у кіно чи театр.

# FILMBUY

## start service

```
docker compose up
``` 
*requires Windows Docker Desktop or manual installation and Visual Studio Code with extension Docker.
### Download Windows Docker Desktop: https://docs.docker.com/desktop/install/windows-install/
### Download Visual Studio Code: https://code.visualstudio.com/

## mongoDB (my custom database for application)

* dump db (save db)
    ```
    ./.internal/mongo_tools/mongodump.exe -d kino_db -o db
    ```
* restore/import db (load db)
    ```
    ./.internal/mongo_tools/mongorestore.exe -d kino_db db/kino_db
    ```
