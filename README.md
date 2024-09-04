# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
.

**(Nombre Seg01):**

**(Nombre Seg02)**


Enlace de Miro:

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
<td>.</td>
<td><p><strong>Como</strong> .</p>
<p><strong>quiero</strong> .</p>
<p><strong>para</strong> .</p></td>
<td>Alta</td>
<td>.</td>
</tr>
<tr class="even">
<td>2</td>
<td>US02</td>
<td>.</td>
<td><p><strong>Como</strong> .</p>
<p><strong>quiero</strong> .</p>
<p><strong>para</strong> .</p></td>
<td>Baja</td>
<td>1</td>
</tr>

</tbody>
</table>
