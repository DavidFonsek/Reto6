# Reto6
# ST0256 Tópicos Especiales en Telemática

## Estudiante:
- Nombre: David Fonseca Lara
- Correo: dfonsecal@eafit.edu.co

## Profesor:
- Nombre: Álvaro Ospina
- Correo: aeospinas@eafit.edu.co

# Reto 6 - Hive y Spark
## Cluster de Amazon EMR
Este es el cluster de Amazon EMR que se utilizó para el desarrollo del reto 5. El cluster fue creado con las indicaciones del
[Lab 0](https://github.com/st0263eafit/st0263-241/blob/main/bigdata/00-lab-aws-emr/Install-AWS-EMR.pdf)

1.Primero creé en el HDFS la carpeta donde iban a estar los datos en el CSV
![](./Images/HiveCreadoHDFS.png)

2. Subí el archivo CSV en el HDFS para ser leído en por Hive
![](./Images/ArchivoSubido.png)

3. Creé la tabla interna en Hive con los datos en HDFS
![](./Images/ComandoCrearTabla.png)

4. Esta es una vista de la tabla hdi que son los datos del CSV en el S3 observados desde el Hive
![](./Images/DatosEnLaDB.png)

5. Subí el archivo CSV en el S3 para ser leído en por Hive
![](./Images/DatosS3.png)

6. Esta es una vista de la tabla hdi2 que son los datos del CSV en el S3 observados desde el Hive
![](./Images/DatosTablaExterna.png)

7. Cree una tabla para otro CSV alojada en el S3
![](./Images/CreacionTablaExpo.png)

