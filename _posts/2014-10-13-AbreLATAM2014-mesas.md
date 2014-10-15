---
layout: post

title: Una reseña de Open Data en AbreLATAM 2014
subtitle: "Una reseña de las mesas en las que participé."
excerpt: "Una reseña de las mesas en las que participé."
cover_image: biblioteca_de_mexico.jpg

author:
  name: Noé Domínguez Porras
  twitter: noe_dgz
  gplus: +NoeDominguez
  bio: Software Engineer Open Data & Civic Innovation
  image: authors/noe.jpeg
---

Hace apenas un par de días tuvo lugar AbreLATAM 2014, el 30 de Septiembre del año en curso. Ya habíamos tenido
la oportunidad de participar en el evento que ocurrió en Uruguay durante 2013. Este año, 9 de 10 personas del equipo de
Codeando México estuvimos presentes para colaborar.


**AbreLATAM 2014 fue una desconferencia**


Personalmente me gustan mucho los seminarios y desconferencias, pues son espacios donde múltiples personas se
unen para compartir experiencias y tratar de que un grupo tenga un nivel uniforme de aprendizaje. Me gusta
porque funcionan muy bien tanto en el ambito académico como en el tecnológico y porque al final AbreLATAM 2014
fue  para todos los asistentes una plataforma de aceleración de conocimiento y relaciones de colaboración
entre latinoamericanos trabajando en transparencia y con Datos Abiertos.


Algunas de las curiosidades con las que nos encontramos en el evento fue que encontramos pocos equipos fuertemente
técnicos como Codeando México. Es ahí donde es evidente nuestra participación y el aporte que podemos hacer a la
comunidad latinoamericana.


**Las Mesas en las que participé**

AbreLATAM es un evento de solo un día y muchas experiencias que compartir. Tomé un rol activo a pesar de que no lo
había pensado así originalmente. Acompañé la discusión técnica en Open Data de las mesas en las que trabajé y tomé
notas para después compartirlas. Las discusiones se concentraron en:

* Formatos y estándares de datos abiertos.
* Cuándo usar APIs y cuando publicar bases de datos abiertos.
* ¿Cómo podemos integrar un repositorio de datos abiertos en América Latina?


***Formatos y estándares de datos abiertos***

En la mesa de formatos y estándares de datos abiertos se dio una plática muy técnica pero al mismo tiempo muy
nutrida para los que fueron sin saber mucho al respecto. Discutimos mucho sobre los formatos en los que se deben de
publicar los datos abiertos. En ese momento, sin intervenir en temas de data descriptiva o interconectada que
constituye las 4 y 5 estrellas del [5 star Open Data](http://5stardata.info/), documentamos:

* Necesitamos formatos legibles por máquinas y que sean procesables. Es decir necesitamos saber que nuestro documento
es adecuado para ser importado a cualquier programa, libre o propietario, para hacer cálculos.

* Acompañar nuestros datos con un diccionario de datos es muy adecuado sobre todo para explicar las variables y dar
algunos ejemplos sobre cómo usar esos datos o sobre cómo fueron usados en esta base de datos. Vean un ejemplo en el
[Dataset del reto viajes transparentes del IFAI](http://datamx.io/dataset/viajes-de-trabajo-de-los-servidores-publicos-del-ifai).

* La codificación de caracteres en los datos también deben de ser estándar e interoperable entre sistemas operativos.

* Debemos incluir una fuente de los datos pues siempre hay un organismo o una persona responsable detrás de esos datos.
Vean los campos descritos en [Project Open Data](http://project-open-data.github.io/) como 
[mbox](http://project-open-data.github.io/schema/#mbox) y
[publisher](http://project-open-data.github.io/schema/#publisher).

* El tenedor de los datos debe de extender una licencia que debe de ser abierta; es decir, se debe ser explícito sobre cómo
se pueden reutilizar esos datos. Pueden revisar el proyecto [Open Definition](http://opendefinition.org/licenses/) de
la [Open Knowledge Foundation](http://okfn.org) donde analizan distintas licencias para Open Data, es de hecho aquí
de donde se importan todas las licencias a elegir por defecto en el administrador de datos abiertos [CKAN](http://ckan.org).

* Para documentar los  datasets en México estamos  utilizando el estándar DCAT, así como también lo están usando en la
Unión Europea. Pueden ver más detalles en el perfil definitivo de aplicación del estándar DCAT para portales de datos en
la Unión Europea
([DCAT-AP](https://joinup.ec.europa.eu/asset/dcat_application_profile/asset_release/dcat-application-profile-data-portals-europe-final#download-links)).


En términos generales y no muy distinto al contexto mexicano las organizaciones están preocupadas sobre cómo podemos
ayudar a que los gobiernos publiquen más datos y a que las ONGs los utilicen de manera activa para tomar decisiones
e informar a la ciudadanía sobre problemas específicos. En general creo que hubo un consenso muy evidente en esta edición
sobre el uso de Datos Abiertos en periodismo y es que las visualizaciones de datos abiertos son una de las vías más
efectivas de comunicación.

Otra de las preocupaciones entre las ONGs es sobre la completitud de los datos de gastos en instancias de gobierno.
El ciclo objetivo, coincidimos, es desde que se genera un presupuesto o se asigna hasta que se ejerce y tiene impacto
en la vida de los ciudadanos. Recordemos que los gobiernos toman decisión en nombre de los ciudadanos, por eso la preocupación
de evaluar el impacto en la vida de los ciudadanos. En el mismo tema, Marcela Rozo del Banco Mundial nos platicó sobre
la iniciativa del estándar de Datos Abiertos para Contrataciones Abiertas, que está actualmente en Beta
y se puede comentar en idioma Inglés en su [sitio web](http://www.open-contracting.org/beta-release-open-contracting-data-standards).
De hecho tuve el gusto de participar en un Sprint en el PyconUS 2014 y en un post futuro les platicaré un poco más.


Técnicamente hablando nos preocupa también la educación dentro de las instancias de gobierno para que se reconozcan como
un ente de operación y generación de datos. La integración de sus datos debe ser prioridad pues actualmente se generan
de manera aislada. Esto puede llevarnos a tomar mejores decisiones y es una de las capacidades que tenemos que desarrollar
tan pronto como sea posíble, recordemos que en enero de este año se nombró el primer Chief Data Scientist que preside el
[Data Sciences Group](http://www.ida.gov.sg/About-Us/Organisation-and-Team/Data-Sciences-Group) en Singapur.

Para cerrar nuestra experiencia en esta mesa hablamos sobre [Datamx.io](http://datamx.io), en la cual compartí sobre [nuestro centro de apertura
de datos](http://apertura.datamx.io) donde ayudamos a particulares y a organizaciones a convertir datos públicos en formatos cerrados o propietarios en datos de formatos legibles por máquinas para su análisis.

***Base homologada de datos en la región. ¿Open Data u Open API?***

Otra de las mesas que resulta ser muy interesante es donde discutimos sobre el uso de  **interfaces de programación de
aplicaciones (API por sus siglas en inglés)** contra  el uso de bases de datos en formatos abiertos. Una parte importante de esta discusión
ocurrió alrededor de los casos de uso sobre cuando utilizar una interfaz de programación de aplicaciones y sobre cuándo utilizar
una base en formatos abiertos. El sueño de todo programador y la tendencia del internet de las cosas es que todo tenga una API,
sin embargo es mucho más costoso que la sola publicación de los datos en un portal. Además, concluimos que en algunas ocasiones
las bases de datos sí necesitan API, como cuando los datos se deben de publicar con una periodicidad diaria o aún más frecuente. En otras palabras, necesitamos una API cuando un dato debe ser inmediato o cuando facilita tareas periódicas a quien publica. Sin embargo,
hay ciertos tipos de datos que aunque no sean actualizados de manera periódica o muy frecuente también es importante que estén
en formato de API, un caso de uso muy particular pueden ser datos de alerta sobre emergencias o datos que afecten la seguridad
de los ciudadanos.

Yendo un poco mas hacia la función de contraloría o testigo de los datos, las API deben de tener un acompañamiento de documentos en formatos
abiertos. Los ciudadanos deben de poder bajar una "foto" del estado actual de la base de datos. En México se comentó que hay bases de datos
que cambian de la noche a la mañana.

Como conclusión personal de AbreLATAM 2014, me quedo con que hay que llevar los datos a la ciudadanía con comunicación efectiva.
No vale la pena duplicar esfuerzos, ni aplicaciones. Es inmenso el potencial de cooperación entre latinoamericanos.
Además Codeando México seguirá teniendo un rol muy activo y propositivo  para que el software que use activamente datos suceda en la región.

Me gustaría también felicitar a nuestra organización hermana [SocialTIC](http://socialtic.org) por la realización del evento
y por su constante preocupación de conectar organizaciones en América Latina para resolver los problemas sociales de la región.


Foto: [La ciudad de los libros (CC)](https://www.flickr.com/photos/pauloslachevsky/14480968212/in/photolist-o4CKkJ-o4sBBB-4Y1zJJ-o2W3Gd-nMg6qb-o4CvCd-o4soFX-o4L3Pv-o4DEam-nMgeR9-nMgz6P-nMgfdQ-o4Dtpo-o4s6TD-4XWxza-o4Kj5T-9bJdSZ-9Kgh5Z-9bMir5-9bJdNX-9bJdVi-9bMirY-9bMisU-9bMivh-9bJdR4-oDFsnV).
Flickr/pauloslachevsky
