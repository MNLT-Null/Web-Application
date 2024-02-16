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
### 7. Move back to Docker and click on port 8001:8001
![image](https://github.com/MNLT-Null/Web-Application/assets/158077285/946ffbf8-b823-42e6-b51b-03e017f7db78)

## Admin Menu
### If you want access to Admin menu you need to sing in with:
#### Login: admin
#### Password: admin
![image](https://github.com/MNLT-Null/Web-Application/assets/158077285/c87cdfe6-0de3-4ef9-9e6a-33f39ef2fa97)



## mongoDB (database commands for backup save and load)

* dump db (save db)
    ```
    ./.internal/mongo_tools/mongodump.exe -d kino_db -o db
    ```
* restore/import db (load db)
    ```
    ./.internal/mongo_tools/mongorestore.exe -d kino_db db/kino_db
    ```
