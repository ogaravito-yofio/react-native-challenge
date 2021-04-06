# Prueba técnica de YoFio para desarrolladores React-Native / Android (Kotlin)

Esta prueba está diseñada para demostrar el conocimiento básico en la herramienta de desarrollo web y móvil. Se debe construir una APP móvil y crear un APK para ser instalado en un dispositivo físico.

Según la vacante a la que se esté aspirando se debe desarrollar en una tecnología específica. 

- React-Native Dev: Usar el FW React-Native con JS o TS.
- Android Dev: Usar Android nativo con Kotlin (No se aceptan soluciones en Java).

## Requerimientos

- Formulario con 3 campos de ingreso: nombre, apellido y fecha de nacimiento.
- Se debe consumir un servicio web para el envío de todos los datos del formulario.
- Debe contener un botón para permitir la toma de una selfie. _(Opcional)_
- En el envío debe enviarse la coordenada de ubicación actual de quien llena el formulario. _(Opcional)_

## Consumo del servicio web

La información recolectada en el formulario debe enviarse, consumiendo un servicio web que está documentado [aquí](https://app.swaggerhub.com/apis/yofio/yo-fio_recruitment_tech_challenge/1.0.0) y cuya URL base es [esta](https://tech-challenge-v2.herokuapp.com).

## Screenshots de referencia

Para una mejor referencia puedes usar estas capturas de pantalla acerca de como debe quedar el formulario. La primera pantalla muestra el formulario completo y la segunda muestra la cámara que se debe desplegar en caso de incluir el requerimiento de enviar la selfie.

En la primera pantalla el ícono de la fotografía sirve como botón para activar la cámara que debe ser desplegada en modo selfie.

![image](https://user-images.githubusercontent.com/62178275/113743728-9b1e9e00-96c9-11eb-8026-98aaade83634.png)

![image](https://user-images.githubusercontent.com/62178275/113743770-a96cba00-96c9-11eb-86b4-256f632476f0.png)

# Envío de la prueba

La prueba debe quedar resuelta en un repositorio que debe incluir un APK instalable en la carpeta `/dist`. Compartir ese repositorio con [ogaravito@yofio.co](mailto:ogaravito@yofio.co).
