# Proyecto Slim API – Ciberseguridad

API REST desarrollada con **Slim Framework 4** y **Docker**, pensada para prácticas didácticas en la asignatura de Ciberseguridad.

---

## Requisitos previos

- Docker
- Docker Compose

---

## Instrucciones de uso

### 1. Clonar el repositorio

```bash
git clone https://github.com/japinuela/ciberseguridad-PIII.git
cd ciberseguridad-slim-api
```

### 2. Configurar las variables de entorno en docker-compose.yml o .env

puede usar los valores de ejemplo incluidos:

```dotenv
DB_HOST=172.17.0.3
DB_PORT=3306
DB_NAME=ejemplo_db
DB_USER=alumno
DB_PASSWORD=alumno123
DB_CHARSET=utf8mb4
JWT_SECRET=clave_secreta_demo
```

### 3. Levantar el entorno

```bash
docker-compose up --build
```

> La primera vez puede tardar unos minutos mientras se construye la imagen y se instalan dependencias.

### 4. Acceder a la API

Abra su navegador en:

http://localhost:8888

---

## Nota para estudiantes

Este proyecto contiene una configuración mínima y funcional para prácticas locales.  
Pueden extenderlo con autenticación, validación de entradas, pruebas, middlewares y más.


