# Albuaves

Albuaves es un proyecto educativo (pet-project) diseñado para enseñar al alumnado los conceptos fundamentales de una solución software completa basada en arquitectura Cliente-Servidor. El proyecto implementa una aplicación de gestión de aves utilizando tecnologías modernas y accesibles.

### Descripción general

Albuaves plantea de manera sencilla todas las partes implicadas en una solución software real:

- Base de datos: Persistencia de datos con SQLite
- Backend: API REST desarrollada en PHP
- Frontend: Interfaz de usuario para consumir la API
- Gestión de datos: Herramientas visuales para administrar la base de datos

## Tecnologías Utilizadas

### Base de Datos

SQLite 3

- Sitio web: https://www.sqlite.org
- Licencia: Dominio Público (Public Domain)
- Descripción: SQLite3 es una base de datos ligera y sin servidor, ideal por su rapidez y simplicidad.

DB Browser for SQLite (SQLiteBrowser)
  
- Sitio web: https://sqlitebrowser.org
- Repositorio: https://github.com/sqlitebrowser/sqlitebrowser
- Licencia: MPL-2.0 y GPL-3.0
- Descripción: Herramienta visual de código abierto para crear, diseñar y editar bases de datos SQLite.

Backend
PHP

- Sitio web: https://www.php.net
- Licencia: PHP License v3.01
- Versión recomendada: 7.4 o superior
- Descripción: PHP es fácil de usar, rápido para crear sitios web y tiene gran soporte y compatibilidad.
  
PHP SQLite3 Extension

- Documentación: https://www.php.net/manual/es/book.sqlite3.php
- Licencia: PHP License v3.01
- Descripción: Extensión nativa de PHP para trabajar con bases de datos SQLite 3.

Formato de Datos
JSON (JavaScript Object Notation)

- Sitio web: https://www.json.org
- Especificación: RFC 8259
- Repositorio del desarrollador principal: https://github.com/douglascrockford
- Licencia: Dominio Público
- Descripción: Formato ligero de intercambio de datos, fácil de leer y escribir para humanos y máquinas.

### Requisitos del Sistema

- Sistema Operativo: Linux (Ubuntu), también compatible con Windows y macOS
- PHP: Versión 7.4 o superior
- SQLite: Versión 3.x
- Servidor Web: Apache o PHP Built-in Server
- Herramientas opcionales: DB Browser for SQLite para gestión visual

### Instalación

En Linux (Ubuntu)

1. Actualizar el sistema e instalar dependencias
   
```bash
sudo apt update;
sudo apt install sqlitebrowser php-sqlite3 php-cli;
```

2. Verificar instalación

#### Verificar PHP
php --version

#### Verificar extensión SQLite3
php -m | grep sqlite3

#### Verificar SQLite
sqlite3 --version


## Imagenes del proyecto 

#### Activar el sh
![Como ponerlo en marcha](/Imagenes/Marcha.png)

#### Puesto en marcha 
![Puesto en marcha](/Imagenes/Res.png)