# seminari_flutter

## Referències

A continuació es llisten les fonts utilitzades per al desenvolupament d’aquest seminari de Flutter:

### Repositoris

- [Repositori backend (API)](https://github.com/BlauCamarasa/APIseminari_EA)  
- [Repositori frontend (Flutter)](https://github.com/BlauCamarasa/Seminari_flutter)

### Vídeos sobre Flutter

1. **Introducció breu a Flutter**  
   Una visió general curta per entendre què és Flutter:  
   [https://www.youtube.com/watch?v=lHhRhPV--G0](https://www.youtube.com/watch?v=lHhRhPV--G0)

2. **Exemple senzill amb codi explicat**  
   Vídeo amb explicacions de codi i creació d'una app bàsica:  
   [https://www.youtube.com/watch?v=D4nhaszNW4o](https://www.youtube.com/watch?v=D4nhaszNW4o)

3. **Rutes entre pàgines - Part 1**  
   [https://www.youtube.com/watch?v=RoGUVanZJss](https://www.youtube.com/watch?v=RoGUVanZJss)

4. **Rutes entre pàgines - Part 2**  
   [https://www.youtube.com/watch?v=_my1IHfn0xk&list=PL3nPgdhXQtHfFl-7fQRrzkKQbS5DPWl_x](https://www.youtube.com/watch?v=_my1IHfn0xk&list=PL3nPgdhXQtHfFl-7fQRrzkKQbS5DPWl_x)

### Suport addicional

- [ChatGPT](https://chat.openai.com/) per a la resolució de dubtes tècnics i conceptuals.





# Prova API

## Descripció
Una API bàsica desenvolupada en Node.js amb TypeScript, utilitzant Express i Mongoose per a la gestió de dades en MongoDB. A més, s'inclou documentació amb Swagger.

## Requisits previs
Abans d'executar el projecte, assegura't de tenir instal·lat:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Instal·lació
Clona el repositori i executa la següent comanda per instal·lar les dependències:

```sh
npm install
```

## Configuració
Crea un fitxer `.env` a la arrel del projecte i defineix les següents variables d'entorn//canviar les strings directament en el codi a les línies 16 (Port) i 69 (uri mongo) :
```env
MONGO_URI=mongodb://localhost:27017/la_teva_base_de_dades
PORT=9000
```

## Execució
Per iniciar l'API (tsc + cd ./build + node server.js):

```sh
npm start
```

## Documentació
Swagger està disponible a:
```
http://localhost:9000/api-docs
```

## Dependències Principals
- `dotenv`: Gestió de variables d'entorn.
- `mongodb` i `mongoose`: Base de dades MongoDB.
- `swagger-jsdoc` i `swagger-ui-express`: Generació de documentació.
- `express`: Framework per a l'API.

## Dependències de Desenvolupament
- `typescript`: Suport per a TypeScript.
- `@types/*`: Definicions de tipus per a biblioteques utilitzades.

## Video explicació del codi
https://youtu.be/Si-rIPn3PB8

## Fonts usades
Els exercicis dels seminaris anteriors (Mongoose i JavaScript) i chatGPT sobretot pel swagger.



