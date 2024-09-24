# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

En esta sección se resume la información recopilada, se realiza dos tablas con la situación a mejorar del segmento objetivo, analizando que pasos que se realizaran y como se siente.

*Segmento Estudiantes Universitarios que necesiten movilizarse*

![SMobjetivo1](assets/images/ScenarioMapO1.jpg)

*Segmento Estudiantes Universitarios propetarios de vehiculo privado*

![SMobjetivo2](assets/images/ScenarioMapO2.jpg)

## 3.2. User Stories
<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>
<tr class="even">
<td>E1-US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td>
<p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>Quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>Para</strong> reducir costos y llegar de manera más eficiente</p>
</td>
<td>
<p>Escenario 1: Búsqueda de viajes disponibles</p>
<p><strong>Dado</strong> que el usuario necesita transporte hacia la universidad,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá buscar y ver una lista de conductores disponibles que se dirijan a su universidad en un horario compatible</p>
<p>Escenario 2: Reserva de un viaje</p>
<p><strong>Dado</strong> que el usuario ha encontrado un viaje disponible,</p>
<p><strong>Cuando</strong> selecciona al conductor y realiza la reserva,</p>
<p><strong>Entonces</strong> podrá confirmar su lugar en el vehículo y recibir detalles sobre el viaje</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E1-US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td>
<p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>Quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la unviersidad</p>
<p><strong>Para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p>
</td>
<td>
<p>Escenario 1: Publicación de disponibilidad de asientos</p>
<p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar</p>
<p>Escenario 2: Gestión de reservas</p>
<p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
<p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
<p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios</p>
</td>
<td>1</td>
</tr>

<tr class="even">
<td>E1-US03</td>
<td>Evaluar la seguridad del viaje</td>
<td>
<p><strong>Como</strong> estudiante,</p>
<p><strong>Quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>Para</strong> asegurarme de que el viaje sea seguro y confiable</p>
</td>
<td>
<p>Escenario 1: Ver calificaciones de conductores</p>
<p><strong>Dado</strong> que el usuario está reservando un viaje,</p>
<p><strong>Cuando</strong> selecciona un conductor,</p>
<p><strong>Entonces</strong> podrá ver la calificación y los comentarios de otros pasajeros sobre la experiencia previa a ese conductor</p>
<p>Escenario 2: Dejar una calificación</p>
<p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
<p><strong>Cuando</strong> finalice el trayecto,</p>
<p><strong>Entonces</strong> podrá dejar una calificación y comentarios sobre la experiencia con el conductor</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E2-US01</td>
<td>Recibir notificaciones en tiempo real</td>
<td>
<p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>Quiero</strong> recibir notificaciones en tiempo real sobre mi viaje </p>
<p><strong>Para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p>
</td>
<td>
<p>Escenario 1: Actualización de la hora de llegada</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> haya un cambio en la ruta o el horario,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación en tiempo real indicando el neuvo tiempo estimado de llegada</p>
<p>Escenario 2: Notificación de recogida</p>
<p><strong>Dado</strong> que el conductor está llegando a recoger a un pasajero,</p>
<p><strong>Cuando</strong> esté cerca al punto de encuentro,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación informándole que el conductor está próximo</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US02</td>
<td>Verificación de identidades</td>
<td>
<p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>Quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades </p>
<p><strong>Para</strong> asegurarme de que mi viaje será con persona confiables</p>
</td>
<td>
<p>Escenario 1: Verificación de conductores</p>
<p><strong>Dado</strong> que el usuario va realizar un viaje,</p>
<p><strong>Cuando</strong> seleccione un conductor,</p>
<p><strong>Entonces</strong> podrá ver si el conductor ha verificado su identidad y sus documentos</p>
<p>Escenario 2: Verificación de pasajeros</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> los pasajeros confirmen su reserva,</p>
<p><strong>Entonces</strong> el conductor podrá ver si los pasajeros han verificado su identidad a través de la plataforma</p>
</td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US03</td>
<td>Realizar pagos de manera segura</td>
<td>
<p><strong>Como</strong> pasajero,</p>
<p><strong>Quiero</strong> realizar el pago del viaje a través de la paltaforma de forma segura </p>
<p><strong>Para</strong> no tener que manejar efectivo durante el trayecto</p>
</td>
<td>
<p>Escenario 1: Pago en línea</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> confirme su reserva,</p>
<p><strong>Entonces</strong> podrá realizar el apgo del viaje a través de la plataforma utilizando métodos de pago seguros como tarjeta de crédito, débito o bileteras digitales</p>
<p>Escenario 2: Confirmación de pago</p>
<p><strong>Dado</strong> que el usuario ha realizado el pago,</p>
<p><strong>Cuando</strong> se complete la transacción,</p>
<p><strong>Entonces</strong> recibirá una confirmación del pago en su correo electrónico o dentro de la aplicación</p>
</td>
<td>2</td>
</tr>

 <tr class="even">
        <td>E3-US01</td>
        <td>Registro de usuario</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder crear mi usuario</p>
            <p><strong>Para</strong> acceder al servicio de carpooling</p>
        </td>
        <td>
            <p>Escenario 1: Registro del usuario</p>
            <p><strong>Dado</strong> que el usuario quiere unirse a la plataforma,</p>
            <p><strong>Cuando</strong> complete el formulario de registro,</p>
            <p><strong>Entonces</strong> recibirá un correo electrónico de confirmación después del registro.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US02</td>
        <td>Búsqueda de Viaje Disponibles</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> buscar viajes disponibles</p>
            <p><strong>Para</strong> poder planificar mis desplazamientos</p>
        </td>
        <td>
            <p>Escenario 1: Filtrado de viajes</p>
            <p><strong>Dado</strong> que el usuario necesita un viaje,</p>
            <p><strong>Cuando</strong> ingrese sus criterios de búsqueda,</p>
            <p><strong>Entonces</strong> podrá ver una lista de viajes disponibles con información detallada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US03</td>
        <td>Reserva de Viaje</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder reservar un asiento en el viaje disponible</p>
            <p><strong>Para</strong> garantizar mi lugar.</p>
        </td>
        <td>
            <p>Escenario 1: Confirmación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles del viaje,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para reservar un asiento y confirmar la reserva.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US04</td>
        <td>Comunicación con el Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder comunicarme con el conductor de mi viaje</p>
            <p><strong>Para</strong> coordinar detalles y obtener información adicional.</p>
        </td>
        <td>
            <p>Escenario 1: Mensajería dentro de la plataforma</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> quiera comunicarse con el conductor,</p>
            <p><strong>Entonces</strong> podrá hacerlo a través de la plataforma UniRider.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US05</td>
        <td>Cancelación de Reserva</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder cancelar una reserva de viaje</p>
            <p><strong>Para</strong> los casos de que surjan imprevistos</p>
        </td>
        <td>
            <p>Escenario 1: Cancelación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles de su reserva,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para cancelar su reserva y confirmar la cancelación.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US06</td>
        <td>Calificación y Comentario del Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
            <p><strong>Para</strong> ayudar a otros usuarios en su elección</p>
        </td>
        <td>
            <p>Escenario 1: Calificación del conductor</p>
            <p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
            <p><strong>Cuando</strong> quiera dejar una opinión,</p>
            <p><strong>Entonces</strong> podrá calificar al conductor con una puntuación y un comentario opcional.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US07</td>
        <td>Publicación de disponibilidad de asientos</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> publicar la disponibilidad de asientos</p>
            <p><strong>Para</strong> que otros estudiantes puedan reservar</p>
        </td>
        <td>
            <p>Escenario 1: Publicación de disponibilidad</p>
            <p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
            <p><strong>Cuando</strong> acceda a la plataforma,</p>
            <p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US08</td>
        <td>Gestión de reservas</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> gestionar las reservas de los pasajeros</p>
            <p><strong>Para</strong> confirmar los pasajeros y horarios</p>
        </td>
        <td>
            <p>Escenario 1: Gestión de reservas</p>
            <p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
            <p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
            <p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios.</p>
        </td>
        <td>3</td>
    </tr>
<tr class="even">
        <td>E4-US01</td>
        <td>Visualizar planes de servicio</td>
        <td>
            <p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
            <p><strong>Quiero</strong> visualizar los planes de servicio disponibles</p>
            <p><strong>Para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p>
        </td>
        <td>
            <p>Escenario 1: Visualización inicial de los planes de servicio</p>
            <p><strong>Dado</strong> que el usuario ha accedido a la plataforma,</p>
            <p><strong>Cuando</strong> el usuario navega a la sección de planes de servicio,</p>
            <p><strong>Entonces</strong> se muestran todos los planes disponibles en una lista, incluyendo el nombre del plan, precio y beneficios principales.</p>
        </td>
        <td>
            <p>Escenario 2: Ver detalles de un plan específico</p>
            <p><strong>Dado</strong> que el usuario está visualizando los planes de servicio,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan específico de la lista,</p>
            <p><strong>Entonces</strong> se muestra con los detalles completos del plan, incluyendo una descripción más detallada de los beneficios y cualquier condición asociada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E4-US02</td>
        <td>Seleccionar un plan de servicio</td>
        <td>
            <p><strong>Como</strong>usuario registrado en la plataforma,</p>
            <p><strong>Quiero</strong> seleccionar un plan de servicio</p>
            <p><strong>Para</strong> adquirir los beneficios específicos que ofrece el plan</p>
        </td>
        <td>
            <p>Escenario 1: Selección de un plan desde la lista</p>
            <p><strong>Dado</strong> que el usuario ha visualizado los planes de servicio disponibles,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan de la lista,</p>
            <p><strong>Entonces</strong> se redirige al usuario a una página de confirmación, mostrando un resumen del plan seleccionado.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación de selección del plan</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un plan,</p>
            <p><strong>Cuando</strong> el usuario revisa el resumen del plan en la página de confirmación,,</p>
            <p><strong>Entonces</strong> tiene la opción de confirmar la selección o regresar a la lista de planes para elegir otro.</p>
        </td>
        <td>3</td>
    </tr>
    
<tr class="even">
        <td>E4-US03</td>
        <td>Realizar el pago del plan seleccionado</td>
        <td>
            <p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
            <p><strong>Quiero</strong> realizar el pago del plan seleccionado</p>
            <p><strong>Para</strong> activar los beneficios del plan y comenzar a utilizarlos</p>
        </td>
        <td>
            <p>Escenario 1: Ingreso de detalles de pago</p>
            <p><strong>Dado</strong>  que el usuario ha confirmado la selección de un plan y ha sido redirigido a la página de pago,
            <p><strong>Cuando</strong> el usuario introduce los detalles de pago (tarjeta de crédito, PayPal, etc.),</p>
            <p><strong>Entonces</strong> el sistema verifica la validez de los detalles ingresados y muestra un resumen de la transacción.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación del pago</p>
            <p><strong>Dado</strong> que el usuario ha ingresado detalles de pago válidos,</p>
            <p><strong>Cuando</strong> el usuario confirma la transacción,</p>
            <p><strong>Entonces</strong> el sistema procesa el pago y muestra una confirmación en pantalla, indicando que el plan ha sido activado con éxito.</p>
        </td>
        <td>
            <p>Escenario 3: Notificación de pago exitoso</p>
            <p><strong>Dado</strong> que el pago ha sido procesado con éxito,</p>
            <p><strong>Cuando</strong> la transacción se completa,</p>
            <p><strong>Entonces</strong> el usuario recibe una notificación de confirmación por correo electrónico, detallando el plan adquirido y los beneficios activados.</p>
        </td>
        <td>5</td>
    </tr>

<tr class="odd">
        <td>E4-US04</td>
        <td>Cancelar suscripción o plan</td>
        <td>
            <p><strong>Como</strong>usuario que ha adquirido un plan,</p>
            <p><strong>Quiero</strong> cancelar mi suscripción o plan</p>
            <p><strong>Para</strong> dejar de recibir los beneficios y evitar cargos futuros</p>
        </td>
        <td>
            <p>Escenario 1: Acceso a la opción de cancelación</p>
            <p><strong>Dado</strong> que el usuario tiene un plan activo en su cuenta,</p>
            <p><strong>Cuando</strong> el usuario accede a la sección de “Mis planes” o “Mi cuenta”,</p>
            <p><strong>Entonces</strong> se le muestra la opción de cancelar su suscripción o plan actual.</p>
        </td>
        <td>
            <p>Escenario 2: Coonfirmación de la cancelación</p>
            <p><strong>Dado</strong> que el usuario ha solicitado cancelar su plan,</p>
            <p><strong>Cuando</strong> el usuario hace clic en “Cancelar plan” y se le solicita confirmar la acción,</p>
            <p><strong>Entonces</strong> el sistema muestra un mensaje de confirmación que explica las consecuencias de la cancelación.</p>
        </td>
        <td>3</td>
    </tr>
<tr class="even">
<td>E5-US01</td>
<td>Barra de navegación en la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>Para</strong> tener acceso directo a la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conducto se encuentra en el navbar de navegación</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentre en la sección del navbar,</p>
<p><strong>Entonces</strong> visualiza enlaces de las secciones, botón de idiomas y el botón para redirigir a la aplicación.</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E5-US02</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>Para</strong> poder usarla.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la aplicación a través de un botón</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Cuando</strong> presione el botón “Open app”,</p>
<p><strong>Entonces</strong> es dirigido a la aplicación donde se podrá loguear.</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E5-US03</td>
<td>Sección hero del landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> observar la sección hero de la landing,</p>
<p><strong>Para</strong> poder tener información de lo que es y ofrece la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conductor se encuentra en la sección de hero</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentra en la sección hero,</p>
<p><strong>Entonces</strong> observa una presentación de la aplicación.</p>
<p>Escenario 2: El cliente o conductor accede a la aplicación por el botón de Sign Up</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> presiona el botón “Sign up”,</p>
<p><strong>Entonces</strong> es redirigido al formulario de registro de cuentas.</p>
</td>
<td>3</td>
</tr>

<tr class="odd">
<td>E5-US04</td>
<td>Versión en español de la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>Para</strong> tener accesibilidad en cuanto a opciones de idioma.</p>
</td>
<td>
<p>Escenario 1: El cliente entra a la landing page</p>
<p><strong>Dado</strong> que el usuario se encuentra en el landing page,</p>
<p><strong>Cuando</strong> sea su primera vez,</p>
<p><strong>Entonces</strong> el idioma predeterminado de la landing page será inglés.</p>
<p>Escenario 2: El cliente quiere cambiar de idioma</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Y</strong> desea cambiar de idioma a español,</p>
<p><strong>Cuando</strong> presiona el botón para cambiar de inglés a español,</p>
<p><strong>Entonces</strong> la landing page se muestra en el idioma de preferencia seleccionado.</p>
</td>
<td>4</td>
</tr>

<tr class="even">
<td>E5-US05</td>
<td>Sección about the product y about the team</td>
<td>
<p><strong>Como</strong> cliente o staff,</p>
<p><strong>Quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>Para</strong> conocer las características de la aplicación y del grupo de desarrolladores.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la sección about the product y the team</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Entonces</strong> puede acceder directamente a la sección correspondiente.</p>
</td>
<td>5</td>
</tr>

<tr class="odd">
  <td>E1-US01</td>
  <td>Agendar notificaciones de recordatorio de viajes</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje</p>
    <p><strong>Para</strong> asegurarme de estar listo a tiempo</p>
  </td>
  <td>
    <p>Escenario 1: Recordatorio antes del viaje</p>
    <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
    <p><strong>Cuando</strong> queden 30 minutos para que comience el viaje,</p>
    <p><strong>Entonces</strong> recibirá una notificación recordándole el inicio próximo del viaje</p>
    <p>Escenario 2: Ubicación del conductor</p>
    <p><strong>Dado</strong> que el usuario ha recibido la notificación de recordatorio,</p>
    <p><strong>Cuando</strong> abra la aplicación,</p>
    <p><strong>Entonces</strong> podrá ver la ubicación y el tiempo estimado de llegada del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US02</td>
  <td>Filtrar viajes por tipos de vehículos</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> poder filtrar los viajes según el tipo de vehículo</p>
    <p><strong>Para</strong> seleccionar el que más se ajuste a mis necesidades</p>
  </td>
  <td>
    <p>Escenario 1: Aplicar filtros</p>
    <p><strong>Dado</strong> que el usuario está buscando un viaje,</p>
    <p><strong>Cuando</strong> acceda a los filtros,</p>
    <p><strong>Entonces</strong> podrá seleccionar el tipo de vehículo, como sedan, SUV, o camioneta</p>
    <p>Escenario 2: Búsqueda de vehículos filtrados</p>
    <p><strong>Dado</strong> que el usuario ha aplicado el filtro,</p>
    <p><strong>Cuando</strong> seleccione "Buscar",</p>
    <p><strong>Entonces</strong> verá solo los viajes disponibles con el tipo de vehículo seleccionado</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US03</td>
  <td>Establecer destinos secundarios</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder establecer destinos secundarios durante mi ruta</p>
    <p><strong>Para</strong> recoger a más estudiantes en puntos intermedios</p>
  </td>
  <td>
    <p>Escenario 1: Añadir destinos secundarios</p>
    <p><strong>Dado</strong> que el usuario ha publicado un viaje,</p>
    <p><strong>Cuando</strong> esté configurando su ruta,</p>
    <p><strong>Entonces</strong> podrá agregar puntos de parada adicionales en el trayecto</p>
    <p>Escenario 2: Verificación de paradas</p>
    <p><strong>Dado</strong> que el conductor ha agregado un destino secundario,</p>
    <p><strong>Cuando</strong> un pasajero busque viajes,</p>
    <p><strong>Entonces</strong> podrá ver si hay paradas adicionales en la ruta del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US04</td>
  <td>Opciones de seguridad adicionales para conductores</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real</p>
    <p><strong>Para</strong> garantizar un viaje seguro</p>
  </td>
  <td>
    <p>Escenario 1: Activar seguimiento de ubicación</p>
    <p><strong>Dado</strong> que el conductor ha iniciado un viaje,</p>
    <p><strong>Cuando</strong> comience el recorrido,</p>
    <p><strong>Entonces</strong> podrá activar la opción de compartir su ubicación en tiempo real con un contacto de confianza</p>
    <p>Escenario 2: Desactivar el seguimiento</p>
    <p><strong>Dado</strong> que el conductor ha compartido su ubicación,</p>
    <p><strong>Cuando</strong> termine el viaje,</p>
    <p><strong>Entonces</strong> podrá desactivar el seguimiento de la ubicación</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US05</td>
  <td>Identificación de usuarios frecuentes</td>
  <td>
    <p><strong>Como</strong> pasajero frecuente,</p>
    <p><strong>Quiero</strong> poder marcar ciertos conductores como favoritos</p>
    <p><strong>Para</strong> facilitar la reserva de futuros viajes con ellos</p>
  </td>
  <td>
    <p>Escenario 1: Marcar un conductor como favorito</p>
    <p><strong>Dado</strong> que el pasajero ha completado varios viajes con un conductor,</p>
    <p><strong>Cuando</strong> acceda a su perfil,</p>
    <p><strong>Entonces</strong> podrá marcarlo como "Favorito" para futuros viajes</p>
    <p>Escenario 2: Recibir notificaciones de conductores favoritos</p>
    <p><strong>Dado</strong> que el pasajero ha marcado a un conductor como favorito,</p>
    <p><strong>Cuando</strong> busque viajes,</p>
    <p><strong>Entonces</strong> recibirá notificaciones cuando ese conductor tenga disponibilidad</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US06</td>
  <td>Programar viajes recurrentes</td>
  <td>
    <p><strong>Como</strong> usuario,</p>
    <p><strong>Quiero</strong> poder programar viajes recurrentes</p>
    <p><strong>Para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p>
  </td>
  <td>
    <p>Escenario 1: Programar viaje recurrente</p>
    <p><strong>Dado</strong> que el usuario necesita transporte diario,</p>
    <p><strong>Cuando</strong> acceda a la opción de "Viajes recurrentes",</p>
    <p><strong>Entonces</strong> podrá establecer un horario y ruta fijos para repetir el viaje automáticamente</p>
    <p>Escenario 2: Confirmación de viajes recurrentes</p>
    <p><strong>Dado</strong> que el usuario ha programado un viaje recurrente,</p>
    <p><strong>Cuando</strong> se aproxime la fecha del viaje,</p>
    <p><strong>Entonces</strong> recibirá una confirmación automática del viaje y detalles del conductor</p>
  </td>
  <td>1</td>
</tr>

</tbody>
</table>
<hr>

## 3.3. Impact Mapping.


## 3.4. Product Backlog.
<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td><p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>para</strong> reducir costos y llegar de manera más eficiente</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>2</td>
<td>US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td><p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la universidad</p>
<p><strong>para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>3</td>
<td>US03</td>
<td>Evaluar la seguridad del viaje</td>
<td><p><strong>Como</strong> estudiante,</p>
<p><strong>quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>para</strong> asegurarme de que el viaje sea seguro y confiable</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>4</td>
<td>US04</td>
<td>Recibir notificaciones en tiempo real</td>
<td><p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones en tiempo real sobre mi viaje</p>
<p><strong>para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>5</td>
<td>US05</td>
<td>Verificación de identidades</td>
<td><p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades</p>
<p><strong>para</strong> asegurarme de que mi viaje será con personas confiables</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>6</td>
<td>US06</td>
<td>Realizar pagos de manera segura</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> realizar el pago del viaje a través de la plataforma de forma segura</p>
<p><strong>para</strong> no tener que manejar efectivo durante el trayecto</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>7</td>
<td>US07</td>
<td>Registro de usuario</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder crear mi usuario</p>
<p><strong>para</strong> acceder al servicio de carpooling</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>8</td>
<td>US08</td>
<td>Búsqueda de viajes disponibles</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> buscar viajes disponibles</p>
<p><strong>para</strong> poder planificar mis desplazamientos</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>9</td>
<td>US09</td>
<td>Reserva de viaje</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder reservar un asiento en el viaje disponible</p>
<p><strong>para</strong> garantizar mi lugar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>10</td>
<td>US10</td>
<td>Comunicación con el conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder comunicarme con el conductor de mi viaje</p>
<p><strong>para</strong> coordinar detalles y obtener información adicional</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>11</td>
<td>US11</td>
<td>Cancelación de reserva</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder cancelar una reserva de viaje</p>
<p><strong>para</strong> los casos de que surjan imprevistos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>12</td>
<td>US12</td>
<td>Calificación y comentario del conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
<p><strong>para</strong> ayudar a otros usuarios en su elección</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>13</td>
<td>US13</td>
<td>Publicación de disponibilidad de asientos</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> publicar la disponibilidad de asientos</p>
<p><strong>para</strong> que otros estudiantes puedan reservar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>14</td>
<td>US14</td>
<td>Gestión de reservas</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> gestionar las reservas de los pasajeros</p>
<p><strong>para</strong> confirmar los pasajeros y horarios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>15</td>
<td>US15</td>
<td>Visualizar planes de servicio</td>
<td><p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
<p><strong>quiero</strong> visualizar los planes de servicio disponibles</p>
<p><strong>para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>16</td>
<td>US16</td>
<td>Seleccionar un plan de servicio</td>
<td><p><strong>Como</strong> usuario registrado en la plataforma,</p>
<p><strong>quiero</strong> seleccionar un plan de servicio</p>
<p><strong>para</strong> adquirir los beneficios específicos que ofrece el plan</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>17</td>
<td>US17</td>
<td>Realizar el pago del plan seleccionado</td>
<td><p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
<p><strong>quiero</strong> realizar el pago del plan seleccionado</p>
<p><strong>para</strong> activar los beneficios del plan y comenzar a utilizarlos</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>18</td>
<td>US18</td>
<td>Cancelar suscripción o plan</td>
<td><p><strong>Como</strong> usuario que ha adquirido un plan,</p>
<p><strong>quiero</strong> cancelar mi suscripción o plan</p>
<p><strong>para</strong> dejar de recibir los beneficios y evitar cargos futuros</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>19</td>
<td>US19</td>
<td>Barra de navegación en la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>para</strong> tener acceso directo a la aplicación</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>20</td>
<td>US20</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>para</strong> poder usarla</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>21</td>
<td>US21</td>
<td>Sección hero del landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> observar la sección hero de la landing,</p>
<p><strong>para</strong> poder tener información de lo que es y ofrece la aplicación</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>22</td>
<td>US22</td>
<td>Versión en español de la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>para</strong> tener accesibilidad en cuanto a opciones de idioma</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>23</td>
<td>US23</td>
<td>Sección about the product y about the team</td>
<td><p><strong>Como</strong> cliente o staff,</p>
<p><strong>quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>para</strong> conocer las características de la aplicación y del grupo de desarrolladores</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>24</td>
<td>US24</td>
<td>Agendar notificaciones de recordatorio de viajes</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje,</p>
<p><strong>para</strong> asegurarme de estar listo a tiempo</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>25</td>
<td>US25</td>
<td>Filtrar viajes por tipos de vehículos</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> poder filtrar los viajes según el tipo de vehículo,</p>
<p><strong>para</strong> seleccionar el que más se ajuste a mis necesidades</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>26</td>
<td>US26</td>
<td>Establecer destinos secundarios</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder establecer destinos secundarios durante mi ruta,</p>
<p><strong>para</strong> recoger a más estudiantes en puntos intermedios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>27</td>
<td>US27</td>
<td>Opciones de seguridad adicionales para conductores</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real,</p>
<p><strong>para</strong> garantizar un viaje seguro</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>28</td>
<td>US28</td>
<td>Identificación de usuarios frecuentes</td>
<td><p><strong>Como</strong> pasajero frecuente,</p>
<p><strong>quiero</strong> poder marcar ciertos conductores como favoritos,</p>
<p><strong>para</strong> facilitar la reserva de futuros viajes con ellos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>29</td>
<td>US29</td>
<td>Programar viajes recurrentes</td>
<td><p><strong>Como</strong> usuario,</p>
<p><strong>quiero</strong> poder programar viajes recurrentes,</p>
<p><strong>para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p></td>
<td>Alta</td>
<td>8</td>
</tr>
</tbody>
</table>
