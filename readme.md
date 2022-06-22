### API sin JWT para marcas y modelos, el objetivo es que Azure entregue el token

```
npm install
```

```
cd nodejs-mysql && npm install && DEBUG=nodejs-mysql:* nodemon start
```

```
cd nodejs-mysql && npm install && DEBUG=nodejs-mysql:* npm start
```

## se debe importar el SQL a una BBDD SQL y configurar los datos en el archivo configs/config.js

## por el momento se añade archivo postman para usar, pero se puede hacer manual con las siguientes direcciones

```
http://localhost:3000/marcas
```
```
http://localhost:3000/modelos?id=5
```
