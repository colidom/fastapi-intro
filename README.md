# Instalación
```
pip install fastapi
```

# Servidor ASGI
```
pip install "uvicorn[standard]"
```

# Ejecución del servidor
_El parámetro --reload hará que recargue automáticamente el servicio cuando detecta un cambio en el código_

```
uvicorn main:app --reload
```

# Documentación interactiva de APIs
> http://127.0.0.1:8000/docs
