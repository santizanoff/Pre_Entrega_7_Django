# Blog Django

Proyecto base de una aplicación web de blog desarrollada con Django.

## Descripción
Repositorio con la estructura inicial de Django y la app modular `posts`, integrando el punto de partida web del proyecto.

## Instalación y Ejecución

1. Clonar el repositorio:
```bash
git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>
2. Crear un entorno virtual:
python -m venv venv
3. Activar el entorno:
.\venv\Scripts\Activate

4. Instalar dependencias:
pip install -r requirements.txt
5. Configurar base de datos y ejecutar migraciones:
python manage.py migrate
6. Crear superusuario (opcional):
python manage.py createsuperuser
7. Ejecutar servidor de desarrollo:
python manage.py runserver