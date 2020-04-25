# JSON API Flask con SQLAlchemy

## Crear ambiente virtual para python
```commandline
sudo apt install python3-env
python3 -m venv venv
```

## Activar ambiente virtual
```commandline
source venv/bin/activate
```

## Instalar paquetes necesarios
```commandline
pip install -r requeriments.txt
```

## Crear base de datos SQLite
```commandline
python build_database
```

## Ejecutar servidor

```commandline
python server.py
```

## Homepage
`http://localhost:5000/`

## API REST
`http://localhost:5000/api/ui/`