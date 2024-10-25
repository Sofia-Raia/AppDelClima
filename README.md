﻿# IntegradorOrgEmp
## Grupo: CodeCrafters</>
### Integrantes:
- Sofia Raia (Product Owner)
- Martina Molina (Scrum Master)
- Ailen Carretero (Developer) 
- Ignacio Juarez (Developer) 
- Mariano Videla (Developer) 

Para el correcto funcionamiento de la App es necesario crear un archivo .env con una variable de entorno API_KEY.

Para correr la app necesitamos correr los comandos:

docker build -t my_python_app .   (esto se hace la primera ves que se corre)
docker run -it --env-file .env my_python_app  (Para que corra la app)
