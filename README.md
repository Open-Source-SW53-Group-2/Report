# Capítulo IV: Product Design
En este capítulo describimos las directrices de diseño y estilo para el producto, asegurando una experiencia visual coherente y atractiva para el usuario.

## 4.1. Style Guidelines.
En esta sección se describen las pautas generales de estilo que guían la apariencia visual del producto, incluyendo el uso de colores, tipografía y espaciado.

### 4.1.1. General Style Guidelines.
Las directrices generales aseguran una estética que refuerza la marca y proporciona claridad visual para los usuarios.

#### Historia de la marca
La marca busca transmitir modernidad y profesionalismo, reflejando estos valores en cada elemento visual del diseño.

#### Misión
Proporcionar a los usuarios una experiencia fluida y atractiva, con interfaces claras y consistentes.

#### Visión
Ser reconocidos como una marca que combina funcionalidad y estilo en el diseño de productos digitales.

#### Brand Name
El nombre de la marca es un elemento clave de nuestra identidad, representando los valores fundamentales de la empresa.

#### Colores
La paleta de colores está diseñada para proporcionar un equilibrio visual. Utilizamos una combinación de tonos brillantes y neutros para transmitir profesionalismo y modernidad.

![Paleta de Colores](assets/images/colors.png)

#### Tipografía
Usamos la tipografía **Roboto** en diferentes pesos para establecer jerarquía visual y garantizar una legibilidad óptima. El color de la letra principal es `#404040`.

![Guía de Tipografía](assets/images/guidelines.png)

#### Espaciado
El espaciado entre elementos visuales asegura una estructura clara y organizada, ayudando a los usuarios a navegar por el contenido de forma fluida.

- **Tamaño de letra**: Las fuentes varían desde 12px hasta 98px según la jerarquía del texto.
- **Interlineado**: Mantenemos un interlineado proporcional para mejorar la legibilidad.

### 4.1.2. Web Style Guidelines.
Las pautas de estilo para la web están diseñadas para asegurar que el diseño sea funcional y atractivo tanto en dispositivos móviles como en pantallas grandes. Incluir consistencia en colores, tipografías y espaciado es clave para mantener la identidad visual en todas las plataformas.

## 4.2. Information Architecture.
En esta sección, se describe cómo se organizará el contenido en la plataforma **GoUni**, tanto en la web como en las aplicaciones móviles. Se busca que la estructura sea intuitiva para los estudiantes universitarios, permitiendo una navegación fluida y el acceso rápido a las principales funcionalidades de la plataforma.

<hr>

### 4.2.1. Organization System.
El Sistema de Organización de **GoUni** está diseñado para facilitar la interacción entre el usuario y la plataforma, asegurando que los estudiantes puedan encontrar y utilizar los servicios clave, como la búsqueda de viajes o la oferta de plazas en vehículos.

- **Jerarquía Visual**: La página principal destacará las acciones más importantes para el usuario, como “Buscar viaje” y “Publicar viaje”, con énfasis en botones de llamada a la acción que lleven a estas secciones.
- **Organización Secuencial**: Se aplicará a procesos clave como el registro de usuario, reserva de un viaje y configuración de perfil. Estos procesos se guiarán paso a paso, asegurando que los usuarios completen cada tarea sin problemas.
- **Organización Matricial**: Los filtros de búsqueda permitirán a los usuarios seleccionar viajes según el tipo de vehículo, horario y calificaciones del conductor, haciendo que sea más fácil encontrar un viaje que se ajuste a sus necesidades.
- **Esquemas de Categorización**: La categorización de la información podrá hacerse por orden alfabético (al buscar conductores por nombre), cronológico (al organizar las reservas según la fecha), o por audiencia (al segmentar entre conductores y pasajeros).

<br>

### 4.2.2. Labeling System.
En **GoUni**, las etiquetas se diseñarán para ser claras, directas y comprensibles para los estudiantes, priorizando una navegación simple y una experiencia de usuario intuitiva.

### Etiquetas:
- **Inicio**: Al hacer clic en el logo de GoUni, los usuarios serán redirigidos a la página principal.
- **Buscar Viaje**: Opción en el menú principal que permite a los estudiantes buscar viajes disponibles en su universidad.
- **Publicar Viaje**: Los usuarios con vehículo propio podrán acceder a esta opción para publicar su ruta y disponibilidad de asientos.
- **Reservas Actuales**: Sección donde los usuarios pueden ver y gestionar sus reservas actuales.
- **Perfil**: Permite a los usuarios gestionar sus datos personales, verificar su identidad y ver su historial de viajes.

Una vez que los usuarios se registren y accedan a su cuenta, aparecerán nuevas etiquetas como:
- **Mis Viajes**: Un lugar donde los usuarios pueden revisar sus reservas activas y pasadas.
- **Calificar Conductores**: Opción que aparece tras la finalización de un viaje, permitiendo dejar comentarios y puntuaciones.

<br>

### 4.2.3. SEO Tags and Meta Tags.
Los SEO Tags y Meta Tags son esenciales para mejorar la visibilidad de **GoUni** en los motores de búsqueda.

### Para la Landing Page:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GoUni - Carpooling para Estudiantes Universitarios</title>
<meta name="description" content="GoUni es la plataforma de carpooling exclusiva para estudiantes universitarios, enfocada en la seguridad, sostenibilidad y economía colaborativa.">
<meta name="keywords" content="carpooling universitario, compartir autos estudiantes, movilidad sostenible, transporte colaborativo">
<meta name="author" content="GoUni Team">
```
### Para la Aplicación Web:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GoUni - Comparte tu auto con otros estudiantes universitarios</title>
<meta name="description" content="Con GoUni, puedes compartir tu auto con otros estudiantes universitarios y reducir tus gastos de transporte mientras ayudas al medio ambiente.">
<meta name="keywords" content="carpooling estudiantes, compartir auto universidad, transporte sostenible, viaje colaborativo">
<meta name="author" content="GoUni Team">
```

<br>

### 4.2.4. Searching Systems.
El sistema de búsqueda en GoUni facilitará a los usuarios encontrar viajes disponibles de forma rápida y efectiva. La funcionalidad de búsqueda incluirá:

Búsqueda por Universidad: Los estudiantes podrán buscar viajes que conecten con su universidad específica.
Filtros de Búsqueda: Los usuarios podrán filtrar los resultados por tipo de vehículo, horario de salida, calificación del conductor y disponibilidad de plazas.
Organización de Resultados: Los resultados se podrán ordenar de manera alfabética, por hora de salida o por la proximidad del conductor al punto de recogida.

![Searching.png](assets/images/search.png)

<br>

### 4.2.5. Navigation Systems.
El sistema de navegación de GoUni estará diseñado para que los usuarios puedan encontrar la información y realizar las acciones deseadas con el mínimo esfuerzo.

Navegación Principal: El menú superior incluirá accesos rápidos a las funciones clave: "Buscar Viaje", "Publicar Viaje", "Reservas Actuales" y "Perfil".
Navegación Móvil: En la versión móvil, el menú será desplegable para ahorrar espacio y mostrar solo las opciones más importantes de manera compacta. Los usuarios podrán regresar a la página de inicio pulsando el logo de GoUni.
Navegación Secundaria: En secciones como el perfil, habrá opciones adicionales para gestionar la cuenta, verificar la identidad o ajustar preferencias de notificaciones.
![Navigation.png](assets/images/navigation.png)

<br>

## 4.3. Landing Page UI Design.
<hr>
<td align="center">
En esta sección, presentamos el diseño de la interfaz de usuario
de la landing page para GoUni. El diseño se ha desarrollado teniendo
en cuenta la experiencia del usuario y la accesibilidad tanto en
versiones de escritorio como móviles. El objetivo principal es
proporcionar una navegación clara y atractiva. </td>

### 4.3.1. Landing Page Wireframe.
<td align="center">
A continuación, mostramos los wireframes de la landing page, 
los cuales representan la estructura básica y el layout sin 
elementos gráficos detallados. Estos sirven como una guía inicial
para el diseño visual, asegurando que todos los elementos
necesarios estén presentes y correctamente organizados.
</td>

Enlace a los wireframes de la Landing Page en Figma:

[Landing Page Wireframes Link](https://www.figma.com/design/wsF29U5csRMNSNzzX1BfIR/Landing-Page-Wireframe-GoUni?node-id=0-1&t=PrfjiFfYo27WAa3q-1)

#### Wireframe de la Landing Page en Figma:

#### Versión Desktop:

##### Wireframe de la página principal:

Wireframe de la sección Header:
![Header_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Header_Wireframes_Desktop.png)

Wireframe de la sección Hero:
![HeroSection_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/HeroSection_Wireframes_Desktop.png)

Wireframe de la sección How It Works:
![HowItWorks_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/HowItWorks_Wireframes_Desktop.png)

Wireframe de la sección Benefits of GoUni:
![BenefitsofGoUni_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/BenefitsofGoUni_Wireframes_Desktop.png)

Wireframe de la sección Security:
![Security_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Security_Wireframes_Desktop.png)

Wireframe de la sección Plans:
![Plans_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Plans_Wireframes_Desktop.png)

Wireframe de la sección Our Apps and Portals:
![OurAppsandPortals_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/OurAppsandPortals_Wireframes_Desktop.png)

Wireframe de la sección Contact Us:
![ContactUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/ContactUs_Wireframes_Desktop.png)

Wireframe de la sección Footer:
![Footer_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Footer_Wireframes_Desktop.png)

##### Wireframe de la sección Sobre Nosotros:

Wireframe de la sección Header:

![headerAboutUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/headerAboutUs_Wireframes_Desktop.png)

Wireframe de la sección Who We Are:

![whoWeAre_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/whoWeAre_Wireframes_Desktop.png)

Wireframe de la sección Our Sponsor:

![ourSponsors_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/ourSponsors_Wireframes_Desktop.png)

Wireframe de la sección whyGoUni?:

![whyGoUni?_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/whyGoUni_Wireframes_Desktop.png)

Wireframe de la sección Our Team:

![ourTeam_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/ourTeam_Wireframes_Desktop.png)

Wireframe de la sección Footer:

![footerAboutUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/footerAboutUs_Wireframes_Desktop.png)

##### Versión Mobile:

##### Wireframe de la página principal:

Wireframe de la sección Header:

![homeHome_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/homeHome_Wireframe_Mobiles.png)

Wireframe de la sección How It Works:

![howItWorks_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/howItWorks_Wireframe_Mobiles.png)

Wireframe de la sección Benefits of GoUni:

![benefitsOfGoUni_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/benefitsOfGoUni_Wireframe_Mobiles.png)

Wireframe de la sección Security:

![security_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/security_Wireframe_Mobiles.png)

Wireframe de la sección Plans:

![plans_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/plans_Wireframe_Mobiles.png)

Wireframe de la sección Our Apps and Portals:

![ourAppsAndPortals_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/ourAppsAndPortals_Wireframe_Mobiles.png)

Wireframe de la sección Contact Us:

![contactUs_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/contactUs_Wireframe_Mobiles.png)

Wireframe de la sección Footer:

![footerHome_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/footerHome_Wireframe_Mobiles.png)

##### Wireframe de la sección Sobre Nosotros:

Wireframe de la sección Header:

![headerAboutUs_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/headerAboutUs_Wireframes_Mobiles.png)

Wireframe de la sección Why GoUni?:

![whyGoUni_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/whyGoUni_Wireframes_Mobiles.png)

Wireframe de la sección Our Sponsors:

![ourSponsors_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/ourSponsors_Wireframes_Mobiles.png)

Wireframe de la sección Our Team:

![ourTeam_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/ourTeam_Wireframes_Mobiles.png)

Wireframe de la sección Footer:

![footerAboutUs_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/footerAboutUs_Wireframes_Mobiles.png)



### 4.3.2. Landing Page Mockup.
<td align="center">
Esta sección presenta los mockups de la landing page,
que ilustran el diseño final con detalles gráficos, tipografía,
y color. Los mockups son fundamentales para visualizar cómo se
verá la página final y para realizar ajustes antes del desarrollo.
</td>

Enlace a la mockup de la Landing Page en Figma:

#### Mockups de la Landing Page en Figma:

##### Versión Desktop:

#### Mockups de la página principal

Mockup de la sección Header:

![homeHome_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/homeHome_Mockup_Desktop.png)

Mockup de la sección Hero:
![heroHowItWorks_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/heroHowItWorks_Mockup_Desktop.png)

Mockup de la sección How It Works:
![howItWorks_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/howItWorks_Mockup_Desktop.png)

Mockup de la sección Benefits of GoUni:
![benefitsOfGoUni_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/benefitsOfGoUni_Mockup_Desktop.png)

Mockup de la sección Security:
![security_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/security_Mockup_Desktop.png)

Mockup de la sección Plans:
![plans_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/plans_Mockup_Desktop.png)

Mockup de la sección Our Apps and Portals:
![ourAppsAndPortals_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/ourAppsAndPortals_Mockup_Desktop.png)

Mockup de la sección Contact Us:
![contactUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/contactUs_Mockup_Desktop.png)

Mockup de la sección Footer:
![footerHome_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/footerHome_Mockup_Desktop.png)

#### Mockups de la sesion Sobre Nosotros:

Mockup de la sección Header:
![headerAboutUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/headerAboutUs_Mockup_Desktop.png)

Mockup de la sección Who We Are:
![whoWeAre_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/whoWeAre_Mockup_Desktop.png)

Mockup de la sección Why GoUni?:
![whyGoUni_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/whyGoUni_Mockup_Desktop.png)

Mockup de la sección Our Sponsors:
![ourSponsors_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/ourSponsors_Mockup_Desktop.png)

Mockup de la sección Our Team:
![ourTeam_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/ourTeam_Mockup_Desktop.png)

Mockup de la sección Footer:
![footerAboutUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/footerAboutUs_Mockup_Desktop.png)

##### Versión Mobile:

#### Mockups de la página principal

Mockup de la sección Header:

![homeHome_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/homeHome_Mockup_Mobile.png)

Mockup de la sección How It Works:

![howItWorks_Mockuo_Mobile.png](assets/images/landingPage/mockups/mobile/home/howItWorks_Mockup_Mobile.png)

Mockup de la sección Benefits of GoUni:

![benefitsOfGoUni_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/benefitsOfGoUni_Mockup_Mobile.png)

Mockup de la sección Security:

![security_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/security_Mockup_Mobile.png)

Mockup de la sección Plans:

![plans_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/plans_Mockup_Mobile.png)

Mockup de la sección Our Apps and Portals:

![ourAppsAndPortals_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/ourAppsAndPortals_Mockup_Mobile.png)

Mockup de la sección Contact Us:

![contactUs_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/contactUs_Mockup_Mobile.png)

Mockup de la sección Footer:
![footerHome_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/footerHome_Mockup_Mobile.png)


##### Mockups de la sesion Sobre Nosotros:

Mockup de la sección Header:

![headerAboutUs_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/headerAboutUs_Mockup_Mobile.png)

Mockup de la sección Why GoUni?:

![whyGoUni_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/whyGoUni_Mockup_Mobile.png)

Mockup de la sección Our Sponsors:

![ourSponsors_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/ourSponsors_Mockup_Mobile.png)

Mockup de la sección Our Team:

![ourTeam_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/ourTeam_Mockup_Mobile.png)

Mockup de la sección Footer:

![footerAboutUs_Mockup_Mobiles.png](assets/images/landingPage/mockups/mobile/aboutUs/footerAboutUs_Mockup_Mobiles.png)


## 4.4. Web Applications UX/UI Design
.

### 4.4.1. Web Applications Wireframes
.

### 4.4.2. Web Applications Wireflow Diagrams

Enlace a traves de la herramienta LucidChart:

.

### 4.4.3. Web Applications Mock-ups

En esta sección, presentamos los mockups de la aplicación web de GoUni, que ilustran el diseño final con detalles gráficos, tipografía y color. Los mockups son fundamentales para visualizar cómo se verá la aplicación final y para realizar ajustes antes del desarrollo.

Inicio de sesión:

![iniciarSesion_WebApplications.png](assets/images/webApplication/mockups/iniciarSesion_WebApplications.png)

Creación de cuenta:

![crearCuenta_WebApplication.png](assets/images/webApplication/mockups/crearCuenta_WebApplication.png)

Elegir entre ser conductor o pasajero:

![opcionEorC_WebApplications.png](assets/images/webApplication/mockups/opcionEorC_WebApplications.png)

Registro de estudiante:

![registroEstudiante_WebApplications.png](assets/images/webApplication/mockups/registroEstudiante_WebApplications.png)

Registro de conductor:

![registroConductor_WebApplications.png](assets/images/webApplication/mockups/registroConductor_WebApplications.png)

Inicio de la Web Applications:

![inicio_WebApplications.png](assets/images/webApplication/mockups/inicio_WebApplications.png)

Servicios de la Web Applications:

![servicio_WebApplications.png](assets/images/webApplication/mockups/servicio_WebApplications.png)


Planes de la Web Applications:
![planes_WebApplications.png](assets/images/webApplication/mockups/planes_WebApplications.png)

Pagos del plan de la Web Applications:

![pagos_WebApplications.png](assets/images/webApplication/mockups/pagos_WebApplications.png)

Mapa de la Web Applications:

![mapa_WebApplications.png](assets/images/webApplication/mockups/mapa_WebApplications.png)

Reservas de la Web Applications:

![reserva_WebApplications.png](assets/images/webApplication/mockups/reserva_WebApplications.png)

Reserva descripción de la Web Applications:

![reservaDescripcion_WebApplications.png](assets/images/webApplication/mockups/reservaDescripcion_WebApplications.png)

Confirmación de reserva de la Web Applications:

![confirmacionReserva_WebApplications.png](assets/images/webApplication/mockups/confirmacionReserva_WebApplications.png)

Tus reservas de la Web Applications:

![tusReservas_WebApplications.png](assets/images/webApplication/mockups/tusReservas_WebApplications.png)

Chat de la Web Applications:

![chat_WebApplications.png](assets/images/webApplication/mockups/chat_WebApplications.png)

Calificación de la Web Applications:

![puntaje_WebApplications.png](assets/images/webApplication/mockups/puntaje_WebApplications.png)

Enlace a la mockup de la App Web en Figma:
[Link Web Applications Mockups](https://www.figma.com/design/S0hrTzLLDq3a8tOxTfWqJx/Web-Applications-UX%2FUI-Design?node-id=0-1&t=mGQ1yGMxL5NhHeba-1)


### 4.4.4 Web Applications User Flow Diagrams.

Los User Flow Diagrams son diagramas que representan la secuencia de pasos que un usuario sigue al interactuar con la aplicación web. Estos diagramas muestran cómo los usuarios navegan por la plataforma, desde el inicio de sesión hasta la reserva de un viaje.

Enlace de los User Flow Diagrams en LucidChart:
[Link de los User Flow Diagrams](https://lucid.app/lucidspark/7a90b2a6-17d1-4722-836a-0c5cea806e6c/edit?viewport_loc=-242%2C-2574%2C12846%2C6844%2C0_0&invitationId=inv_976795c2-e182-45e2-a40d-3b91afa9fea9)

Inicio de sesión y creación de cuenta:
![iniciarSesion.png](assets/images/webApplication/userFlowDiagrams/iniciarSesion.png)

Plan de pago:
![plan.png](assets/images/webApplication/userFlowDiagrams/plan.png)

Realizar reserva:
![reservarViaje.png](assets/images/webApplication/userFlowDiagrams/reservarViaje.png)

## 4.5. Web Applications Prototyping.
<hr>
En esta sección, presentamos los prototipos interactivos de las aplicaciones web de GoUni. Los prototipos permiten a los usuarios navegar por las diferentes pantallas y funcionalidades, simulando la experiencia de uso de la aplicación antes de su desarrollo.

![WebApplicationsPrototyping.png](assets/images/webApplication/WebApplicationProtoyping/WebApplicationsPrototyping.png)

Link Web Applications Prototyping:
[Link Web Applications Prototyping](https://www.figma.com/proto/S0hrTzLLDq3a8tOxTfWqJx/Web-Applications-UX%2FUI-Design?page-id=0%3A1&node-id=1-50&node-type=FRAME&viewport=1434%2C1917%2C0.23&t=s9nxfg2WlkRXlbt2-1&scaling=scale-down-width&content-scaling=fixed&starting-point-node-id=7%3A894)

## 4.6 Domain-Driven Software Architecture.


### 4.6.1. Software Architecture Context Diagram.

![Diagrama de clase](assets/images/diagramcontext.png)

### 4.6.2. Software Architecture Container s.

![Diagrama de clase](assets/images/diagramcontainer.png)

### 4.6.3 Software Architecture Components Diagrams.

![Diagrama de clase](assets/images/diagramcomponent.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

![Diagrama de clase](assets/images/Diagrama_clase.png)

### 4.7.2. Class Dictionary
<hr>
Usuario:
La clase Usuario representa a un usuario dentro de la plataforma, ya sea un conductor o pasajero.

Atributos:

|Atributo|Descripción|
| :- | :- |
|nombre: String|Almacena el nombre del usuario.|
|email: String|Almacena la dirección de correo electrónico del usuario.|
|contraseña: String|Almacena la contraseña del usuario.|
|rol: Rol|Define el rol del usuario en la plataforma (conductor o pasajero).|
|verificado: Boolean|Indica si el usuario ha verificado su identidad.|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|registrarse(): void|Método para registrar a un nuevo usuario en la plataforma.|
|iniciarSesion(): void|Método para que el usuario inicie sesión en la plataforma.|
|verificarIdentidad(): void|Verifica la identidad del usuario a través de documentos o información adicional.|
# **Evaluación**
La clase Evaluación permite a los usuarios calificar y dejar comentarios sobre sus experiencias de viaje.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|calificación: int|Almacena la calificación numérica del viaje (por ejemplo, de 1 a 5).|
|comentario: String|Almacena los comentarios opcionales sobre el viaje.|
|evaluador: Usuario|Almacena la información del usuario que realiza la evaluación.|
|viaje: Viaje|Almacena la información del viaje evaluado.|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|calificar(): void|Permite al usuario dejar una calificación sobre el viaje.|
|dejarComentario(): void|Permite al usuario dejar un comentario opcional sobre el viaje.|
# **Pasajero**
La clase Pasajero es una extensión de Usuario y representa a los usuarios que buscan y reservan viajes.
## **Métodos:**

|Método|Descripción|
| :- | :- |
|buscarViaje(): void|Permite al pasajero buscar viajes disponibles en la plataforma.|
|reservarViaje(): void|Permite al pasajero reservar un asiento en un vehículo disponible.|
# **Vehículo**
La clase Vehículo representa a los vehículos registrados por los conductores para ofrecer sus viajes.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|tipo: String|Almacena el tipo de vehículo (sedán, SUV, camioneta, etc.).|
|matrícula: String|Almacena la matrícula del vehículo.|
|capacidad: int|Almacena la capacidad de pasajeros del vehículo.|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|registrarVehiculo(): void|Permite al conductor registrar su vehículo en la plataforma.|
|actualizarDetallesVehiculo(): void|Permite actualizar la información del vehículo.|
# **Viaje**
La clase Viaje representa un viaje específico que un conductor ofrece a los pasajeros.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|origen: String|Almacena el lugar de origen del viaje.|
|destino: String|Almacena el destino del viaje.|
|horario: Date|Almacena la hora de salida del viaje.|
|conductor: Conductor|Almacena la información del conductor que ofrece el viaje.|
|estado: String|Almacena el estado del viaje (disponible, completado, cancelado).|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|publicarViaje(): void|Permite al conductor publicar un viaje en la plataforma.|
|reservarAsiento(): void|Permite reservar un asiento en el vehículo para un pasajero.|
|actualizarEstado(): void|Actualiza el estado del viaje (por ejemplo, lleno, en curso).|
# **Reserva**
La clase Reserva representa la acción de un pasajero que reserva un asiento en un viaje.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|pasajero: Pasajero|Almacena la información del pasajero que realizó la reserva.|
|viaje: Viaje|Almacena la información del viaje reservado.|
|asientoReservado: String|Almacena el asiento reservado en el vehículo.|
|estado: String|Almacena el estado de la reserva (confirmada, cancelada).|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|confirmarReserva(): void|Confirma la reserva realizada por el pasajero.|
|cancelarReserva(): void|Permite cancelar una reserva antes del inicio del viaje.|
# **Pago**
La clase Pago representa la transacción realizada por un pasajero al reservar un viaje.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|monto: float|Almacena el monto del pago por el viaje.|
|metodoDePago: String|Almacena el método de pago utilizado (tarjeta, billetera digital, etc.).|
|estado: String|Almacena el estado del pago (completado, pendiente).|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|realizarPago(): void|Realiza el pago del viaje reservado.|
|confirmarPago(): void|Confirma que el pago ha sido realizado con éxito.|
# **Notificación**
La clase Notificación gestiona el envío de mensajes a los usuarios en relación con sus viajes y reservas.
## **Atributos:**

|Atributo|Descripción|
| :- | :- |
|mensaje: String|Almacena el contenido de la notificación.|
|tipo: String|Almacena el tipo de notificación (recordatorio, cambio de ruta, etc.).|
|tiempo: Date|Almacena la fecha y hora de envío de la notificación.|
## **Métodos:**

|Método|Descripción|
| :- | :- |
|enviarNotificacion(): void|Envía la notificación al usuario correspondiente.|
<br>

## 4.8. Database Design

![Diagrama de clase](assets/images/Diagrama_clase.png)

### 4.8.1. Database Diagram

A continuación se detalla el modelo físico realizado para esta entrega, donde se consideró los requerimientos necesarios para el negocio.

![Diagrama de la Base de Datos](assets/images/databasediagram.png)
