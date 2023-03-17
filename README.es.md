<h1 align="center">PORTAFOLIO DE MANUEL GUTIÉRREZ</h1>

![Profile Banner](https://user-images.githubusercontent.com/89094000/224618817-b6034161-aafe-46d4-bd9b-26e75057c7da.png)

<div align="center"><a href="README.md">English version</a> | <a href="README.fr.md">Version française</a></div>

<p> ¡Bienvenido/a a mi portafolio! Soy un desarrollador de software con experiencia en el desarrollo de videojuegos y aplicaciones para PC y dispositivos móviles. Me especializo en proyectos 2D y Realidad Aumentada, y también tengo experiencia en el desarrollo de Realidad Virtual y 3D. Explora mi portafolio para ver ejemplos de mi trabajo y no dudes en contactarme para cualquier consulta.</p>

Información de contacto:

- E-mail: manugutier@outlook.com
- LinkedIn: https://www.linkedin.com/in/manugutier/?locale=es_ES
</p>

<details>
<summary><h2>Acerca de este portafolio</h2></summary>

Mi portafolio está organizado en cuatro categorías: XR (AR/VR), 2D, 3D y proyectos varios. Cada juego/aplicación está etiquetado con uno de tres estados:

- Publicado: El juego/aplicación ha sido publicado en una plataforma determinada o entregado directamente al cliente.
- Prototipo: El proyecto tiene alguna funcionalidad que puede ser utilizada en futuros proyectos o fue creado con fines de aprendizaje.
- En progreso: El proyecto se encuentra actualmente en desarrollo y se planea lanzar en el futuro. </p>

Además del estado del proyecto, cada elemento especificará el motor de juego utilizado para su desarrollo, si fue un esfuerzo colaborativo o independiente, mi rol/contribución y el periodo de su lanzamiento.

Puedes hacer clic/tocar en las imágenes del proyecto para ser redirigido a una demostración.
</details>

--------------------------

<details>
<summary><h2>XR (AR y VR)</h2></summary>
<h2 align="center">Honduras Ancestral </h2>

[![Ver el video](https://user-images.githubusercontent.com/89094000/224602828-5880e883-e5a8-4d52-a280-630366620999.png)](https://www.linkedin.com/feed/update/urn:li:activity:7040070646256521216/)

<p>"Honduras Ancestral" es una aplicación de Realidad Aumentada creada en un esfuerzo colaborativo con Realidad Virtual Honduras y comisionada por CANATURH. La aplicación permite a los usuarios explorar la historia y cultura de Honduras de una manera única y emocionante.

La aplicación se centra en dos sitios turísticos históricos de Honduras: las Ruinas de Copán y la Fortaleza de San Fernando de Omoa. Al utilizar marcadores de imagen en estos sitios, los usuarios pueden dar vida a personajes históricos y monumentos de la cultura de estos lugares y capturar recuerdos únicos a través de fotos y videos.

El objetivo de Honduras Ancestral es inspirar a los usuarios a profundizar en su conocimiento y apreciación por el patrimonio cultural de Honduras y América Central.

- Sitio web: https://www.hondurasancestral.com/
- Play Store: https://play.google.com/store/apps/details?id=com.VRHonduras.HondurasAncestral
- App Store: https://apps.apple.com/hn/app/honduras-ancestral/id1669387406
</p>

    Estado: Publicado
    Motor: Unity
    Tipo de proyecto: colaborativo
    Contribución: funcionalidad AR, funcionalidad UI, prototipado de interacción AR, programación
    Periodo: febrero 2023

<h2 align="center">Montaña Rusa BCIE</h2>

[![Ver el video](https://user-images.githubusercontent.com/89094000/198506478-06c4411a-fa19-4091-aeb7-22f3573a5549.png)](https://www.linkedin.com/posts/realidad-virtual-honduras_proyecto-bcie-vr-activity-6986455961334902785-_EOO?utm_source=share&utm_medium=member_desktop)

<p>Una experiencia en realidad virtual creada en colaboración con Realidad Virtual Honduras para el BCIE (Banco Centroamericano de Integración Económica). La experiencia presenta una montaña rusa con 6 estaciones, cada una representando un diorama de los proyectos realizados por el BCIE en cada uno de los países de Centroamérica, incluyendo datos relevantes sobre estos proyectos.

Este proyecto fue desarrollado como un advergame para ser presentado en eventos organizados por el BCIE.
</p>

    Estado: Publicado
    Motor: Unity
    Tipo de proyecto: colaborativo   
    Contribución: Blocking/blockout, lógica y programación de la física, diseño de escenas/niveles
    Periodo: Septiembre 2022

<h2 align="center">Portal AR</h2>

[![Ver el video](https://img.youtube.com/vi/CleX8_8_PDM/maxresdefault.jpg)](https://youtu.be/CleX8_8_PDM)

<p>Un proyecto creado con fines educativos. La aplicación utiliza la cámara para detectar superficies planas en el mundo real. Una vez que se detectan estas superficies planas, el usuario puede instanciar un portal con 3 entornos diferentes disponibles (en este proyecto, se presentan áreas de una casa).

El portal funciona en ambas direcciones, el usuario puede ingresar al entorno digital por la parte frontal o trasera, y salir igualmente por cualquiera de estos lados. El usuario también puede salir (destruir) el entorno tocando el botón correspondiente, lo que le permite colocar el portal de realidad aumentada en una posición diferente.

Complementariamente, se ha utilizado la herramienta de localización de Unity para agregar soporte de idioma en inglés, español y francés.
</p>

    Estado: Prototipo
    Motor: Unity
    Tipo de proyecto: Independiente
    Contribución: Programación, Shaders, Diseño, UI, Traducción
    Periodo: Agosto 2022
</details>

<details>
<summary><h2>Proyectos 2D</h2></summary></h2>

<h2 align="center">Personalización de personajes</h2>

[![Ver el video](https://img.youtube.com/vi/uaw7ap6sOME/maxresdefault.jpg)](https://youtu.be/uaw7ap6sOME)

<p>Este es un prototipo de pantalla de personalización de personajes. Toda la funcionalidad se puede reutilizar y adaptar a diferentes proyectos 2D donde los personajes u objetos puedan requerir personalización.

Este prototipo pasó por dos versiones: la primera manejaba la personalización creando sprites a partir de texturas en tiempo de ejecución (a través de código) y se usaba PlayerPrefs para guardar el progreso. La segunda versión, mucho más óptima, maneja la personalización y el progreso a través de scriptable objects; se realizó una refactorización completa en el sistema de personalización para que esto fuera posible, lo que facilita la adición de más elementos personalizables en este o en un proyecto 2D diferente.

El prototipo también utiliza la fecha y la hora del sistema para manejar un ciclo día/noche, cambiando el color del ambiente según la hora del día. Además, se creó un sistema de tienda e inventario.

Este proyecto también muestra el uso de una vista de desplazamiento dinámica para generar botones que representan diferentes opciones de personalización basadas en las elecciones del jugador. Esta funcionalidad permite a los jugadores navegar sin problemas a través de las opciones de personalización disponibles, mejorando la experiencia general del usuario. Al generar botones de manera dinámica que corresponden a características personalizables específicas, esta función de vista de desplazamiento es un excelente ejemplo de cómo mejorar la usabilidad de un juego mediante la implementación de un diseño de interfaz de usuario práctico y efectivo.

Aunque todavía hay margen de mejora, como mejorar los visuales de la interfaz de usuario, el potencial de esta característica es emocionante, y un mayor desarrollo solo mejorará sus posibilidades.
</p>

    Estado: Prototipo
    Motor: Unity
    Tipo de proyecto: independiente
    Contribución: todo
    Período: marzo 2023

<h2 align="center">Owl Party (Nombre tentativo)</h2>

[![Ver el video](https://img.youtube.com/vi/OS6xDnV0QVA/maxresdefault.jpg)](https://youtu.be/OS6xDnV0QVA)

<p>Este emocionante juego está programado para ser lanzado en PC y consolas, ofreciendo a los jugadores una variedad de opciones de juego. Con un modo campaña y un modo versus, los jugadores podrán elegir su estilo de juego preferido. En el modo versus, el objetivo es hacer que los oponentes caigan del escenario, proporcionando un emocionante desafío para los jugadores. Para asegurar una experiencia única para cada jugador, habrá una variedad de opciones de personalización disponibles para los personajes, como se muestra en los videos acompañantes. Ya sea jugando solo o con amigos, este juego seguramente proporcionará horas de entretenimiento para los jugadores de todos los niveles.</p>

[![Ver el video](https://img.youtube.com/vi/G3LQ4F9yeL0/maxresdefault.jpg)](https://youtu.be/G3LQ4F9yeL0)

    Estado: En progreso
    Motor: Unity
    Tipo de proyecto: independiente
    Contribución: todo
    Período: Hiatus

<h2 align="center">Internet Guardians</h2>

[![Banner_Thumbnail](https://user-images.githubusercontent.com/89094000/198503898-d2ba4be1-6c76-4974-a6b6-f3bb8ee56d65.png)](https://gutier.itch.io/internet-guardians)

<p>¡Toma el papel de un guardián solitario o únete a un amigo para proteger Internet de los malintencionados bugs en este emocionante juego de disparos! A medida que navegas por el ciberespacio, tu misión es depurar Internet y recuperar archivos perdidos, ganando puntos y medallas de Internet en el camino.

Creado para la #OperaGXGameJam organizada por Game Jolt, este juego fue diseñado en torno al tema "OVNIs e Internet" y desarrollado en un plazo de dos semanas. Para garantizar una experiencia completamente inmersiva, todos los activos del juego fueron creados por mí mismo.

- Juega en itch.io: https://gutier.itch.io/internet-guardians
- Juega en Game Jolt: https://gamejolt.com/games/internetguardians/637967
</p>

    Estado: Publicado
    Motor: GameMaker Studio 2
    Tipo de proyecto: independiente
    Contribución: todo
    Período: agosto 2021

<h2 align="center">Prototipo de estrategia 2D</h2>

[![Ver el video](https://img.youtube.com/vi/KqAdgOjmlNc/maxresdefault.jpg)](https://youtu.be/KqAdgOjmlNc)

<p>Este proyecto es un prototipo de un juego de estrategia local multijugador por turnos en 2D. Fue desarrollado en conjunto con el curso "La guía definitiva para crear un juego de estrategia 2D en Unity" en Udemy, dirigido por Blackthornprod. Las características destacadas del proyecto incluyen un sistema de barracas, seguimiento de unidades y estadísticas (con estadísticas únicas para cada clase), mecánicas de combate por turnos, animaciones cuidadosamente diseñadas, efectos de sonido inmersivos e ilustraciones detalladas. Estas características trabajan juntas para crear una experiencia de juego atractiva e interactiva para los jugadores.</p>

    Estado: Prototipo
    Motor: Unity
    Tipo de proyecto: independiente
    Contribución: todo
    Período: febrero 2021

<h2 align="center">Introdos D</h2>

[![Ver el video](https://img.youtube.com/vi/FHEM14KuGVg/maxresdefault.jpg)](https://youtu.be/FHEM14KuGVg)

<p>Este prototipo fue creado como parte de mi formación en el desarrollo de videojuegos y se realizó en conjunto con el curso "Introducción a Unity para videojuegos 2D" de Juan Diego Vázquez Moreno en Domestika. El proyecto implementa tanto mecánicas de plataforma como de hack and slash en 2D, lo que me brindó la oportunidad de aprender los principios fundamentales del desarrollo de videojuegos a través de la experiencia práctica. Este prototipo representa un hito importante en mi camino en el desarrollo de videojuegos y me ha proporcionado una base sólida sobre la cual construir.</p>

    Estado: Prototipo
    Motor: Unity
    Tipo de proyecto: independiente
    Contribución: programación, diseño, animaciones
    Período: julio 2020

</details>

<details>
<summary><h2>Proyectos 3D</h2></summary></h2>

<h2 align="center">Prototipos del Unity Junior Programmer Pathway</h2>

[![unity-junior-programmer](https://user-images.githubusercontent.com/89094000/198504459-3e206eed-8f33-4704-a7c0-12c6902d9fa5.png)](https://learn.unity.com/pathway/junior-programmer)

<p>Estos proyectos fueron desarrollados con el propósito de aprender y comprender conceptos y temas clave en el desarrollo de videojuegos. Si bien el diseño y las mecánicas pueden ser simples, sirven como ejemplos prácticos de los principios aprendidos a lo largo del curso de estudio. Al implementar los conceptos aprendidos de manera práctica, estos proyectos brindan una valiosa experiencia práctica y ayudan a solidificar la comprensión de los temas tratados. A través de la experimentación, la iteración y la aplicación del conocimiento teórico, estos proyectos sirven como escalones hacia juegos más complejos y pulidos en el futuro.

- Perfil de Unity (con prototipos): https://learn.unity.com/u/manugutier
- Insignia certificada: https://www.credly.com/badges/e29487e5-bd85-4305-8ca0-d99342828614/public_url
</p>

    Estado: Prototipo
    Motor: Unity
    Tipo de proyecto: independiente
    Contribución: programación, diseño
    Periodo: noviembre 2021

</details>

<details>
<summary><h2>Proyectos varios</h2></summary></h2>

<h2 align="center">Boo — Citas. Amigos. Chat.</h2>

![Boo — Citas. Amigos. Chat.](https://user-images.githubusercontent.com/89094000/224623479-2cd5aa5f-5767-4362-a0ee-dd61689ce931.jpeg)

<p>Boo es una aplicación móvil que utiliza el Indicador de Tipo de Myers-Briggs (MBTI) y otros elementos de psicología para conectar a sus usuarios en todo el mundo.

En el desarrollo de la aplicación, mi rol fue el de Traductor y Corrector. Específicamente, fui responsable de traducir y corregir el contenido en inglés al español y francés, asegurando que cada cadena de texto se localizara con precisión para cumplir con los estándares del idioma objetivo. En total, contribuí con 21,035 palabras traducidas y 22,353 palabras en los idiomas de destino.

- Página web: https://boo.world/
- Play Store: https://play.google.com/store/apps/details?id=enterprises.dating.boo&hl=en&gl=US
- App Store: https://apps.apple.com/us/app/boo-dating-friends-chat/id1498407272
</p>

    Estado: Publicado
    Motor: Crowdin
    Tipo de proyecto: colaborativo
    Contribución: traducción
    Periodo: octubre 2021

</details>

--------------------------

<details>
<summary><h2>Certificaciones y competencias</h2></summary></h2>

Certificaciones relacionadas con el desarrollo de software y videojuegos (ordenadas por fecha de emisión):
- [Diseño avanzado de videojuegos RPG con Unity](https://www.domestika.org/es/certificates/6f981ad72269690a1c56f7ba732179dd.pdf) - Juan Diego Vázquez Moreno en Domestika
- [Salesforce Platform App Builder](https://trailhead.salesforce.com/en/credentials/certification-detail-print/?searchString=NaXIgsLnW4H+rr2y23Mcm25BlqlnBRZFpNZOZFSl9eZc9ydpkrBfP0TkJag1lEih) - Salesforce
- [Unity Junior Programmer](https://www.credly.com/badges/e29487e5-bd85-4305-8ca0-d99342828614/public_url) - Unity Learn
- [La guía definitiva para crear un juego de estrategia 2D en Unity](https://www.udemy.com/certificate/UC-04a2331b-308f-41ca-adec-328ebff7d179/) - Blackthornprod en Udemy
- [Unity práctico: juego de plataformas 2D](https://www.linkedin.com/learning/certificates/f8e62526bd5c15cb0433dc30517d1112f50ca6116be1a717f51ef9a3321ef6ac?trk=backfilled_certificate&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_certifications_details%3BQ9Lim9EcSSqaQbvz%2F5GGqA%3D%3D) - LinkedIn
- [Introducción a Unity para videojuegos 2D](https://www.domestika.org/es/certificates/c59950c75f857e4993c5afb7eb94b6fb) - Juan Diego Vázquez Moreno en Domestika
- Introducción al diseño de videojuegos - Miríadax

Certificaciones misceláneas:
- Curso de astronomía básica - ASTRO
- Fundamentos de marketing digital - IAB Spain

Idiomas:
- Español (nativo)
- Inglés (C1)
- Francés (B2)
</details>
