OBRAS PARTICULARES
==================

Sistema para la gestion de tramites de obras particulares.

Instalación y Uso
---

**Nota de uso:** Debemos tener instalado Git en el sistema.

##### Paso 1: Clonar el repositorio a nuestro sistema
    git clone https://github.com/UNPSJB/obras_particulares.git
    cd obras_particulares
    
##### Paso 2: Instalar lista de dependencias
    pip install -r requirements.txt
    
##### Paso 3: Realizar migraciones de aplicaciones
    python manage.py makemigrations app
    
##### Paso 4: Correr el código
    python manage.py runserver
    
##### Paso 5: Acceso al sistema
    Ir a http://localhost:8000
