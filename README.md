## Prueba técnica para Frontend Developer

### Objetivo

Para la evaluación de las competencias tecnicas y los criterios de diseño se deberá realizar la siguiente prueba técnica.

### Descripción

En esta oportunidad se tiene un prototipo de una aplicación de chat que podrán encontrar en: [Prototipo](https://www.figma.com/design/94v3l1fbHl8W3Ch687fGxt/Chat-Prueba-Tecnica?node-id=0-1&t=KDWveo3707jI2S0G-1)

-   Se debe realizar una maquetacion utilizando HTML y CSS del prototipo proporcionado.
-   Se debe poder filtrar por chats aplicando filtros rapidos `All` y `Unread`.
-   Al seleccionar un chat deberá mostrar a mano derecha la conversación con el contacto seleccionado.
-   Se debe poder enviar mensajes de tipo texto en la conversacion. (solo deberá mostrar el mensaje enviado, no es necesario que se envie a un servidor).
-   Si no hay chat seleccionado, se debe mostrar un mensaje de `Selecciona un chat para comenzar a chatear`.
-   Los filtros son "activables" es decir, si se selecciona `All` se debe mostrar todos los chats, si se selecciona `Unread` se deben mostrar solo los chats no leidos. Pero visualmente deseleccionarse el filtro anterior.
-   Se debe implementar una herramienta de busqueda de chats, que filtre los chats por el alias del contacto.

Los chats tienen la siguiente estructura:

-   `id`: Identificador del chat.
-   `alias`: Alias del contacto.
-   `lastMessage`: Ultimo mensaje enviado.
-   `lastMessageDatetime`: Fecha y hora del último mensaje enviado.
-   `read`: es un valor booleano.

Los mensajes tienen la siguiente estructura:

-   `id`: Identificador del mensaje.
-   `chatId`: Identificador del chat al que pertenece.
-   `message`: Mensaje enviado.
-   `dateTime`: Fecha y hora de envio del mensaje.
-   `direction`: Este campo será OUTGOING o INCOMING tratarlo como string.

### Requerimientos

-   Se debe utilizar HTML, CSS para la maqueta.
-   Se debe utilizar Angular 17+ para la funcionalidad.
-   Se debe crear la estructura de componentes necesarios para la aplicación que usted considere necesarios.
-   Se debe utilizar Angular Material para los componentes.

### Evaluación

-   Para la evaluación se tomará en cuenta la calidad del código, la estructura de los componentes, la calidad del diseño y la funcionalidad de la aplicación.
-   Se evaluará la capacidad de resolver problemas y la creatividad en la solución de los mismos.
-   Tener en cuenta que el código de la aplicación debe cumplir con los estándares OWASP.
-   Tener en cuenta el uso de SonarQube para la evaluación de la calidad del código. Ya que esto es lo que se utilizará en la empresa.
-   Se evaluará la prolijidad del uso de git y los commits realizados. Se deberá utilizar para cada commit el siguiente formato:
    > `<type>(<optional scope>): <description>`

#### Optativos

-   Responsive: No es necesario que la aplicación sea responsive, pero se tomará en cuenta si se implementa.
-   Websockets: Si se implementa la funcionalidad de websockets se tomará en cuenta como un plus. Por ejemplo que si llegara un mensaje entrante, al chat seleccionado se le muestre el mensaje sin necesidad de recargar la página. O si éste no está seleccionado, se muestre un badge con la cantidad de mensajes no leidos.
-   Manejo de fechas: Si el último mensaje de un chat fue enviado o recibido el mismo día, se debe mostrar la hora del mensaje, si fue enviado o recibido ayer, se debe mostrar `Ayer`, si fue enviado o recibido hace más de un día, se debe mostrar la fecha del mensaje.
-   Traduccion de la aplicación: Si se implementa la funcionalidad de traducción de la aplicación se tomará en cuenta como un plus. (Se recomienda que para esto, todos los strings se encuentren en un archivo y el front en funcion de como este configurado, se utilice en un idioma u otro).
-   Si usted considera que puede agregar alguna funcionalidad que no se encuentra en los requerimientos, puede hacerlo y se tomará en cuenta como un plus.

Para la implementación de cualquier funcionalidad OPTATIVA se puede utilizar cualquier librería o framework que usted considere necesario, en cualquier tipo de tecnología.

### Entrega

Para la entrega de la prueba técnica se deberá hacer un fork del repositorio y subir el código al repositorio forkeado. Luego enviar el link del repositorio a la persona que se lo haya solicitado con permisos de lectura.

### Tiempo

El tiempo para la realización de la prueba es de máximo 7 días a partir de la fecha de envío. Cuanto antes se entregue, antes se podrá agendar la reunión de feedback.

### Dudas

Si tienes alguna duda sobre la prueba técnica, por favor comunicate con la persona que se lo haya solicitado via mail o por el medio que te hayan contactado.

### Buena suerte!
