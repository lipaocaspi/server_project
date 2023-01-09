# server_project

- Instalar [json-server](https://github.com/typicode/json-server).
```
npm install --save json-server
```
- Editar package.json y agregar la IP del ordenador al script. Ejemplo:
```
"run-server": "json-server --host 192.168.1.37 db.json"
```
- Correr el servidor.
```
npm run run-server
```
