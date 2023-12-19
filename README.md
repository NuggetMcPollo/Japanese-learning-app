# Japanese learning app
Japanese learning app

Este proyecto es una aplicación, desarrollada en Kotlin y optimizada para Android mediante Jetpack Compose, representa una innovadora solución para el aprendizaje autodidacta del idioma japonés. Con un enfoque en la flexibilidad y la accesibilidad, ofreciendo una experiencia de aprendizaje integral, desde los fundamentos hasta conceptos avanzados, adecuada tanto para principiantes como para estudiantes avanzados.

La aplicación destaca por su comprensivo módulo de vocabulario, que no solo proporciona traducciones, sino también ejemplos contextuales para facilitar la comprensión y el uso correcto de las palabras y frases en japonés. Cuenta con historias únicas y cautivadoras, diseñadas específicamente para mejorar la comprensión auditiva y la fluidez en el idioma.

Cuenta con un sistema de recordatorios personalizados. Asegurando una constante motivación y seguimiento del progreso, incentivando a los usuarios a mantenerse comprometidos con sus lecciones y objetivos de aprendizaje.

Está diseñada siguiendo los principios de Clean Architecture y SOLID, y utiliza varias tecnologías y bibliotecas importantes para proporcionar una experiencia robusta y escalable.



https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/6c498a1b-24f6-4ca9-b1c4-c31ffc6abb12

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/66f375e4-e184-4fa3-aec4-3cf16c592d74

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/76413f7f-ffe5-4e64-9e23-4b1034e0a052

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/f2f31932-e1d8-422e-ba37-1f898bcc5531

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/93b36a77-be42-4687-92d6-1fe206ce8d46

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/0a30e56f-fd74-4a8d-a0ba-3c3bc11824a3

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/0998c5cc-3f04-473f-8693-2a7cecd62adf

https://github.com/NuggetMcPollo/Japanese-learning-app/assets/119012808/4c9dce83-44f7-490c-99d8-26c108a8efcb



🛠 Tech Stack

* Clean Architecture: El proyecto está estructurado siguiendo el patrón de Clean Architecture, lo que facilita la separación de responsabilidades y mejora la mantenibilidad del código.
* SOLID: Los principios SOLID (Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) se aplican en el diseño de la aplicación para promover un código limpio, modular y extensible.
* Inyección de Dependencias - Dagger-Hilt: Se utiliza Dagger-Hilt para realizar la inyección de dependencias, lo que simplifica la gestión de las dependencias y permite una mejor escalabilidad y prueba unitaria del código.
* Jetpack Compose: La interfaz de usuario se desarrolla utilizando Jetpack Compose, el moderno toolkit de UI de Android que facilita la creación de interfaces de usuario flexibles y dinámicas.
* Firebase Authentication: Se integra Firebase Authentication para proporcionar un sistema de autenticación seguro y confiable para los usuarios de la aplicación.
* Room: Se utiliza Room, la biblioteca de persistencia de Android, para almacenar los datos de los recordatorios por dia en una base de datos local y permitir un acceso rápido y eficiente a ellos.
* Retrofit: Se utiliza Retrofit para realizar las llamadas a una API remota y obtener datos relacionados al vocabulario, lo que permite una sincronización eficiente y actualizada de la información.
* Notificaciones: La aplicación permite configurar recordatorios personalizados por dia y muestra notificaciones en el dia y hora especificada para ayudar a los usuarios a seguir sus lecciones.
* AlarmManager: El componente AlarmManager de Android se utiliza para programar las notificaciones y garantizar que se muestren en los momentos adecuados.
* Broadcast Receivers: Se utilizan Broadcast Receivers para gestionar el agregado de alarmas cuando el usuario reinicia el dispositivo, y cuando suena una alarma, para configurar la siguiente.
* Offline-First: La aplicación está diseñada siguiendo el enfoque "Offline-First", lo que significa que la funcionalidad principal está disponible incluso cuando el dispositivo está sin conexión a Internet
* Data Preferences: Implementa este sistema para brindar al usuario personalizacion de elementos como la continuidad de la reproducción musical, fondo de la aplicación, entre otras cosas. Asegurando que sus preferencias y progresos sean recordados y aplicados consistentemente.
