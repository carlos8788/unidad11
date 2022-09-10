## Despliegue de apps Spring boot en Heroku

1. Crear cuenta en heroku.com y github.com
2. Crear el archivo `system.properties` en el proyecto con el contenido:
"""
java.runtime.version=17
"""
3. Tener configurado git en la pc
4. Subir el proyecto a github desde IntelliJ IDEA desde la VCS > Share project on GitHub
5. Desde Heroku, crear app y elegir método Github y buscar el repositorio subido
6. Habilitar deploy automatico y ejecutar el deploy
