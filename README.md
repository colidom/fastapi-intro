# Instalación

```
pip install fastapi
```

# Servidor ASGI

```
pip install "uvicorn[standard]"
```

# Ejecución del servidor

El comando **uvicorn main:app** hace referencia a:

```

main: el archivo main.py (el "módulo" de Python).
app: el objeto creado dentro de main.py con la línea app = FastAPI().
--reload: hace que el servidor se reinicie después de cambios en el código. Usar sólo para desarrollo.
```

# Documentación interactiva de APIs

> http://127.0.0.1:8000/docs
