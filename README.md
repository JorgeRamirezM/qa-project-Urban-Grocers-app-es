# Urban Grocers App - QA Project

Este proyecto es una aplicación diseñada para realizar pruebas de calidad (QA) y asegurar el correcto funcionamiento de un sistema relacionado con "Urban Grocers".

## Estructura del Proyecto

### Archivos y Directorios Principales

-   **.idea**: Archivos de configuración del IDE (por ejemplo, PyCharm).
-   **.pytest_cache**: Caché generada por pytest para mejorar el rendimiento en las pruebas.
-   **.venv**: Entorno virtual de Python que contiene las dependencias del proyecto.
-   **configuration.py**: Archivo que gestiona configuraciones clave del proyecto.
-   **create_kit_test.py**: Script para ejecutar pruebas relacionadas con un "kit".
-   **data.py**: Archivo encargado de manejar los datos del proyecto.
-   **sender_stand_request.py**: Archivo que gestiona solicitudes HTTP (para interacción con una API).
-   ****pycache****: Archivos compilados de Python generados automáticamente.

### Tecnologías Utilizadas

-   **Python**: Lenguaje de programación principal del proyecto.
-   **pytest**: Framework de pruebas utilizado para automatizar y gestionar las pruebas.
-   **Requests**: Biblioteca de Python para realizar solicitudes HTTP.

### Instrucciones de Instalación

1.  Clonar el repositorio del proyecto:
    
    `git clone <URL_DEL_REPOSITORIO>`
    
2.  Navegar al directorio del proyecto:
    
    `cd qa-project-Urban-Grocers-app-es`
    
3.  Crear un entorno virtual y activarlo:
    
    `python -m venv .venv` `source .venv/bin/activate # En Windows: venv\Scripts\activate`
    
4.  Instalar las dependencias del proyecto:
    
    `pip install requirements`
    

### Cómo Ejecutar el Proyecto

1.  Asegúrate de estar en el entorno virtual (`.venv`).
    
2.  Ejecutar las pruebas con pytest:
    
    `pytest`
    
3.  Modifica los scripts (`create_kit_test.py`, `sender_stand_request.py`) para personalizar las pruebas según sea necesario.

### Lista de comprobación de pruebas
![](https://i.ibb.co/60SVcw8s/lista-de-comprobacion.png)

### Contribuciones

Si deseas contribuir, por favor sigue los pasos:

1.  Realiza un fork del proyecto.
    
2.  Crea una rama con tus cambios: `git checkout -b mi-rama`
    
3.  Envía un pull request describiendo tus modificaciones.