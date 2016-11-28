# migracionOraPgsql
realiza el migrado de oracle a postgres de los siguientes objetos tablas, secuencias, indices, constraints y la información de las tablas 
Los comandos son :
java -jar MigrarSiso.jar -e //migra la estrucutra
java -jar MigrarSiso.jar -d 15 //extrae los datos de las tablas a archivo en la ruta /opt/filessicod y cantidad de tablas en hilos 
java -jar MigrarSiso.jar -l 20 //carga los datos desde los archivos planos a la base de datos  y cantidad de hilos
java -jar MigrarSiso.jar -v //verificar la cantidad de datos en ambas bases de datos por tabla y solo muestra las q sean diferentes
