# ProyectoPaginaWeb-03.github.io

Página web creada con:
- **HTML:** permite crear la estructura del sitio web mediante etiquetas
- **SASS:** herramienta que permite generar, de manera automática, hojas de estilo, añadiéndoles características que no tiene CSS como variables, funciones, selectores anidados, herencia,
- **JavaScript:** añade características que permite establecer acciones interactivas al sitio web
- **PHP:** favorece la conexión entre los servidores y la interfaz de usuario

Este sitio web fue creado y desarrollado usando la plataforma **NetBeans 10.0**. Además está adaptado para ejecutarse en dispositivos móviles.

El archivo **index.html** es el que contiene la página de inicio, la página principal del sitio web.

La página de inicio o principal consta de varias secciones: 
- **Un encabezado:** donde se muestra el logotipo de la organización
- **Una sección principal:** que contiene un mensaje, el menú principal, una sección adaptada para mostrar un enunciado especial, un carrusel de imagenes 
- **Un pie de página:** que muestra la información de la organización

El menú principal consta de cuatro opciones: 
- **Quienes somos:** muestra información acerca de la organización. Integra un submenú con 6 opciones adicionales, las cuales describen aspectos tales como la visión, la misión, los valores, entre otros, de la organización
- **Reflexiones:** muestra una página dedicada a publicar artículos, noticias, mensajes y/o reflexiones bíblicas
- **Actividades:** muestra las actividades que va a realizar la organización durante el mes en curso; así como actividades que se van a realizar a corto plazo 
- **Contáctenos:** consta de dos secciones: un formulario de contacto para que la persona puede ponerse en contacto con la organización y un mapa que muestra la ubicación junto con datos adicionales de contacto

En cada archivo de estilos css se utiliza la técnica de rejilla CSS Grid Layout para organizar de manera más eficiente cada elemento de la interfaz del sitio web, el cual los acomoda tanto a lo largo como a lo ancho de la ventana del navegador. Además, es complementado con flexbox, el cual ayudar a distribuir el espacio entre los ítems de la interfaz y mejora las capacidades de alineación de cada elemento.

Para el formulario de contacto se programaron validaciones tanto del lado cliente realizado con JavaScript; así como del lado del servidor programado con PHP

Para enviar la información del usuario a través del formulario de contacto se utiliza una clase llamada PHPMailer. PHPMailer es una clase php para enviar emails basada en el componente active server ASPMail. Permite de una forma sencilla tareas complejas como por ejemplo:
- Enviar mensajes de correo con ficheros adjuntos (attachments) 
- Enviar mensajes de correo en formato HTML 
- Enviar emails via sendmail, PHP mail(), o con SMTP.

A continuación se presentan algunas imágenes del sitio web brevemente descrito anteriormente:

![03 1  PaginaInicio_1](https://user-images.githubusercontent.com/98922137/171462265-d5876f0b-050f-4017-a469-43e1abe29e32.jpg)

![03 2  PaginaInicio_1](https://user-images.githubusercontent.com/98922137/171462275-b7eb0a2f-4398-4fd7-973b-75b4783b249d.jpg)

![03 3  PaginaInicio_1](https://user-images.githubusercontent.com/98922137/171462279-64800fee-a268-41f9-833a-a0ea0f2c4cd8.jpg)

![06  Nuestra misión_1](https://user-images.githubusercontent.com/98922137/165000732-f6fe0235-a8ad-4ea2-94ab-c57a827120ac.jpg)

![08  Nuestra vivencia_1](https://user-images.githubusercontent.com/98922137/165000734-28c89e9a-eb38-403c-aade-7eaa212b4387.jpg)

![11  Reflexión_1](https://user-images.githubusercontent.com/98922137/165000764-9786ebc3-b5ed-4dc5-b7a2-96e9aaf86a29.jpg)

![12  Reflexión_2](https://user-images.githubusercontent.com/98922137/165000765-0d8e5800-49f1-4803-a562-7cf3e068b167.jpg)

![15  Actividades_2](https://user-images.githubusercontent.com/98922137/165000766-d1a11dc2-5706-417d-baca-0380d30e286b.jpg)

![16  Actividades_3](https://user-images.githubusercontent.com/98922137/165000767-da24cb59-01c0-467f-a776-34d73b82fdb6.jpg)

![19  Contacto_3](https://user-images.githubusercontent.com/98922137/165000768-b9b3c0da-72cf-4271-a4f2-1a2e8d7afdda.jpg)

![20  Contacto_4](https://user-images.githubusercontent.com/98922137/165000769-0e48ac09-d028-4afc-b4db-84fec441600f.jpg)

![22  Contacto_6](https://user-images.githubusercontent.com/98922137/165000770-2a9e9235-0297-42d0-9692-8db2fe448e6a.png)
