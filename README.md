# Unidad 3 - Laboratorios

## Lab 00

1. Se crea el cluster EMR con la configuración indicada:

Se elige el software:
![image](https://user-images.githubusercontent.com/46629861/170850103-a2bc45db-b99c-4ab0-853f-1b28920039f0.png)

Se pone el bucket s3:
![image](https://user-images.githubusercontent.com/46629861/170850116-57b4601f-232c-4a86-8a92-61196aea87b8.png)

Se cambia el tipo de instancias. En mi caso elegí on-demand para no depender de disponibilidad de instancias on-spot:
![image](https://user-images.githubusercontent.com/46629861/170850140-38136775-7646-4df0-9775-d94502c21c6e.png)

El cluster creado:
![image](https://user-images.githubusercontent.com/46629861/170850177-27e8be9b-af5a-43fb-8ab3-8f5235f08075.png)

2. Acceso a Hue:

![image](https://user-images.githubusercontent.com/46629861/170850323-bcc1d7b7-f9d8-4d93-8396-1ee280210b2b.png)

3. Conexión a Jupyter y ejecución de notebook:
![image](https://user-images.githubusercontent.com/46629861/170850342-8dd7d8a2-774c-4a44-9555-86667c304cad.png)

4. Conexión y ejecución a Zeppelin:

![image](https://user-images.githubusercontent.com/46629861/170850358-25992ef4-1913-424a-b8d2-112f262f12cc.png)


## Lab 01

1. Lo primero es hacer el tutorial de https://github.com/ST0263/st0263-2022-1/blob/main/Big%20Data/01-hdfs/hdfs-scripts.txt luego de hacer SSH al nodo master:

Se instala git, se clone el repo del profe y se pone la carpeta 'datasets' en root (`/`):

Se sube el dataset de gutenberg-small a hdfs:

![image](https://user-images.githubusercontent.com/46629861/170851419-61768ff6-951f-4f3e-b7a1-3d76f2d019c0.png)

Se suben todos los datasets:

![image](https://user-images.githubusercontent.com/46629861/170851483-06ff7fed-982e-4fa5-9947-a63efab93dea.png)

