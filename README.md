# TodoXamarin

# Taller en clase 

## Integrantes
* Jorge Alba
* Juan Bolaños
* Bernabé Dávila
* Byron Huaraca

## Instalación de sqlite-net-pcl

Como primer paso se debe realizar la instalación de sqlite-net-pcl, se debe ejecutar la consola de administrador de paquetes y se colocal el comando que ofrece la documentación oficial:

![image](https://user-images.githubusercontent.com/66254573/150614672-e3ab39f0-88f1-412b-8812-a2c077c314d2.png)

Una vez instaldo dicho paquete; se deben generar las carpetas del proyecto que son: Views, Models y Data; también se crean los archivos AsyncLazy.cs, Constants.cs como se muestra en la siguiente figura:

![image](https://user-images.githubusercontent.com/66254573/150614823-c03a5a88-def5-40a5-85d3-41876962dcbd.png)

Dentro de cada carpeta se crea los archivos necesarios y el codigo correspondiente:

![image](https://user-images.githubusercontent.com/66254573/150614883-171f9e64-a4fc-46ef-94a9-3f72bc649932.png)

A continuación se muestra un ejemplo del codigo correspondiente a la carpeta de Views -> TodoItemPage.xaml:

![image](https://user-images.githubusercontent.com/66254573/150614963-8830e7ed-15bd-4098-862c-8ffe76e19004.png)

Cuando todo el codigo sea implementado correctamente se debe realizar la referencia del paquete de sqlite-net-pcl en el archivo Todo.csproj, la cual permite que se haga uso de las funcionalidades delpaquete instalado.

![image](https://user-images.githubusercontent.com/66254573/150615073-11960617-86ef-49f7-a0c0-87ff8dece480.png)


