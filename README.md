Este es un trabajo que realicé para una capacitación en Quales de Analista de Datos. El trabajo consistía en realizar **ETL**s a partir de unos csv a una base de datos SQL y realizar un reporte.

![image](https://github.com/user-attachments/assets/53ce6e09-f123-4fd5-b42d-28d5951e41e9)

La parte más interesante del trabajo en realidad fue el trabajo sobre ETLs, a partir de los csv se llegó a estas tablas para realizarlo:

![image](https://github.com/user-attachments/assets/b1e1326f-77ff-41e3-bb7f-68f1ba915e9d)

Cada carga y transformación se realizó en **SQL**, con **stored procedures** que se proporcionan en los archivos .bak.

Finalmente, se obtiene un modelo estrella, bajo una arquitectura OLAP, listo para ser consumido por PBI:

![image](https://github.com/user-attachments/assets/ecd353a9-31ef-42e4-ab22-6c5d0c14ec0e)
