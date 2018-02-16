
# Clasificacion de invetario con la metodologia ABC
Esta aplicacion consiste en mostrar la metodologia abc en base al costo, demanda, ingreso.
#### Para ejecutar el contenedor docker backend
```
docker-compose run --rm --service-ports backend -bash
python src/manage.py runserver 0.0.0.0:8000
```

#### Para ejecutar el contenedor docker base de datos
```
docker-compose run --rm database
docker-compose exec database psql -U postgres template1
template1=# create database inventory_master;
```


## Clasificacion de invetario por Costos
<img src="https://github.com/limbertlopezlaime/ClasificacionInventarioABC/blob/master/public/media/costo1.png"/>
<img src="https://github.com/limbertlopezlaime/ClasificacionInventarioABC/blob/master/public/media/costo2.png"/>

## Clasificacion de invetario por Demanda
<img src="https://github.com/limbertlopezlaime/ClasificacionInventarioABC/blob/master/public/media/demanda1.png"/>
<img src="https://github.com/limbertlopezlaime/ClasificacionInventarioABC/blob/master/public/media/demanda2.png"/>
