[![](https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg)](https://cloud.ibm.com)
[![Platform](https://img.shields.io/badge/platform-nodejs-lightgrey.svg?style=flat)](https://developer.ibm.com/node/)
[![](https://img.shields.io/discord/734849667174498465?logo=discord)](https://discord.gg/Q9At74C)

# Desafio 02 | Tortuga Code

- [1. Acerca de Tortuga Code](#1-acerca-de-tortuga-code)
- [2. Reto de negocio](#2-reto-de-negocio)
- [3. Objetivo](#3-objetivo)
- [4. Desarrollando la solución](#4-desarrollando-la-solución)
  - [4.1. Pre-requisitos](#41-pre-requisitos)
  - [4.2. Resumen de las tareas](#42-resumen-de-las-tareas)
  - [4.3. Desarrollo](#43-desarrollo)
- [5. Envío](#5-envío)
- [6. Sobre la evaluación](#6-sobre-la-evaluación)

## Para Ayudarte

- [Material de apoyo](#material-de-apoyo)
- [Solución de problemas](#solución-de-problemas)
- [Licencia](#licencia)


## 1. Acerca de Tortuga Code

Tortuga Code – es una plataforma de educación on-line y gratuita para todas y todos, enfocada en el aprendizaje de programación y tecnología.

<div align="center">
    <a href="https://youtu.be/r1umCMJIBMk">
       <img width="50%" src="./Docs/Images/apr-02-es.png" alt='video'>
    </a>
</div>

## 2. Reto de negocio

El desafío que propone Tortuga Code tiene que ver con la usabilidad del portal y cómo las personas podrían sacarle mayor provecho al mismo. Hoy en día en el portal se pueden encontrar diferentes contenidos técnicos como cursos, blogs y videos los cuales pueden ser buscados y consumidos sin ningún criterio de personalización.
Lo que busca  Tortuga Code, teniendo en cuenta el potencial que hoy ofrece la Inteligencia Artificial, es ofrecerle a los usuarios una experiencia diferente donde puedan encontrar el contenido más adecuado para ellos. Para eso, se quiere crear un catálogo de contenido donde el usuario, en base a sus skills y conocimiento previo, pueda encontrar recomendaciones y contenido personalizado.

Los participantes deberán utilizar la tecnología de IBM Watson Studio en IBM Cloud para crear este catálogo de contenido y así ayudar a los estudiantes de Tortuga Code a encontrar el material más adecuado, según su experiencia y conocimiento previo.


## 3. Objetivo

En este desafío, TORTUGA CODE traerá herramientas de IBM, Cloud Pak for Data, para construir un modelo basado en el aprendizaje automático e integrarlo con una solución de asistente virtual, centrado en la recomendación de contenidos y cursos personalizados. Tu tarea será mejorar un modelo ya proporcionado e integrar los diversos servicios involucrados en esta solución!

La idea esencial del **Desafío 2** es crear un modelo basado en machine learning capaz de identificar las principales deficiencias del estudiante, permitiendo una tutoría personalizada del estudiante. Para simplificar el problema, se centrarán en los datos de tres asignaturas del curso de Tecnología: Data Science, Backend Web y Front end Web . En este repositorio el archivo ``notebook.ipynb`` contiene un notebook completo para Watson Studio ya con una solución básica lista, totalmente funcional. Puedes (y se recomienda) mejorar el modelo para obtener una mayor puntuación :)

## 4. Desarrollando la solución

### 4.1. Pre-requisitos

Para poder realizar este desafío, se deben cumplir con los siguientes requisitos previos:

- Regístrate en [Maratón Behind the Code](https://maratona.dev/es) y confirma tu e-mail de registro.
- Tener una cuenta en [IBM Cloud](https://ibm.biz/registro-maratona), que puede ser una cuenta GRATUITA o de pago (no es necesario registrarse en el evento con el mismo correo electrónico utilizado para crear tu cuenta IBM Cloud).

### 4.2. Resumen de las tareas

1. Instanciar Watson Studio (Cloud Pak for Data as a Service) en IBM Cloud.
2. Instanciar Cloud Object Storage en IBM Cloud.
3. Crear un proyecto y cargargar el notebook de este en este repositorio (``notebook.ipynb``) en Watson Studio.
4. Leer y ejecutar las instrucciones contenidas en el Notebook ``notebook.ipynb``.
5. Descargar el archivo de resultado `results.csv` y el notebook de trabajo `notebook.ipynb`
6. Acceder a https://tortuga.maratona.dev/, probar y envíar su solución.

### 4.3. Desarrollo

La idea esencial del **Desafío 2** es crear un modelo basado en machine learning capaz de identificar las principales deficiencias del estudiante, permitiendo una tutoría personalizada del estudiante. Para simplificar el problema, se centrarán en los datos de tres asignaturas del curso de Tecnología: Data Science, Backend Web y Frontend Web. 

En este repositorio el archivo ``notebook.ipynb`` contiene un notebook completo para Watson Studio ya con una solución básica lista, totalmente funcional. Puedes (y se recomienda) mejorar el modelo para obtener una mayor puntuación :)

En el video a continuación, se explica en detalle todo el proceso de desarrollo de la solución. Si eres un principiante en el mundo de la ciencia de datos y  *machine learning*, te recomendamos que veas el video para responder cualquier pregunta sobre este desafío.

**¡ATENCIÓN!** UPDATE EN EL PROCESO DE ENTREGA

Vea el video https://youtu.be/U_8brUf5Xuc con las nuevas instruciones (solo para envíos realizados después del 3 Septiembre)

NOTA: A continuación se muestra el video tutorial, que aún puede ser útil. También demuestra la integración del modelo creado con Watson Machine Learning. Después del 2 de septiembre de 2020, Watson Machine Learning se ha actualizado y este paso ya no es necesario para enviar el desafío.

<div align="center">
    <a href="https://youtu.be/i8RM8lpGD_E">
       <img width="50%" src="./Docs/Images/tuto-02-es.png" alt='video'>
    </a>
</div>

## 5. Envío

Para hacer la entrega, debes acceder a la siguiente página: [https://tortuga.maratona.dev/](https://tortuga.maratona.dev/) y cargar un archivo zip  con el archivo csv `results.csv` con los resultados de su predicción y el notebook que desarrolló `notebook.ipynb`.

**Si cambia el nombre o formato del archivo csv su solución no será evaluada**

**Si cambia el nombre del notebook su solución no será evaluada**

 
🚨 **PRUEBA TU SOLUCIÓN ANTES DE PRESENTARLA** 🚨

Después de realizar las pruebas, haz clic en el botón en la esquina inferior derecha para ENVIAR TU SOLUCIÓN, como se muestra en la imagen a continuación, y completa el formulario con su dirección de correo electrónico con la que te registraste en MARATÓN 2020. 

<img src="./Docs/Images/TORTUGA_SEND.png" alt="es1"></a>


## 6. Sobre la evaluación

En esencia, el reto puntuará la calidad de tu modelo. Nuestro sistema de evaluación automática calculará la métrica de precisión y calificará tu solución según la calidad del archivo de resultado presentado. Como se explica en el vídeo anterior, el problema que debe resolver el modelo de machine learning es un problema clásico de clasificación de clases múltiples, y se encuentran más detalles en el notebook jupyter proporcionado.

El tiempo de entrega no se incluye en el cálculo de la puntuación del desafío. Sin embargo, para todos los participantes que presenten este desafío en la primera semana después del lanzamiento, recibirán una bonificación del 10% de la puntuación final.

## Material de apoyo

- [Una guía del portal de IBM Developer para principiantes del Machine Learning](https://developer.ibm.com/es/patterns/use-icp4d-to-build-the-machine-learning-model-for-return-propensity/)

## Solución de problemas

Mira el [video explicativo](#43-desarrollo) provisto en la Sección 4, o si lo deseas, revisa la documentación de los servicios involucrados en este desafío:

- [Video Dudas Retos de la Maratón](https://www.youtube.com/watch?v=9HsfPf6QrLc)
- [Video solución dudas comunes desafío 1 y 2](https://www.youtube.com/watch?v=vmiQ54bK65I)
- [Video ¿Como mejorar el puntaje en los desafios 1 y 2?](https://www.youtube.com/watch?v=1VbxxVkd-xI)
- [IBM Cloud Pak for Data as a Service (Watson Studio)](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/welcome-main.html?audience=wdp&context=cpdaas)

Accede al discord oficial de la Maratón 2020 para hacer preguntas y/o interactuar con otros participantes: [Discord](https://discord.gg/Q9At74C).

## Licencia

Copyright 2020 Maratona Behind the Code

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
