# Documentació del projecte

## Diaris App

Aquesta aplicació web permet visualitzar les notícies de diferents diaris, com La Vanguardia, El País i El Nacional (encara que en el meu cas només funciona La Vanguardia). Pots optar per utilitzar el mode remot, on les notícies s'obtenen directament de la web de La Vanguardia, o el mode local, on es fa servir un XML descarregat.

### Requisits previs

- Python 3.x instal·lat al teu sistema. Pots descarregar Python des del [lloc web oficial](https://www.python.org/downloads/).
- PIP, el gestor de paquets de Python, instal·lat amb la teva distribució de Python. Normalment, ja ve inclòs amb la instal·lació de Python.

### Configuració

1. Clona aquest repositori al teu sistema local.
2. Crea un entorn virtual per al projecte per mantenir les dependències aïllades. Pots seguir [aquesta guia](https://docs.python.org/3/library/venv.html) per aprendre com crear un entorn virtual.
3. Activa l'entorn virtual.
4. Instal·la les dependències necessàries executant la següent comanda en la teva terminal:
- pip install -r requirements.txt


## Ús

### Mode Local

Si vols utilitzar el mode local per obtenir les notícies:

1. Descarrega l'arxiu de La Vanguardia i col·loca'l a la carpeta arrel del projecte.
2. Executa l'aplicació amb la comanda:
python app.py local

### Mode Remot

Per utilitzar el mode remot i obtenir les notícies directament de la web de La Vanguardia:

1. Assegura't que tens accés a Internet.
2. Executa l'aplicació amb la comanda:
flask run --port=5001


L'aplicació estarà ara disponible a l'adreça `http://localhost:5001` en el teu navegador web.


## Recursos addicionals

- [Documentació de Flask](https://flask.palletsprojects.com/en/2.1.x/)







