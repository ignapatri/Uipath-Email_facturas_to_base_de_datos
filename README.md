# Uipath Email Facturas to Base de Datos  
  
Este bot de Uipath filtra todos los correos sin leer, de la bandeja de entrada, por el asunto  
y cuando encuentra uno que el asunto contiene la palabra "factura" se salva el adjunto en una carpeta  
ya que es una factura, acto seguido, movemos el correo a una carpeta de outlook llamada gestionados.    
Creamos un datatable, recorremos todas las facturas que tenemos en el directorio, las abrimos una a una  
extraemos los datos que necesitamos de cada una y los añadimos al Datatable.  
Movemos la factura a otro directorio llamado Facturas procesadas.  
Nos conectamos a nuestra base de datos, ya sea sql server, mysql etc e introducimos los datos en ella  
desde el Datatable.  
  
![](https://github.com/ignapatri/Uipath_Email_Facturas_to_Base_de_Datos/blob/main/Email_facturas_database.png)
