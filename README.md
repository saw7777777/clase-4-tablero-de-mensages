# Django Base - Task List App

Este proyecto es una aplicación básica de Django para gestionar una lista de tareas.

## Estructura del Proyecto

- `manage.py`: Script para tareas administrativas de Django.
- `db.sqlite3`: Base de datos SQLite.
- `django_base/`: Configuración principal del proyecto.
- `tasks/`: Aplicación para gestionar tareas.
- `templates/`: Plantillas HTML.

## Instalación

1. Clona el repositorio.
2. Instala las dependencias:
   ```sh
   pip install -r requierenst.txt
   ```
3. Realiza las migraciones:
   ```sh
   python manage.py migrate
   ```
4. Crea un superusuario (opcional, para acceder al admin):
   ```sh
   python manage.py createsuperuser
   ```
5. Ejecuta el servidor de desarrollo:
   ```sh
   python manage.py runserver
   ```

## Uso

- Accede a la lista de tareas en [http://localhost:8000/](http://localhost:8000/).
- Administra tareas desde el panel de administración en [http://localhost:8000/admin/](http://localhost:8000/admin/).

## Archivos principales

- `tasks/models.py`: Modelo `Task` con campos `title`, `created_at`, `updated_at`.
- `tasks/views.py`: Vista basada en clase `TaskListView` para mostrar las tareas.
- `tasks/urls.py`: Rutas de la app de tareas.
- `templates/tasks_list.html`: Plantilla para mostrar la lista de tareas.

## Requisitos

- Python 3.9+
- Django 5.2.6

## Licencia
