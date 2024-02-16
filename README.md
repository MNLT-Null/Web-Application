# Web-Application
Projekt i implementacja aplikacji webowej do sprzedaży biletóww kinie lub teatrze. | Розробка та впровадження веб-аплікації для продажу квитків у кіно чи театр.

# FILMBUY

## start service

```
docker compose up
``` 
*requires Windows Docker Desktop or manual installation and Visual Studio Code with extension Docker.
![image](https://github.com/MNLT-Null/Web-Application/assets/158077285/e461cf2a-b6cc-44c0-aa08-415d1ce216b2)
##1.Open terminal
##2.Paste code from "start service"
### Download Windows Docker Desktop: https://docs.docker.com/desktop/install/windows-install/
### Download Visual Studio Code: https://code.visualstudio.com/

## mongoDB (database commands for backup save and load)

* dump db (save db)
    ```
    ./.internal/mongo_tools/mongodump.exe -d kino_db -o db
    ```
* restore/import db (load db)
    ```
    ./.internal/mongo_tools/mongorestore.exe -d kino_db db/kino_db
    ```
