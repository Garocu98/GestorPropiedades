# 🏠 Gestor de Propiedades

Gestor de Propiedades es una aplicación web desarrollada en **PHP** que permite administrar propiedades inmobiliarias de forma sencilla. Incluye funcionalidades como creación, edición, eliminación y visualización de anuncios, con un panel de administración y manejo de imágenes.

## 🚀 Características

- CRUD de propiedades (Crear, Leer, Actualizar, Eliminar)
- Panel de administración
- Subida y gestión de imágenes
- Autenticación básica (inicio y cierre de sesión)
- Estructura modular con archivos reutilizables
- Diseño responsive 

## 🛠️ Tecnologías utilizadas

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Apache / XAMPP / Laragon

## 📂 Estructura del proyecto (actual)

GestorPropiedades/
├── admin/ # Panel de administración
├── build/ # Archivos compilados / distribución (CSS, JS)
├── imagenes/ # Imágenes del proyecto
├── includes/ # Funciones y archivos reutilizables
├── src/ # Código fuente principal
├── anuncios.php
├── blog.php
├── cerrar-sesion.php
├── index.php
└── ...
> ⚠️ *La estructura está en proceso de mejora para una organización más clara y escalable.*

## ⚙️ Requisitos

- PHP >= 7.4
- MySQL
- Servidor local (XAMPP, WAMP, Laragon, etc.)
- Navegador web moderno

## 🔧 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Garocu98/GestorPropiedades.git
Mueve el proyecto a tu servidor local:

htdocs/GestorPropiedades
Crea una base de datos en MySQL.

Importa el archivo .sql o configura las tablas manualmente.

Configura la conexión a la base de datos en el archivo correspondiente dentro de includes/.

Inicia el servidor y accede desde el navegador:

http://localhost/GestorPropiedades

## 🔐 Credenciales de acceso

Usuario: admin
Contraseña: admin
✏️ Cambia estas credenciales en producción.

## 📄 Licencia

Este proyecto es de uso educativo y personal.
Puedes añadir una licencia si planeas distribuirlo públicamente.

## ✨ Autor

Garocu98
GitHub: @Garocu98
