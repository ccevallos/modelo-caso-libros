# modelo-caso-libros

El archivo **modeloIA1.ipynb** contiene el modelo generado por el sistema IACT (**I**nteligencia **A**rtificial para la gestión de la **C**apacidad **T**ecnológica)

En la carpeta **demanda** se encuentra el archivo CSV con el detalle de la carga transaccional medida para el caso de Administración de Libros.

En la carpeta **capacidad** se encuentran los datos de las métricas tomadas del uso de los recursos durante la carga transaccional. A continuación se detalla cada archivo:
   - monitoreo_memoria.csv, tiene el monitoreo de memoria en la máquina virtual java del servidor de aplicaciones.
   - srvapp.csv, tiene la información consolidada de uso de recursos del computador en el que se encontraba el servidor de aplicaciones WildFly.
   - srvapp.zip, contine las métricas en bruto recolectadas por Pandora Software Agent del computador en el que se encontraba el servidor de aplicaciones WildFly.
   - srvbdd.csv, tiene la información consolidada de uso de recursos del computador en el que se encontraba el servidor de base de datos PostgreSQL.
   - srvbdd.zip, contine las métricas en bruto recolectadas por Pandora Software Agent del computador en el que se encontraba el servidor de base de datos PostgreSQL.
