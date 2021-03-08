## Proyecto Final Sig 2

## Pasos


#### 1. Tener instalado Postgres, PostGIS y pgAdmin4
```bash
#Url para descargar postgresql
https://www.postgresql.org/download/
```
#### 2. Crear una base de datos y agregarle la extención PostGIS
```bash
#Comando Cmd
  cd C:\Program Files\PostgreSQL\12\bin

#Comando para abril la terminal psql
./psql.exe -h localhost -U postgres -p5432

#Comandos en psql
CREATE DATABASE final_project;
GRANT ALL PRIVILEGES ON DATABASE final_project TO postgres;
\c final_project;
CREATE EXTENSION postgis;
```
#### 3. Descomprimir el archivo DB_Vr2.rar para cargar la base de datos en postgres usando pgAdmin4
```bash
#Ubicación del archivo DB_Vr2.rar
@common/database/DB_Vr2.rar
```
#### 3. En GeoServer cargar los Shapefile, con PostGIS y tener en cuenta las coordenadas geográficas 3116

<p align="center">
  <img src="https://raw.githubusercontent.com/CarlosOrtiz9901/SIG2/develop/public/img/Coordenadas_Geograficas_3116.jpeg" width="700" alt="img" />
</p>

#### 4. Abril el archivo ProyectoFinal.html

```bash
ProyectoFinal.html
```

<p align="center">
  <img src="https://raw.githubusercontent.com/CarlosOrtiz9901/SIG2/develop/public/vista.png" width="1000" alt="vista" />
</p>
