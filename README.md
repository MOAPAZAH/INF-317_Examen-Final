# INF-317_Proyecto Final
Sistemas En Tiempo Real Y Distribuido - Inf-317

Proyecto de Integración de Datos con Talend
Este proyecto utiliza Talend Enterprise Data Integration para cargar datos desde archivos de texto y Excel a bases de datos SQL Server y MySQL.

1. Carga desde Archivo de Texto:

  - Se creó el archivo cine.txt, delimitado por comas, para cargar datos a las bases de datos.
  - Se establecieron conexiones a SQL Server (examenfinal) y MySQL (prueba).
  - Se utilizó un espacio de trabajo en Talend para conectar el archivo de texto a ambas bases de datos, creando las tablas correspondientes (dbo.cine en SQL Server y cine en MySQL).
  - 
2. Carga desde Archivos Excel:
  - Se creó un archivo prueba.xlsx, que contiene cuatro tablas a insertar en las bases de datos.
  - Se reutilizaron las conexiones existentes para insertar las tablas persona y ticket de manera individual.
  -También se empleó tMap para insertar las tablas pelicula y sala desde Excel a ambas bases de datos.
  - Cada etapa del proceso se probó con éxito, garantizando la correcta integración de los datos en las bases de datos especificadas.


