# Sisteme-de-transport

## Descriere

Această aplicație permite gestionarea unui sistem de transport public. Utilizatorii pot vizualiza informații despre stațiile de autobuz, traseele disponibile și orarele de sosire ale autobuzelor. De asemenea, utilizatorii pot căuta trasee între două stații și pot vizualiza informații despre autobuzele care circulă pe un anumit traseu.
Interfața text a aplicației este implementată în Python, iar datele sunt stocate într-o bază de date MySQL.

## Rulare cod

1. Clonează proiectul de pe GitHub:
    ```
    git clone https://github.com/dvmizew/Sisteme-de-transport.git
    ```

2. Navighează în directorul proiectului:
    ```
    cd Sisteme-de-transport
    ```

3. Instalează dependențele Python pentru a putea rula aplicația:
    ```
    pip install -r requirements.txt
    ```

## Utilizare

1. Importă baza de date:
    ```
    mysql -u username -p database_name < db.sql
    ```

2. Cum se rulează aplicația:
    ```
    python main.py
    ```