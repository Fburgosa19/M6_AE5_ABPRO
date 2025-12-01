# Plataforma de Eventos

Una plataforma web para la gestión y registro de eventos, desarrollada con Django.

## Descripción

Este proyecto es una aplicación web que permite a los usuarios registrarse, crear eventos y gestionar su participación en los mismos.

## Características

- Autenticación de usuarios (login/logout)
- Registro de nuevos usuarios
- Creación y registro de eventos
- Base de datos SQLite

## Tecnologías

- **Backend**: Django
- **Base de Datos**: SQLite
- **Frontend**: HTML/CSS

## Estructura del Proyecto

```
Plataforma_eventos/
├── eventos/              # Aplicación principal
├── Plataforma_eventos/   # Configuración del proyecto
├── manage.py            # Script de gestión de Django
└── db.sqlite3           # Base de datos
```

## Instalación

1. Clonar el repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Aplicar migraciones: `python manage.py migrate`
4. Ejecutar servidor: `python manage.py runserver`

## Uso

Accede a la aplicación en `http://localhost:8000`

## Autor

Ejercicio grupal - M6_AE5_ABPRO
