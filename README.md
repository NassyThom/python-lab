# Nombre del Proyecto
Python-lab
Este proyecto está creado para comenzar en el mundo de python 3.12 con poetry

## Características
- 


## Requisitos

- Python >= 3.12.10
- Poetry >= 2.4.1

## Instalación



### Instalar dependencias

```bash
poetry install
```

### Activar el entorno virtual

```bash
poetry shell
```

> Alternativamente, puedes ejecutar los comandos con `poetry run`.

## Uso

Ejemplo de ejecución:

```bash
poetry run python main.py
```

O si el proyecto expone un script:

```bash
poetry run mi-comando
```

## Configuración

Describe las variables de entorno necesarias.

Ejemplo:

```bash
cp .env.example .env
```

Variables:

| Variable | Descripción | Requerida |
|----------|-------------|-----------|
| API_KEY | Llave de acceso | Sí |
| DEBUG | Modo desarrollo | No |

## Estructura del proyecto

```text
.
├── pyproject.toml
├── poetry.lock
├── README.md
├── src/
│   └── proyecto/
├── tests/
├── docs/
└── .env.example
```

## Desarrollo

Instalar dependencias de desarrollo:

```bash
poetry install --with dev
```

Ejecutar pruebas:

```bash
poetry run pytest
```

Ejecutar cobertura:

```bash
poetry run pytest --cov=src
```

Formatear código:

```bash
poetry run black .
```

Lint:

```bash
poetry run ruff check .
```

Corregir automáticamente:

```bash
poetry run ruff check . --fix
```

Verificar tipos:

```bash
poetry run mypy src
```

## Gestión de dependencias

Agregar una dependencia:

```bash
poetry add requests
```

Agregar una dependencia de desarrollo:

```bash
poetry add --group dev pytest
```

Actualizar dependencias:

```bash
poetry update
```

## Publicación (opcional)

Construir el paquete:

```bash
poetry build
```

Publicar:

```bash
poetry publish
```


## Autor

- Nazario Tomas Hernandez
