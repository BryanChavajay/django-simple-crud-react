# DJANGO SIMPLE CRUD WITH REACT

## Requisitos previos
1. Nodes.js >=18.12.1
2. Pnpm >=8.6.5
3. Python >= 3.8.0

## Instalación
*NOTA:* Se recomienda trabajar una consola para el frontend y otra para el backend

### Frontend
Entre a la carpeta *client* desde la consola e
instale las dependencias con pnpm
   
```bash
pnpm install
```

### Backend
Cree un entorno virtual
```bash
pip install virtualenv

python -m venv venv
```

Activa el entorno virtual
En windows
```bash
.\venv\Scripts\activate
```

En MacOs/Linux
```bash
source venv/bin/activate
``` 

Dentro del entorno virtual instale las depencias
```bash
pip install -r requirements.txt
```

Realiza las migraciones de la DB
```bash
python manage.py makemigrations
```

Aplica las migraciones
```bash
python manage.py migrate
```

## Correr los servidores
Para levantar el servidor de desarrollo del frontend
```bash
pnpm run dev
```

Para levantar el servidor del backend
```bash
python manage.py runserver
```

## Notas adicionales
1. El frontend se ejecuta en el puerto *5173*
2. Si necesita ver la documentación del backend visite http://127.0.0.1:8000/tasks/docs/