[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=fastAPISemillero&metric=coverage)](https://sonarcloud.io/summary/new_code?id=fastAPISemillero)

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=fastAPISemillero)](https://sonarcloud.io/summary/new_code?id=fastAPISemillero)

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/summary/new_code?id=fastAPISemillero)

# Comandos
## Instalar dependencias
`pip install --no-cache-dir --upgrade -r requirements.txt`
## Ejecutar el servicio
`uvicorn app.main:app --host 0.0.0.0 --port 8000`
## Ejecutar pruebas unitarias
`python -m unittest discover tests`
## Compilar Docker
`docker build -t devco/fast-api-example:latest .`
