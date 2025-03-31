# Proyecto30032025Marketing
 
**Autor**: [Óscar Pacheco Fernández]  
 
## 📌 Descripción  
Breve descripción del proyecto. Explica su propósito, funcionalidades principales y cualquier información relevante que los usuarios deban conocer antes de empezar.  
 
Ejemplo:  
*"Este proyecto es un análisis de datos para un [departamento de marketing]. Permite [limpiar datos], [analizar datos] y está construido con [python y diferentes librerías]."*  
 
## 🚀 Características  
- **Característica 1**: Lectura del archivo.  
- **Característica 1**: Limpieza de datos.  
- **Característica 1**: Análisis de datos.  
 
## 🛠️ Tecnologías Utilizadas  
- Lenguaje: [Python]  
- Frameworks/Librerías: [Pandas, Numpy, Matplotlib, Seaborn]  
 
## 📦 Instalación  
Pasos para instalar y configurar el proyecto localmente:  
 
1. Clona el repositorio:  
git clone https://github.com/pachecoofdzz/Proyecto30032025Marketing
 
Al observar los archivos aparecen algunos errores pero al descargarlo en local y ejecutarlo funciona de manera correcta
 
 
# ¿CÓMO HE LIMPIADO LOS DATOS?
 
1. **Importo todas las librerías**  
![](imagenesReadme/foto1.PNG)
2. **Cargo los datos**  
![](imagenesReadme/foto2.PNG)
3. **Muestro las primeras filas del DataFrame**  
![](imagenesReadme/foto3.PNG)
4. **Muestro información del DataFrame**  
![](imagenesReadme/foto4.PNG)
5. **Muestro estadísticas descriptivas del DataFrame**  
![](imagenesReadme/foto5.PNG)
6. **Elimino filas con valores NaN (Not a Number)**
![](imagenesReadme/foto6.PNG)
7. **Elimino filas duplicadas en el DataFrame**  
![](imagenesReadme/foto7PNG)
8. **Muestro cantidad de filas y columnas del DataFrame limpio**
![](imagenesReadme/foto8.PNG)  
9. **Corrijo formato de fechas**
![](imagenesReadme/foto9.PNG)  
10. **Paso los campos que deberían ser numéricos a `float`**  
![](imagenesReadme/foto10.PNG)
11. **Los campos de texto los paso a minúscula y quito espacios de principio y fin** 
![](imagenesReadme/foto11.PNG) 
12. **Compruebo los valores únicos**  
![](imagenesReadme/foto12.PNG)
13. **Manejo valores atípicos usando cuartiles**  
![](imagenesReadme/foto13.PNG)
14. **Creo la columna `DuracionCampaña` que es `End_Date` menos `Start_Date`**  
![](imagenesReadme/foto14.PNG)
15. **Creo la columna `ROIajustado` que es `ROI` menos `DuracionCampaña`**  
![](imagenesReadme/foto15.PNG)
16. **Creo la columna `EficienciaCosto` que es `Revenue` menos `Budget`**  
![](imagenesReadme/foto16.PNG)
17. **Verifico las columnas creadas anteriormente**  
![](imagenesReadme/foto17.PNG)
18. **Creo la columna `EstacionInicio` que es el `Quarter` de `Start_Date`**  
![](imagenesReadme/foto18.PNG)
19. **Creo la columna `MesInicio` que es el mes de `Start_Date`**  
![](imagenesReadme/foto19.PNG)
20. **Creo la columna `ROIdiario` que es `ROI` dividido entre `DuracionCampaña`** 
![](imagenesReadme/foto20.PNG) 
21. **Compruebo los valores nulos de las nuevas columnas**  
![](imagenesReadme/foto21.PNG)
22. **Compruebo los tipos de datos de las nuevas columnas**  
![](imagenesReadme/foto22.PNG)
23. **Saco la media de todas las columnas numéricas**  
![](imagenesReadme/foto23.PNG)
24. **Saco la mediana de todas las columnas numéricas**  
![](imagenesReadme/foto24.PNG)
25. **Exporto el DataFrame y lo paso a CSV**
![](imagenesReadme/foto25.PNG)