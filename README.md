# MarketLink – MongoDB Schemas & Queries

Este repositorio contiene los **scripts de base de datos MongoDB** utilizados en el proyecto **MarketLink**.  
Incluye la creación de la base de datos, colecciones y consultas básicas empleadas durante el desarrollo y las evidencias del Trabajo B2 (TB2).

---

## Contenido

- `create_db_and_collections.mongosh`  
  Creación de la base de datos `miPrimeraDB` y de la colección `usuarios`.

- `insert_usuarios.mongosh`  
  Inserción de documentos de ejemplo en la colección `usuarios`.

- `queries_usuarios.mongosh`  
  Consultas básicas para listar, filtrar y contar usuarios.

---

## Cómo ejecutar los scripts

- Conectarse a MongoDB usando `mongosh`:
   
```bash
mongosh "mongodb://admin:TU_PASSWORD@localhost:27017/miPrimeraDB?authSource=admin"
```

- Ejecutar los scripts de forma manual copiando y pegando los comandos, o bien usando:

```
mongosh < create_db_and_collections.mongosh
mongosh < insert_usuarios.mongosh
mongosh < queries_usuarios.mongosh

```
