# E-Health-Team

**Nombre del proyecto:** Plataforma de unificación y automatización de seguimiento médico.

**Descripción del proyecto:** Plataforma que unifica y automatiza el protocolo de seguimiento médico, esto siendo el proceso de toma de análisis y recibimiento de tratamiento que normalmente lleva mucho tiempo con el procedimiento actual del seguro social. Mediante una I.A. y una página web se determina el seguimiento que se le debe de dar a cada paciente y así evitamos intermediarios innecesarios. 

**Link de TikTok:**

**Diagrama de Azure:** ![Diagrama de Azure](https://user-images.githubusercontent.com/87103059/127761360-e4f56d53-eded-44e1-ba73-31aaba21d592.jpeg)

**SLA Compuesto:**

**TCO 3 años:**

**Precio total al mes:**

TODOS LOS PRECIOS AQUÍ ESTABLECIDOS SE MUESTRAN EN PESOS MEXICANOS (MXN)

![detecciones en wexico](https://user-images.githubusercontent.com/87103059/127759384-5867c223-f614-4c41-9610-9a539ad5ce7a.png)
Datos recabados de: http://www.imss.gob.mx/conoce-al-imss/memoria-estadistica-2020 Capitulo VI. Salud Pública 

En México se detectan aproximadamente 70 millones de casos de enfermedades como: sífilis, tuberculosis, cáncer cérvico uterino, diabetes, cáncer mamario, etc. Al año en el seguro social, sumamos 10 millones más de casos para tener un margen de error considerable y esta cantidad (80 millones) al dividirla entre los 12 meses del año nos da un aproximado de 7 millones de casos detectables al mes.  
Por lo que al mes en el servicio de Azure Cognitive Service el costo sería el siguiente: 
![precio text](https://user-images.githubusercontent.com/87103059/127761291-67d154f3-fcb4-49a0-aef8-70c6d62df9a1.png)


Al tener en cuenta la página web que usarán los doctores, tenemos que tener en cuenta que serán miles, quizá millones en todo el país, por lo que tenemos con la opción de más potencia que nos ofrece Azure en app service. Además, utilizamos como sistema operativo Linux para ahorrar dinero y que el costo mensual sea inferior. 

![precio app service](https://user-images.githubusercontent.com/87103059/127759438-4897e0f3-907d-4eb3-86f8-e5fcdf8ce21a.png)

Utilizamos una base de datos en PostgreSQL para utilizar archivos de diferentes tipos en la base de datos

![precio posgre sql](https://user-images.githubusercontent.com/87103059/127761083-41ded442-ba9f-429a-9ac1-1ed77a5a11b0.png)


**Tiempo sin disponibilidad a un año:**

**Que te parecio el evento:**

