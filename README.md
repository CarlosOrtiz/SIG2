## Proyecto Final Sig 2

## Pasos

#### 1.Cargar la base de datos en postgres
```bash
#Ubicación
@common/database/DB_Vr1.sql

#Comando Cmd
  cd C:\Program Files\PostgreSQL\12\bin

#Comando psql
  psql -U postgres -W -h localhost nombre_base < DB_Vr1.sql
```
#### 2.En GeoServer cargar los Shapefile, con PostGIS y tener en cuenta las coordenadas geográficas 3116

<p align="center">
  <img src="https://raw.githubusercontent.com/CarlosOrtiz9901/SIG2/develop/img/Coordenadas_Geograficas_3116.jpeg" width="700" alt="img" />
</p>

#### 3. Abril el archivo ProyectoFinal.html

```bash
#Ubicación
C:\Program Files (x86)\GeoServer 2.15.1\data_dir\www\ProyectoFinal.html
