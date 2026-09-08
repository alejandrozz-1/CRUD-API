# FakeStore CRUD API

## Descripción

Este proyecto consiste en la realización de **40 consultas CRUD** sobre una API externa utilizando **FakeStoreAPI** y **Postman**. El objetivo del ejercicio ha sido practicar las operaciones básicas de una API REST: creación, lectura, actualización y eliminación de recursos.

API utilizada: **https://fakestoreapi.com/**

## Herramientas utilizadas

- Postman
- FakeStoreAPI
- JSON
- HTTP Methods (GET, POST, PUT, DELETE)

---

# Operaciones realizadas

## CREATE (POST)

Se realizaron 10 peticiones para crear nuevos productos en la API.

### Acciones realizadas

1. Crear producto "Portátil Lenovo".
2. Crear producto de electrónica.
3. Crear producto de informática.
4. Crear producto de accesorios.
5. Crear producto de oficina.
6. Crear producto personalizado.
7. Crear producto de prueba.
8. Crear producto tecnológico.
9. Crear producto adicional.
10. Crear producto final.

**Endpoint utilizado**

```http
POST /products
```

**Resultado:** La API devolvió un código `201 Created` junto con los datos del producto creado.

---

## READ (GET)

Se realizaron 10 consultas para obtener información de productos, categorías, usuarios y carritos.

### Acciones realizadas

1. Obtener listado completo de productos.
2. Obtener producto con ID 1.
3. Obtener producto con ID 5.
4. Obtener producto con ID 10.
5. Obtener listado de categorías.
6. Obtener productos de la categoría electrónica.
7. Obtener productos de la categoría joyería.
8. Obtener listado de usuarios.
9. Obtener usuario con ID 1.
10. Obtener listado de carritos.

**Endpoints utilizados**

```http
GET /products
GET /products/1
GET /products/5
GET /products/10
GET /products/categories
GET /products/category/electronics
GET /products/category/jewelery
GET /users
GET /users/1
GET /carts
```

**Resultado:** La API devolvió respuestas satisfactorias con código `200 OK`.

---

## UPDATE (PUT)

Se realizaron 10 peticiones para actualizar productos existentes.

### Acciones realizadas

1. Actualizar producto ID 1.
2. Actualizar producto ID 2.
3. Actualizar producto ID 3.
4. Actualizar producto ID 4.
5. Actualizar producto ID 5.
6. Actualizar producto ID 6.
7. Actualizar producto ID 7.
8. Actualizar producto ID 8.
9. Actualizar producto ID 9.
10. Actualizar producto ID 10.

**Endpoint utilizado**

```http
PUT /products/{id}
```

**Resultado:** Se modificaron los datos enviados en el cuerpo de la petición y la API devolvió los valores actualizados con código `200 OK`.

---

## DELETE (DELETE)

Se realizaron 10 peticiones para eliminar recursos de la API.

### Acciones realizadas

1. Eliminar producto ID 1.
2. Eliminar producto ID 2.
3. Eliminar producto ID 3.
4. Eliminar producto ID 4.
5. Eliminar producto ID 5.
6. Eliminar producto ID 6.
7. Eliminar producto ID 7.
8. Eliminar producto ID 8.
9. Eliminar carrito ID 1.
10. Eliminar carrito ID 2.

**Endpoints utilizados**

```http
DELETE /products/{id}
DELETE /carts/{id}
```

**Resultado:** La API devolvió una respuesta exitosa indicando que el recurso había sido eliminado.

---

# Resumen

| Operación | Cantidad |
|-----------|----------|
| CREATE (POST) | 10 |
| READ (GET) | 10 |
| UPDATE (PUT) | 10 |
| DELETE (DELETE) | 10 |
| **TOTAL** | **40** |

## Conclusión

Mediante este ejercicio se han practicado las principales operaciones CRUD sobre una API REST utilizando Postman. Se verificó el funcionamiento de los métodos HTTP POST, GET, PUT y DELETE, interpretando las respuestas de la API y gestionando recursos como productos, categorías, usuarios y carritos dentro de FakeStoreAPI.
