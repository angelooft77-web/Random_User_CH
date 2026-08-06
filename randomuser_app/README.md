# TRABAJOO EN CLASE 

Ejercicio realizado en la UPMH por **Angel Uriel Barrera Choreño**

Esta aplicacion se conecta ah la api de random.user 

# TABAJO EN CLASE

-Edad
-Direccion
-Nombre
-Genero
-Telefono

## Despliegue en Render

1. Asegúrate de haber subido este repositorio a Git (por ejemplo GitHub).
2. En Render, crea un nuevo **Web Service** apuntando al repositorio.
3. Render detecta `requirements.txt`. El servidor usará el `Procfile` incluido.

Comando `Procfile` usado:

`web: gunicorn randomuser_app.randomuser_app.app:app`

Si deseas probarlo localmente, instala dependencias y ejecuta:

```
pip install -r requirements.txt
gunicorn randomuser_app.randomuser_app.app:app
```

