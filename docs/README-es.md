# 🐳 Docker Microservicios – Nginx + PHP

🌎 **Idiomas**  
🇧🇷 [Português](../README.md)  
🇺🇸 [English](./README-en.md)  
🇪🇸 Español (actual)

Proyecto práctico de **Docker y Microservicios**, desarrollado como parte de un desafío educativo de la **DIO**, con enfoque en el aislamiento de aplicaciones, independencia entre infraestructura y código, y buenas prácticas iniciales con contenedores.

---

## 📌 Sobre el proyecto
Este proyecto demuestra la creación de una aplicación web simple utilizando **Docker**, **Nginx** y **PHP**, organizada en contenedores.

El objetivo es aplicar conceptos fundamentales de **microservicios**, abstrayendo el entorno de ejecución de la aplicación y facilitando la portabilidad y replicación.

El desafío está basado en el proyecto de referencia **Toshiro Shibakita**, con adaptaciones y organización propias.

---

## 🧱 Arquitectura
- Contenedor Docker
- Servidor web **Nginx**
- Aplicación **PHP**
- Configuración personalizada de Nginx
- Estructura base para evolución en microservicios

---

## 🛠 Tecnologías utilizadas
- Docker
- Nginx
- PHP
- Linux
- Git y GitHub

---

## 📂 Estructura del proyecto
- Dockerfile        → Build de la imagen Docker
- nginx.conf        → Configuración de Nginx
- index.php         → Aplicación PHP
- system_data.sql   → Ejemplo de estructura de datos
- docs/             → Documentación multilingüe

---

## ▶️ Cómo ejecutar

### Requisitos previos
- Docker instalado  
https://docs.docker.com/get-docker/

### Pasos

1) Construir la imagen:
```bash
docker build -t nginx-php-app .

2) Ejecutar el contenedor:
docker run -p 8080:80 nginx-php-app

3) Acceder en el navegador:
http://localhost:8080

---

## ⚠️ Notas importantes
- Proyecto orientado a estudios y laboratorio
- No recomendado para producción sin ajustes de seguridad
- Ideal para comprender los fundamentos de Docker y microservicios

---

## 📚 Referencias
- Repositorio base (DIO):  
  https://github.com/denilsonbonatti/toshiro-shibakita

- Docker Docs:  
  https://docs.docker.com/

- Nginx Docs:  
  https://nginx.org/en/docs/

---

## 📄 Licencia
Proyecto libre para estudio y modificación.

---

## ⭐ Sobre este repositorio

Este proyecto forma parte de mi portafolio de estudios en Docker, Linux y DevOps, desarrollado durante mi formación y práctica continua con contenedores y arquitectura de aplicaciones.

### ✔ Competencias aplicadas
- Containerización con Docker
- Conceptos iniciales de microservicios
- Servidor web Nginx
- Aplicaciones PHP en contenedores
- Organización de proyectos para portafolio
- Control de versiones con Git
- Documentación técnica

Proyecto desarrollado con fines educativos y de portafolio.

