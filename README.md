![image](https://github.com/user-attachments/assets/0c105bf0-4f3e-41ec-aaa2-752b6b957594)


CULTIVO DE PLANTAS FRUTALES EN TIERRA DEL FUEGO
---------
Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

Politécnico Malvinas Argentinas. https://politecnico.tdf.gob.ar/

---------------
Bloque: Desarrollo de Sistemas de IA      Año: 2024

Autor: ORTEGA, Emilio

--------------

💡

# Indice

- [Informe del Proyecto](#Informe)
- [Objetivo del Proyecto](#Objetivo)
- [Metodología](#Metodología)
- [Conclusiones](#Conclusiones)
- [Descripción sobre origen y tipo de datos](./docs/Descripcion%20de%20los%20Datos.md)
- [Modelo y Analisis de Resultados](./reports/Reporte%20de%20Resultados.md)
- [Video explicativo del proyecto](/references/Emilio_ORTEGA_Congelamiento_del_Suelo_31_07_24_Aprendizaje_automatico.mp4)
  

-------------
# Informe:

El cultivo de plantas frutales en Tierra del Fuego presenta desafíos únicos debido al clima extremo de la región, caracterizado por bajas temperaturas, fuertes vientos y una temporada de crecimiento corta. Sin embargo, hay especies frutales que pueden adaptarse bien, como las grosellas, frambuesas y moras. Estas especies toleran el frío y requieren técnicas de cultivo específicas para maximizar la producción en este entorno.

Entre las prácticas recomendadas, el uso de sistemas de riego controlados y la protección contra el viento son esenciales. Además, es común implementar métodos de protección contra heladas y técnicas de fertilización específicas para mejorar la resistencia de las plantas. En Tierra del Fuego, la selección de variedades resistentes y el monitoreo constante de factores como la disponibilidad de agua y la aparición de plagas son fundamentales para el éxito del cultivo frutal.

**[⬆ Volver al Indice](#Indice)**



-------------
# Objetivo:

El objetivo del cultivo de plantas frutales en Tierra del Fuego es desarrollar un sistema productivo eficiente y sostenible que permita optimizar la producción de frutas adaptadas al clima extremo de la región, como grosellas y frambuesas. Este objetivo incluye mejorar la resistencia de las plantas frente a condiciones adversas, como bajas temperaturas y vientos fuertes, y asegurar una calidad de cosecha adecuada mediante técnicas de riego, fertilización y control de plagas. La meta final es contribuir a la autosuficiencia alimentaria local, generar ingresos para los agricultores y promover el desarrollo agrícola en áreas marginales.


**[⬆ Volver al Indice](#Indice)**



----------------
# Metodología:

El proyecto seguirá los siguientes pasos:
1. Recopilación de Datos: Se recopilarán datos históricos de variables meteorológicas (como temperatura, humedad, precipitación, etc.) y características del suelo de una o varias ubicaciones relevantes.
2. Preprocesamiento de Datos: Se realizará un proceso de limpieza y preparación de los datos para eliminar valores atípicos, manejar datos faltantes y convertir los datos en un formato adecuado para el entrenamiento del modelo.
3. Selección de Características: Se identificarán las características más relevantes para la predicción del congelamiento del suelo utilizando técnicas de selección de características.
4. Entrenamiento del Modelo: Se entrenarán varios modelos de aprendizaje automático, como modelos de regresión, clasificación o métodos basados en árboles de decisión, utilizando los datos preparados.
5. Evaluación del Modelo: Se evaluará el rendimiento de los modelos utilizando métricas adecuadas, como precisión, sensibilidad y especificidad, utilizando conjuntos de datos de prueba.
6. Optimización y Ajuste del Modelo: Se realizarán ajustes en los hiperparámetros y la arquitectura del modelo para mejorar su rendimiento.
7. Despliegue y Monitoreo: Una vez que se haya seleccionado el modelo final, se implementará en un entorno de producción y se monitoreará su rendimiento continuamente para realizar ajustes según sea necesario.

**[⬆ Volver al Indice](#Indice)**



-----------------------
# Conclusiones:

El cultivo de plantas frutales en Tierra del Fuego representa una oportunidad para desarrollar una agricultura adaptada a condiciones climáticas extremas, permitiendo la diversificación de la producción local y el fortalecimiento de la autosuficiencia alimentaria. Si bien la región enfrenta desafíos como las bajas temperaturas, vientos fuertes y una temporada de crecimiento limitada, la selección de especies resistentes, como las grosellas y frambuesas, junto con la implementación de técnicas de riego, protección contra el viento y manejo de plagas, han demostrado ser efectivas. 

En conclusión, con una planificación adecuada y el apoyo de tecnologías específicas, el cultivo frutal en Tierra del Fuego puede ser sostenible y rentable, beneficiando tanto a los productores locales como a la economía regional.


**[⬆ Volver al Indice](#Indice)**


----------------------------------------------------------------
 Instalación
 ________________________________________________________________
 

[-] Instalación del Servicio de FastApi para poder ejecutar el Sistema Experto

1- ejecutar simbolo de sistemas como administrador

2- ir hasta la direccion de descarga:

ej: C:\Users\lenovo\Downloads\FastAPI_Kine_Node>

4- ejecutamos el comando para windows:

python -m venv fastapi-env

En caso que de, dentro de la terminal de windows salga un msj de error que no se reconoce el comando cmlet python instalar el paquete Git desde https://git-scm.com/downloads/win

5- Ya creado el entorno, hay q activarlo:

fastapi-env\Scripts\activate
6- si todo sale bien, en el promp tendras algo asi:

(fastapi-env) C:\Users\lenovo\Downloads\FastAPI_Kine_Node>

7- ahora hay q hacer las instalaciones para q funcione fastapi

8- ir a: fastapi.tiangolo.com --> buscar los comandos!!!!

pip install "fastapi[standard]"

pip install "uvicorn[standard]"
9- Instalamos nodejs desde https://nodejs.org/en

9- desde nuestra ruta en la consola, en mi caso:

(fastapi-env) C:\Users\lenovo\Downloads\GIT_Politecnico\FastAPI_Kine_Node>

Ejecutamos los siguientes comandos en este orden:

cd frontend
cd frontend
npm install
npm start
se nos abre el chrome en la ruta http://localhost:3000/ - pero no mostrara la base de conocimiento sin antes realizar los pasos del 10 en adelante!

10- ahora abrir vscode --> Abrir la carpeta completa "FastAPI_Kine_Node"

11- seleccionar el archivo "main.py" y abrir la consola "Terminal"

12- Levantar el servidor:

Ejecutar el siguiente comando:

uvicorn main:app --reload
13- Por defecto tendria que cargar el servicio en la direccion IP:

 http://localhost:3000/


14- Poner la direccion IP junto con el Numero de puerto en el navegador, esta ruta es un localhost, por ende tambien es lo mismo poner http://localhost:3000/ Con esto ya tendria que abrir la Interfaz del Sistema Experto
