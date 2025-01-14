# Proppify Backend

Proppyfy es una plataforma de gestión de propiedades que permite a los usuarios gestionar, listar, y alquilar propiedades de manera eficiente. Este repositorio contiene el backend de la aplicación, construido con Django y Django REST Framework (DRF).

## Requisitos

- **Python** >= 3.8
- **Django** >= 4.0
- **djangorestframework** 
- **PostgreSQL** - **psycopg2-binary**
- **djangorestframework-simplejwt**
- **django-cors-headers** 
- **pillow**


## Instalación

### 1. Clonar el Repositorio


git clone https://github.com/iangenta/proppify_backend.git
cd proppyfy_backend

### 2. Crear entorno virtual
python -m venv venv
 En Windows:
venv\Scripts\activate
 En macOS/Linux:
source venv/bin/activate

### 3. Instalar dependencias
pip install -r requirements.txt


## Ramas y convenciones
El flujo de trabajo de ramas sigue el siguiente patrón:

main: Esta es la rama principal. Aquí se fusionan las características finalizadas y las correcciones de bugs estables.

test: rama intermedia entre development y main, en esta se espera probar el flujo y someter a pruebas previo al pase a producción.

development: Rama de desarrollo donde se integran nuevas características y correcciones antes de ser fusionadas en main.

Para agregar nuevas funcionalidades o características, crea una rama siguiendo este patrón:
git checkout -b feature/nueva-caracteristica

Para arreglar bugs, crea una rama con el siguiente patrón:
git checkout -b fixbugs/bug-description

Una vez que hayas completado la implementación de la característica o arreglo, realiza un pull request hacia la rama development.

