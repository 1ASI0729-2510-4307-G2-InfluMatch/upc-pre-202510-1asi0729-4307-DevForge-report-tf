# **Capítulo V: Product Implementation, Validation & Deployment**

## **5.1. Software Configuration Management**
### **5.1.1. Software Development Environment Configuration**

**Product UX/UI Desing**

Figma: Plataforma o aplicación que se usa para la elaboración de todo tipo de prototipos y diseño digital. En nuestro proyecto será utilizado para el desarrollo de los Wireframes y el Wireflow en el landing page, así mismo tmb estara en el diseño de WebApp y MobileApp.
Ruta referencial: https://www.figma.com/

**Software Development**

* Visual Studio Code: Plataforma que se usa como el entorno de desarrollo y compilación del código, usado por el dominio que los miembros del equipo tienen sobre esta herramienta. Esta IDE es de facil acceso, incluye diversas opciones de configuración así como la opción de añadir extensiones y tiene un soporte amplio de diversos lenguajes de programación.
  Ruta referencial: https://code.visualstudio.com/
* HTML5: El HyperText Markup Language es utilizado para el desarrollo de código de etiquetas para páginas web.
  Ruta referencial: https://www.w3schools.com/html/html5_syntax.asp
* CSS: El Cascading Style Sheets maneja el diseño de las páginas web. Este mismo siempre va relacionado y de la mano con HTML.
  Ruta referencial: https://google.github.io/styleguide/htmlcssguide.html
* Javascript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de usuario dentro de la aplicación.
  Ruta de referencia https://developer.mozilla.org/es/docs/Web/JavaScript

**Software Deployment**

Git: Herramienta que sirve para control de versiones. Permite registrar y gestionar las diferentes versiones del programa. Se utilizará para teber un control en los cambios y reducir la corrección de errores. Los miembros del equipo podrán acceder mediante la línea de comandos en sus sistemas locales.
Ruta de referencia https://git-scm.com/

**Software Documentation and Project Management**

Github: Plataforma que funciona como nube la cual alojará los repositorios de código del proyecto. Facilita la colaboración en tiempo real y la revisión de contribuciones de cada miembro del equipo. Los miembros del equipo pueden acceder a través de sus navegadores web. 
Ruta de referencia https://github.com/

### **5.1.2. Source Code Management**

Para el nuestro proyecto usaremos el flujo de trabajo propuesto por el modelo GitFlow. Github sera usada como plataforma y sistema de control de versiones. Se detallará a continuación como se implementa GitFlow en el repositorio. Así mismo se proporcionaran los URL de los repositorios de GitHub para cada producto: Landing Page, Web Services y Frontend Web Applications.

**Repositorio de Github**

* Repositorio: 
  https://github.com/1ASI0729-2510-4307-G2-InfluMatch
* Landing Page: 

* Frondend: https://github.com/1ASI0729-2510-4307-G2-InfluMatch/upc-pre-202510-1asi0729-4307-DevForge-report-tf

**Flujo de trabajo GitFlow**
El flujo de trabajo a utilizar para el desarrollo del proyecto fue el planteado por Vincent Driessen en "A successful Git branching model".

**Estructuras de Branches (Ramas)**
  1. **Master Branch (Rama Principal):** Esta rama esta destinada a la producción de la aplicación, cada cambio deberá tener autorización de un compañero de equipo para evitar cambios sin verificar.
  2. **HotFix Branch:** Esta rama incluye todas las versiones que poseen errores y que, con cada arreglo, se despliegue otra vez a la Main Branch además de implementarla en lo que será Develop Branch.
  3. **Develop Branch:**  Esta rama se añade las constantes implementaciones de los features.
  4. **Feature Branch:** Esta rama incluye cada funcionalidad desarrollada por el equipo. Cuando una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto.
  5. **Release Branch:** Esta rama se utiliza para mantener una instancia de la rama develop.

### **5.1.3. Source Code Style Guide & Conventions**
Usaremos buenas prácticas en cuanto al código de manera que sea coherente y sostenible.

HTML:
* Cada etiqueta, id, nombre y clase será nombrada usando Lowercase.
* Utilizar UTF-8.
* Redacción en inglés.
* En cada referencia a un archivo, colocar el tipo de archivo (.css, .js).
*Terminar cada etiqueta con />.

CSS:
* Width del body al 100%.
* En cuanto a las imágenes, especificar el ancho (Width) de acuerdo a la etiqueta padre.
* Cada etiqueta, nombre y clase será nombrada de acuerdo al propósito y clasificación del elemento.
* Separación de palabras con un guion "-".
* Margin y padding en "*" con valor de 0.

### **5.1.4. Software Deployment Configuration**

## **5.2. Landing Page, Services & Applications Implementation**

### **5.2.1. Sprint 1**
En la siguiente sección se expondrá el sprint #1, el cual contiene la versión inicial del proyecto, mostrando la estructura, el diseño y los resultados obtenidos de la landing page.

#### **5.2.1.1. Sprint Planning 1**

Sprint # |Date |Time |Location |Prepared By |Attendees|
| :- | :- | :- | :- | :- | :- |
|1|10/04/2025 |6:00 pm|Reunión mediante Meet|Nelson Pereira|<p>Sebastian Escobar. </p><p>Luis Rubio.</p><p>Irving Allcca.</p><p>Daniel Rodriguez.</p>|
|Sprint 1 Goal |Sprint 1 Velocity |Sum of Story Points||||
|Diseñar y desarrollar la landing page informativa para la aplicación InfluMatch..|<p>18</p><p></p>|18||||


#### **5.2.1.2. Sprint Backlog 1**
Durante el primer sprint, el equipo centró sus esfuerzos en desarrollar una landing page visualmente atractiva y funcional, distribuyendo las tareas a través del tablero de Sprint de acuerdo con las competencias de cada integrante.

|Sprint #||Sprint 1||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|User Story||Work Item / Task||||||
|Id|Title|Id|Title|Descripción|Estimación (Hours)|Assigned to|Status (In -process / To - review / Done)|
|US01|Descripción de la web|UT01|Acerca de la web|Descripción de lo que trata nuestra pagina web. |4|Mathias Javier|Done|
|US02|Accesibilidad del contenido|UT02|Disponibilidad accesible del contenido.|Que la página muestre el contenido correctamente (imágenes y enlaces).|8|Marco Nakasone y Sebastian Escobar|Done|
|US02|Accesibilidad del contenido|UT03|Diseño responsive de la página|Que la página se visualice correctamente en cualquier dispositivo.|6|Ian Macavilca|Done|



#### **5.2.1.3. Development Evidence for Sprint Review**

#### **5.2.1.4. Testing Suite Evidence for Sprint Review**


#### **5.2.1.5. Execution Evidence for Sprint Review**


#### **5.2.1.6. Services Documentation Evidence for Sprint Review**
En esta entrega del proyecto, el enfoque principal fue el desarrollo de la landing page, por lo que no se requirió la implementación de servicios adicionales.

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**
En esta ocasión se utilizó GitHub Pages para publicar la landing page, lo cual permitió desplegar el sitio directamente desde el código alojado en un repositorio. A continuación se presenta el enlace a la landing page: https://1asi0729-2510-4307-g2-influmatch.github.io/Landing-Page-InfluMatch/ 

<div style="text-align: center;">
  <img src="https://i.imgur.com/856mXmj.png"  width="100%" />
</div>


#### **5.2.1.8. Team Collaboration Insights during Sprint**
Para el desarrollo de este proyecto se emplearon diversas herramientas, entre las cuales destacan Visual Studio Code y el sistema de control de versiones Git. La landing page presentada fue segmentada en distintas secciones, asignadas a los integrantes del equipo de manera individual. Finalmente, un miembro se encargó de integrar las contribuciones de cada participante, consolidando así el producto final.

<div style="text-align: center;">
  <img src="https://i.imgur.com/g3atknY.png" width="300%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/6AhCCLF.png" width="100%" />
</div>

#### **Avance de Conclusiones**
- Durante el desarrollo de la plataforma InfluMatch, el equipo ha conseguido implementar con éxito las funcionalidades y características previstas, generando una experiencia de usuario eficaz que facilita la vinculación entre influencers y empresas.

- La construcción de InfluMatch ha servido como evidencia de la capacidad del equipo para transformar requerimientos y especificaciones en soluciones funcionales, logrando una estructura sólida y un diseño atractivo que mejora la interacción entre marcas e influencers.

- La colaboración y el trabajo conjunto han sido claves para el logro del proyecto, permitiendo compartir conocimientos y habilidades en el uso de herramientas avanzadas.

- Igualmente, el uso de plataformas de diseño como Figma ha permitido crear una interfaz uniforme y estéticamente agradable que refuerza la imagen profesional de InfluMatch. Por su parte, Trello ha sido útil para mantener una organización eficiente y un seguimiento adecuado de las tareas, lo que ha favorecido el cumplimiento de los objetivos.

- Este primer desarrollo ha establecido una base sólida para la expansión de la plataforma en etapas futuras, garantizando una infraestructura tecnológica estable y con potencial de escalabilidad.

#### **Bibliografia**
1. Aglowid IT Solutions. (2024). **Top 12 Angular best practices to adapt in 2024**. *Aglowid IT Solutions*. [https://aglowiditsolutions.com](https://aglowiditsolutions.com)
2. C# Corner. (2024). **Using trackBy with ngFor to optimize rendering**. *C# Corner*. [https://www.c-sharpcorner.com](https://www.c-sharpcorner.com)
3. C# Corner. (2024). **Implementing lazy loading in Angular for performance improvements**. *C# Corner*. [https://www.c-sharpcorner.com](https://www.c-sharpcorner.com)
4. C# Corner. (2024). **Handling Observables to prevent memory leaks in Angular**. *C# Corner*. [https://www.c-sharpcorner.com](https://www.c-sharpcorner.com)
5. Aglowid IT Solutions. (2024). **The single responsibility principle in Angular development**. *Aglowid IT Solutions*. [https://aglowiditsolutions.com](https://aglowiditsolutions.com)
11. Aglowid IT Solutions. (2024). **Optimizing Angular templates for better performance**. *Aglowid IT Solutions*. [https://aglowiditsolutions.com](https://aglowiditsolutions.com)
12. Aglowid IT Solutions. (2024). **Breaking large components into manageable sizes in Angular**. *Aglowid IT Solutions*. [https://aglowiditsolutions.com](https://aglowiditsolutions.com)
29. **TutorialsPoint**. (2024). *Firebase for backend integration with Angular applications*. [https://www.tutorialspoint.com](https://www.tutorialspoint.com)
30. **C# Corner**. (2024). *Managing Firebase environment variables for staging and production*. [https://www.c-sharpcorner.com](https://www.c-sharpcorner.com)


#### **Anexo**
1. Despliegue del Landing Page: https://1asi0729-2510-4307-g2-influmatch.github.io/Landing-Page-InfluMatch/
2. Figma con los User Flow Diagrams, wireframes y mockups de la landing page.: https://www.figma.com/design/o8mqq96SoWiUWDlFJZYB8T/InfluMatch---Mockups-Wireframes?node-id=0-1&p=f