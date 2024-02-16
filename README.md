# Web-Application
Projekt i implementacja aplikacji webowej do sprzedaży biletóww kinie lub teatrze. | Розробка та впровадження веб-аплікації для продажу квитків у кіно чи театр.

# FILMBUY

## start service

```
docker compose up
``` 
*requires Windows Docker Desktop or manual installation and Visual Studio Code with extension Docker.

## Instructions
### 1. Download Windows Docker Desktop: https://docs.docker.com/desktop/install/windows-install/ ;
### 2. Install Docker and open. You can skip registration;
### 3. Download Visual Studio Code: https://code.visualstudio.com/ ;
### 4. Install Visual Studio Code. Drag and drop folder with project in VSCode;
### 5. Open terminal in Visual Studio Code;
### 6. Paste code from "start service" and press Enter.
![image](https://github.com/MNLT-Null/Web-Application/assets/158077285/e461cf2a-b6cc-44c0-aa08-415d1ce216b2)

## mongoDB (database commands for backup save and load)

* dump db (save db)
    ```
    ./.internal/mongo_tools/mongodump.exe -d kino_db -o db
    ```
* restore/import db (load db)
    ```
    ./.internal/mongo_tools/mongorestore.exe -d kino_db db/kino_db
    ```
