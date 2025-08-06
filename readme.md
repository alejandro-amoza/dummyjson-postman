# 🧪 DummyJSON API Testing (Postman)

Este proyecto contiene una colección de pruebas API usando Postman para la API pública [DummyJSON](https://dummyjson.com), cubre operaciones CRUD (sin autenticación) sobre usuarios y productos, con tests automatizados.

---

## 📦 Contenido

- Listado de usuarios (`GET /users`)
- Detalle por ID (`GET /users/:id`)
- Actualizar usuario (`PUT /users/:id`)
- Modificación parcial (`PATCH /users/:id`)
- Eliminar usuario (`DELETE /users/:id`)

- Listado de productos (`GET /products`)
- Detalle por ID (`GET /products/:id`)
- Actualizar producto (`PUT /products/:id`)
- Modificación parcial (`PATCH /products/:id`)
- Eliminar producto (`DELETE /products/:id`)

📄 Diseños de los CP disponibles en:
https://docs.google.com/spreadsheets/d/14_mix5PI5AwI25oh7e5Ec1dmpWA8sKArtYVzxJPopnY/edit?gid=0#gid=0

---

## 🔐 Autenticación

No requiere autenticación para estos endpoints.

---

## 📦 Endpoints testeados

- `GET /users`
- `GET /users/:id`
- `PUT /users/:id`
- `PATCH /users/:id`
- `DELETE /users/:id`
- `GET /products`
- `GET /products/:id`
- `PUT /products/:id`
- `PATCH /products/:id`
- `DELETE /products/:id`

---

## 📁 Estructura del proyecto

- `collections/`: colección principal exportada desde Postman  
- `environments/`: archivo de entorno con variables usadas  

---

## 🧪 Tests automáticos

Cada request contiene scripts en Postman para validar:  
- Códigos de estado HTTP  
- Datos esperados en las respuestas  
- Almacenamiento de variables para uso encadenado  

---

## 🚀 Cómo usar

1. Cloná este repo.  
2. Importá la colección y el entorno en Postman.  
3. Seleccioná el entorno `DummyJSON Local`.  
4. Ejecutá los requests según necesites.

---

## 📎 Fuente de la API

> https://dummyjson.com/docs

---

## 🙌 Autor  
Alejandro Amoza – QA Tester  
- [LinkedIn](https://www.linkedin.com/in/alejandro-amoza)  
- [Portfolio](https://alejandro-amoza.github.io/portfolio)  
