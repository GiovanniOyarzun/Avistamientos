# Avistamientos 
1. Primero de todo comenzamos con el lab y nos ofrece las credenciales:
![image](https://github.com/user-attachments/assets/b91f10f5-c15e-4695-80d4-c342764a68b0)

2. ingresamos las credenciales y abrimos el cloud con la cuenta que nos ofrecieron, ingresamos al proyecto y creamos el bucket el cual tiene como nombre "giovanni-matias": 
![image](https://github.com/user-attachments/assets/ce678bb2-45d4-4f09-9669-c239d2a8cc60)

Aqui se puede ver como se creo el bucket: 
![image](https://github.com/user-attachments/assets/3d81eea6-6e40-4853-97b2-133b1c895430)

3. Seguimos con la creacion del dataset el cual tiene como nombre "ovni":
![image](https://github.com/user-attachments/assets/a2a05a2e-0f12-48ab-a506-92a4ddc301ec)
![image](https://github.com/user-attachments/assets/3590bc07-0962-4c5f-8e8d-c8fda5073ef4)

4. Ingresamos al dataprep y creamos un flow llamado Avistamientos:
![image](https://github.com/user-attachments/assets/2d8b062a-6b09-4040-87df-f1144cf2f719)

5. Cargamos el archivoi csv llamado ufo_sighting en el flow, en el cual lo tuvimos que trasformar de archivo xlsx a csv:
![image](https://github.com/user-attachments/assets/c9a7af8c-92af-4367-9e96-757f50e46d44)

Asi quedaria la estructura del flow: 
![image](https://github.com/user-attachments/assets/889f3269-d9e0-4331-9886-b89607800e87)

7. ingresamos al cvs y podemos observar que todos los datos se cargaron correctamente:
![image](https://github.com/user-attachments/assets/64a96e0f-cccf-4e64-be4b-d7a83fdb8d23)

8. Ahora tenemos que borrar todos los datos que esten en vacios o que afecten las tablas, en pocas palabras estamos preparando el archivo:
![image](https://github.com/user-attachments/assets/60d9313c-87f3-443c-ac98-60a848daea16)

Las tablas se deberian de ver de la siguiente manera luego de limpiarlas: 
![image](https://github.com/user-attachments/assets/9fc4cb6a-3dde-40c3-8b5b-36d45f5a8b98)

9. Lo siguiente seria darle a run y esperar a que los cambios se generen correctamente:
![image](https://github.com/user-attachments/assets/9c049603-c275-4644-a6f0-9240dcb094b8)

10. Tendremos que extraer este csv y tendremos que agregarlo a nuestro bucket llamado "giovanni-matias":
![image](https://github.com/user-attachments/assets/eac7becb-2751-4ff7-b7d3-c7d780e7ab36)

11. Para luego crear nuestra tabla llamada "avistamientos" en el dataset "ovni":
![image](https://github.com/user-attachments/assets/1e46bd2f-6d48-433f-a085-552db39c1018)

Vemos la vista previa y podemos observar que todos los datos se cargaron correctamente (tuvimos unos problemas con la tabla avistamientos y tuvimos que crear otra tabla):
![image](https://github.com/user-attachments/assets/e135b4ad-af57-4c4f-9541-7dae55ac0455)

12. Ahora pondremos las 3 consultas para ver si los datos estan correctos:
![image](https://github.com/user-attachments/assets/4b1a364c-6cdd-4a25-af6e-f63ecc3d0d42)
![image](https://github.com/user-attachments/assets/ad169881-b921-4b4c-820c-ad5c1fceb79d)
![image](https://github.com/user-attachments/assets/112dfe9b-1137-4d7a-bdd1-15dcd11ee72c)

13. luego de ejecutar las consultas estas las pasaremos a graficos en loocker studio:

consulta n1: 
![image](https://github.com/user-attachments/assets/a00c7d12-fbd6-462e-906c-9761f0d41b13)
consulta n2: 
![image](https://github.com/user-attachments/assets/a98acdc7-0899-4da0-984a-97e9e076335b)
consulta n3: 
![image](https://github.com/user-attachments/assets/ff761e12-19b8-4519-95d7-91e14256e324)





   


