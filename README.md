# Sistema Web de Pedidos para Cafetería

Proyecto desarrollado con Django para gestionar productos,
usuarios y pedidos de una cafetería.

## Tecnologías

- Python
- Django
- SQLite
- HTML
- Bootstrap
- Pillow
- Git
- GitHub
- GitHub Actions

## Funcionalidades

- Inicio y cierre de sesión
- Usuarios
- Categorías
- Productos con imágenes
- Control de stock
- Pedidos
- Administración
- Control de acceso

## Instalar el proyecto en una nueva computadora

### 1. Clonar repositorio

git clone URL_DEL_REPOSITORIO

### 2. Entrar a la carpeta

cd cafeteria_django

### 3. Crear entorno virtual

python -m venv entorno

### 4. Habilitar scripts en PowerShell

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process

### 5. Activar entorno

.\entorno\Scripts\Activate.ps1

### 6. Instalar dependencias

pip install -r requirements.txt

### 7. Ejecutar migraciones si existen pendientes

python manage.py migrate

### 8. Ejecutar servidor

python manage.py runserver

### 9. Abrir navegador

http://127.0.0.1:8000/
