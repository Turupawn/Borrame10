PRAGMA foreign_keys=OFF;
BEGIN TRANSACTION;
CREATE TABLE IF NOT EXISTS "posts" ("id" integer not null primary key autoincrement, "uuid" varchar(36) not null, "title" varchar(150) not null, "slug" varchar(150) not null, "markdown" text null, "mobiledoc" text null, "html" text null, "amp" text null, "image" text null, "featured" boolean not null default '0', "page" boolean not null default '0', "status" varchar(150) not null default 'draft', "language" varchar(6) not null default 'en_US', "visibility" varchar(150) not null default 'public', "meta_title" varchar(150) null, "meta_description" varchar(200) null, "author_id" integer not null, "created_at" datetime not null, "created_by" integer not null, "updated_at" datetime null, "updated_by" integer null, "published_at" datetime null, "published_by" integer null);
INSERT INTO "posts" VALUES(2,'b32157bf-8509-43df-aa99-73a8f5cd58dd','Acerca de','acerca-de','![](www.afsps.org/content/images/2017/07/portada-oficial-AFSPS.jpg)


#Alianza Francesa de San Pedro Sula, 45 años de #plusfrancais 


La Alianza Francesa nace en Paris, Francia, en 1883, nuestra misión es la enseñanza del idioma francés, la promoción y difusión de la cultura en general, especialmente de la cultura francesa. Actualmente es una de las redes culturales mas grande del mundo con presencia en 132 países a través de aproximadamente 800 centros culturales.

La Alianza Francesa de San Pedro Sula se constituyó como centro cultural y centro de estudios del idioma francés y organización no gubernamental sin fines de lucro en febrero de 1972. Operó inicialmente en el Barrio el Centro, luego en Río de Piedras, y actualmente cuenta con un edificio funcional y moderno, con amplio parqueo y seguridad privada, en el sector El Playón al noroeste de la ciudad.

La Alianza Francesa ha sido, sobre las décadas, un constante pilar para el enriquecimiento cultural de la comunidad sampedrana y las relaciones entre Francia y Honduras.

Actualmente en la Alianza Francesa de San Pedro Sula contamos con un equipo pedagógico especializado en la enseñanza del francés, proponiendo cursos de francés para niveles básico, intermedio y avanzado, adaptados a todo público, ofreciendo cursos para niños (7-9), pre-adolescentes (10-12), adolescentes (13-15) y adultos (16 en adelante). Además, brindamos cursos profesionales de música (violín, guitarra, y piano) y pintura.

La Alianza Francesa de San Pedro Sula también ofrece una rica programación cultural que abarca una diversidad de disciplinas, brindando espacio y apoyo tanto a artistas nacionales como internacionales. La Alianza propicia intercambios culturales de Honduras y Francia, promueve la música, las artes visuales y escénicas y organiza constantemente conciertos, muestras de artes, mesas de debate, talleres en varias disciplinas, conferencias y otros eventos.',NULL,'<p><img src="/content/images/2017/07/portada-oficial-AFSPS.jpg" alt="" /></p>

<h1 id="alianzafrancesadesanpedrosula45aosdeplusfrancais">Alianza Francesa de San Pedro Sula, 45 años de #plusfrancais</h1>

<p>La Alianza Francesa nace en Paris, Francia, en 1883, nuestra misión es la enseñanza del idioma francés, la promoción y difusión de la cultura en general, especialmente de la cultura francesa. Actualmente es una de las redes culturales mas grande del mundo con presencia en 132 países a través de aproximadamente 800 centros culturales.</p>

<p>La Alianza Francesa de San Pedro Sula se constituyó como centro cultural y centro de estudios del idioma francés y organización no gubernamental sin fines de lucro en febrero de 1972. Operó inicialmente en el Barrio el Centro, luego en Río de Piedras, y actualmente cuenta con un edificio funcional y moderno, con amplio parqueo y seguridad privada, en el sector El Playón al noroeste de la ciudad.</p>

<p>La Alianza Francesa ha sido, sobre las décadas, un constante pilar para el enriquecimiento cultural de la comunidad sampedrana y las relaciones entre Francia y Honduras.</p>

<p>Actualmente en la Alianza Francesa de San Pedro Sula contamos con un equipo pedagógico especializado en la enseñanza del francés, proponiendo cursos de francés para niveles básico, intermedio y avanzado, adaptados a todo público, ofreciendo cursos para niños (7-9), pre-adolescentes (10-12), adolescentes (13-15) y adultos (16 en adelante). Además, brindamos cursos profesionales de música (violín, guitarra, y piano) y pintura.</p>

<p>La Alianza Francesa de San Pedro Sula también ofrece una rica programación cultural que abarca una diversidad de disciplinas, brindando espacio y apoyo tanto a artistas nacionales como internacionales. La Alianza propicia intercambios culturales de Honduras y Francia, promueve la música, las artes visuales y escénicas y organiza constantemente conciertos, muestras de artes, mesas de debate, talleres en varias disciplinas, conferencias y otros eventos.</p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-06-28 13:33:51',1,'2017-07-12 07:44:45',1,'2017-06-28 13:33:54',1);
INSERT INTO "posts" VALUES(3,'f37b3a82-bba8-4699-ab55-989e0cbbef37','Cursos','cursos','
######NIÑOS (7-9 años)

* Lunes y miércoles
   3:00 – 4:30 p.m.

######PRE-ADOLESCENTES (10-12 años) 
 
* Martes y jueves
   4:30 – 6:00 p.m.

######ADOLESCENTES (13-15 años)
 
* Martes y jueves
   4:30 – 6:00 p.m.

######ADULTOS (16 años en adelante):

* Lunes y miércoles 
   6:30 – 8:00 p.m. 
* Viernes 8:30 – 11:30 a.m.
* Sábados 8:00 – 11:00 a.m.
* Sábados 12:00 – 3:00 p.m.

(HORARIOS POR CONFIRMAR)

##Contacto
Teléfono **2566-3733**
Correo **alianzafrancesasps@gmail.com**
',NULL,'<h6 id="nios79aos">NIÑOS (7-9 años)</h6>

<ul>
<li>Lunes y miércoles
3:00 – 4:30 p.m.</li>
</ul>

<h6 id="preadolescentes1012aos">PRE-ADOLESCENTES (10-12 años)</h6>

<ul>
<li>Martes y jueves
4:30 – 6:00 p.m.</li>
</ul>

<h6 id="adolescentes1315aos">ADOLESCENTES (13-15 años)</h6>

<ul>
<li>Martes y jueves
4:30 – 6:00 p.m.</li>
</ul>

<h6 id="adultos16aosenadelante">ADULTOS (16 años en adelante):</h6>

<ul>
<li>Lunes y miércoles 
6:30 – 8:00 p.m. </li>
<li>Viernes 8:30 – 11:30 a.m.</li>
<li>Sábados 8:00 – 11:00 a.m.</li>
<li>Sábados 12:00 – 3:00 p.m.</li>
</ul>

<p>(HORARIOS POR CONFIRMAR)</p>

<h2 id="contacto">Contacto</h2>

<p>Teléfono <strong>2566-3733</strong> <br />
Correo <strong>alianzafrancesasps@gmail.com</strong></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-06-28 13:35:05',1,'2017-07-14 17:41:44',2,'2017-06-28 13:35:09',1);
INSERT INTO "posts" VALUES(4,'540b81ac-3933-4e92-9173-eac2686cc683','Contacto','contacto','#Nuestra dirección:
Colonia Altavista, Sector el Playón, San Pedro Sula, <br>Cortés, Honduras C.A.

Teléfono: **2566-3733**
Celular/Wpp: **9437-3857**
Correo: **alianzafrancesasps@gmail.com**
Facebook: **[@afsps](https://www.facebook.com/afsps)**
Instagram: **[@alianzafrancesasps](https://www.instagram.com/alianzafrancesasps/)**



<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3844.2239121739494!2d-88.03520548469643!3d15.52612270788594!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8f665b66a0ab5443%3A0x542bd3aabbb99654!2sAlianza+Francesa%2C+San+Pedro+Sula+21102!5e0!3m2!1ses-419!2shn!4v1498742479133" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>',NULL,'<h1 id="nuestradireccin">Nuestra dirección:</h1>

<p>Colonia Altavista, Sector el Playón, San Pedro Sula, <br>Cortés, Honduras C.A.</p>

<p>Teléfono: <strong>2566-3733</strong> <br />
Celular/Wpp: <strong>9437-3857</strong> <br />
Correo: <strong>alianzafrancesasps@gmail.com</strong> <br />
Facebook: <strong><a href="https://www.facebook.com/afsps">@afsps</a></strong> <br />
Instagram: <strong><a href="https://www.instagram.com/alianzafrancesasps/">@alianzafrancesasps</a></strong></p>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3844.2239121739494!2d-88.03520548469643!3d15.52612270788594!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8f665b66a0ab5443%3A0x542bd3aabbb99654!2sAlianza+Francesa%2C+San+Pedro+Sula+21102!5e0!3m2!1ses-419!2shn!4v1498742479133" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>',NULL,'/content/images/2017/07/Screen-Shot-2017-07-25-at-11.17.23-AM.png',0,0,'published','en_US','public',NULL,NULL,2,'2017-06-28 13:36:09',1,'2017-07-25 17:17:49',2,'2017-06-28 13:36:09',1);
INSERT INTO "posts" VALUES(5,'026114e5-82b6-48f9-999c-6f94a0094052','Concierto para flauta sola por Gaspar Hoyos','concierto-para-flauta-sola-por-gaspar-hoyos','Gaspar Hoyos saca de sus orígenes colombianos la luz y el calor de sonido que iluminan los escenarios internacionales que recorre como solista
Gaspar Hoyos es reconocido como uno de los flautistas más dinámicos y virtuosos de su generación. Su talento innato y gran musicalidad lo han llevado a realizar giras en Suramérica, los Estados Unidos, Europa y Asia, donde ha sido un unánimemente aclamado por el público y la crítica.
Les invitamos cordialmente a compartir con nosotros este **martes 9 de mayo a las 7:30 p.m.** en la sede de la Alianza Francesa de San Pedro Sula.
La entrada es gratuita, el cupo es limitado, por lo que les rogamos confirmar su asistencia.

##Reserva tu cupo

Para sus reservaciones llamar al **Tel.: 2566-3733.**
¡Les esperamos!

##Este evento cuenta con el patrocinio de

* Ambassade de France au Honduras
* CASA DEL RON
* COPANTL, Hotel & Convention Center
* LA CELIA, Marcas Mundiales de Honduras

![](www.afsps.org/content/images/2017/06/18319228_439169119785511_2590704921008549693_o-1.jpg)',NULL,'<p>Gaspar Hoyos saca de sus orígenes colombianos la luz y el calor de sonido que iluminan los escenarios internacionales que recorre como solista <br />
Gaspar Hoyos es reconocido como uno de los flautistas más dinámicos y virtuosos de su generación. Su talento innato y gran musicalidad lo han llevado a realizar giras en Suramérica, los Estados Unidos, Europa y Asia, donde ha sido un unánimemente aclamado por el público y la crítica. <br />
Les invitamos cordialmente a compartir con nosotros este <strong>martes 9 de mayo a las 7:30 p.m.</strong> en la sede de la Alianza Francesa de San Pedro Sula. <br />
La entrada es gratuita, el cupo es limitado, por lo que les rogamos confirmar su asistencia.</p>

<h2 id="reservatucupo">Reserva tu cupo</h2>

<p>Para sus reservaciones llamar al <strong>Tel.: 2566-3733.</strong> <br />
¡Les esperamos!</p>

<h2 id="esteeventocuentaconelpatrociniode">Este evento cuenta con el patrocinio de</h2>

<ul>
<li>Ambassade de France au Honduras</li>
<li>CASA DEL RON</li>
<li>COPANTL, Hotel &amp; Convention Center</li>
<li>LA CELIA, Marcas Mundiales de Honduras</li>
</ul>

<p><img src="/content/images/2017/06/18319228_439169119785511_2590704921008549693_o-1.jpg" alt="" /></p>',NULL,'/content/images/2017/06/RecitalGasparHoyos-Afiche-03-2.png',0,0,'published','en_US','public',NULL,NULL,2,'2017-06-28 13:41:21',1,'2017-07-12 07:45:36',1,'2017-06-28 13:43:13',1);
INSERT INTO "posts" VALUES(6,'f2daf9b7-bb9f-40cf-810c-cedc9a57d318','Concurso Internacional de Fotografía','concurso-internacional-de-fotografia','La Alianza Francesa de San Pedro Sula convoca al concurso internacional de fotografía de la Fondation Alliance Française 2017 y **Gana un viaje de una semana a París** y una exposición de todas las obras elegidas en una Galería de Paris.
La temática de este año es **“La Mode et Les Codes Vestimentaries"** (La moda y los códigos de vestimenta).

##Inscripción
El plazo para enviar la hoja de inscripción y las fotografías termina el **26 de Junio de 2017**.
Solicita las fichas de Inscripción y reglamento por Inbox en [nuestra página de Facebook](https://www.facebook.com/afsps/).

![](www.afsps.org/content/images/2017/06/18955078_454518608250562_8546991284853702026_o.jpg)',NULL,'<p>La Alianza Francesa de San Pedro Sula convoca al concurso internacional de fotografía de la Fondation Alliance Française 2017 y <strong>Gana un viaje de una semana a París</strong> y una exposición de todas las obras elegidas en una Galería de Paris. <br />
La temática de este año es <strong>“La Mode et Les Codes Vestimentaries"</strong> (La moda y los códigos de vestimenta).</p>

<h2 id="inscripcin">Inscripción</h2>

<p>El plazo para enviar la hoja de inscripción y las fotografías termina el <strong>26 de Junio de 2017</strong>. <br />
Solicita las fichas de Inscripción y reglamento por Inbox en <a href="https://www.facebook.com/afsps/">nuestra página de Facebook</a>.</p>

<p><img src="/content/images/2017/06/18955078_454518608250562_8546991284853702026_o.jpg" alt="" /></p>',NULL,'/content/images/2017/06/Untitled.jpg',0,0,'draft','en_US','public',NULL,NULL,2,'2017-06-28 15:14:58',1,'2017-07-12 07:45:59',1,'2017-06-28 15:21:10',1);
INSERT INTO "posts" VALUES(7,'74641c17-5cb6-4ac2-b6ea-125d84a8c805','Segunda Sesión para aplicar al Programa de Maestrías a Larga Distancia','apertura-de-una-segunda-sesion-para-aplicar-al-programa-de-maestrias-a-larga-distancia','Programa de formación de Maestría a distancia:
Becas de maestría a distancia, movilidad de maestría y doctorado, y doctorado en alternancia ha sido prorrogada hasta el 11 de junio por el IFAC.

Para mayor información visita la página de [Institut Français](http://institutfrancais-ifac.com/instituto-frances/convocatorias/convocatoria-programa-de-movilidad-centram-sup-maestria-a-distancia/?lang=es).

![](www.afsps.org/content/images/2017/06/2e-session-affiche.png)',NULL,'<p>Programa de formación de Maestría a distancia: <br />
Becas de maestría a distancia, movilidad de maestría y doctorado, y doctorado en alternancia ha sido prorrogada hasta el 11 de junio por el IFAC.</p>

<p>Para mayor información visita la página de <a href="http://institutfrancais-ifac.com/instituto-frances/convocatorias/convocatoria-programa-de-movilidad-centram-sup-maestria-a-distancia/?lang=es">Institut Français</a>.</p>

<p><img src="/content/images/2017/06/2e-session-affiche.png" alt="" /></p>',NULL,'/content/images/2017/06/campus-france-image-2.jpg',0,0,'published','en_US','public',NULL,NULL,2,'2017-06-29 14:34:32',1,'2017-07-12 07:45:02',1,'2017-06-01 14:38:00',1);
INSERT INTO "posts" VALUES(8,'998bc1d3-34f6-4cc3-ac5b-1c058b633a9d','Cursos vacacionales de Francés','cursos-vacacionales-de-frances','Desde el 26 de junio hasta el 11 de agosto

###Niños (7-9)
Lunes, miercoles y viernes
9:00 a 11:00 a.m.

###Pre-adolecentes (10-12)
Lunes, miercoles y viernes
9:00 a 11:00 a.m.

###Adolecentes (13-15)
Lunes, miércoles y viernes
9:00 a 11:00 a.m.

##¡Matrícula abierta!
Teléfono: **2566 3733**
Email: **alianzafrancesasps@gmail.com**
What''s app: **9437 3857**

![](www.afsps.org/content/images/2017/06/19400391_461380590897697_5376611880566961610_o--1-.png)

',NULL,'<p>Desde el 26 de junio hasta el 11 de agosto</p>

<h3 id="nios79">Niños (7-9)</h3>

<p>Lunes, miercoles y viernes <br />
9:00 a 11:00 a.m.</p>

<h3 id="preadolecentes1012">Pre-adolecentes (10-12)</h3>

<p>Lunes, miercoles y viernes <br />
9:00 a 11:00 a.m.</p>

<h3 id="adolecentes1315">Adolecentes (13-15)</h3>

<p>Lunes, miércoles y viernes <br />
9:00 a 11:00 a.m.</p>

<h2 id="matrculaabierta">¡Matrícula abierta!</h2>

<p>Teléfono: <strong>2566 3733</strong> <br />
Email: <strong>alianzafrancesasps@gmail.com</strong> <br />
What''s app: <strong>9437 3857</strong></p>

<p><img src="/content/images/2017/06/19400391_461380590897697_5376611880566961610_o--1-.png" alt="" /></p>',NULL,'/content/images/2017/06/19400391_461380590897697_5376611880566961610_o.png',0,0,'published','en_US','public',NULL,NULL,2,'2017-06-29 14:48:49',1,'2017-07-12 07:45:46',1,'2017-06-29 14:51:03',1);
INSERT INTO "posts" VALUES(9,'efc11f81-3638-4b94-ad1d-bbf71abde742','La Fête de la Musique','la-fete-de-la-musique','La Fête de la Musique es un evento de origen francés que ha sido fijado sobre una fecha única y simbólica, el 21 de junio, día del solsticio de verano.
En Francia se propone como una gran manifestación popular gratuita y se abre a todos los músicos, los aficionados de todo nivel o los profesionales; celebra la música viva y valoriza la amplitud y la diversidad de las prácticas musicales, así como todos los géneros musicales.
Se dirige a todos los públicos y contribuye familiarizando a los jóvenes y los menos jóvenes de todas condición sociales a todas las expresiones musicales.

![](www.afsps.org/content/images/2017/06/18836011_452875191748237_5185948888585188014_n.png)',NULL,'<p>La Fête de la Musique es un evento de origen francés que ha sido fijado sobre una fecha única y simbólica, el 21 de junio, día del solsticio de verano. <br />
En Francia se propone como una gran manifestación popular gratuita y se abre a todos los músicos, los aficionados de todo nivel o los profesionales; celebra la música viva y valoriza la amplitud y la diversidad de las prácticas musicales, así como todos los géneros musicales. <br />
Se dirige a todos los públicos y contribuye familiarizando a los jóvenes y los menos jóvenes de todas condición sociales a todas las expresiones musicales.</p>

<p><img src="/content/images/2017/06/18836011_452875191748237_5185948888585188014_n.png" alt="" /></p>',NULL,'/content/images/2017/06/fete-1.jpg',0,0,'published','en_US','public',NULL,NULL,2,'2017-06-29 14:54:24',1,'2017-07-10 19:30:17',2,'2017-06-10 14:57:00',1);
INSERT INTO "posts" VALUES(11,'00017317-9051-457a-af84-5f1e41b835b1','YVES TRÉMORIN | FOTÓGRAFO | FRANCIA','yves-tremorin-fotografo-francia','##Programa

**Martes 11 de julio | 7:00 p.m.** <BR>
LA CASA DE TODO, Copán Ruinas
Conferencia y proyección de fotografías

**Jueves 13 de julio | 6:00 p.m.** <br>
MUSEO DE ANTROPOLOGÍA E HISTORIA DE SPS
Conferencia

**Viernes 14 de julio | 7:00 p.m.** <br>
ALIANZA FRANCESA DE SAN PEDRO SULA
Proyección de fotografías como parte de la celebración de la Fête Nationale.

##+Info
Tel.: 2566 3733
Wpp: 9437 3857
alianzafrancesasps@gmail.com

**Este evento cuenta con el patrocinio de:**

* CALVET - Comisariato los Andes 
* La Ensenada Beach Resort 
* La Casa Rosada Hotel - Copán Ruinas
* ABBOTT Consulting & Training
* Museo de Antropología e Historia de San Pedro Sula
* LA CASA DE TODO, COPÁN RUINAS

![](www.afsps.org/content/images/2017/07/WEB-MATERIAL-GRAFIC-YVES-TREMORIN-1.jpg)',NULL,'<h2 id="programa">Programa</h2>

<p><strong>Martes 11 de julio | 7:00 p.m.</strong> <BR>
LA CASA DE TODO, Copán Ruinas <br />
Conferencia y proyección de fotografías</p>

<p><strong>Jueves 13 de julio | 6:00 p.m.</strong> <br>
MUSEO DE ANTROPOLOGÍA E HISTORIA DE SPS <br />
Conferencia</p>

<p><strong>Viernes 14 de julio | 7:00 p.m.</strong> <br>
ALIANZA FRANCESA DE SAN PEDRO SULA <br />
Proyección de fotografías como parte de la celebración de la Fête Nationale.</p>

<h2 id="info">+Info</h2>

<p>Tel.: 2566 3733 <br />
Wpp: 9437 3857 <br />
alianzafrancesasps@gmail.com</p>

<p><strong>Este evento cuenta con el patrocinio de:</strong></p>

<ul>
<li>CALVET - Comisariato los Andes </li>
<li>La Ensenada Beach Resort </li>
<li>La Casa Rosada Hotel - Copán Ruinas</li>
<li>ABBOTT Consulting &amp; Training</li>
<li>Museo de Antropología e Historia de San Pedro Sula</li>
<li>LA CASA DE TODO, COPÁN RUINAS</li>
</ul>

<p><img src="/content/images/2017/07/WEB-MATERIAL-GRAFIC-YVES-TREMORIN-1.jpg" alt="" /></p>',NULL,'/content/images/2017/07/WEB-MATERIAL-GRAFIC-YVES-TREMORIN.jpg',0,0,'published','en_US','public',NULL,NULL,2,'2017-07-10 16:59:43',2,'2017-07-11 14:58:51',2,'2017-07-10 17:10:59',2);
INSERT INTO "posts" VALUES(13,'233e6504-e8e3-4e25-964d-f43cde148174','Entrega de DIPLOMAS DELF','entrega-de-diplomas-delf-2','![](www.afsps.org/content/images/2017/07/Screen-Shot-2017-07-10-at-1.23.02-PM.jpg)

El pasado sábado 8 de julio de 2017 en la sede de la Alianza Francesa de San Pedro Sula celebramos un evento especial para el cuerpo diplomático francés y la comunidad sampedrana en donde compartimos la realización y el alcance de un nivel más en la profesionalización y especialización en el manejo del idioma francés.

Para el evento tuvimos el honor de contar con la presencia del SEÑOR EMBAJADOR DE FRANCIA EN HONDURAS PIERRE CHRISTIAN SOCCOJA y con la junta directiva de la Alianza Francesa de San Pedro Sula.

![](www.afsps.org/content/images/2017/07/Screen-Shot-2017-07-10-at-12.34.31-PM.jpg)

####La importancia de tener un DIPLOMA DELF

La Alianza Francesa de San Pedro Sula, desde 1972, ha procurado promover la cultura francesa a la comunidad sampedrana, actividad que durante 45 años ha generado intercambios con grandes resultados que van desde la profesionalización del idioma francés a intercambios culturales con diversos países francófonos a nivel mundial.

Los DELF son los diplomas oficiales entregados por el Ministerio de Educación francés para certificar las competencias en lengua francesa de los candidatos extranjeros. Los diplomas DELF también existen en versión adaptada a jóvenes adolescentes.   

Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos, la Alianza Francesa de San Pedro Sula.

![](www.afsps.org/content/images/2017/07/Screen-Shot-2017-07-10-at-12.23.26-PM.jpg)

Las certificaciones del DELF tienen en cuenta:
 
* Las normas internacionales de diseño de pruebas ALTE
* La armonización con el Marco común europeo de referencia para las lenguas (CECR).

Las certificaciones DELF están bajo la autoridad de la Comisión Nacional del DELF cuya sede se encuentra en el Centro internacional de Estudios Pedagógicos (CIEP) en Francia.

Los 6 diplomas que constituyen el DELF son totalmente independientes. Por lo tanto, los candidatos pueden inscribirse directamente en el examen que prefiera, según su nivel.

En cada nivel se evalúan las 4 competencias: comprensión y expresión orales, comprensión y expresión escritas.

Es para la Alianza Francesa de San Pedro Sula es un honor, entregar los DIPLOMAS DELF a los alumnos que realizaron los exámenes correspondientes durante el 2016.
',NULL,'<p><img src="/content/images/2017/07/Screen-Shot-2017-07-10-at-1.23.02-PM.jpg" alt="" /></p>

<p>El pasado sábado 8 de julio de 2017 en la sede de la Alianza Francesa de San Pedro Sula celebramos un evento especial para el cuerpo diplomático francés y la comunidad sampedrana en donde compartimos la realización y el alcance de un nivel más en la profesionalización y especialización en el manejo del idioma francés.</p>

<p>Para el evento tuvimos el honor de contar con la presencia del SEÑOR EMBAJADOR DE FRANCIA EN HONDURAS PIERRE CHRISTIAN SOCCOJA y con la junta directiva de la Alianza Francesa de San Pedro Sula.</p>

<p><img src="/content/images/2017/07/Screen-Shot-2017-07-10-at-12.34.31-PM.jpg" alt="" /></p>

<h4 id="laimportanciadetenerundiplomadelf">La importancia de tener un DIPLOMA DELF</h4>

<p>La Alianza Francesa de San Pedro Sula, desde 1972, ha procurado promover la cultura francesa a la comunidad sampedrana, actividad que durante 45 años ha generado intercambios con grandes resultados que van desde la profesionalización del idioma francés a intercambios culturales con diversos países francófonos a nivel mundial.</p>

<p>Los DELF son los diplomas oficiales entregados por el Ministerio de Educación francés para certificar las competencias en lengua francesa de los candidatos extranjeros. Los diplomas DELF también existen en versión adaptada a jóvenes adolescentes.   </p>

<p>Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos, la Alianza Francesa de San Pedro Sula.</p>

<p><img src="/content/images/2017/07/Screen-Shot-2017-07-10-at-12.23.26-PM.jpg" alt="" /></p>

<p>Las certificaciones del DELF tienen en cuenta:</p>

<ul>
<li>Las normas internacionales de diseño de pruebas ALTE</li>
<li>La armonización con el Marco común europeo de referencia para las lenguas (CECR).</li>
</ul>

<p>Las certificaciones DELF están bajo la autoridad de la Comisión Nacional del DELF cuya sede se encuentra en el Centro internacional de Estudios Pedagógicos (CIEP) en Francia.</p>

<p>Los 6 diplomas que constituyen el DELF son totalmente independientes. Por lo tanto, los candidatos pueden inscribirse directamente en el examen que prefiera, según su nivel.</p>

<p>En cada nivel se evalúan las 4 competencias: comprensión y expresión orales, comprensión y expresión escritas.</p>

<p>Es para la Alianza Francesa de San Pedro Sula es un honor, entregar los DIPLOMAS DELF a los alumnos que realizaron los exámenes correspondientes durante el 2016.</p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-07-10 18:15:01',2,'2017-07-12 16:00:36',2,'2017-07-10 18:38:27',2);
INSERT INTO "posts" VALUES(14,'f73743ec-602f-4614-beca-0bf96e843d8b','Conferencia: Jacques-Louis David y la Revolución Francesa','conferencia-jacques-louis-david-y-la-revolucion-francesa-2','En conmemoración de la Fête Nationale tenemos el honor de invitarles a:

* La conferencia **Jacques-Louis David y la Revolución Francesa** impartida por Gustavo Larach, 
Doctor en Historia del Arte.

* Proyección de fotografías de la serie **EMBLEMAS** del fotógrafo francés Yves Trémorin.

**Viernes 14 de julio | 7:00 p.m.** <br>
ALIANZA FRANCESA DE SAN PEDRO SULA

####Info: <br>
Tel.: `2566 3733`
Wpp: `9437 3857`
`alianzafrancesasps@gmail.com`

![](www.afsps.org/content/images/2017/07/web-2-JACQUES-LOUIS-DAVID.png)





######Este evento cuenta con el patrocinio de:
CALVET - Comisariato los Andes
La Ensenada Beach Resort
La Casa Rosada Hotel - Copán Ruinas
ABBOTT Consulting & Training
Museo de Antropología e Historia de San Pedro Sula
LA CASA DE TODO, COPÁN RUINAS

',NULL,'<p>En conmemoración de la Fête Nationale tenemos el honor de invitarles a:</p>

<ul>
<li><p>La conferencia <strong>Jacques-Louis David y la Revolución Francesa</strong> impartida por Gustavo Larach, 
Doctor en Historia del Arte.</p></li>
<li><p>Proyección de fotografías de la serie <strong>EMBLEMAS</strong> del fotógrafo francés Yves Trémorin.</p></li>
</ul>

<p><strong>Viernes 14 de julio | 7:00 p.m.</strong> <br>
ALIANZA FRANCESA DE SAN PEDRO SULA</p>

<h4 id="infobr">Info: <br></h4>

<p>Tel.: <code>2566 3733</code> <br />
Wpp: <code>9437 3857</code> <br />
<code>alianzafrancesasps@gmail.com</code></p>

<p><img src="/content/images/2017/07/web-2-JACQUES-LOUIS-DAVID.png" alt="" /></p>

<h6 id="esteeventocuentaconelpatrociniode">Este evento cuenta con el patrocinio de:</h6>

<p>CALVET - Comisariato los Andes <br />
La Ensenada Beach Resort <br />
La Casa Rosada Hotel - Copán Ruinas <br />
ABBOTT Consulting &amp; Training <br />
Museo de Antropología e Historia de San Pedro Sula <br />
LA CASA DE TODO, COPÁN RUINAS</p>',NULL,'',0,0,'published','en_US','public',NULL,NULL,2,'2017-07-12 17:30:15',2,'2017-07-12 18:03:42',2,'2017-07-12 17:44:33',2);
INSERT INTO "posts" VALUES(16,'b463cdee-d70a-446a-a2fb-63915c669737','Exámenes DELF 2017 segunda sesión','examenes-delf-2017-segunda-sesion','#Todo lo que quieras RÉALISER (lograr)

Certificación oficial de francés con el CIEP - 
del Ministerio francés de la Educación Nacional.

**¡INSCRIPCIONES ABIERTAS!**

Exámenes DELF: 
*Inscripciones del 29 de junio al 27 de julio de 2017*

Exámenes segunda sesión DELF 2017: 
*del lunes 7 al domingo 13 de agosto* 

Las certificaciones DELF están bajo la autoridad de la Comisión Nacional del DELF cuya sede se encuentra en el Centro internacional de Estudios Pedagógicos (CIEP) en Francia.

Los 6 diplomas que constituyen el DELF son totalmente independientes. Por lo tanto, los candidatos pueden inscribirse directamente en el examen que prefiera, según su nivel.

En cada nivel se evalúan las 4 competencias: comprensión y expresión orales, comprensión y expresión escritas.

**Info:** <br>
Tel.: 2566 3733 
Wpp: 9437 3857 
alianzafrancesasps@gmail.com

![](www.afsps.org/content/images/2017/07/EXAMENES-DELF.png)',NULL,'<h1 id="todoloquequierasraliserlograr">Todo lo que quieras RÉALISER (lograr)</h1>

<p>Certificación oficial de francés con el CIEP - <br />
del Ministerio francés de la Educación Nacional.</p>

<p><strong>¡INSCRIPCIONES ABIERTAS!</strong></p>

<p>Exámenes DELF: <br />
<em>Inscripciones del 29 de junio al 27 de julio de 2017</em></p>

<p>Exámenes segunda sesión DELF 2017: <br />
<em>del lunes 7 al domingo 13 de agosto</em> </p>

<p>Las certificaciones DELF están bajo la autoridad de la Comisión Nacional del DELF cuya sede se encuentra en el Centro internacional de Estudios Pedagógicos (CIEP) en Francia.</p>

<p>Los 6 diplomas que constituyen el DELF son totalmente independientes. Por lo tanto, los candidatos pueden inscribirse directamente en el examen que prefiera, según su nivel.</p>

<p>En cada nivel se evalúan las 4 competencias: comprensión y expresión orales, comprensión y expresión escritas.</p>

<p><strong>Info:</strong> <br>
Tel.: 2566 3733 <br />
Wpp: 9437 3857 <br />
alianzafrancesasps@gmail.com</p>

<p><img src="/content/images/2017/07/EXAMENES-DELF.png" alt="" /></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-07-13 20:23:52',2,'2017-07-20 17:44:28',2,'2017-07-13 20:25:20',2);
INSERT INTO "posts" VALUES(17,'dfe855d0-00e4-4412-a01b-9d05ca4989a1','Conferencia: Yves Trémorin, su proceso creativo','conferencia-yves-tremorin','#EMBLEMAS
####DE YVES TRÉMORIN
![](www.afsps.org/content/images/2017/07/web2.jpg)

La noche de ayer 13 de julio en el Museo de Antropología e Historia de San Pedro Sula, el artista fotógrafo Yves Trémorin impartió su conferencia en donde nos explicó su proceso creativo y de producción fotográfica.

Las palabras de bienvenida estuvieron a cargo de la Señora Teresa Campos de Pastor, Directora del Museo de Antropología e Historia de San Pedro Sula, también la bienvenida de Gustavo Larach, Director de la Alianza Francesa de San Pedro Sula.

![](www.afsps.org/content/images/2017/07/web1.jpg)



"Este matemático de formación, introducido a la fotografía a la edad de 21 años, tuvo su primera exposición a los 25, creando en el año 1986 el grupo Límite Negro, con Jean Bélégou y Florence Chevalier y persigue sólo su camino marcado en 1983 con su obra titulada Cette femme-là, puesta en escena rigurosamente, hacienda uso de sus propios medios, trabajando en torno a su familia y su entorno, con su visión íntima y cercana, casi con una objetividad científica.

Como bien dice Catherine Elkar, Yves Trémorin está en constante expansión de su territorio tanto en el medio y más allá del campo de la fotografía. Su responsabilidad como artista de hecho excede el territorio estricto del arte para cuestionar la sociedad, la política y la cultura en general." 
http://www.les-lettres-francaises.fr/2015/12/les-emblemes-dyves-tremorin/

![](www.afsps.org/content/images/2017/07/web3.jpg)

"La fotografía contemporánea, cuando se trata de no construirse en la potencia del momento sino con una consciencia deliberada del anacronismo del símbolo, sabe reproducir, reactivar, actualizar todos o casi todos los modos de representación, incluso los más antiguos.

El fotógrafo francés Yves Trémorin requiere una potencia de sentido antigua: la del emblema. Sin ningún tipo de nostalgia para las formas y los lenguajes históricos. Trémorin alcanza el registro del emblema vía un trabajo cuidadoso y preciso, una gran vigilancia en el principio de ahorro de la imagen que ha nutrido su larga ruta artística: Trémorin prefiere trabajos más cerca del símbolo."  
https://www.facebook.com/ElArtistaMagazine/posts/609736655832322#

Este evento tuvo una exquisita degustación de vinos CALVET, patrocinados por Comisariato los Andes.

![](www.afsps.org/content/images/2017/07/WhatsApp-Image-2017-07-14-at-9.08.05-AM.jpeg)

Hoy 14 de julio, tendremos la proyección de su colección fotográfica **EMBLEMAS** luego de la conferencia sobre: *Jacques-Louis David y la Revolución Francesa* como parte de la conmemoración de la Fête National.

![](www.afsps.org/content/images/2017/07/Screen-Shot-2017-07-12-at-11.34.00-AM-2.png)',NULL,'<h1 id="emblemas">EMBLEMAS</h1>

<h4 id="deyvestrmorin">DE YVES TRÉMORIN</h4>

<p><img src="/content/images/2017/07/web2.jpg" alt="" /></p>

<p>La noche de ayer 13 de julio en el Museo de Antropología e Historia de San Pedro Sula, el artista fotógrafo Yves Trémorin impartió su conferencia en donde nos explicó su proceso creativo y de producción fotográfica.</p>

<p>Las palabras de bienvenida estuvieron a cargo de la Señora Teresa Campos de Pastor, Directora del Museo de Antropología e Historia de San Pedro Sula, también la bienvenida de Gustavo Larach, Director de la Alianza Francesa de San Pedro Sula.</p>

<p><img src="/content/images/2017/07/web1.jpg" alt="" /></p>

<p>"Este matemático de formación, introducido a la fotografía a la edad de 21 años, tuvo su primera exposición a los 25, creando en el año 1986 el grupo Límite Negro, con Jean Bélégou y Florence Chevalier y persigue sólo su camino marcado en 1983 con su obra titulada Cette femme-là, puesta en escena rigurosamente, hacienda uso de sus propios medios, trabajando en torno a su familia y su entorno, con su visión íntima y cercana, casi con una objetividad científica.</p>

<p>Como bien dice Catherine Elkar, Yves Trémorin está en constante expansión de su territorio tanto en el medio y más allá del campo de la fotografía. Su responsabilidad como artista de hecho excede el territorio estricto del arte para cuestionar la sociedad, la política y la cultura en general." <br />
<a href="http://www.les-lettres-francaises.fr/2015/12/les-emblemes-dyves-tremorin/">http://www.les-lettres-francaises.fr/2015/12/les-emblemes-dyves-tremorin/</a></p>

<p><img src="/content/images/2017/07/web3.jpg" alt="" /></p>

<p>"La fotografía contemporánea, cuando se trata de no construirse en la potencia del momento sino con una consciencia deliberada del anacronismo del símbolo, sabe reproducir, reactivar, actualizar todos o casi todos los modos de representación, incluso los más antiguos.</p>

<p>El fotógrafo francés Yves Trémorin requiere una potencia de sentido antigua: la del emblema. Sin ningún tipo de nostalgia para las formas y los lenguajes históricos. Trémorin alcanza el registro del emblema vía un trabajo cuidadoso y preciso, una gran vigilancia en el principio de ahorro de la imagen que ha nutrido su larga ruta artística: Trémorin prefiere trabajos más cerca del símbolo." <br />
<a href="https://www.facebook.com/ElArtistaMagazine/posts/609736655832322#">https://www.facebook.com/ElArtistaMagazine/posts/609736655832322#</a></p>

<p>Este evento tuvo una exquisita degustación de vinos CALVET, patrocinados por Comisariato los Andes.</p>

<p><img src="/content/images/2017/07/WhatsApp-Image-2017-07-14-at-9.08.05-AM.jpeg" alt="" /></p>

<p>Hoy 14 de julio, tendremos la proyección de su colección fotográfica <strong>EMBLEMAS</strong> luego de la conferencia sobre: <em>Jacques-Louis David y la Revolución Francesa</em> como parte de la conmemoración de la Fête National.</p>

<p><img src="/content/images/2017/07/Screen-Shot-2017-07-12-at-11.34.00-AM-2.png" alt="" /></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-07-14 16:48:04',2,'2017-07-14 20:20:29',2,'2017-07-14 17:38:58',2);
INSERT INTO "posts" VALUES(18,'ff18634c-1bd2-474e-bd14-cfba85b52381','JACQUES-LOUIS DAVID Y LA REVOLUCIÓN FRANCESA','jacques-louis-david-y-la-revolucion-francesa','##Jacques-Louis David (1748-1825)',NULL,'<h2 id="jacqueslouisdavid17481825">Jacques-Louis David (1748-1825)',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-07-18 15:26:13',2,'2017-07-18 16:14:44',2,'2017-07-18 16:08:19',2);
INSERT INTO "posts" VALUES(19,'6e385f7f-93ce-4fb5-a86b-f837d5b50279','OFERTA ACADÉMICA | 3 SESIÓN 2017','oferta-academica-3-sesion-2017','#OFERTA ACADÉMICA | 3 SESIÓN 2017
###1er. Nivel de francés:
<br>
###Matrícula abierta
Inicio de clases: 28 de agosto

#####NIÑOS (7-9 años) <BR>
**• Lunes y miércoles** <BR>
   *3:00 – 4:30 p.m.* <BR>

####PRE-ADOLESCENTES (10-12 años) 
**• Lunes y miércoles** <BR>
   *4:30 – 6:00 p.m.*<br>
**• Martes y jueves** <BR>
   *4:30 – 6:00 p.m.*<br>

####ADOLESCENTES (13-15 años) 
**• Lunes y miércoles** <BR>
   *4:30 – 6:00 p.m.* <BR>
**• Sábados** <BR>
*8:00 – 11:00 a.m.*

####ADULTOS (16 años en adelante) 
**• Lunes y miércoles** <BR>
   *6:30 – 8:00 p.m.* <BR>
**• Martes y jueves** <BR>
   *6:30 – 8:00 p.m.* <BR>
**• Viernes** <BR>
*8:30 – 11:30 a.m.* <BR>
*3:00 - 6:00 p.m.* <br>
**• Sábados** <BR>
*12:00 – 3:00 p.m.*

*• Si es suscriptor de Diario La Prensa, obtiene matrícula gratis + 10% de descuento sobre el costo del cuatrimestre. <br>
• Extra financiamiento a 0% interés con BAC Credomatic y BANPAIS a plazo de 3 meses. <br> 
• Todos los grupos se abren con mínimo de 8 alumnos.*


####+Info: 
Tel.: **2566 3733**
Wpp: **9437 3857** 
**alianzafrancesasps@gmail.com**

###Pregunte por nuestros cursos de arte.',NULL,'<h1 id="ofertaacadmica3sesin2017">OFERTA ACADÉMICA | 3 SESIÓN 2017</h1>

<h3 id="1erniveldefrancs">1er. Nivel de francés:</h3>

<p><br>  </p>

<h3 id="matrculaabierta">Matrícula abierta</h3>

<p>Inicio de clases: 28 de agosto</p>

<h5 id="nios79aosbr">NIÑOS (7-9 años) <BR></h5>

<p><strong>• Lunes y miércoles</strong> <BR>
   <em>3:00 – 4:30 p.m.</em> <BR></p>

<h4 id="preadolescentes1012aos">PRE-ADOLESCENTES (10-12 años)</h4>

<p><strong>• Lunes y miércoles</strong> <BR>
   <em>4:30 – 6:00 p.m.</em><br>
<strong>• Martes y jueves</strong> <BR>
   <em>4:30 – 6:00 p.m.</em><br></p>

<h4 id="adolescentes1315aos">ADOLESCENTES (13-15 años)</h4>

<p><strong>• Lunes y miércoles</strong> <BR>
   <em>4:30 – 6:00 p.m.</em> <BR>
<strong>• Sábados</strong> <BR>
<em>8:00 – 11:00 a.m.</em></p>

<h4 id="adultos16aosenadelante">ADULTOS (16 años en adelante)</h4>

<p><strong>• Lunes y miércoles</strong> <BR>
   <em>6:30 – 8:00 p.m.</em> <BR>
<strong>• Martes y jueves</strong> <BR>
   <em>6:30 – 8:00 p.m.</em> <BR>
<strong>• Viernes</strong> <BR>
<em>8:30 – 11:30 a.m.</em> <BR>
<em>3:00 - 6:00 p.m.</em> <br>
<strong>• Sábados</strong> <BR>
<em>12:00 – 3:00 p.m.</em></p>

<p><em>• Si es suscriptor de Diario La Prensa, obtiene matrícula gratis + 10% de descuento sobre el costo del cuatrimestre. <br>
• Extra financiamiento a 0% interés con BAC Credomatic y BANPAIS a plazo de 3 meses. <br> 
• Todos los grupos se abren con mínimo de 8 alumnos.</em></p>

<h4 id="info">+Info:</h4>

<p>Tel.: <strong>2566 3733</strong> <br />
Wpp: <strong>9437 3857</strong> <br />
<strong>alianzafrancesasps@gmail.com</strong></p>

<h3 id="preguntepornuestroscursosdearte">Pregunte por nuestros cursos de arte.</h3>',NULL,'/content/images/2017/07/Screen-Shot-2017-07-24-at-11.47.53-AM-1.png',0,0,'published','en_US','public',NULL,NULL,2,'2017-07-24 17:27:21',2,'2017-07-28 14:23:27',2,'2017-07-24 17:45:57',2);
INSERT INTO "posts" VALUES(20,'283aa9f5-4458-4c2e-89d1-f2d1356ca2bf','INTERCAMBIO CULTURAL 2 SEMANAS EN PARIS','intercambio-cultural-2-semanas-en-paris','![](www.afsps.org/content/images/2017/07/portada-BROCHURE_PAR-ICI-PARIS_2017-1.png)


**Del 9 al 23 de diciembre del 2017 la Alianza Francesa de París** ofrece una formación extensiva de 9 horas de cursos de francés por semana, con una estadía de dos semanas que incluye: hospedaje, tres comidas diarias (de lunes a viernes), y excursiones a lugares turísticos dentro de esta ciudad (Versailles, la Seine (Bateaux-mouche), Monmartre, Musée du Louvre, Tour Eiffel, Chateaux de la Loire etc). Los estudiantes irán acompañados por dos profesores de la Alianza Francesa de San Pedro Sula. 

**Precio:** a partir de 1341 euros (sin boleto de avión). 

**Beneficios:**
  
* Los estudiantes serán hospedados con una familia francesa.

* Todo transporte entre el aeropuerto, la residencia, así como a la Alianza y las actividades turísticas está incluido. El transporte fuera de itinerario oficial estará a cargo de cada alumno. 
  
* Obtendrán un certificado de participación en la formación por parte de la Alianza Francesa de París.

* Estarán en contacto permanente con la lengua francesa. 
* Tendrán la oportunidad de conocer los lugares turísticos más visitados en París.
 
* Recibirán un regalo sorpresa por parte de la Alianza Francesa de París.
 
**Requisitos:**
  
* Ser mayor de 18 años.

* Ser estudiante de la Alianza Francesa de San Pedro Sula.

* Para realizar el intercambio se requiere un mínimo 10 estudiantes interesados en el viaje.

* Una vez que haya al menos 10 estudiantes dispuestos a realizar el viaje, ellos firmaran una carta de compromiso con la Alianza Francesa de San Pedro Sula.
 
*Los estudiantes interesados deben inscribirse en la administración de la Alianza Francesa de San Pedro Sula con Ana Fúnez y Lilian Robles.*
 
**Fecha límite de inscripción: 1 de septiembre.**

',NULL,'<p><img src="/content/images/2017/07/portada-BROCHURE_PAR-ICI-PARIS_2017-1.png" alt="" /></p>

<p><strong>Del 9 al 23 de diciembre del 2017 la Alianza Francesa de París</strong> ofrece una formación extensiva de 9 horas de cursos de francés por semana, con una estadía de dos semanas que incluye: hospedaje, tres comidas diarias (de lunes a viernes), y excursiones a lugares turísticos dentro de esta ciudad (Versailles, la Seine (Bateaux-mouche), Monmartre, Musée du Louvre, Tour Eiffel, Chateaux de la Loire etc). Los estudiantes irán acompañados por dos profesores de la Alianza Francesa de San Pedro Sula. </p>

<p><strong>Precio:</strong> a partir de 1341 euros (sin boleto de avión). </p>

<p><strong>Beneficios:</strong></p>

<ul>
<li><p>Los estudiantes serán hospedados con una familia francesa.</p></li>
<li><p>Todo transporte entre el aeropuerto, la residencia, así como a la Alianza y las actividades turísticas está incluido. El transporte fuera de itinerario oficial estará a cargo de cada alumno. </p></li>
<li><p>Obtendrán un certificado de participación en la formación por parte de la Alianza Francesa de París.</p></li>
<li><p>Estarán en contacto permanente con la lengua francesa. </p></li>
<li><p>Tendrán la oportunidad de conocer los lugares turísticos más visitados en París.</p></li>
<li><p>Recibirán un regalo sorpresa por parte de la Alianza Francesa de París.</p></li>
</ul>

<p><strong>Requisitos:</strong></p>

<ul>
<li><p>Ser mayor de 18 años.</p></li>
<li><p>Ser estudiante de la Alianza Francesa de San Pedro Sula.</p></li>
<li><p>Para realizar el intercambio se requiere un mínimo 10 estudiantes interesados en el viaje.</p></li>
<li><p>Una vez que haya al menos 10 estudiantes dispuestos a realizar el viaje, ellos firmaran una carta de compromiso con la Alianza Francesa de San Pedro Sula.</p></li>
</ul>

<p><em>Los estudiantes interesados deben inscribirse en la administración de la Alianza Francesa de San Pedro Sula con Ana Fúnez y Lilian Robles.</em></p>

<p><strong>Fecha límite de inscripción: 1 de septiembre.</strong></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-07-26 14:25:27',2,'2017-07-26 20:43:00',2,'2017-07-26 14:46:40',2);
INSERT INTO "posts" VALUES(21,'739dcc1b-dd9f-4857-851b-e80106ee1e1a','FIRMA DE CONVENIO ACADÉMICO','firma-de-convenio-academico-2','##FIRMA DE CONVENIO ACADÉMICO 
####Decroly Christian International School y la Alianza Francesa de SPS <br>

![](www.afsps.org/content/images/2017/08/Screen-Shot-2017-08-03-at-6.38.50-PM.jpg)
*En la foto: el Director Ejecutivo de la Alianza Francesa, Gustavo Larach. La presidenta de la junta directiva de la Alianza Francesa, Ing. Daphne Pérez. La Directora Académica de Decroly Christian International School, Licda. Martha A. de Corbera. El Señor Embajador de Francia en Honduras, Pierre Christian Soccoja. Y el Representante legal de Decroly Christian International School, Ing. Raymundo E. Aguirre.*

El día jueves 3 de agosto de 2017, en la sede de Decroly Christian International School de San Pedro Sula se llevó a cabo un evento especial para el cuerpo diplomático francés y la comunidad sampedrana, porque a partir de este período académico 2017-2018 incursionarán en el aprendizaje de francés como tercer idioma los alumnos de Decroly Christian International School.

En este evento contó con la presencia del SEÑOR EMBAJADOR DE FRANCIA EN HONDURAS PIERRE CHRISTIAN SOCCOJA y autoridades y personal de la Alianza Francesa de San Pedro Sula y de Decroly Christian International School de San Pedro Sula, entre otros invitados especiales.

####UNA ALIANZA ENTRE INSTITUCIONES EDUCATIVAS
La Alianza Francesa de San Pedro Sula, desde 1972, ha procurado promover la cultura francesa a la comunidad sampedrana, actividad que durante 45 años a generado intercambios con grandes resultados que van desde la profesionalización del idioma francés a intercambios culturales con diversos países francófonos a nivel mundial.

La Alianza Francesa ha sido, sobre las décadas, un constante pilar para el enriquecimiento cultural de la comunidad sampedrana y las relaciones entre Francia y Honduras.

Además de ofrecer una rica programación cultural, también contamos con un equipo pedagógico especializado en la enseñanza del francés, proponiendo cursos adaptados a todo público. Esta oferta académica con altos estándares de calidad nos permite entablar esta alianza con Decroly Christian International School. 

',NULL,'<h2 id="firmadeconvenioacadmico">FIRMA DE CONVENIO ACADÉMICO</h2>

<h4 id="decrolychristianinternationalschoolylaalianzafrancesadespsbr">Decroly Christian International School y la Alianza Francesa de SPS <br></h4>

<p><img src="/content/images/2017/08/Screen-Shot-2017-08-03-at-6.38.50-PM.jpg" alt="" />
<em>En la foto: el Director Ejecutivo de la Alianza Francesa, Gustavo Larach. La presidenta de la junta directiva de la Alianza Francesa, Ing. Daphne Pérez. La Directora Académica de Decroly Christian International School, Licda. Martha A. de Corbera. El Señor Embajador de Francia en Honduras, Pierre Christian Soccoja. Y el Representante legal de Decroly Christian International School, Ing. Raymundo E. Aguirre.</em></p>

<p>El día jueves 3 de agosto de 2017, en la sede de Decroly Christian International School de San Pedro Sula se llevó a cabo un evento especial para el cuerpo diplomático francés y la comunidad sampedrana, porque a partir de este período académico 2017-2018 incursionarán en el aprendizaje de francés como tercer idioma los alumnos de Decroly Christian International School.</p>

<p>En este evento contó con la presencia del SEÑOR EMBAJADOR DE FRANCIA EN HONDURAS PIERRE CHRISTIAN SOCCOJA y autoridades y personal de la Alianza Francesa de San Pedro Sula y de Decroly Christian International School de San Pedro Sula, entre otros invitados especiales.</p>

<h4 id="unaalianzaentreinstitucioneseducativas">UNA ALIANZA ENTRE INSTITUCIONES EDUCATIVAS</h4>

<p>La Alianza Francesa de San Pedro Sula, desde 1972, ha procurado promover la cultura francesa a la comunidad sampedrana, actividad que durante 45 años a generado intercambios con grandes resultados que van desde la profesionalización del idioma francés a intercambios culturales con diversos países francófonos a nivel mundial.</p>

<p>La Alianza Francesa ha sido, sobre las décadas, un constante pilar para el enriquecimiento cultural de la comunidad sampedrana y las relaciones entre Francia y Honduras.</p>

<p>Además de ofrecer una rica programación cultural, también contamos con un equipo pedagógico especializado en la enseñanza del francés, proponiendo cursos adaptados a todo público. Esta oferta académica con altos estándares de calidad nos permite entablar esta alianza con Decroly Christian International School. </p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-08-04 00:37:09',2,'2017-08-04 00:51:09',2,'2017-08-04 00:50:49',2);
INSERT INTO "posts" VALUES(22,'bd255216-8560-482b-a810-44922002c5c9','Offre d’ emploi / Oferta de empleo','offre-d-emploi-oferta-de-empleo','![](www.afsps.org/content/images/2017/08/OFERTA-DE-EMPLEO.jpg)

#PUESTO DE PROFESOR/A FLE.

**Información general:** <BR>
· Disponibilidad: inmediata <BR>
· Título del puesto: Profesor/a FLE <BR>
· Ciudad y país : San Pedro Sula, Honduras <BR>
· Contacto: info@alianzafrancesasps.com

**Perfil y competencias requeridas:** <BR>
• Formación mínima: dominio de la lengua francesa y diploma en la enseñanza del francés que lo certifique. <BR> 
• Experiencia comprobada de enseñanza del francés como lengua extranjera, de preferencia en el extranjero. <BR>
• Buen conocimiento de los públicos multiculturales y excelentes cualidades de relaciones personales. <BR>
• Excelente conocimiento del Marco Europeo Común de Referencia para las lenguas.<BR>
• Gusto por las nuevas tecnologías. <BR>
• Poseer iniciativa y disponibilidad. <BR>
• Certificación DELF que certifique su nivel de idioma. <BR>
• Curso de francés general, escrito y oral bajo objetivos específicos y de especialidad. 

####Enviar el CV por e-mail: info@alianzafrancesasps.com

',NULL,'<p><img src="/content/images/2017/08/OFERTA-DE-EMPLEO.jpg" alt="" /></p>

<h1 id="puestodeprofesorafle">PUESTO DE PROFESOR/A FLE.</h1>

<p><strong>Información general:</strong> <BR>
· Disponibilidad: inmediata <BR>
· Título del puesto: Profesor/a FLE <BR>
· Ciudad y país : San Pedro Sula, Honduras <BR>
· Contacto: info@alianzafrancesasps.com</p>

<p><strong>Perfil y competencias requeridas:</strong> <BR>
• Formación mínima: dominio de la lengua francesa y diploma en la enseñanza del francés que lo certifique. <BR> 
• Experiencia comprobada de enseñanza del francés como lengua extranjera, de preferencia en el extranjero. <BR>
• Buen conocimiento de los públicos multiculturales y excelentes cualidades de relaciones personales. <BR>
• Excelente conocimiento del Marco Europeo Común de Referencia para las lenguas.<BR>
• Gusto por las nuevas tecnologías. <BR>
• Poseer iniciativa y disponibilidad. <BR>
• Certificación DELF que certifique su nivel de idioma. <BR>
• Curso de francés general, escrito y oral bajo objetivos específicos y de especialidad. </p>

<h4 id="enviarelcvporemailinfoalianzafrancesaspscom">Enviar el CV por e-mail: info@alianzafrancesasps.com</h4>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-08-07 18:34:13',2,'2017-08-07 18:40:05',2,'2017-08-07 18:38:37',2);
INSERT INTO "posts" VALUES(23,'494bb3c2-9aa5-47f4-be3c-ffade3156847','CLÉA VINCENT - DESDE FRANCIA','clea-vincent-desde-francia','![](www.afsps.org/content/images/2017/08/AFSPS-Afiche-Cle-a-Vincent-Ame-rica-Central-.jpg)

**Introducción:** *La Alianza Francesa de San Pedro Sula, en un constante esfuerzo por aportar un movimiento cultural de alta calidad a la comunidad sampedrana, gestiona y produce eventos que procuran intercambios y alianzas institucionales y culturales entre Honduras y Francia, apoyando tanto a los artistas nacionales como internacionales.*

*Para este mes de septiembre tendremos el honor de recibir en directo desde Francia la visita de Cléa Vincent, con los cual seremos la primera ciudad y país en ser sede para una de sus presentaciones durante su gira por Centroamérica.*

**Les invitamos cordialmente a compartir con nosotros este martes 5 de septiembre a las 7:30 p.m. en la sede de la Alianza Francesa de San Pedro Sula.**

**La entrada es libre y gratuita.**

#Sobre Cléa Vincent

Es difícil escribir la biografía de alguien que todavía tiene toda la vida por delante. Entonces tendremos que conjugar en futuro el talento de la parisina Cléa Vincent. Joven y muy decidida, *¡Cléa es capaz de todo!* 

Como todos los que crecieron a finales de los 90 e inicios de los 2000, lleva consigo la música electrónica, pero su curiosidad la lleva a explorar el repertorio francés que remonta hasta los años 60. Eso hace que se presente ahora como una “France Gall EDM”. 

Pianista de formación, Cléa Vincent perpetúa la tradición de la variété française, aportándole arreglos con colores a la vez orgánicos  y sintéticos, que le dan  a su música un tono moderno y libre. 

En 2014, Cléa lanza su primer EP titulado “Non mais Oui”, que contiene su canción “Retiens mon désir”. La reconocida boutique parisina Colette incluye ese single en su compilación “French Kiss”, con el objetivo de promover a la nueva escena francesa. 

La revista Les Inrockuptibles se enamora rápidamente de la obra de la joven parisina y le da una gran difusión a su vídeo “Retiens mon désir”, que cuenta ya con más de 458,000 vistas en Youtube y su sencillo “Château Perdu” es difundido masivamente por el canal M6 en Francia. 

Tras el éxito de dos EP, Cléa lanza finalmente su primer disco “Retiens mon désir” en 2015, incluyendo versiones remasterizadas de sus primeros sencillos y canciones con sonidos frescos e innovadores. En 2017, se estrena “Tropi-Cléa”, un nuevo EP con sonidos tropicales y aires de bossa nova, que fue grabado en solamente 2 días y en condiciones en vivo para mantener toda la espontaneidad y libertad que caracterizan a Cléa Vincent. 

https://www.facebook.com/cleavincentmusic

https://twitter.com/clea_vincent

https://instagram.com/cleavincent/

https://soundcloud.com/cleavincent

####Este evento cuenta con el gentil patrocinio de:
* Hotel Hilton Princess San Pedro Sula
* LA CITÉ - Cocina Mediterránea

**Y el gentil co-patrocinio de:**

* CALVET - Comisariato Los Andes
* AROMAS Pizza - Café
* L''art du Pain
* Diario La Prensa
* Radio XY 107.3 FM
',NULL,'<p><img src="/content/images/2017/08/AFSPS-Afiche-Cle-a-Vincent-Ame-rica-Central-.jpg" alt="" /></p>

<p><strong>Introducción:</strong> <em>La Alianza Francesa de San Pedro Sula, en un constante esfuerzo por aportar un movimiento cultural de alta calidad a la comunidad sampedrana, gestiona y produce eventos que procuran intercambios y alianzas institucionales y culturales entre Honduras y Francia, apoyando tanto a los artistas nacionales como internacionales.</em></p>

<p><em>Para este mes de septiembre tendremos el honor de recibir en directo desde Francia la visita de Cléa Vincent, con los cual seremos la primera ciudad y país en ser sede para una de sus presentaciones durante su gira por Centroamérica.</em></p>

<p><strong>Les invitamos cordialmente a compartir con nosotros este martes 5 de septiembre a las 7:30 p.m. en la sede de la Alianza Francesa de San Pedro Sula.</strong></p>

<p><strong>La entrada es libre y gratuita.</strong></p>

<h1 id="sobreclavincent">Sobre Cléa Vincent</h1>

<p>Es difícil escribir la biografía de alguien que todavía tiene toda la vida por delante. Entonces tendremos que conjugar en futuro el talento de la parisina Cléa Vincent. Joven y muy decidida, <em>¡Cléa es capaz de todo!</em> </p>

<p>Como todos los que crecieron a finales de los 90 e inicios de los 2000, lleva consigo la música electrónica, pero su curiosidad la lleva a explorar el repertorio francés que remonta hasta los años 60. Eso hace que se presente ahora como una “France Gall EDM”. </p>

<p>Pianista de formación, Cléa Vincent perpetúa la tradición de la variété française, aportándole arreglos con colores a la vez orgánicos  y sintéticos, que le dan  a su música un tono moderno y libre. </p>

<p>En 2014, Cléa lanza su primer EP titulado “Non mais Oui”, que contiene su canción “Retiens mon désir”. La reconocida boutique parisina Colette incluye ese single en su compilación “French Kiss”, con el objetivo de promover a la nueva escena francesa. </p>

<p>La revista Les Inrockuptibles se enamora rápidamente de la obra de la joven parisina y le da una gran difusión a su vídeo “Retiens mon désir”, que cuenta ya con más de 458,000 vistas en Youtube y su sencillo “Château Perdu” es difundido masivamente por el canal M6 en Francia. </p>

<p>Tras el éxito de dos EP, Cléa lanza finalmente su primer disco “Retiens mon désir” en 2015, incluyendo versiones remasterizadas de sus primeros sencillos y canciones con sonidos frescos e innovadores. En 2017, se estrena “Tropi-Cléa”, un nuevo EP con sonidos tropicales y aires de bossa nova, que fue grabado en solamente 2 días y en condiciones en vivo para mantener toda la espontaneidad y libertad que caracterizan a Cléa Vincent. </p>

<p><a href="https://www.facebook.com/cleavincentmusic">https://www.facebook.com/cleavincentmusic</a></p>

<p><a href="https://twitter.com/clea_vincent">https://twitter.com/clea_vincent</a></p>

<p><a href="https://instagram.com/cleavincent/">https://instagram.com/cleavincent/</a></p>

<p><a href="https://soundcloud.com/cleavincent">https://soundcloud.com/cleavincent</a></p>

<h4 id="esteeventocuentaconelgentilpatrociniode">Este evento cuenta con el gentil patrocinio de:</h4>

<ul>
<li>Hotel Hilton Princess San Pedro Sula</li>
<li>LA CITÉ - Cocina Mediterránea</li>
</ul>

<p><strong>Y el gentil co-patrocinio de:</strong></p>

<ul>
<li>CALVET - Comisariato Los Andes</li>
<li>AROMAS Pizza - Café</li>
<li>L''art du Pain</li>
<li>Diario La Prensa</li>
<li>Radio XY 107.3 FM</li>
</ul>',NULL,'/content/images/2017/08/AFSPS-Afiche-Cle-a-Vincent-Ame-rica-Central--1.jpg',0,0,'published','en_US','public',NULL,NULL,2,'2017-08-31 14:37:09',2,'2017-08-31 16:51:09',2,'2017-08-31 14:47:55',2);
INSERT INTO "posts" VALUES(24,'cb25dae7-d7e7-442b-a4c1-9931d8a79b44','(Untitled)','untitled','#JUSQU’OÙ VOUS VOULEZ ARRIVER !
###(HASTA DONDE QUIERAS LLEGAR)

Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.

Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.

Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).

![](www.afsps.org/content/images/2017/09/AFSPS---NIVELES-MERC-1.jpg)',NULL,'<h1 id="jusquovousvoulezarriver">JUSQU’OÙ VOUS VOULEZ ARRIVER !</h1>

<h3 id="hastadondequierasllegar">(HASTA DONDE QUIERAS LLEGAR)</h3>

<p>Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.</p>

<p>Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.</p>

<p>Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).</p>

<p><img src="/content/images/2017/09/AFSPS---NIVELES-MERC-1.jpg" alt="" /></p>',NULL,NULL,0,0,'draft','en_US','public',NULL,NULL,2,'2017-09-11 22:38:43',2,'2017-09-11 22:38:43',2,NULL,NULL);
INSERT INTO "posts" VALUES(25,'5b9d9759-897d-451a-8be3-09b414d02acf','JUSQU’OÙ VOUS VOULEZ ARRIVER !','untitled-2','#JUSQU’OÙ VOUS VOULEZ ARRIVER !
##(HASTA DONDE QUIERAS LLEGAR!)

Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.

Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.

Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).

![](www.afsps.org/content/images/2017/09/AFSPS---NIVELES-MERC-2.jpg)',NULL,'<h1 id="jusquovousvoulezarriver">JUSQU’OÙ VOUS VOULEZ ARRIVER !</h1>

<h2 id="hastadondequierasllegar">(HASTA DONDE QUIERAS LLEGAR!)</h2>

<p>Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.</p>

<p>Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.</p>

<p>Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).</p>

<p><img src="/content/images/2017/09/AFSPS---NIVELES-MERC-2.jpg" alt="" /></p>',NULL,NULL,0,0,'draft','en_US','public',NULL,NULL,2,'2017-09-11 22:39:56',2,'2017-09-11 22:40:46',2,NULL,NULL);
INSERT INTO "posts" VALUES(26,'25a1523a-638f-4ca1-bb0c-6c4b6f4aba08','JUSQU’OÙ VOUS VOULEZ ARRIVER !','jusquou-vous-voulez-arriver','##JUSQU’OÙ VOUS VOULEZ ARRIVER !
####(HASTA DONDE QUIERAS LLEGAR!)

Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.

Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.

Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).


![](www.afsps.org/content/images/2017/09/AFSPS---NIVELES-MERC-3.jpg)',NULL,'<h2 id="jusquovousvoulezarriver">JUSQU’OÙ VOUS VOULEZ ARRIVER !</h2>

<h4 id="hastadondequierasllegar">(HASTA DONDE QUIERAS LLEGAR!)</h4>

<p>Los DELF son los diplomas oficiales entregados por el Ministerio de Educación Nacional en Francia para certificar las competencias en lengua francesa de los estudiantes a nivel mundial.</p>

<p>Es posible presentarse a las pruebas en los 900 centros de exámenes concertados distribuidos por 154 países, entre ellos la Alianza Francesa de San Pedro Sula.</p>

<p>Les compartimos parte de la tabla para Niveles MERC (Marco común europeo de referencia para las lenguas).</p>

<p><img src="/content/images/2017/09/AFSPS---NIVELES-MERC-3.jpg" alt="" /></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-09-11 22:41:11',2,'2017-09-11 22:45:41',2,'2017-09-11 22:44:31',2);
INSERT INTO "posts" VALUES(27,'947a80c2-1dd3-40ac-af91-71ec5370c11d','PROCESO DE NAHUATLIZACIÓN Y NAHUATLISMOS DE USO EN HONDURAS','proceso-de-nahuatlizacion-y-nahuatlismos-de-uso-en-honduras','![](www.afsps.org/content/images/2017/09/libro-ATANASIO.jpg)

**La Universidad Nacional Autónoma de Honduras en el Valle de Sula y la Alianza Francesa de San Pedro Sula**

*INVITAN a la presentación del libro* 

####PROCESO DE NAHUATLIZACIÓN Y NAHUATLISMOS DE USO EN HONDURAS
**Escrito por el Doctor en Filología ATANASIO HERRANZ**


Día: jueves 14 de Septiembre 
Hora: 9:30 a. m.
Lugar: Alianza Francesa de San Pedro Sula
(Col. Altavista, Sector el Playón,
  Tel.: 2566-3733)

Ingreso libre

*"Como es poco conocido, el habla de los hondureños contiene más de mil palabras procedentes de la cultura mexicana, particularmente de la lengua náhuatl, llegadas al territorio centroamericano mediante migraciones y desplazamientos humanos que tardaron siglos.*

*Algunas de nuestras abuelas hablaron náhuatl, nosotros hablamos náhuatl cuando decimos, por ejemplo:*

*Achiote, aguacate, amate, ayotera, cacahuanance, chichicaste, chichicuilote, pizote, chapulinero, guatuza, tecolote, coyote, zopilote, pepesca, chacalín, chucho, atol, chilate, chilmol, elote, jilote, nacatamal, pozol, pupusa, totoposte, comal, guacal, pascón, petate, huacal, paste, milpa, ayotal, ciguanaba, cipitillo, entre muchos otros...*

*Vengan, acompáñennos par de horas el jueves y seguro que se divertirán (y conocerán) mucho 
con la sabiduría y simpatía de Atanasio Herranz..."* (Diario La Tribuna)

###Sobre el Doctor ATANASIO HERRANZ:

ATANASIO HERRANZ, de nacionalidad hondureña y española, es Doctor en Filología Románica por la Universidad Complutense de Madrid.

Ha sido profesor en la UNAH y en la Maestría en Lexicografía de la Real Academia Española (RAE). Es miembro de número de la Academia Hondureña de la Lengua, de la Academia de Letras de Uruguay y miembro honorario de la Academia Hondureña de Geografía e Historia. Coordinó el equipo redactor del Diccionario de Americanismos de la Asociación de Academias de la Lengua Española (2010).

Sus investigaciones sociolingüísticas han estado dirigidas a las lenguas indígenas y afrohondureñas y al español de Honduras: Ha realizado trabajos de investigación de la lengua Lenca de Honduras y de El Salvador, así como sobre la lengua de las etnias tawahka y garífuna. Algunos títulos de sus obras son: El español hablado en Honduras; Educación Bilingüe e Intercultural en Centroamérica y México, (Editorial Guaymuras); Toponimias indígenas de Centroamérica (Honduras, El Salvador, Guatemala y Nicaragua) de Alberto Membreño con prólogo de A. Herranz; Estado, sociedad y lenguaje: política lingüística en Honduras (1502-1995); Proceso de nahuatlización y nahuatlismos de uso en Honduras, de la Editorial Universitaria de la UNAH, que se presenta este día.

*Libros en prensa: Mitos creencias y medicina popular en un pueblo del área lenca de Honduras; El lenca de Honduras y el lenca de El Salvador o Chilanga; La lengua española en Honduras y el Diccionario de uso del español en Honduras (DUEH), que se editará en 2018.*
',NULL,'<p><img src="/content/images/2017/09/libro-ATANASIO.jpg" alt="" /></p>

<p><strong>La Universidad Nacional Autónoma de Honduras en el Valle de Sula y la Alianza Francesa de San Pedro Sula</strong></p>

<p><em>INVITAN a la presentación del libro</em> </p>

<h4 id="procesodenahuatlizacinynahuatlismosdeusoenhonduras">PROCESO DE NAHUATLIZACIÓN Y NAHUATLISMOS DE USO EN HONDURAS</h4>

<p><strong>Escrito por el Doctor en Filología ATANASIO HERRANZ</strong></p>

<p>Día: jueves 14 de Septiembre <br />
Hora: 9:30 a. m. <br />
Lugar: Alianza Francesa de San Pedro Sula <br />
(Col. Altavista, Sector el Playón,
  Tel.: 2566-3733)</p>

<p>Ingreso libre</p>

<p><em>"Como es poco conocido, el habla de los hondureños contiene más de mil palabras procedentes de la cultura mexicana, particularmente de la lengua náhuatl, llegadas al territorio centroamericano mediante migraciones y desplazamientos humanos que tardaron siglos.</em></p>

<p><em>Algunas de nuestras abuelas hablaron náhuatl, nosotros hablamos náhuatl cuando decimos, por ejemplo:</em></p>

<p><em>Achiote, aguacate, amate, ayotera, cacahuanance, chichicaste, chichicuilote, pizote, chapulinero, guatuza, tecolote, coyote, zopilote, pepesca, chacalín, chucho, atol, chilate, chilmol, elote, jilote, nacatamal, pozol, pupusa, totoposte, comal, guacal, pascón, petate, huacal, paste, milpa, ayotal, ciguanaba, cipitillo, entre muchos otros...</em></p>

<p><em>Vengan, acompáñennos par de horas el jueves y seguro que se divertirán (y conocerán) mucho 
con la sabiduría y simpatía de Atanasio Herranz..."</em> (Diario La Tribuna)</p>

<h3 id="sobreeldoctoratanasioherranz">Sobre el Doctor ATANASIO HERRANZ:</h3>

<p>ATANASIO HERRANZ, de nacionalidad hondureña y española, es Doctor en Filología Románica por la Universidad Complutense de Madrid.</p>

<p>Ha sido profesor en la UNAH y en la Maestría en Lexicografía de la Real Academia Española (RAE). Es miembro de número de la Academia Hondureña de la Lengua, de la Academia de Letras de Uruguay y miembro honorario de la Academia Hondureña de Geografía e Historia. Coordinó el equipo redactor del Diccionario de Americanismos de la Asociación de Academias de la Lengua Española (2010).</p>

<p>Sus investigaciones sociolingüísticas han estado dirigidas a las lenguas indígenas y afrohondureñas y al español de Honduras: Ha realizado trabajos de investigación de la lengua Lenca de Honduras y de El Salvador, así como sobre la lengua de las etnias tawahka y garífuna. Algunos títulos de sus obras son: El español hablado en Honduras; Educación Bilingüe e Intercultural en Centroamérica y México, (Editorial Guaymuras); Toponimias indígenas de Centroamérica (Honduras, El Salvador, Guatemala y Nicaragua) de Alberto Membreño con prólogo de A. Herranz; Estado, sociedad y lenguaje: política lingüística en Honduras (1502-1995); Proceso de nahuatlización y nahuatlismos de uso en Honduras, de la Editorial Universitaria de la UNAH, que se presenta este día.</p>

<p><em>Libros en prensa: Mitos creencias y medicina popular en un pueblo del área lenca de Honduras; El lenca de Honduras y el lenca de El Salvador o Chilanga; La lengua española en Honduras y el Diccionario de uso del español en Honduras (DUEH), que se editará en 2018.</em></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-09-13 18:11:15',2,'2017-09-13 18:55:26',2,'2017-09-13 18:19:40',2);
INSERT INTO "posts" VALUES(28,'38b3c490-f770-415c-ac94-d77e05dfabb3','TODO SOBRE EL TOUR DE CINE FRANCES','tour-de-cine-frances','#TOUR DE CINE FRANCÉS

Octubre estará de cine, comenzando con el Tour de Cine Francés del 5 al 18 y el 31 con el cine-concert de Virgile et son accodeón parlant.

[Horarios y cartelera](http://www.cinepolis.com.hn)

[+info del TOUR DE CINE FRANCES](http://www.tourdecinefrances.com/)

![](www.afsps.org/content/images/2017/10/Poster-TCF-2017-CA-21x30-72dpi.jpg)

###Sobre el Tour de cine francés
El TOUR DE CINE FRANCÉS es una muestra itinerante que presenta la mejor selección de cine francés contemporáneo (en versión original subtitulada) alrededor de la República Mexicana y Centroamérica, previo a su estreno comercial en salas.

Fundado por Nueva Era Films, Cinépolis®, la Embajada de Francia en México y la Federación de Alianzas Francesas, esta muestra tiene el propósito de promover el cine francés, y crear un nuevo público cinematográfico, ávido de la cultura y el lenguaje galo.

Cada película se presenta durante dos semanas en cada una de las ciudades que forman parte de nuestro amplio circuito de exhibición.

Desde 2005, el Tour de Cine Francés otorga el premio “La Palmita” como reconocimiento al mejor cortometraje. El jurado del premio esta constituido por directores, críticos, distribuidores y actores. La Palmita se ha convertido en un importante impulso a nivel nacional que permite al proyecto ganador darse a conocer internacionalmente con el apoyo necesario que la industria le puede ofrecer.

###Calendario
![](www.afsps.org/content/images/2017/10/2CALENDARIO-TCF-CA-2017-01.png)

###INFORMACIÓN DE LAS PELÍCULAS SEGÚN PROGRAMACIÓN 

![](www.afsps.org/content/images/2017/10/Una-Familia-Peculiar-72dpi-Artwork.jpg)
####UNA FAMILIA PECULIAR
#####Cigarettes et chocolat chaud

De: Sophie Reine
Con: Gustave Kervern, Camille Cottin, Héloïse Dugas
Producción: Francia, 2016
Género : Comedia dramática
Duración: 98 min

**Sinopsis:**
Denis Patar es un padre cariñoso, pero con exceso de trabajo, que lucha solo para sacar adelante a sus hijas, Janis de 13 años y Mercredi de 9 años. Una noche olvida recoger a una de ellas en la escuela y una trabajadora social se da a la tarea de investigar el funcionamiento de la familia Patar. Denis se ve obligado a tomar un “curso de paternidad” para evitar perder la custodia de sus hijas. Un entrañable retrato de una familia poco común.

![](www.afsps.org/content/images/2017/10/Aun-mas-bella-72dpi-Artwork.jpg)
###AÚN MÁS BELLA
#####(De plus belle)

De: Anne-Gaëlle Daval
Con: Florence Foresti, Mathieu Kassovitz, Nicole Garcia
Producción: Francia, 2017
Género: Comedia dramática
Duración: 99 min

**Sinopsis:**
Recién curada de cáncer de seno, Lucie trata de retomar su vida. Sin embargo, aunque su familia y amigos la alientan para que siga adelante, ella no encuentra la fuerza para hacerlo. Cuando conoce a Dalila, una profesora de danza que invita a mujeres como Lucie a vivir plenamente, a quererse, aceptarse y amarse de nuevo, se trasforma su perspectiva de sí misma y de la vida. En medio de éste proceso conoce a Clovis, un hombre atractivo y seductor que intrigado por el carácter de Lucie, hará todo lo posible por conquistarla pese a sus constantes negativas.

![](www.afsps.org/content/images/2017/10/Los-ex-72dpi-Artwork.jpg)
###LOS EX
#####(Les Ex)

De: Maurice Barthélemy
Con: Jean-Paul Rouve, Patrick Chesnais, Stéfi Celma
Produccion: Francia, 2017
Género: Comedia
Duración: 84 min

**Sinopsis:**
París no es sólo la ciudad de los enamorados, ¡también es la ciudad de los ex! Una divertida reflexión sobre las ex parejas en la que los personajes se ven envueltos en un gran lío dentro del cual podrían volver a enamorarse, ¿pero de quién? Antonie no se atreve a comprometerse, Didier extraña a su ex esposa, el padre Laurent debe oficiar el matrimonio de su ex, Serge es acosado por Lise y Greg se consuela con el perro de su ex novia… Ya sea que los amemos o los detestemos, ¡siempre es difícil olvidar a los ex!

![](www.afsps.org/content/images/2017/10/El-Vinedo-que-nos-une-72dpi-Artwork.jpg)
###EL VIÑEDO QUE NOS UNE
#####(Ce qui nous lie)

De: Cédric Klapisch
Con: Pio Marmaï, Ana Girardot, François Civil
Producción: Francia, 2017
Género: Drama
Duración: 113 min

**Sinopsis:**
Hace diez años que Jean salió de su Borgoña natal para darle la vuelta al mundo y alejarse de su familia. Al enterarse que su padre está enfermo, regresa a la tierra de su infancia en donde se reencuentra con sus hermanos Juliette y Jérémie. Su padre fallece justo antes del inicio de las vendimias y durante un año, al ritmo de las 4 estaciones, estos 3 jóvenes adultos buscan reinventar su fraternidad creciendo y madurando al mismo ritmo que el vino que fabrican.

![](www.afsps.org/content/images/2017/10/Frantz-72dpi-Artwork.jpg)
###FRANTZ
#####(Frantz)

De: François Ozon
Con: Pierre Niney, Paula Beer, Ernst Stötzner
Producción: Francia, Alemania 2016
Género: Drama
Duración : 113 min

**Sinopsis:**
En una pequeña ciudad alemana, después de la Primera Guerra Mundial, Anna visita todos los días la tumba de su prometido, Frantz, quien murió en el frente en Francia. Su vida cambiará con la llegada de Adrien, un enigmático soldado francés quien dice ser amigo de Frantz pero ¿de qué se conocían realmente?. La presencia de éste soldado, después de la derrota alemana, provocará reacciones apasionadas.

![](www.afsps.org/content/images/2017/10/El-Reencuentro-72dpi-Artwork.jpg)
###EL REENCUENTRO
#####(Sage femme)

De: Martin Provost
Con: Catherine Frot, Catherine Deneuve, Olivier Gourmet
Producción: Francia, 2017
Género: Drama
Duración: 116 min

**Sinopsis:**
Claire es una partera, dedicada por completo a su oficio. Su rutinaria vida se transforma con el regreso de Béatrice, una mujer egoísta y caprichosa que fue pareja de su difunto padre. Una emotiva historia sobre el reencuentro de dos mujeres completamente distintas que, unidas por el cariño, tratan de hacer las paces con su pasado.

![](www.afsps.org/content/images/2017/10/Paso-a-paso-72dpi-Artwork.jpg)
###PASO A PASO
#####(Patients)

De: Grand Corps Malade y Mehdi Idir
Con: Pablo Pauly, Soufiane Guerrab, Moussa Mansaly
Producción: Francia, 2017
Género: Comedia dramática
Duración: 111 min

**Sinopsis:**
Bañarse, vestirse, caminar, jugar basket, son algunas de las actividades que Ben no puede hacer a su llegada al centro de rehabilitación debido a un grave accidente. Sus nuevos amigos son tetrapléjicos, parapléjicos, con traumas craneales… Juntos aprenderán a ser pacientes. Se resistirán a los tratamientos, se pelearán entre ellos, se enamorarán y encontrarán juntos la energía para volver a vivir. Paso a paso es la historia de un renacimiento, de un viaje caótico hecho de victorias y derrotas, de lágrimas y de risas, pero sobre todo de encuentros: uno no puede curarse solo.

[Horarios y cartelera](http://www.cinepolis.com.hn)

[+info del TOUR DE CINE FRANCES](http://www.tourdecinefrances.com)',NULL,'<h1 id="tourdecinefrancs">TOUR DE CINE FRANCÉS</h1>

<p>Octubre estará de cine, comenzando con el Tour de Cine Francés del 5 al 18 y el 31 con el cine-concert de Virgile et son accodeón parlant.</p>

<p><a href="http://www.cinepolis.com.hn">Horarios y cartelera</a></p>

<p><a href="http://www.tourdecinefrances.com/">+info del TOUR DE CINE FRANCES</a></p>

<p><img src="/content/images/2017/10/Poster-TCF-2017-CA-21x30-72dpi.jpg" alt="" /></p>

<h3 id="sobreeltourdecinefrancs">Sobre el Tour de cine francés</h3>

<p>El TOUR DE CINE FRANCÉS es una muestra itinerante que presenta la mejor selección de cine francés contemporáneo (en versión original subtitulada) alrededor de la República Mexicana y Centroamérica, previo a su estreno comercial en salas.</p>

<p>Fundado por Nueva Era Films, Cinépolis®, la Embajada de Francia en México y la Federación de Alianzas Francesas, esta muestra tiene el propósito de promover el cine francés, y crear un nuevo público cinematográfico, ávido de la cultura y el lenguaje galo.</p>

<p>Cada película se presenta durante dos semanas en cada una de las ciudades que forman parte de nuestro amplio circuito de exhibición.</p>

<p>Desde 2005, el Tour de Cine Francés otorga el premio “La Palmita” como reconocimiento al mejor cortometraje. El jurado del premio esta constituido por directores, críticos, distribuidores y actores. La Palmita se ha convertido en un importante impulso a nivel nacional que permite al proyecto ganador darse a conocer internacionalmente con el apoyo necesario que la industria le puede ofrecer.</p>

<h3 id="calendario">Calendario</h3>

<p><img src="/content/images/2017/10/2CALENDARIO-TCF-CA-2017-01.png" alt="" /></p>

<h3 id="informacindelaspelculassegnprogramacin">INFORMACIÓN DE LAS PELÍCULAS SEGÚN PROGRAMACIÓN</h3>

<p><img src="/content/images/2017/10/Una-Familia-Peculiar-72dpi-Artwork.jpg" alt="" /></p>

<h4 id="unafamiliapeculiar">UNA FAMILIA PECULIAR</h4>

<h5 id="cigarettesetchocolatchaud">Cigarettes et chocolat chaud</h5>

<p>De: Sophie Reine <br />
Con: Gustave Kervern, Camille Cottin, Héloïse Dugas <br />
Producción: Francia, 2016 <br />
Género : Comedia dramática <br />
Duración: 98 min</p>

<p><strong>Sinopsis:</strong>
Denis Patar es un padre cariñoso, pero con exceso de trabajo, que lucha solo para sacar adelante a sus hijas, Janis de 13 años y Mercredi de 9 años. Una noche olvida recoger a una de ellas en la escuela y una trabajadora social se da a la tarea de investigar el funcionamiento de la familia Patar. Denis se ve obligado a tomar un “curso de paternidad” para evitar perder la custodia de sus hijas. Un entrañable retrato de una familia poco común.</p>

<p><img src="/content/images/2017/10/Aun-mas-bella-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="anmsbella">AÚN MÁS BELLA</h3>

<h5 id="deplusbelle">(De plus belle)</h5>

<p>De: Anne-Gaëlle Daval <br />
Con: Florence Foresti, Mathieu Kassovitz, Nicole Garcia <br />
Producción: Francia, 2017 <br />
Género: Comedia dramática <br />
Duración: 99 min</p>

<p><strong>Sinopsis:</strong>
Recién curada de cáncer de seno, Lucie trata de retomar su vida. Sin embargo, aunque su familia y amigos la alientan para que siga adelante, ella no encuentra la fuerza para hacerlo. Cuando conoce a Dalila, una profesora de danza que invita a mujeres como Lucie a vivir plenamente, a quererse, aceptarse y amarse de nuevo, se trasforma su perspectiva de sí misma y de la vida. En medio de éste proceso conoce a Clovis, un hombre atractivo y seductor que intrigado por el carácter de Lucie, hará todo lo posible por conquistarla pese a sus constantes negativas.</p>

<p><img src="/content/images/2017/10/Los-ex-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="losex">LOS EX</h3>

<h5 id="lesex">(Les Ex)</h5>

<p>De: Maurice Barthélemy <br />
Con: Jean-Paul Rouve, Patrick Chesnais, Stéfi Celma <br />
Produccion: Francia, 2017 <br />
Género: Comedia <br />
Duración: 84 min</p>

<p><strong>Sinopsis:</strong>
París no es sólo la ciudad de los enamorados, ¡también es la ciudad de los ex! Una divertida reflexión sobre las ex parejas en la que los personajes se ven envueltos en un gran lío dentro del cual podrían volver a enamorarse, ¿pero de quién? Antonie no se atreve a comprometerse, Didier extraña a su ex esposa, el padre Laurent debe oficiar el matrimonio de su ex, Serge es acosado por Lise y Greg se consuela con el perro de su ex novia… Ya sea que los amemos o los detestemos, ¡siempre es difícil olvidar a los ex!</p>

<p><img src="/content/images/2017/10/El-Vinedo-que-nos-une-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="elviedoquenosune">EL VIÑEDO QUE NOS UNE</h3>

<h5 id="cequinouslie">(Ce qui nous lie)</h5>

<p>De: Cédric Klapisch <br />
Con: Pio Marmaï, Ana Girardot, François Civil <br />
Producción: Francia, 2017 <br />
Género: Drama <br />
Duración: 113 min</p>

<p><strong>Sinopsis:</strong>
Hace diez años que Jean salió de su Borgoña natal para darle la vuelta al mundo y alejarse de su familia. Al enterarse que su padre está enfermo, regresa a la tierra de su infancia en donde se reencuentra con sus hermanos Juliette y Jérémie. Su padre fallece justo antes del inicio de las vendimias y durante un año, al ritmo de las 4 estaciones, estos 3 jóvenes adultos buscan reinventar su fraternidad creciendo y madurando al mismo ritmo que el vino que fabrican.</p>

<p><img src="/content/images/2017/10/Frantz-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="frantz">FRANTZ</h3>

<h5 id="frantz">(Frantz)</h5>

<p>De: François Ozon <br />
Con: Pierre Niney, Paula Beer, Ernst Stötzner <br />
Producción: Francia, Alemania 2016 <br />
Género: Drama <br />
Duración : 113 min</p>

<p><strong>Sinopsis:</strong>
En una pequeña ciudad alemana, después de la Primera Guerra Mundial, Anna visita todos los días la tumba de su prometido, Frantz, quien murió en el frente en Francia. Su vida cambiará con la llegada de Adrien, un enigmático soldado francés quien dice ser amigo de Frantz pero ¿de qué se conocían realmente?. La presencia de éste soldado, después de la derrota alemana, provocará reacciones apasionadas.</p>

<p><img src="/content/images/2017/10/El-Reencuentro-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="elreencuentro">EL REENCUENTRO</h3>

<h5 id="sagefemme">(Sage femme)</h5>

<p>De: Martin Provost <br />
Con: Catherine Frot, Catherine Deneuve, Olivier Gourmet <br />
Producción: Francia, 2017 <br />
Género: Drama <br />
Duración: 116 min</p>

<p><strong>Sinopsis:</strong>
Claire es una partera, dedicada por completo a su oficio. Su rutinaria vida se transforma con el regreso de Béatrice, una mujer egoísta y caprichosa que fue pareja de su difunto padre. Una emotiva historia sobre el reencuentro de dos mujeres completamente distintas que, unidas por el cariño, tratan de hacer las paces con su pasado.</p>

<p><img src="/content/images/2017/10/Paso-a-paso-72dpi-Artwork.jpg" alt="" /></p>

<h3 id="pasoapaso">PASO A PASO</h3>

<h5 id="patients">(Patients)</h5>

<p>De: Grand Corps Malade y Mehdi Idir <br />
Con: Pablo Pauly, Soufiane Guerrab, Moussa Mansaly <br />
Producción: Francia, 2017 <br />
Género: Comedia dramática <br />
Duración: 111 min</p>

<p><strong>Sinopsis:</strong>
Bañarse, vestirse, caminar, jugar basket, son algunas de las actividades que Ben no puede hacer a su llegada al centro de rehabilitación debido a un grave accidente. Sus nuevos amigos son tetrapléjicos, parapléjicos, con traumas craneales… Juntos aprenderán a ser pacientes. Se resistirán a los tratamientos, se pelearán entre ellos, se enamorarán y encontrarán juntos la energía para volver a vivir. Paso a paso es la historia de un renacimiento, de un viaje caótico hecho de victorias y derrotas, de lágrimas y de risas, pero sobre todo de encuentros: uno no puede curarse solo.</p>

<p><a href="http://www.cinepolis.com.hn">Horarios y cartelera</a></p>

<p><a href="http://www.tourdecinefrances.com">+info del TOUR DE CINE FRANCES</a></p>',NULL,'/content/images/2017/10/Screen-Shot-2017-10-03-at-12.16.20-PM-copy.jpg',0,0,'published','en_US','public',NULL,NULL,2,'2017-10-03 17:31:20',2,'2017-10-03 18:18:38',2,'2017-10-03 18:11:36',2);
INSERT INTO "posts" VALUES(29,'1c2f875e-2ca9-4141-872d-b8811f4e6109','Noche de cine-concierto con Virgile y Sylvain','noche-de-cine-concierto-con-virgile-y-sylvain','![](www.afsps.org/content/images/2017/10/afiche-tabloide-oficial.png)

#OCTUBRE DE CINE!

###NOCHE DE CINE-CONCIERTO
###Con Virgile Goller, Sylvain Rabourdin (Francia)
###y músicos hondureños invitados

Verás como los artistas animan las películas a través de su música en vivo, creando fusiones instrumentales entre artistas de Francia y Honduras.

En el repertorio se presentaran tres cortos del cine de los autores: Charles Chaplin, Buster Keaton y del Cinéma primitif français.

Los músicos locales invitados que los acompañarán durante el cine-concierto formarán parte de una residencia para artistas impartida por Virgile y Sylvain en las instalaciones de la Alianza Francesa de San Pedro Sula.

Por Honduras los artistas participantes son:
• Nimrod Rodríguez <br>
• Hunty Gabbe <br>
• Oscar Mateo Ayala <br>
• Santos Valladares <br>
• Juan Ramón Valenzuela

###Cine-concierto
**Día: martes 31 de octubre | Hora: 7:30 p.m.** <br>
**Lugar: Alianza Francesa de San Pedro Sula** <br>
**Entrada libre y gratuita | Para todo público** <br>

####SOBRE LOS ARTISTAS
#####Virgile, Sylvain y el cine-concierto
<br
Hace casi diez años que Sylvain Rabourdin y Virgile Goller se encontraron en el Conservatorio de Perpignan en la Clase de jazz e improvisación de Serge Lazarevitch.  Desde las primeras notas que tocaron juntos, se creó una afinidad particular entre los dos músicos: un acordeón, un violín, influencias comunes y una misma manera de vivir la música, centrada en el intercambio y el placer de tocar, juntos y por los demás… Todo les acerca. 

En 2008, para ir más allá, Virgile Goller invita a Sylvain Rabourdin para un cine-concierto organizado por el Instituto Jean Vigo (cinemateca euro-regional de Perpignan, Francia) en el marco del congreso Domitor (asociación internacional de investigación sobre el cine primitivo). Durante este verdadero maratón (una hora y media para musicalizar 17 cortos metrajes), sus improvisaciones revelan sabores todavía desconocidos incluso por los mismos artistas y el público saludó con entusiasmo la inventividad y riqueza de sus intercambios que subliman este cine maravilloso y balbuceante.
 
Así empieza un período de colaboraciones exitosas, acompañando con viveza y placer permanentemente, numerosas sesiones más de cine mudo.

Sea cual sea el género del film (yendo de la fantasía del cine primitivo, al western, pasando por lo burlesco, las películas policiacas u obras de maestros del expresionismo) desde las primeras notas e imágenes, tanto el público como los músicos se dejan llevar por esta fusión, a veces mecidos, a veces sacudidos, otras veces bamboleante, o carcajeando, como si fuera un eco a las multitudes que se concentraban frente a las lonas de ferias en Europa, hace cien años.

*¡Inmutable y vivaz cine mudo, inmutables y vivaces músicos, por siempre conectados por la magia del cine-concierto, siguen su ruta más allá del tiempo y de las fronteras!*

![](www.afsps.org/content/images/2017/10/Vrgile-Goller--Mia-Nazarie-photography-.jpg)

####Virgile y su acordeón parlante
#####Cine-conciertos

Virgile Goller, que permaneció mucho tiempo atormentado por los héroes en blanco y negro de las películas mudas de su niñez, parece el mismo sacado de una tela de cine!

El cine mudo le cautiva, le conmueve, le atrae inexorablemente. ¿Qué hacer para alcanzar esos locos inofensivos, esos inventores y magos de otro siglo? ¿Cómo alcanzarles y encontrarles más allá del tiempo? 

Las respuestas a sus preguntas vinieron del festival de Anères en Francia donde por primera vez vio películas mudas acompañadas en directo por talentosos pianistas, conjuntos de cuerdas y sobre todo por un acordeonista, ¡suprema revelación! Fascinado, volvió a este festival varios años seguidos para sumergirse en las salas oscuras y nutrirse de imágenes y músicas. Con su acordeón, añade su propio toque endiablado a la fiesta, cada noche, en el café típico de este pueblo. 

Por fin, animado por el equipo del festival, decide hacer un paso adelante musicalizando en vivo por primera vez una película muda. En 2003, acompaña un corto surrealista y un largo metraje. Es también el año cuando musicaliza un documental inédito sobre la Retirada, en el festival Confrontation del Institut Jean Vigo en Perpignan. Nace una relación estrecha con este instituto (ahora llamada Cinemathèque euro-régionale) y pronto le da la oportunidad de acompañar un florilegio de películas, solo o acompañado de otros músicos (yendo de la fantasía del cine primitivo, al western, pasando por lo burlesco, las películas policiacas u obras de maestros del expresionismo). 

Desde entonces, festival tras festival Virgile, acompañado de su “acordeón parlante”, camina por las carreteras de Francia, España y África (Mali y Guinea-Ecuatorial). También es invitado a dirigir residencias de trabajo y encuentros pedagógicos en instituciones en el extranjero, para producirse en solo o acompañado de músicos locales: Instituto Francés (Guinea ecuatorial, Malabo), Alianza Francesa de Guatemala y Alianza Francesa de La Antigua Guatemala. 

Bajo la acaricia de sus dedos sobre el teclado de su acordeón, su sueño se hace realidad: encuentra a sus héroes, les viste, les nutre, les reconforta y les realza!

![](www.afsps.org/content/images/2017/10/Sylvain-Rabourdin-1.jpg)

####Sylvain Rabourdin

Sylvain Rabourdin ni siquiera se acuerda de las primeras notas que tocó con su violín, cuando tenía 4 años. Creció con este instrumento, que lo llevó al Conservatorio de Narbonne, y después al de Perpignan, adónde pasó su Diploma de Estudios Musicales de violín, ensayando al lado de Diego Tosi y Christian Rouquié. Descubrió de forma paralela los talleres de jazz de Serge Lazarevitch. 

En 2010 obtuvo el premio Marion Bourgine en el festival Jazz de Marciac (Francia). Apasionado por la improvisación, siguió este camino con el Jazz Manouche, y las estéticas más modernas, interesándose a las músicas de John Zorn o Bill Frisell.
 
Violinista ecléctico, también descubrió el violín popular francés, europeo, y brasileño, que le abrió nuevos horizontes musicales: Choro, Samba, Forro.

Dentro de varios ensambles, pudo acompañar o grabar para varios artistas como Richard Galliano, Wilmenia Fernandez, Michel Portal, Laurent Korcia, Giovanni Mirabassi, Evan Christopher.

También es comediante en el espectáculo musical Homocordus con la compañía Zorozora.

Junto con Virgile Goller también pudo aplicar sus conocimientos para musicalizar películas mudas de Charlie Chaplin, Buster Keaton, Alfred Hitchcock o Charley Chase.

+ info al: (504) 2566-3733

##Un evento de:
• Alianza Francesa de San Pedro Sula  <br>
• Embajada de Francia en Honduras  <br>
• ALIANCE FRANÇAIS América Central <br>
• Institut Français Amérique Centrale  <br>

**Patrocinador oficial:** <br>
• Hotel Hilton Princess de San Pedro Sula  <br>

**Con el Patrocinio de:**  <br>
• La Cité, cocina mediterránea  <br>
• El Portal de las carnes  <br>
• Restaurante Chedrani  <br>

**Con el co-patrocinio de:** <br>
• Comisariato Los Andes - Vinos Calvet <br>
• L''art du Pain <br>
• Hasta La Pasta <br>
• Aromas Pizza-Cafe <br>
• Diario La Prensa <br>
• Sushiitto',NULL,'<p><img src="/content/images/2017/10/afiche-tabloide-oficial.png" alt="" /></p>

<h1 id="octubredecine">OCTUBRE DE CINE!</h1>

<h3 id="nochedecineconcierto">NOCHE DE CINE-CONCIERTO</h3>

<h3 id="convirgilegollersylvainrabourdinfrancia">Con Virgile Goller, Sylvain Rabourdin (Francia)</h3>

<h3 id="ymsicoshondureosinvitados">y músicos hondureños invitados</h3>

<p>Verás como los artistas animan las películas a través de su música en vivo, creando fusiones instrumentales entre artistas de Francia y Honduras.</p>

<p>En el repertorio se presentaran tres cortos del cine de los autores: Charles Chaplin, Buster Keaton y del Cinéma primitif français.</p>

<p>Los músicos locales invitados que los acompañarán durante el cine-concierto formarán parte de una residencia para artistas impartida por Virgile y Sylvain en las instalaciones de la Alianza Francesa de San Pedro Sula.</p>

<p>Por Honduras los artistas participantes son: <br />
• Nimrod Rodríguez <br>
• Hunty Gabbe <br>
• Oscar Mateo Ayala <br>
• Santos Valladares <br>
• Juan Ramón Valenzuela</p>

<h3 id="cineconcierto">Cine-concierto</h3>

<p><strong>Día: martes 31 de octubre | Hora: 7:30 p.m.</strong> <br>
<strong>Lugar: Alianza Francesa de San Pedro Sula</strong> <br>
<strong>Entrada libre y gratuita | Para todo público</strong> <br></p>

<h4 id="sobrelosartistas">SOBRE LOS ARTISTAS</h4>

<h5 id="virgilesylvainyelcineconcierto">Virgile, Sylvain y el cine-concierto</h5>

<p><br <br />
Hace casi diez años que Sylvain Rabourdin y Virgile Goller se encontraron en el Conservatorio de Perpignan en la Clase de jazz e improvisación de Serge Lazarevitch.  Desde las primeras notas que tocaron juntos, se creó una afinidad particular entre los dos músicos: un acordeón, un violín, influencias comunes y una misma manera de vivir la música, centrada en el intercambio y el placer de tocar, juntos y por los demás… Todo les acerca. </p>

<p>En 2008, para ir más allá, Virgile Goller invita a Sylvain Rabourdin para un cine-concierto organizado por el Instituto Jean Vigo (cinemateca euro-regional de Perpignan, Francia) en el marco del congreso Domitor (asociación internacional de investigación sobre el cine primitivo). Durante este verdadero maratón (una hora y media para musicalizar 17 cortos metrajes), sus improvisaciones revelan sabores todavía desconocidos incluso por los mismos artistas y el público saludó con entusiasmo la inventividad y riqueza de sus intercambios que subliman este cine maravilloso y balbuceante.</p>

<p>Así empieza un período de colaboraciones exitosas, acompañando con viveza y placer permanentemente, numerosas sesiones más de cine mudo.</p>

<p>Sea cual sea el género del film (yendo de la fantasía del cine primitivo, al western, pasando por lo burlesco, las películas policiacas u obras de maestros del expresionismo) desde las primeras notas e imágenes, tanto el público como los músicos se dejan llevar por esta fusión, a veces mecidos, a veces sacudidos, otras veces bamboleante, o carcajeando, como si fuera un eco a las multitudes que se concentraban frente a las lonas de ferias en Europa, hace cien años.</p>

<p><em>¡Inmutable y vivaz cine mudo, inmutables y vivaces músicos, por siempre conectados por la magia del cine-concierto, siguen su ruta más allá del tiempo y de las fronteras!</em></p>

<p><img src="/content/images/2017/10/Vrgile-Goller--Mia-Nazarie-photography-.jpg" alt="" /></p>

<h4 id="virgileysuacordenparlante">Virgile y su acordeón parlante</h4>

<h5 id="cineconciertos">Cine-conciertos</h5>

<p>Virgile Goller, que permaneció mucho tiempo atormentado por los héroes en blanco y negro de las películas mudas de su niñez, parece el mismo sacado de una tela de cine!</p>

<p>El cine mudo le cautiva, le conmueve, le atrae inexorablemente. ¿Qué hacer para alcanzar esos locos inofensivos, esos inventores y magos de otro siglo? ¿Cómo alcanzarles y encontrarles más allá del tiempo? </p>

<p>Las respuestas a sus preguntas vinieron del festival de Anères en Francia donde por primera vez vio películas mudas acompañadas en directo por talentosos pianistas, conjuntos de cuerdas y sobre todo por un acordeonista, ¡suprema revelación! Fascinado, volvió a este festival varios años seguidos para sumergirse en las salas oscuras y nutrirse de imágenes y músicas. Con su acordeón, añade su propio toque endiablado a la fiesta, cada noche, en el café típico de este pueblo. </p>

<p>Por fin, animado por el equipo del festival, decide hacer un paso adelante musicalizando en vivo por primera vez una película muda. En 2003, acompaña un corto surrealista y un largo metraje. Es también el año cuando musicaliza un documental inédito sobre la Retirada, en el festival Confrontation del Institut Jean Vigo en Perpignan. Nace una relación estrecha con este instituto (ahora llamada Cinemathèque euro-régionale) y pronto le da la oportunidad de acompañar un florilegio de películas, solo o acompañado de otros músicos (yendo de la fantasía del cine primitivo, al western, pasando por lo burlesco, las películas policiacas u obras de maestros del expresionismo). </p>

<p>Desde entonces, festival tras festival Virgile, acompañado de su “acordeón parlante”, camina por las carreteras de Francia, España y África (Mali y Guinea-Ecuatorial). También es invitado a dirigir residencias de trabajo y encuentros pedagógicos en instituciones en el extranjero, para producirse en solo o acompañado de músicos locales: Instituto Francés (Guinea ecuatorial, Malabo), Alianza Francesa de Guatemala y Alianza Francesa de La Antigua Guatemala. </p>

<p>Bajo la acaricia de sus dedos sobre el teclado de su acordeón, su sueño se hace realidad: encuentra a sus héroes, les viste, les nutre, les reconforta y les realza!</p>

<p><img src="/content/images/2017/10/Sylvain-Rabourdin-1.jpg" alt="" /></p>

<h4 id="sylvainrabourdin">Sylvain Rabourdin</h4>

<p>Sylvain Rabourdin ni siquiera se acuerda de las primeras notas que tocó con su violín, cuando tenía 4 años. Creció con este instrumento, que lo llevó al Conservatorio de Narbonne, y después al de Perpignan, adónde pasó su Diploma de Estudios Musicales de violín, ensayando al lado de Diego Tosi y Christian Rouquié. Descubrió de forma paralela los talleres de jazz de Serge Lazarevitch. </p>

<p>En 2010 obtuvo el premio Marion Bourgine en el festival Jazz de Marciac (Francia). Apasionado por la improvisación, siguió este camino con el Jazz Manouche, y las estéticas más modernas, interesándose a las músicas de John Zorn o Bill Frisell.</p>

<p>Violinista ecléctico, también descubrió el violín popular francés, europeo, y brasileño, que le abrió nuevos horizontes musicales: Choro, Samba, Forro.</p>

<p>Dentro de varios ensambles, pudo acompañar o grabar para varios artistas como Richard Galliano, Wilmenia Fernandez, Michel Portal, Laurent Korcia, Giovanni Mirabassi, Evan Christopher.</p>

<p>También es comediante en el espectáculo musical Homocordus con la compañía Zorozora.</p>

<p>Junto con Virgile Goller también pudo aplicar sus conocimientos para musicalizar películas mudas de Charlie Chaplin, Buster Keaton, Alfred Hitchcock o Charley Chase.</p>

<ul>
<li>info al: (504) 2566-3733</li>
</ul>

<h2 id="uneventode">Un evento de:</h2>

<p>• Alianza Francesa de San Pedro Sula  <br>
• Embajada de Francia en Honduras  <br>
• ALIANCE FRANÇAIS América Central <br>
• Institut Français Amérique Centrale  <br></p>

<p><strong>Patrocinador oficial:</strong> <br>
• Hotel Hilton Princess de San Pedro Sula  <br></p>

<p><strong>Con el Patrocinio de:</strong>  <br>
• La Cité, cocina mediterránea  <br>
• El Portal de las carnes  <br>
• Restaurante Chedrani  <br></p>

<p><strong>Con el co-patrocinio de:</strong> <br>
• Comisariato Los Andes - Vinos Calvet <br>
• L''art du Pain <br>
• Hasta La Pasta <br>
• Aromas Pizza-Cafe <br>
• Diario La Prensa <br>
• Sushiitto</p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-10-12 16:06:05',2,'2017-10-27 15:31:55',2,'2017-10-12 16:40:50',2);
INSERT INTO "posts" VALUES(30,'16620a84-9764-4984-9e45-69f2b9d33f52','DOCUMENTAL CASA EN TIERRA AJENA','documental-casa-en-tierra-ajena','![](www.afsps.org/content/images/2017/11/Evento-proyeccio-n-Alianza-Francesa-Honduras.png)

#CASA EN TIERRA AJENA

**INFORMACIÓN GENERAL** <BR>
TÍTULO O NOMBRE DE LA PRODUCCIÓN: CASA EN TIERRA AJENA
TEMA: Migración forzada en América Central
ENTIDADES PRODUCTORAS O SOLICITANTES:
• Consejo Nacional de Rectores (CONARE) <br>
• Universidad de Costa Rica (UCR) <br>
• Universidad Estatal a Distancia (UNED) <br>
FECHA DE PRODUCCIÓN: 2017

###SINOPSIS
**Casa en Tierra Ajena** *es un documental que relata las historias y los sueños de diversas personas que se encuentran en procesos de emigración forzada en Centroamérica. También recupera las voces de quienes se han quedado en sus países resistiendo y transformando sus realidades. La “Casa del Migrante de Saltillo”, situada en Coahuila, en el norte de México, es el lugar de encuentro de estos relatos, ya que es donde confluyen las diferentes personas migrantes que buscan un lugar seguro para descansar y retomar fuerzas antes de intentar cruzar la frontera a los Estados Unidos. El documental expone los factores de expulsión que fuerzan a las personas a salir de sus países, los mecanismos de control cada vez más violentos y represivos que se imponen para intentar retener a los migrantes y la solidaridad que se teje sin fronteras.*

DURACIÓN: 1h, 20m, 43s
IDIOMA: ESPAÑOL
SUBTÍTULOS: ESPAÑOL - INGLÉS
SITIO WEB: casaentierrajena.com 
REDES SOCIALES:	Facebook: Casa en tierra ajena
NOMBRE DE LOS ARCHIVOS: Casa en tierra ajena 
Trailer oficial: (https://www.youtube.com/watch?v=FD7ANfLwdHU)

####CRÉDITOS DE PRODUCCIÓN	
**PRODUCCIÓN EJECUTIVA** <br>
Carlos Sandoval García 
Luis Fernando Fallas Fallas 
Rafael Díaz Sánchez 

**PRODUCCIÓN GENERAL** <br>
Carlos Sandoval García
Ivannia Villalobos Vindas

**DIRECCIÓN** <br>
Ivannia Villalobos Vindas

**COORDINACIÓN GENERAL** <br>
Carlos Sandoval García

**ASISTENCIA DE PRODUCCIÓN** <br>
Michele Ferris Dobles

**GUIÓN LITERARIO** <br>
Ivannia Villalobos Vindas
Michele Ferris Dobles
Carlos Sandoval García

**DIRECCIÓN DE FOTOGRAFÍA** <br>
Santiago Martínez Artavia

**FOTOGRAFÍA** <br>
Santiago Martínez Artavia
Michelle Ferris Dobles
Ivannia Villalobos Vindas
Ernesto Valverde Villalobos

**EDICIÓN** <br>
David Ramírez Baldizón
Ivannia Villalobos Vindas

**DISEÑO Y ANIMACIÓN** <br>
José Mario Quesada Abrams

**MÚSICA ORIGINAL** <br>
Glendon Ramírez Díaz

**MÚSICA VIDEOS COMPLEMENTARIOS** <br>
Esteban Ramírez Hernández

**COLORIZACIÓN** <br>
José Arce Ramírez

**POSPRODUCCIÓN DE AUDIO** <br>
Iván Pérez Arias

**SONIDO DIRECTO** <br>
Santiago Martínez Artavia
Carlos Sandoval García
Michele Ferris Dobles
Ivannia Villalobos Vindas

**VISIONADO Y TRANSCRIPCIÓN ENTREVISTA GIRA 1** <br>
Carolina Muñoz Cabalceta
Eddson Gómez Chavarría

**TRANSCRIPCIÓN AL ESPAÑOL** <br>
Eduardo Monge Navarro

**SUBTÍTULOS ESPAÑOL** <br>
José Miguel Orozco Piferrer 
Elena Rojas Ulate

**TRADUCCIÓN AL INGLÉS** <br>
Anna Flury

**DISEÑO WEB Y REDES SOCIALES** <br>
Fidel de Rooy 

**AUTORÍA DE DVD** <br>
José Mario Quesada Abrams

**PLAN DE DIFUSIÓN** <br>
Fabiola Pomareda García

**ADMINISTRACIÓN FINANCIERA** <br>
Evelyn Pérez Silva
Marielos López

**COORDINACIÓN DE OPERACIONES Y COMPRA DE EQUIPO** <br>
Rodrigo Ureña Sequeira

**MANTENIMIENTO DE EQUIPOS** <br>
Carlos Andrés Alvarado Elizondo

**APOYO ADMINISTRATIVO**
Alejandra Ramírez González
Andrea Zamora Salazar
Bignory Moraga Peralta
Carmen Caamaño Morúa
Catherine Lara Campos
Ernesto Amey Walter
Hazel González Araya
Iriabel Hernández Vindas
Johanna Rimola
Kathia Castro Fuentes
Lilly Díaz Gamboa 
Lorena Aguilar Solano
Luis Guillermo Carpio Malavassi
Mabel León Blanco
María del C. Calvo
María Sánchez Hernández
Marilyn Fallas Hidalgo
Marjorie Jiménez Castro
Michael Artola Padilla 
Roberto Salom Echeverría
Yelena Durán Rivera

**IMÁGENES DE ARCHIVO AUTORIZADAS PARA USO *EXCLUSIVO* EN EL PROYECTO DOCUMENTAL** <br>
Material del juicio de Efraín Ríos Montt, Serie “Dictador en el Banquillo”. Producción: Skylight (http://skylight.is) 

Fotografía “Muro fronterizo, Otay” en fotoreportaje  “La línea, un limbo atrapasueños”. Copyright por Prometeo Lucero, creador audiovisual y periodista gráfico (http://prometeolucero.photoshelter.com)

Material del video “La Bestia”. Producción: Mauro Corinti, fotógrafo (http://maurocorinti.com)

Material del video “La lucha por la dignidad del pueblo indígena de Santa Cruz de Barillas”. Producción: alianzaporlasolidaridad.org    

Fotografías conflicto armado El Salvador. Copyright © Donna De Cesare.  Todos los derechos de autor reservados.  Estas fotografías están publicadas en el libro bilingüe de Donna De Cesare, Unsettled /Desasosiego: Niños en un mundo de pandillas, publicado por la Editorial de la Universidad de Texas. Mas información disponible en este enlace: http://utpress.utexas.edu/index.php/books/decuns

Imágenes archivo del documental “Bajo Aguán: Grito por la Tierra”. Producción: ALBA SUD y REL-UITA con el apoyo de Movimiento Mundial por los Bosques Tropilar (WRM), FIAN Internacional y Coordinadora de Organizaciones Populares del Aguán (COPA). Imágenes de archivo realizadas por: Jesse Michael Freeston, Julián Manzanares, David Corea, César Silva, Wilfredo Paz y Luis Miranda. 

Imágenes en video del documental “Radio Venceremos: 10 años tomando el cielo por asalto”. Realización: Sistema Radio Venceremos, Restauración digital: Museo de la Palabra y la Imagen. Cortesía: Carlos Henríquez Consalvi. 

Material del video-reportaje “La Puya 23 de mayo”. Producción: Organización Sociedad Civil Barillas (https://www.youtube.com/watch?v=xSDucVRFS3Y) 

Material del video-reportaje “La Puya, Guatemala_ Mujeres contra el extractivismo”. Producción: Caravana Climática por América Latina (www.caravanaclimatica.org) 

Material del video-reportaje “Comprometidos con la lucha por la vida”. Producción: Comité de Unidad Campesina –CUC- (https://www.youtube.com/watch?v=8JBEMdjHZB4)

**ENTREVISTADOS** <br>
Ana Solórzano, Jefa Dirección de Atención al Migrante, El Salvador
Angélica Escobar, Subdelegada Federal en Saltillo del Instituto Nacional de Migración (INM)
Armando Guzmán, líder comunal de Barra Vieja, Honduras
Artemio Velasco, cofundador de la Casa Mambré en Comitán de Domínguez, Chiapas, México.
Brenda Monrroy, Guatemalteca
Carlos Henríquez Consalvi, Director de Museo de la Palabra y la Imagen (MUPI)
Carlos Enrique, Hondureño
Claudia Lisbeth Interiano, Fundación para la Justicia y Estado Democrático de Derecho AC de México 
Consuelo Castillo, Observatorio de Derechos Humanos del Bajo Aguán, Honduras
Daniel Enrique Ortíz, Programa de Seguimiento a Personas Migrantes, El Salvador
Darío Quintanilla, Hondureño
Dickson Mena, vecino de Barra Vieja, Honduras
Dixi Alexander Martínez, Hondureño
Don Guillermo, Salvadoreño
Doris Amador, vecina de El Progreso, Honduras
Edita Maldonado, vecina de El Progreso, Honduras
Edith Flores, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE)
Edwin Giovanni Méndez, Salvadoreño
Elizabeth, Hondureña
Elsy Orellana, vecina de El Progreso, Honduras
Felipe Jesús Meléndez, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE)
Fray Raúl Vera/Obispo de Saltillo, México.
Guillermo Taylor/ Casa del Migrante Frontera Digna
Identidad protegida, Nicaragüense 
Ismael Moreno, Directo Radio Progreso y Equipo de Reflexión, Investigación y Comunicación.
Irma Lemus, Observatorio de Derechos Humanos del Bajo Aguán, Honduras
Jeremías Ortega, Asentamiento Campesino La Lempira en Bajo Aguán, Honduras
Jerson Selvin López, Organización Fraternal Negra Hondureña (OFRANEH)
Jorge López, Director de la Organización de Apoyo a una Sexualidad Integral frente al Sida -OASIS, Guatemala
José Guadalupe Valdez/Director de la Casa del Migrante Frontera Digna, 
Lorena Cabnal, Tzk´at: Red de Sanadoras Ancestrales del Feminismo Comunitario desde Iximulew-Guatemala
Luis Alfonso Alfaro Valencia, psicólogo del Programa Bienvenido a Casa, El Salvador
Luis López, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE)
Luz Marina Mejía, Nicaragüense 
Marcelino López Balán, Asociación de Desarrollo del Ixcán (ADESI)
María del Socorro López López, cofundadora de la Casa Mambré en Comitán de Domínguez, Chiapas, México.
María Guadalupe Argüello “Hermana Lupita”, Casa del Migrante de Saltillo
Marisa Martínez, Fundación Monseñor Romero 
María Olimpia Rosales, vecina de El Salvador
Martha Alicia Cordero Escobar, Guatemalteca
Martha Arnold, Observatorio de Derechos Humanos del Bajo Aguán, Honduras
Oscar Ortega, jefe del Centro de Atención a la Niñez Deportada, Honduras
Misael Nolazco, Hondureño
Máximo Cruz, Salvadoreño
Melvin Guardado, Salvadoreño
Moisés Cedillo, Salvadoreño
Nahun Lalin, Organización Fraternal Negra Hondureña (OFRANEH)
Neftalí Esquivel, Asentamiento La Confianza, MUCA en Bajo Aguán, Honduras
Norma Quioto, líder comunal de Barra Vieja, Honduras
Omar Serrano, Filósofo y teólogo, Vicerrector de Proyección Social de la Universidad Centroamericana “José Simeón Cañas” UCA 
Patricia Melgar, vecina de El Salvador
Pedro Alvarado, Hondureño
Pedro Pantoja, Asesor Casa del Migrante de Saltillo 
Rafael Juárez, Hondureño
Ricardo Alonso, Hondureño
Rigoberto Durán, Observatorio de Derechos Humanos del Bajo Aguán, Honduras
Rubén Herrera, Dirigente de la Asamblea de Pueblos de Huehuetenango por la Defensa del territorio -ADH-
Sonia, vecina de El Progreso, Honduras
Vitalino Álvarez, Asentamiento La Confianza, MUCA (Bajo Aguán, Honduras)
Víctor Izaguirre, vecino de El Progreso, Honduras
Yaeli Mía, Cruz Roja Honduras
Yolanda Oquelí, Red de Sanadoras Ancestrales del Feminismo Comunitario-

**AGRADECIMIENTOS** <br>
Ana R. Alcalde, Directora alianzaporlasolidaridad.org
Ángel Ramos, Comunicación alianzaporlasolidaridad.org
Centro Educativo Los Pinos, Alajuelita
César Orozco, visitador adjunto de la CNDH en la oficina regional de Reynosa, México
Donna De Cesare, Fotógrafa
Ernest Cañada, Periodista 
Ioannen Francise Pérez Castillo, URL Guatemala
José Pablo Castillo Valverde
Karina Fonseca, Servicio Jesuita para Migrantes CR.
Karla Mayorga Pavón y su familia
Lissette Rodríguez Cerdas
Lucía Ramírez Fonseca, Caravana Climática por América Latina 
Mauro Corinti, Fotógrafo
Martha Rojas Weisner, Colegio de la Frontera Sur, San Cristóbal de Las Casas, Chiapas, México
Paco Onís, Director Ejecutivo Skylight
Pamela Yetes, Directora y Productora/Directora Creativa Skylight 
Paola Rojas Lobo
Prometeo Lucero, Fotógrafo
Yamileth Fontana
Yolanda González Cerdeira, Equipo de Reflexión, Investigación y Comunicación (ERIC).
Unidad de Transportes UCR
Unidad de Transportes UNED
ACTORES	Grettel Méndez Ramírez
Ramón Morales
Francis Muñoz
Lissette Rodríguez Cerdas
Carlos Andrés Alvarado Elizondo
José Mario Quesada Abrams.

####PRODUCCIÓN POR PAÍSES
**MÉXICO** <br>
Producción de campo: Artemio Velazco García, Hugo Ángeles Cruz y José Luis Manzo Ramírez.
Conductor: Hugo Ángeles Cruz
Con la colaboración de:
•	Casa del Migrante Mambré. Comitán de Domínguez, Chiapas <br>
•	Casa del Migrante de Saltillo. Saltillo, Coahuila.<br>
•	Casa del Migrante Emaus (Frontera y Dignidad). Ciudad Acuña, Coahuila.<br>
•	Colegio de la Frontera Sur (ECOSUR)<br>
•	Comisión Nacional de los Derechos Humanos (CNDH), México.

**GUATEMALA** <br>
Producción de campo: Marcelino López Balán y Lorena Cabnal Hernández.
Conductor: Juan Manuel Sam Can
Con la colaboración de:
•	Universidad Rafael Landívar  (Unidad de Coordinación del Sistema de Apoyo al Apostolado Social, Vicerrectoría de Investigación y Proyección)<br>
•	Asociación de Desarrollo del Ixcán (ADESI) <br>
•	Tzk´at: Red de Sanadoras Ancestrales del Feminismo Comunitario desde Iximulew-Guatemala <br>
•	Organización de Apoyo a una Sexualidad Integral frente al Sida –OASIS, Guatemala<br>
•	Asamblea de Pueblos de Huehuetenango por la Defensa del territorio -ADH- 

**EL SALVADOR** <br>
Producción de campo: Pilar Colomé Moran
Conductor: Kevin Pérez Cisneros
Con la colaboración de:
•	Universidad Centroamericana José Simeón Cañas (UCA) <br>
•	Asociación Comité de Familiares de Migrantes Fallecidos y Desaparecidos. El Salvador (COFAMIDE). <br>
•	Museo de la Palabra y la Imagen (MUPI) <br>
•	Programa Bienvenido a Casa, Dirección General de Migración y Extranjería, Dirección de Atención al Migrante.<br>

**HONDURAS** <br>
Producción de campo: Jennifer Ávila Reyes
Conductor: Mariano Girón Bonilla 
Con la colaboración de:
•	Radio Progreso <br>
•	Equipo de Reflexión, Investigación y Comunicación (ERIC-SJ) <br>
•	Organización Fraternal Negra Hondureña (OFRANEH) <br>
•	Observatorio de Derechos Humanos del Aguán <br>
•	Comité de Familiares de Migrantes de El Progreso (COFAMIPRO)

Más info:
aliazanfrancesasps@gmail.com


 
',NULL,'<p><img src="/content/images/2017/11/Evento-proyeccio-n-Alianza-Francesa-Honduras.png" alt="" /></p>

<h1 id="casaentierraajena">CASA EN TIERRA AJENA</h1>

<p><strong>INFORMACIÓN GENERAL</strong> <BR>
TÍTULO O NOMBRE DE LA PRODUCCIÓN: CASA EN TIERRA AJENA <br />
TEMA: Migración forzada en América Central <br />
ENTIDADES PRODUCTORAS O SOLICITANTES: <br />
• Consejo Nacional de Rectores (CONARE) <br>
• Universidad de Costa Rica (UCR) <br>
• Universidad Estatal a Distancia (UNED) <br>
FECHA DE PRODUCCIÓN: 2017</p>

<h3 id="sinopsis">SINOPSIS</h3>

<p><strong>Casa en Tierra Ajena</strong> <em>es un documental que relata las historias y los sueños de diversas personas que se encuentran en procesos de emigración forzada en Centroamérica. También recupera las voces de quienes se han quedado en sus países resistiendo y transformando sus realidades. La “Casa del Migrante de Saltillo”, situada en Coahuila, en el norte de México, es el lugar de encuentro de estos relatos, ya que es donde confluyen las diferentes personas migrantes que buscan un lugar seguro para descansar y retomar fuerzas antes de intentar cruzar la frontera a los Estados Unidos. El documental expone los factores de expulsión que fuerzan a las personas a salir de sus países, los mecanismos de control cada vez más violentos y represivos que se imponen para intentar retener a los migrantes y la solidaridad que se teje sin fronteras.</em></p>

<p>DURACIÓN: 1h, 20m, 43s <br />
IDIOMA: ESPAÑOL <br />
SUBTÍTULOS: ESPAÑOL - INGLÉS <br />
SITIO WEB: casaentierrajena.com <br />
REDES SOCIALES:    Facebook: Casa en tierra ajena <br />
NOMBRE DE LOS ARCHIVOS: Casa en tierra ajena <br />
Trailer oficial: (<a href="https://www.youtube.com/watch?v=FD7ANfLwdHU">https://www.youtube.com/watch?v=FD7ANfLwdHU</a>)</p>

<h4 id="crditosdeproduccin">CRÉDITOS DE PRODUCCIÓN</h4>

<p><strong>PRODUCCIÓN EJECUTIVA</strong> <br>
Carlos Sandoval García <br />
Luis Fernando Fallas Fallas <br />
Rafael Díaz Sánchez </p>

<p><strong>PRODUCCIÓN GENERAL</strong> <br>
Carlos Sandoval García <br />
Ivannia Villalobos Vindas</p>

<p><strong>DIRECCIÓN</strong> <br>
Ivannia Villalobos Vindas</p>

<p><strong>COORDINACIÓN GENERAL</strong> <br>
Carlos Sandoval García</p>

<p><strong>ASISTENCIA DE PRODUCCIÓN</strong> <br>
Michele Ferris Dobles</p>

<p><strong>GUIÓN LITERARIO</strong> <br>
Ivannia Villalobos Vindas <br />
Michele Ferris Dobles <br />
Carlos Sandoval García</p>

<p><strong>DIRECCIÓN DE FOTOGRAFÍA</strong> <br>
Santiago Martínez Artavia</p>

<p><strong>FOTOGRAFÍA</strong> <br>
Santiago Martínez Artavia <br />
Michelle Ferris Dobles <br />
Ivannia Villalobos Vindas <br />
Ernesto Valverde Villalobos</p>

<p><strong>EDICIÓN</strong> <br>
David Ramírez Baldizón <br />
Ivannia Villalobos Vindas</p>

<p><strong>DISEÑO Y ANIMACIÓN</strong> <br>
José Mario Quesada Abrams</p>

<p><strong>MÚSICA ORIGINAL</strong> <br>
Glendon Ramírez Díaz</p>

<p><strong>MÚSICA VIDEOS COMPLEMENTARIOS</strong> <br>
Esteban Ramírez Hernández</p>

<p><strong>COLORIZACIÓN</strong> <br>
José Arce Ramírez</p>

<p><strong>POSPRODUCCIÓN DE AUDIO</strong> <br>
Iván Pérez Arias</p>

<p><strong>SONIDO DIRECTO</strong> <br>
Santiago Martínez Artavia <br />
Carlos Sandoval García <br />
Michele Ferris Dobles <br />
Ivannia Villalobos Vindas</p>

<p><strong>VISIONADO Y TRANSCRIPCIÓN ENTREVISTA GIRA 1</strong> <br>
Carolina Muñoz Cabalceta <br />
Eddson Gómez Chavarría</p>

<p><strong>TRANSCRIPCIÓN AL ESPAÑOL</strong> <br>
Eduardo Monge Navarro</p>

<p><strong>SUBTÍTULOS ESPAÑOL</strong> <br>
José Miguel Orozco Piferrer <br />
Elena Rojas Ulate</p>

<p><strong>TRADUCCIÓN AL INGLÉS</strong> <br>
Anna Flury</p>

<p><strong>DISEÑO WEB Y REDES SOCIALES</strong> <br>
Fidel de Rooy </p>

<p><strong>AUTORÍA DE DVD</strong> <br>
José Mario Quesada Abrams</p>

<p><strong>PLAN DE DIFUSIÓN</strong> <br>
Fabiola Pomareda García</p>

<p><strong>ADMINISTRACIÓN FINANCIERA</strong> <br>
Evelyn Pérez Silva <br />
Marielos López</p>

<p><strong>COORDINACIÓN DE OPERACIONES Y COMPRA DE EQUIPO</strong> <br>
Rodrigo Ureña Sequeira</p>

<p><strong>MANTENIMIENTO DE EQUIPOS</strong> <br>
Carlos Andrés Alvarado Elizondo</p>

<p><strong>APOYO ADMINISTRATIVO</strong>
Alejandra Ramírez González <br />
Andrea Zamora Salazar <br />
Bignory Moraga Peralta <br />
Carmen Caamaño Morúa <br />
Catherine Lara Campos <br />
Ernesto Amey Walter <br />
Hazel González Araya <br />
Iriabel Hernández Vindas <br />
Johanna Rimola <br />
Kathia Castro Fuentes <br />
Lilly Díaz Gamboa <br />
Lorena Aguilar Solano <br />
Luis Guillermo Carpio Malavassi <br />
Mabel León Blanco <br />
María del C. Calvo <br />
María Sánchez Hernández <br />
Marilyn Fallas Hidalgo <br />
Marjorie Jiménez Castro <br />
Michael Artola Padilla <br />
Roberto Salom Echeverría <br />
Yelena Durán Rivera</p>

<p><strong>IMÁGENES DE ARCHIVO AUTORIZADAS PARA USO <em>EXCLUSIVO</em> EN EL PROYECTO DOCUMENTAL</strong> <br>
Material del juicio de Efraín Ríos Montt, Serie “Dictador en el Banquillo”. Producción: Skylight (<a href="http://skylight.is">http://skylight.is</a>) </p>

<p>Fotografía “Muro fronterizo, Otay” en fotoreportaje  “La línea, un limbo atrapasueños”. Copyright por Prometeo Lucero, creador audiovisual y periodista gráfico (<a href="http://prometeolucero.photoshelter.com">http://prometeolucero.photoshelter.com</a>)</p>

<p>Material del video “La Bestia”. Producción: Mauro Corinti, fotógrafo (<a href="http://maurocorinti.com">http://maurocorinti.com</a>)</p>

<p>Material del video “La lucha por la dignidad del pueblo indígena de Santa Cruz de Barillas”. Producción: alianzaporlasolidaridad.org    </p>

<p>Fotografías conflicto armado El Salvador. Copyright © Donna De Cesare.  Todos los derechos de autor reservados.  Estas fotografías están publicadas en el libro bilingüe de Donna De Cesare, Unsettled /Desasosiego: Niños en un mundo de pandillas, publicado por la Editorial de la Universidad de Texas. Mas información disponible en este enlace: <a href="http://utpress.utexas.edu/index.php/books/decuns">http://utpress.utexas.edu/index.php/books/decuns</a></p>

<p>Imágenes archivo del documental “Bajo Aguán: Grito por la Tierra”. Producción: ALBA SUD y REL-UITA con el apoyo de Movimiento Mundial por los Bosques Tropilar (WRM), FIAN Internacional y Coordinadora de Organizaciones Populares del Aguán (COPA). Imágenes de archivo realizadas por: Jesse Michael Freeston, Julián Manzanares, David Corea, César Silva, Wilfredo Paz y Luis Miranda. </p>

<p>Imágenes en video del documental “Radio Venceremos: 10 años tomando el cielo por asalto”. Realización: Sistema Radio Venceremos, Restauración digital: Museo de la Palabra y la Imagen. Cortesía: Carlos Henríquez Consalvi. </p>

<p>Material del video-reportaje “La Puya 23 de mayo”. Producción: Organización Sociedad Civil Barillas (<a href="https://www.youtube.com/watch?v=xSDucVRFS3Y">https://www.youtube.com/watch?v=xSDucVRFS3Y</a>) </p>

<p>Material del video-reportaje “La Puya, Guatemala_ Mujeres contra el extractivismo”. Producción: Caravana Climática por América Latina (www.caravanaclimatica.org) </p>

<p>Material del video-reportaje “Comprometidos con la lucha por la vida”. Producción: Comité de Unidad Campesina –CUC- (<a href="https://www.youtube.com/watch?v=8JBEMdjHZB4">https://www.youtube.com/watch?v=8JBEMdjHZB4</a>)</p>

<p><strong>ENTREVISTADOS</strong> <br>
Ana Solórzano, Jefa Dirección de Atención al Migrante, El Salvador <br />
Angélica Escobar, Subdelegada Federal en Saltillo del Instituto Nacional de Migración (INM) <br />
Armando Guzmán, líder comunal de Barra Vieja, Honduras <br />
Artemio Velasco, cofundador de la Casa Mambré en Comitán de Domínguez, Chiapas, México. <br />
Brenda Monrroy, Guatemalteca <br />
Carlos Henríquez Consalvi, Director de Museo de la Palabra y la Imagen (MUPI) <br />
Carlos Enrique, Hondureño <br />
Claudia Lisbeth Interiano, Fundación para la Justicia y Estado Democrático de Derecho AC de México <br />
Consuelo Castillo, Observatorio de Derechos Humanos del Bajo Aguán, Honduras <br />
Daniel Enrique Ortíz, Programa de Seguimiento a Personas Migrantes, El Salvador <br />
Darío Quintanilla, Hondureño <br />
Dickson Mena, vecino de Barra Vieja, Honduras <br />
Dixi Alexander Martínez, Hondureño <br />
Don Guillermo, Salvadoreño <br />
Doris Amador, vecina de El Progreso, Honduras <br />
Edita Maldonado, vecina de El Progreso, Honduras <br />
Edith Flores, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE) <br />
Edwin Giovanni Méndez, Salvadoreño <br />
Elizabeth, Hondureña <br />
Elsy Orellana, vecina de El Progreso, Honduras <br />
Felipe Jesús Meléndez, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE) <br />
Fray Raúl Vera/Obispo de Saltillo, México. <br />
Guillermo Taylor/ Casa del Migrante Frontera Digna <br />
Identidad protegida, Nicaragüense <br />
Ismael Moreno, Directo Radio Progreso y Equipo de Reflexión, Investigación y Comunicación. <br />
Irma Lemus, Observatorio de Derechos Humanos del Bajo Aguán, Honduras <br />
Jeremías Ortega, Asentamiento Campesino La Lempira en Bajo Aguán, Honduras <br />
Jerson Selvin López, Organización Fraternal Negra Hondureña (OFRANEH) <br />
Jorge López, Director de la Organización de Apoyo a una Sexualidad Integral frente al Sida -OASIS, Guatemala <br />
José Guadalupe Valdez/Director de la Casa del Migrante Frontera Digna, <br />
Lorena Cabnal, Tzk´at: Red de Sanadoras Ancestrales del Feminismo Comunitario desde Iximulew-Guatemala <br />
Luis Alfonso Alfaro Valencia, psicólogo del Programa Bienvenido a Casa, El Salvador <br />
Luis López, Comité de Familiares de Migrantes Fallecidos y Desaparecidos, El Salvador (COFAMIDE) <br />
Luz Marina Mejía, Nicaragüense <br />
Marcelino López Balán, Asociación de Desarrollo del Ixcán (ADESI) <br />
María del Socorro López López, cofundadora de la Casa Mambré en Comitán de Domínguez, Chiapas, México. <br />
María Guadalupe Argüello “Hermana Lupita”, Casa del Migrante de Saltillo <br />
Marisa Martínez, Fundación Monseñor Romero <br />
María Olimpia Rosales, vecina de El Salvador <br />
Martha Alicia Cordero Escobar, Guatemalteca <br />
Martha Arnold, Observatorio de Derechos Humanos del Bajo Aguán, Honduras <br />
Oscar Ortega, jefe del Centro de Atención a la Niñez Deportada, Honduras <br />
Misael Nolazco, Hondureño <br />
Máximo Cruz, Salvadoreño <br />
Melvin Guardado, Salvadoreño <br />
Moisés Cedillo, Salvadoreño <br />
Nahun Lalin, Organización Fraternal Negra Hondureña (OFRANEH) <br />
Neftalí Esquivel, Asentamiento La Confianza, MUCA en Bajo Aguán, Honduras <br />
Norma Quioto, líder comunal de Barra Vieja, Honduras <br />
Omar Serrano, Filósofo y teólogo, Vicerrector de Proyección Social de la Universidad Centroamericana “José Simeón Cañas” UCA <br />
Patricia Melgar, vecina de El Salvador <br />
Pedro Alvarado, Hondureño <br />
Pedro Pantoja, Asesor Casa del Migrante de Saltillo <br />
Rafael Juárez, Hondureño <br />
Ricardo Alonso, Hondureño <br />
Rigoberto Durán, Observatorio de Derechos Humanos del Bajo Aguán, Honduras <br />
Rubén Herrera, Dirigente de la Asamblea de Pueblos de Huehuetenango por la Defensa del territorio -ADH- <br />
Sonia, vecina de El Progreso, Honduras <br />
Vitalino Álvarez, Asentamiento La Confianza, MUCA (Bajo Aguán, Honduras) <br />
Víctor Izaguirre, vecino de El Progreso, Honduras <br />
Yaeli Mía, Cruz Roja Honduras <br />
Yolanda Oquelí, Red de Sanadoras Ancestrales del Feminismo Comunitario-</p>

<p><strong>AGRADECIMIENTOS</strong> <br>
Ana R. Alcalde, Directora alianzaporlasolidaridad.org <br />
Ángel Ramos, Comunicación alianzaporlasolidaridad.org
Centro Educativo Los Pinos, Alajuelita <br />
César Orozco, visitador adjunto de la CNDH en la oficina regional de Reynosa, México <br />
Donna De Cesare, Fotógrafa <br />
Ernest Cañada, Periodista <br />
Ioannen Francise Pérez Castillo, URL Guatemala <br />
José Pablo Castillo Valverde <br />
Karina Fonseca, Servicio Jesuita para Migrantes CR. <br />
Karla Mayorga Pavón y su familia <br />
Lissette Rodríguez Cerdas <br />
Lucía Ramírez Fonseca, Caravana Climática por América Latina <br />
Mauro Corinti, Fotógrafo <br />
Martha Rojas Weisner, Colegio de la Frontera Sur, San Cristóbal de Las Casas, Chiapas, México <br />
Paco Onís, Director Ejecutivo Skylight <br />
Pamela Yetes, Directora y Productora/Directora Creativa Skylight <br />
Paola Rojas Lobo <br />
Prometeo Lucero, Fotógrafo <br />
Yamileth Fontana <br />
Yolanda González Cerdeira, Equipo de Reflexión, Investigación y Comunicación (ERIC). <br />
Unidad de Transportes UCR <br />
Unidad de Transportes UNED <br />
ACTORES    Grettel Méndez Ramírez <br />
Ramón Morales <br />
Francis Muñoz <br />
Lissette Rodríguez Cerdas <br />
Carlos Andrés Alvarado Elizondo <br />
José Mario Quesada Abrams.</p>

<h4 id="produccinporpases">PRODUCCIÓN POR PAÍSES</h4>

<p><strong>MÉXICO</strong> <br>
Producción de campo: Artemio Velazco García, Hugo Ángeles Cruz y José Luis Manzo Ramírez. <br />
Conductor: Hugo Ángeles Cruz <br />
Con la colaboración de: <br />
•    Casa del Migrante Mambré. Comitán de Domínguez, Chiapas <br>
•    Casa del Migrante de Saltillo. Saltillo, Coahuila.<br>
•    Casa del Migrante Emaus (Frontera y Dignidad). Ciudad Acuña, Coahuila.<br>
•    Colegio de la Frontera Sur (ECOSUR)<br>
•    Comisión Nacional de los Derechos Humanos (CNDH), México.</p>

<p><strong>GUATEMALA</strong> <br>
Producción de campo: Marcelino López Balán y Lorena Cabnal Hernández. <br />
Conductor: Juan Manuel Sam Can <br />
Con la colaboración de: <br />
•    Universidad Rafael Landívar  (Unidad de Coordinación del Sistema de Apoyo al Apostolado Social, Vicerrectoría de Investigación y Proyección)<br>
•    Asociación de Desarrollo del Ixcán (ADESI) <br>
•    Tzk´at: Red de Sanadoras Ancestrales del Feminismo Comunitario desde Iximulew-Guatemala <br>
•    Organización de Apoyo a una Sexualidad Integral frente al Sida –OASIS, Guatemala<br>
•    Asamblea de Pueblos de Huehuetenango por la Defensa del territorio -ADH- </p>

<p><strong>EL SALVADOR</strong> <br>
Producción de campo: Pilar Colomé Moran <br />
Conductor: Kevin Pérez Cisneros <br />
Con la colaboración de: <br />
•    Universidad Centroamericana José Simeón Cañas (UCA) <br>
•    Asociación Comité de Familiares de Migrantes Fallecidos y Desaparecidos. El Salvador (COFAMIDE). <br>
•    Museo de la Palabra y la Imagen (MUPI) <br>
•    Programa Bienvenido a Casa, Dirección General de Migración y Extranjería, Dirección de Atención al Migrante.<br></p>

<p><strong>HONDURAS</strong> <br>
Producción de campo: Jennifer Ávila Reyes <br />
Conductor: Mariano Girón Bonilla <br />
Con la colaboración de: <br />
•    Radio Progreso <br>
•    Equipo de Reflexión, Investigación y Comunicación (ERIC-SJ) <br>
•    Organización Fraternal Negra Hondureña (OFRANEH) <br>
•    Observatorio de Derechos Humanos del Aguán <br>
•    Comité de Familiares de Migrantes de El Progreso (COFAMIPRO)</p>

<p>Más info: <br />
aliazanfrancesasps@gmail.com</p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2017-11-02 17:27:57',2,'2017-11-02 18:01:02',2,'2017-11-02 17:49:34',2);
INSERT INTO "posts" VALUES(31,'d1e5fc22-eaea-4fc2-a33b-33bae34ac09f','Cursos de francés 1er. Nivel | ENERO 2018','cursos-de-frances-1er-nivel-enero-2018','![](www.afsps.org/content/images/2017/12/peq-ANUNCIOS-1C-2018-01.png)

####Inicio de clases: 8 de enero de 2018
####¡Matrícula abierta!<BR>

<BR>
#Oferta académica:

**Maternal (4-6 años)** <br>
• Sábados
   9:00 - 11:00 a.m. <br>

**NIÑOS (7-9 años)** <br> 
• Lunes y miércoles
   3:00 – 4:30 p.m.<br>
• Sábados
   8:00 - 11:00 a.m. <br>
<br>
**PRE-ADOLESCENTES (10-12 años)** <br>
• Lunes y miércoles
   4:30 – 6:00 p.m. <br>

**ADOLESCENTES (13-14 años)** <br>
• Martes y jueves
   4:30 – 6:00 p.m. <br>
• Sábados
   12:00 – 3:00 p.m. 

**ADULTOS (15 años en adelante)** <br>
• Lunes y miércoles 
   6:30 – 8:00 p.m. <br>
• Viernes 
   8:30 – 11:30 a.m. <br>
• Sábados 
   12:00 – 3:00 p.m. <br>

###Cursos libres de arte
**Guitarra** <br>
De 10 años en adelante: 
• Miércoles - 6:00 a 8:00 p.m. <br>
• Sábado - 8:00 a 10:00 a.m.

**Pintura** <br>
8-13 años:
• Miércoles 3:00 a 5:00 p.m. <br>
14 años en adelante:
• Miércoles 5:00 a 7:00 p.m.

**Violín** <br>
De 5 años en adelante: 
• Viernes 3:00 a 4:30 p.m.

**Piano** <br>
De 5 años en adelante:
• Miércoles 3:00 a 4:30 p.m.<br>
• Viernes 3:00 a 4:30 p.m.<br>
• Sábado 10:30 a 12:00 m.<br>

**Aplica únicamente para las clases de francés:** <br>
• Si es suscriptor de Diario La Prensa, obtiene matrícula gratis + 10% de descuento sobre el costo del cuatrimestre. <br>
• Extra financiamiento a 0% interés con BAC Credomatic y BANPAIS a plazo de 3 meses. <br>
• Todos los grupos se abren con mínimo de 8 alumnos. <br>

#####Llame ya para reservar su cupo al: <br> 
+504 2566 3733 | +504 2566 3743',NULL,'<p><img src="/content/images/2017/12/peq-ANUNCIOS-1C-2018-01.png" alt="" /></p>

<h4 id="iniciodeclases8deenerode2018">Inicio de clases: 8 de enero de 2018</h4>

<h4 id="matrculaabiertabr">¡Matrícula abierta!<BR></h4>

<p><BR>  </p>

<h1 id="ofertaacadmica">Oferta académica:</h1>

<p><strong>Maternal (4-6 años)</strong> <br>
• Sábados
   9:00 - 11:00 a.m. <br></p>

<p><strong>NIÑOS (7-9 años)</strong> <br> 
• Lunes y miércoles
   3:00 – 4:30 p.m.<br>
• Sábados
   8:00 - 11:00 a.m. <br>
<br> <br />
<strong>PRE-ADOLESCENTES (10-12 años)</strong> <br>
• Lunes y miércoles
   4:30 – 6:00 p.m. <br></p>

<p><strong>ADOLESCENTES (13-14 años)</strong> <br>
• Martes y jueves
   4:30 – 6:00 p.m. <br>
• Sábados
   12:00 – 3:00 p.m. </p>

<p><strong>ADULTOS (15 años en adelante)</strong> <br>
• Lunes y miércoles 
   6:30 – 8:00 p.m. <br>
• Viernes 
   8:30 – 11:30 a.m. <br>
• Sábados 
   12:00 – 3:00 p.m. <br></p>

<h3 id="cursoslibresdearte">Cursos libres de arte</h3>

<p><strong>Guitarra</strong> <br>
De 10 años en adelante: <br />
• Miércoles - 6:00 a 8:00 p.m. <br>
• Sábado - 8:00 a 10:00 a.m.</p>

<p><strong>Pintura</strong> <br>
8-13 años: <br />
• Miércoles 3:00 a 5:00 p.m. <br>
14 años en adelante: <br />
• Miércoles 5:00 a 7:00 p.m.</p>

<p><strong>Violín</strong> <br>
De 5 años en adelante: <br />
• Viernes 3:00 a 4:30 p.m.</p>

<p><strong>Piano</strong> <br>
De 5 años en adelante: <br />
• Miércoles 3:00 a 4:30 p.m.<br>
• Viernes 3:00 a 4:30 p.m.<br>
• Sábado 10:30 a 12:00 m.<br></p>

<p><strong>Aplica únicamente para las clases de francés:</strong> <br>
• Si es suscriptor de Diario La Prensa, obtiene matrícula gratis + 10% de descuento sobre el costo del cuatrimestre. <br>
• Extra financiamiento a 0% interés con BAC Credomatic y BANPAIS a plazo de 3 meses. <br>
• Todos los grupos se abren con mínimo de 8 alumnos. <br></p>

<h5 id="llameyaparareservarsucupoalbr">Llame ya para reservar su cupo al: <br></h5>

<p>+504 2566 3733 | +504 2566 3743</p>',NULL,'/content/images/2017/12/peq-ANUNCIOS-1C-2018-01-1.png',0,0,'published','en_US','public',NULL,NULL,2,'2017-12-15 20:33:41',2,'2018-01-05 17:59:20',2,'2017-12-15 20:52:15',2);
INSERT INTO "posts" VALUES(32,'85f690b9-1bbd-48f1-b36f-1a7f0d5eaf13','Programa de formación de Maestría FLE a distancia,  Unilateral de Centroamérica con la Universidad de las Antillas (UA)','untitled-3','![](www.afsps.org/content/images/2018/01/logo-footer.jpg)

**Programa de formación de Maestría FLE a distancia, Unilateral de Centroamérica con la Universidad de las Antillas (UA)**

#Becas
####CONVOCATORIA 2018
**Institut français d’Amérique centrale**

*Correo para contacto y envío de documentos:*
**maestriadistancia@institutfrancais-ifac.com**


1.	Objetivos y características

El “Institut français d’Amérique centrale (IFAC)” brinda la oportunidad a profesores universitarios, de la enseñanza primaria y secundaria o a estudiantes graduados con un pre grado de América Central, de continuar sus estudios de Master de FLE a distancia con la Universidad de las Antillas-UA- en Martinica. Este programa financiado por el IFAC tiene las características siguientes:
 
-	El inscrito en Master a distancia recibirá los cursos virtualmente y por medio de videoconferencias (el inscrito deberá disponer del equipo informático necesario) y enviará regularmente sus trabajos a la Universidad de las Antillas-UA- también de manera virtual.
-	La formación es 100% virtual por lo que se lleva a cabo en su país de origen.
-	Este programa permitirá establecer contactos entre las instituciones de educación superior de ambos países.
-	Los cursos darán inicio en el mes de setiembre (cuando inicia el año universitario francés).

2.Condiciones de elegibilidad

Para ser elegible, el candidato deberá antes del 30 de marzo del 2018:
-inscribirse en línea en el siguiente sitio http://icefi.martinique.univ-ag.fr/candidature
-y enviar los documentos indicados más adelante, únicamente de forma electrónica a la siguiente dirección:maestriadistancia@institutfrancais-ifac.com



3.Criterios de selección 

Con base en estos documentos, el proceso de selección contempla dos etapas:
a)	Etapa de preselección:  los criterios serán los siguientes:
-	Trayectoria (profesional y/o universitaria) y notas académicas
-	Calidad del proyecto de estudios
-	Nivel de idioma
b)	Etapa de selección: lo candidatos preseleccionados serán entrevistados:
 En presencial en el IFAC, 
A distancia por Skype, para los estudiantes que no podrán venir al IFAC.
Las candidaturas serán después examinadas por la comisión de validación de la UA.

4.Modalidades de financiamiento 

El IFAC cubre los gastos de inscripción a 100% (por un monto máximo de 450 euros por año universitario). 

5.Etapas a seguir 
 
La presentación de candidaturas debe hacerse en dos etapas y ante dos entes diferentes según calendario indicado abajo (la UA y el IFAC) 
Todas las personas interesadas deberán respetar el siguiente calendario establecido por la UA para presentar candidatura

5.1.	 Convocatoria: del 5 de febrero al 30 de marzo del 2018

Todos los candidatos que hagan la solicitud de beca ante el IFAC, deberán cumplir, obligatoriamente, con los siguientes procesos: 
Deben completar el expediente en línea disponible en el siguiente sitio: http://icefi.martinique.univ-ag.fr/candidature  y adjuntar los siguientes documentos ( ningún expediente  o documentos enviados por otro canal o vía  no serán recibidos)

•	CV en Francés 
•	Carta de motivación en Francés
•	Copia del diploma universitario más elevado (no es necesario ni traducirlo ni certificarlo)
•	Atestado de nivel B2 en Francés obligatorio (los que ya tienen un diploma universitario de « Licence » o de « Maîtrise »  extendido por una universidad francesa o los que tienen un Bachillerato o Licenciatura en Francés obtenida en una universidad extranjera o de su país de origen no deben presentar este atestado. Cualquier otra materia queda excluida de esta excepción). 
Enviar los documentos solicitados anteriormente y únicamente de forma electrónica a: maestriadistancia@institutfrancais-ifac.com  







5.2.	Procesos de selección y entrevista

-	Preselección y entrevistas por el IFAC: del 3 al 20 de abril del 2018 
-	Comisión de validación por la UA: del 23 de abril al 11 de mayo del 2018: Obligatoria para todas las personas que no posean un diploma universitario francés.


5.3. Publicación de los resultados

-	Resultados: el 28 de mayo del 2018 (solamente los candidatos  que hayan sido aceptados por la UA obtendrán la beca del IFAC). 
-	Hacer llegar al IFAC copia de la carta o correo electrónico de aceptación o de admisión en el Master FLE de la UA una vez recibida dicha carta de aceptación por parte de la UA en mayo del 2018


',NULL,'<p><img src="/content/images/2018/01/logo-footer.jpg" alt="" /></p>

<p><strong>Programa de formación de Maestría FLE a distancia, Unilateral de Centroamérica con la Universidad de las Antillas (UA)</strong></p>

<h1 id="becas">Becas</h1>

<h4 id="convocatoria2018">CONVOCATORIA 2018</h4>

<p><strong>Institut français d’Amérique centrale</strong></p>

<p><em>Correo para contacto y envío de documentos:</em>
<strong>maestriadistancia@institutfrancais-ifac.com</strong></p>

<ol>
<li>Objetivos y características</li>
</ol>

<p>El “Institut français d’Amérique centrale (IFAC)” brinda la oportunidad a profesores universitarios, de la enseñanza primaria y secundaria o a estudiantes graduados con un pre grado de América Central, de continuar sus estudios de Master de FLE a distancia con la Universidad de las Antillas-UA- en Martinica. Este programa financiado por el IFAC tiene las características siguientes:</p>

<ul>
<li>El inscrito en Master a distancia recibirá los cursos virtualmente y por medio de videoconferencias (el inscrito deberá disponer del equipo informático necesario) y enviará regularmente sus trabajos a la Universidad de las Antillas-UA- también de manera virtual.</li>
<li>La formación es 100% virtual por lo que se lleva a cabo en su país de origen.</li>
<li>Este programa permitirá establecer contactos entre las instituciones de educación superior de ambos países.</li>
<li>Los cursos darán inicio en el mes de setiembre (cuando inicia el año universitario francés).</li>
</ul>

<p>2.Condiciones de elegibilidad</p>

<p>Para ser elegible, el candidato deberá antes del 30 de marzo del 2018: <br />
-inscribirse en línea en el siguiente sitio <a href="http://icefi.martinique.univ-ag.fr/candidature">http://icefi.martinique.univ-ag.fr/candidature</a>
-y enviar los documentos indicados más adelante, únicamente de forma electrónica a la siguiente dirección:maestriadistancia@institutfrancais-ifac.com</p>

<p>3.Criterios de selección </p>

<p>Con base en estos documentos, el proceso de selección contempla dos etapas: <br />
a)    Etapa de preselección:  los criterios serán los siguientes: <br />
-    Trayectoria (profesional y/o universitaria) y notas académicas
-    Calidad del proyecto de estudios
-    Nivel de idioma
b)    Etapa de selección: lo candidatos preseleccionados serán entrevistados: <br />
 En presencial en el IFAC, 
A distancia por Skype, para los estudiantes que no podrán venir al IFAC. <br />
Las candidaturas serán después examinadas por la comisión de validación de la UA.</p>

<p>4.Modalidades de financiamiento </p>

<p>El IFAC cubre los gastos de inscripción a 100% (por un monto máximo de 450 euros por año universitario). </p>

<p>5.Etapas a seguir </p>

<p>La presentación de candidaturas debe hacerse en dos etapas y ante dos entes diferentes según calendario indicado abajo (la UA y el IFAC) <br />
Todas las personas interesadas deberán respetar el siguiente calendario establecido por la UA para presentar candidatura</p>

<p>5.1.     Convocatoria: del 5 de febrero al 30 de marzo del 2018</p>

<p>Todos los candidatos que hagan la solicitud de beca ante el IFAC, deberán cumplir, obligatoriamente, con los siguientes procesos: <br />
Deben completar el expediente en línea disponible en el siguiente sitio: <a href="http://icefi.martinique.univ-ag.fr/candidature">http://icefi.martinique.univ-ag.fr/candidature</a>  y adjuntar los siguientes documentos ( ningún expediente  o documentos enviados por otro canal o vía  no serán recibidos)</p>

<p>•    CV en Francés 
•    Carta de motivación en Francés
•    Copia del diploma universitario más elevado (no es necesario ni traducirlo ni certificarlo)
•    Atestado de nivel B2 en Francés obligatorio (los que ya tienen un diploma universitario de « Licence » o de « Maîtrise »  extendido por una universidad francesa o los que tienen un Bachillerato o Licenciatura en Francés obtenida en una universidad extranjera o de su país de origen no deben presentar este atestado. Cualquier otra materia queda excluida de esta excepción). 
Enviar los documentos solicitados anteriormente y únicamente de forma electrónica a: maestriadistancia@institutfrancais-ifac.com  </p>

<p>5.2.    Procesos de selección y entrevista</p>

<ul>
<li>Preselección y entrevistas por el IFAC: del 3 al 20 de abril del 2018 </li>
<li>Comisión de validación por la UA: del 23 de abril al 11 de mayo del 2018: Obligatoria para todas las personas que no posean un diploma universitario francés.</li>
</ul>

<p>5.3. Publicación de los resultados</p>

<ul>
<li>Resultados: el 28 de mayo del 2018 (solamente los candidatos  que hayan sido aceptados por la UA obtendrán la beca del IFAC). </li>
<li>Hacer llegar al IFAC copia de la carta o correo electrónico de aceptación o de admisión en el Master FLE de la UA una vez recibida dicha carta de aceptación por parte de la UA en mayo del 2018</li>
</ul>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2018-01-31 20:38:43',2,'2018-01-31 20:47:47',2,'2018-01-31 20:44:58',2);
INSERT INTO "posts" VALUES(33,'54699754-d3d0-4c4d-9c13-0447a70f72be','CONVOCATORIAS PARA PASANTÍAS EN FRANCIA','convocatorias-para-pasantias-en-francia','![](www.afsps.org/content/images/2018/02/Logo-IFAC---Copie.jpg)

Para el año 2018, el Ministerio de Cultura francés publicó una programación para acoger a profesionales del ámbito de la cultura, con el objetivo de promover la diversidad cultural y cooperación internacional y alentar los intercambios duraderos entre profesionales franceses y extranjeros de alto nivel. Esta convocatoria se declina en dos tipos de pasantías:

#1. Programa “Corrientes del Mundo” (Programme « Courants du Monde »)

El programa Programa “Corrientes del Mundo” se compone de seminarios colectivos y temáticos con una duración de 10 días. Se dirige a profesionales extranjeros que buscan recolectar informaciones pertinentes en relación con su ámbito profesional. En ese sentido, se proponen sesiones teóricas y prácticas para mutualizar las pericias y competencias ante problemáticas comunes.

Para **profesionales anglófonos,** los seminarios tendrán lugar del 4 al 14 de junio del 2018. Las temáticas propuestas son:
a. Desafíos e implementación de la política de los públicos en las estructuras culturales
b. Las estructuras culturales al servicio del desarrollo territorial.
La fecha límite para aplicar es el **5 de marzo del 2018.**

Para **profesionales francófonos,** los seminarios tendrán lugar del 8 al 19 de octubre del 2018. Las temáticas propuestas son:
a. Desarrollo de proyectos culturales y Francofonía
b. La cultura y el arte en el espacio público
c. Apoyo para prácticas innovadoras
La fecha límite para aplicar es el **25 de mayo del 2018.**

*Modalidades de la pasantía
La duración de la estadía en Francia es de diez (10) días.

El Ministerio francés de Cultura financia los gastos de alojamiento y restauración, los desplazamientos en Francia, el seguro social y los gastos pedagógicos. La financiación del tiquete de transporte del país de residencia hasta Francia estará a cargo del candidato o de su administración.

#2. “Destinos Cultura” (Appel à candidature « Séjours Culture »)
El programa “Destinos Cultura” consta de pasantías semi-individualizadas y personalizadas para profesionales extranjeros interesados por tener un acercamiento a las políticas culturales francesas relacionadas a su campo de actividad. 

El programa les permitirá asistir a conferencias, encuentros y citas con profesionales franceses de todos los ámbitos culturales. Las temáticas de este año son:

a. Espectáculo en vivo
b. Artes visuales, design, moda y oficios de arte y creación numérica
c. Patrimonio construido y calidad arquitectónica
d. Libro
e. Industrias culturales y creativas

Las pasantías que tendrán lugar del 14 al 23 de mayo se dirigen a francófonos. La fecha límite para aplicar es el 5 de marzo del 2018.

Las pasantías que tendrán lugar del 13 al 22 de noviembre son para francófonos y anglófonos. La fecha límite para aplicar es el 3 de agosto del 2018.

*Modalidades de la pasantía
La duración de la estadía en Francia es de diez (10) días.

El Ministerio francés de Cultura financia los gastos de alojamiento y restauración, los desplazamientos en Francia, el seguro social y los gastos pedagógicos. La financiación del tiquete de transporte del país de residencia hasta Francia estará a cargo del candidato o de su administración.

###Contacto
Los documentos de candidatura están disponibles en el la página del Ministerio de Cultura: **www.culturecommunication.gouv.fr/Thematiques/Europe-et-international/Accueil-et-formation**

Los candidatos deben completarlos antes de mandarlos al Instituto francés de América central (IFAC): **caroline.socie@diplomatie.gouv.fr.**',NULL,'<p><img src="/content/images/2018/02/Logo-IFAC---Copie.jpg" alt="" /></p>

<p>Para el año 2018, el Ministerio de Cultura francés publicó una programación para acoger a profesionales del ámbito de la cultura, con el objetivo de promover la diversidad cultural y cooperación internacional y alentar los intercambios duraderos entre profesionales franceses y extranjeros de alto nivel. Esta convocatoria se declina en dos tipos de pasantías:</p>

<h1 id="1programacorrientesdelmundoprogrammecourantsdumonde">1. Programa “Corrientes del Mundo” (Programme « Courants du Monde »)</h1>

<p>El programa Programa “Corrientes del Mundo” se compone de seminarios colectivos y temáticos con una duración de 10 días. Se dirige a profesionales extranjeros que buscan recolectar informaciones pertinentes en relación con su ámbito profesional. En ese sentido, se proponen sesiones teóricas y prácticas para mutualizar las pericias y competencias ante problemáticas comunes.</p>

<p>Para <strong>profesionales anglófonos,</strong> los seminarios tendrán lugar del 4 al 14 de junio del 2018. Las temáticas propuestas son: <br />
a. Desafíos e implementación de la política de los públicos en las estructuras culturales <br />
b. Las estructuras culturales al servicio del desarrollo territorial. <br />
La fecha límite para aplicar es el <strong>5 de marzo del 2018.</strong></p>

<p>Para <strong>profesionales francófonos,</strong> los seminarios tendrán lugar del 8 al 19 de octubre del 2018. Las temáticas propuestas son: <br />
a. Desarrollo de proyectos culturales y Francofonía <br />
b. La cultura y el arte en el espacio público <br />
c. Apoyo para prácticas innovadoras <br />
La fecha límite para aplicar es el <strong>25 de mayo del 2018.</strong></p>

<p>*Modalidades de la pasantía
La duración de la estadía en Francia es de diez (10) días.</p>

<p>El Ministerio francés de Cultura financia los gastos de alojamiento y restauración, los desplazamientos en Francia, el seguro social y los gastos pedagógicos. La financiación del tiquete de transporte del país de residencia hasta Francia estará a cargo del candidato o de su administración.</p>

<h1 id="2destinosculturaappelcandidaturesjoursculture">2. “Destinos Cultura” (Appel à candidature « Séjours Culture »)</h1>

<p>El programa “Destinos Cultura” consta de pasantías semi-individualizadas y personalizadas para profesionales extranjeros interesados por tener un acercamiento a las políticas culturales francesas relacionadas a su campo de actividad. </p>

<p>El programa les permitirá asistir a conferencias, encuentros y citas con profesionales franceses de todos los ámbitos culturales. Las temáticas de este año son:</p>

<p>a. Espectáculo en vivo <br />
b. Artes visuales, design, moda y oficios de arte y creación numérica <br />
c. Patrimonio construido y calidad arquitectónica <br />
d. Libro <br />
e. Industrias culturales y creativas</p>

<p>Las pasantías que tendrán lugar del 14 al 23 de mayo se dirigen a francófonos. La fecha límite para aplicar es el 5 de marzo del 2018.</p>

<p>Las pasantías que tendrán lugar del 13 al 22 de noviembre son para francófonos y anglófonos. La fecha límite para aplicar es el 3 de agosto del 2018.</p>

<p>*Modalidades de la pasantía
La duración de la estadía en Francia es de diez (10) días.</p>

<p>El Ministerio francés de Cultura financia los gastos de alojamiento y restauración, los desplazamientos en Francia, el seguro social y los gastos pedagógicos. La financiación del tiquete de transporte del país de residencia hasta Francia estará a cargo del candidato o de su administración.</p>

<h3 id="contacto">Contacto</h3>

<p>Los documentos de candidatura están disponibles en el la página del Ministerio de Cultura: <strong>www.culturecommunication.gouv.fr/Thematiques/Europe-et-international/Accueil-et-formation</strong></p>

<p>Los candidatos deben completarlos antes de mandarlos al Instituto francés de América central (IFAC): <strong>caroline.socie@diplomatie.gouv.fr.</strong></p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2018-02-14 15:15:10',2,'2018-02-14 15:21:36',2,'2018-02-14 15:21:36',2);
INSERT INTO "posts" VALUES(34,'209055f9-56e5-4071-9e98-fd6522577739','Le langage de l’amour / El idioma del amor','le-langage-de-lamour-el-idioma-del-amor-2','![](www.afsps.org/content/images/2018/02/baja-CONCURSO-FEBRERO2018.jpg)

El francés es reconocido mundialmente como el idioma del amor, por lo que este mes de febrero te invitamos a compartir una fotografía con tu pareja en nuestro muro de Facebook y pide a tus amistades que voten por ti.

###Bases concurso de fotografía
Lanzamiento: **14 de febrero**
Cierre: **28 de febrero**
Anuncio de ganadores: **1 de marzo**
Premiación: **Fiesta de la Francofonía (24 de marzo)**

**Mecánica:** 

1.	Los participantes podrán enviar una (1) fotografía conmemorativa al día de San Valentín, con el tema: amor y amistad. Los participantes deben aparecer en la fotografía.
2.	Las fotografías deben ser publicadas en el muro del fan page de Faceboock de la Alianza Francesa de San Pedro Sula. 
3.	La selección será por votación en línea, gana quien reciba más “LIKES”.
4.	El premio es único y será entregado a la pareja responsable de la fotografía ganadora. 
5.	La pareja ganadora recibirá como premio: matrícula gratis y el 50% de descuento en el costo del cuatrimestre para un nivel de francés (4 meses) aplicado a ambos participantes.
6.	Inicio del concurso: 14 de febrero
7.	Cierre del concurso: 28 de febrero
8.	Anuncio de ganadores: 1 de marzo
9.	La premiación se hará pública durante la Fiesta de la Francofonía, el sábado 24 de marzo.

**Restricciones:**

1.	Podrán participar únicamente personas en pareja (dos) que no sean alumnos, maestros o personal de la Alianza Francesa de SPS.
2.	No pueden participar parientes de ningún empleado de la Alianza Francesa de SPS.
3.	Las fotografías publicadas no pueden ser eróticas, amenazantes o violentas, vulgares o irrespetuosas. Tampoco pueden portar contenido religioso o político.
4.	El premio no se puede canjear por dinero, ni transferir a terceros u otras personas que no hayan concursado o que no aparezcan en la fotografía ganadora.
5.	El premio no incluye: los libros de estudio del nivel, exámenes de nivelación, ni exámenes DELF, ni otros productos o servicios relacionados al estudio del francés que brinda la Alianza Francesa de San Pedro Sula.
6.	No aplica ningún otro descuento, promoción o extra financiamientos.
7.	La edad mínima para participar es de 16 años, la edad máxima: sin límites.

**NOTA:** *Las fotografías que no cumplan con la mecánica y las restricciones serán eliminadas del muro del Faceboock de la Alianza Francesa de San Pedro Sula.*





**Gustavo Larach** / 
Director Ejecutivo AFSPS




**Ana Funes** / Gerente Administrativa AFSPS
',NULL,'<p><img src="/content/images/2018/02/baja-CONCURSO-FEBRERO2018.jpg" alt="" /></p>

<p>El francés es reconocido mundialmente como el idioma del amor, por lo que este mes de febrero te invitamos a compartir una fotografía con tu pareja en nuestro muro de Facebook y pide a tus amistades que voten por ti.</p>

<h3 id="basesconcursodefotografa">Bases concurso de fotografía</h3>

<p>Lanzamiento: <strong>14 de febrero</strong> <br />
Cierre: <strong>28 de febrero</strong> <br />
Anuncio de ganadores: <strong>1 de marzo</strong> <br />
Premiación: <strong>Fiesta de la Francofonía (24 de marzo)</strong></p>

<p><strong>Mecánica:</strong> </p>

<ol>
<li>Los participantes podrán enviar una (1) fotografía conmemorativa al día de San Valentín, con el tema: amor y amistad. Los participantes deben aparecer en la fotografía.  </li>
<li>Las fotografías deben ser publicadas en el muro del fan page de Faceboock de la Alianza Francesa de San Pedro Sula.  </li>
<li>La selección será por votación en línea, gana quien reciba más “LIKES”.  </li>
<li>El premio es único y será entregado a la pareja responsable de la fotografía ganadora.  </li>
<li>La pareja ganadora recibirá como premio: matrícula gratis y el 50% de descuento en el costo del cuatrimestre para un nivel de francés (4 meses) aplicado a ambos participantes.  </li>
<li>Inicio del concurso: 14 de febrero  </li>
<li>Cierre del concurso: 28 de febrero  </li>
<li>Anuncio de ganadores: 1 de marzo  </li>
<li>La premiación se hará pública durante la Fiesta de la Francofonía, el sábado 24 de marzo.</li>
</ol>

<p><strong>Restricciones:</strong></p>

<ol>
<li>Podrán participar únicamente personas en pareja (dos) que no sean alumnos, maestros o personal de la Alianza Francesa de SPS.  </li>
<li>No pueden participar parientes de ningún empleado de la Alianza Francesa de SPS.  </li>
<li>Las fotografías publicadas no pueden ser eróticas, amenazantes o violentas, vulgares o irrespetuosas. Tampoco pueden portar contenido religioso o político.  </li>
<li>El premio no se puede canjear por dinero, ni transferir a terceros u otras personas que no hayan concursado o que no aparezcan en la fotografía ganadora.  </li>
<li>El premio no incluye: los libros de estudio del nivel, exámenes de nivelación, ni exámenes DELF, ni otros productos o servicios relacionados al estudio del francés que brinda la Alianza Francesa de San Pedro Sula.  </li>
<li>No aplica ningún otro descuento, promoción o extra financiamientos.  </li>
<li>La edad mínima para participar es de 16 años, la edad máxima: sin límites.</li>
</ol>

<p><strong>NOTA:</strong> <em>Las fotografías que no cumplan con la mecánica y las restricciones serán eliminadas del muro del Faceboock de la Alianza Francesa de San Pedro Sula.</em></p>

<p><strong>Gustavo Larach</strong> / 
Director Ejecutivo AFSPS</p>

<p><strong>Ana Funes</strong> / Gerente Administrativa AFSPS</p>',NULL,'',0,0,'published','en_US','public',NULL,NULL,2,'2018-02-14 22:00:39',2,'2018-02-14 22:33:16',2,'2018-02-14 22:15:44',2);
INSERT INTO "posts" VALUES(35,'ed91ee43-97c8-4de7-80fe-a832a1ce3410','VIAJE CULTURAL A VICHY, FRANCIA','untitled-4','![](www.afsps.org/content/images/2018/03/C-AF-BROCHURE-FRANCAIS-7616-_Page_04.jpg)

##VIAJE CULTURAL A VICHY, FRANCIA

Del 29 de julio al 11 de agosto

Precio: 1500 euros (sin boleto de avión)

**REQUISITOS**
• Ser alumno de la Alianza Francesa
• Tener 15 años o más
• Firmar una carta de compromiso con la Alianza Francesa de San Pedro Sula
• Los padres de los menores de edad deben presentar el permiso de salida (15 a 20 años) legalmente firmado y con sus respectivos timbres.
• Asistir a las reuniones que se estarán convocando mediante el correo electrónico.

**BENEFICIOS**
✓ Test de nivel al llegar y cursos de francés (19h30 semanales). ✓ Alojamiento con una familia francesa, habitación individual: incluye desayuno y cena + lavandería. ✓ Visita guiada en Vichy, 1 excursión de un día, 1 excursión de media jornada, 1 degustación de productos de la región, 1 velada internacional, acceso libre a las noches de cine del martes y jueves y a las actividades deportivas. ✓ Una permanecía en Paris de sábado a lunes (2 noches); se viaja en tren el sábado en la mañana (el traslado al hotel en París, así como el desayuno y cena están incluidos). ✓ Salidas en Bateau Mouche y Musée du Louvre. ✓ Certificado de stage y de nivel alcanzado por cada alumno.

Los alumnos podrán almorzar de lunes a viernes en el restaurante universitario del campus con una tarifa de 6 €, sin embargo, se puede salir para buscar otras posibilidades (panaderías, snacks, restaurantes, fast food).

**Fecha límite de inscripción: 1 de mayo 2018**

Los estudiantes interesados deben inscribirse en la administración con Ana Fúnez y Lilian Robles.

Cualquier duda comunicarse al teléfono: **8906-0014**


',NULL,'<p><img src="/content/images/2018/03/C-AF-BROCHURE-FRANCAIS-7616-_Page_04.jpg" alt="" /></p>

<h2 id="viajeculturalavichyfrancia">VIAJE CULTURAL A VICHY, FRANCIA</h2>

<p>Del 29 de julio al 11 de agosto</p>

<p>Precio: 1500 euros (sin boleto de avión)</p>

<p><strong>REQUISITOS</strong>
• Ser alumno de la Alianza Francesa
• Tener 15 años o más
• Firmar una carta de compromiso con la Alianza Francesa de San Pedro Sula
• Los padres de los menores de edad deben presentar el permiso de salida (15 a 20 años) legalmente firmado y con sus respectivos timbres.
• Asistir a las reuniones que se estarán convocando mediante el correo electrónico.</p>

<p><strong>BENEFICIOS</strong>
✓ Test de nivel al llegar y cursos de francés (19h30 semanales). ✓ Alojamiento con una familia francesa, habitación individual: incluye desayuno y cena + lavandería. ✓ Visita guiada en Vichy, 1 excursión de un día, 1 excursión de media jornada, 1 degustación de productos de la región, 1 velada internacional, acceso libre a las noches de cine del martes y jueves y a las actividades deportivas. ✓ Una permanecía en Paris de sábado a lunes (2 noches); se viaja en tren el sábado en la mañana (el traslado al hotel en París, así como el desayuno y cena están incluidos). ✓ Salidas en Bateau Mouche y Musée du Louvre. ✓ Certificado de stage y de nivel alcanzado por cada alumno.</p>

<p>Los alumnos podrán almorzar de lunes a viernes en el restaurante universitario del campus con una tarifa de 6 €, sin embargo, se puede salir para buscar otras posibilidades (panaderías, snacks, restaurantes, fast food).</p>

<p><strong>Fecha límite de inscripción: 1 de mayo 2018</strong></p>

<p>Los estudiantes interesados deben inscribirse en la administración con Ana Fúnez y Lilian Robles.</p>

<p>Cualquier duda comunicarse al teléfono: <strong>8906-0014</strong></p>',NULL,'',0,0,'published','en_US','public',NULL,NULL,2,'2018-03-23 00:40:44',2,'2018-03-23 01:33:36',2,'2018-03-23 00:48:22',2);
INSERT INTO "posts" VALUES(36,'ba28ff91-e40f-446f-8451-d729543ecad9','“Miradas sobre el mundo a través de la Historieta” Concurso Regional América Central','miradas-sobre-el-mundo-a-traves-de-la-historieta','![](www.afsps.org/content/images/2018/03/BD-CONCURSO-lo.jpg)
#“Miradas sobre el mundo a través de la Historieta”
###Concurso Regional América Central
<br>
####Reglamento:
<br>
**Art.1:** La Alianza Francesa de Costa Rica, asociación costarricense sin fines
de lucro, con cédula jurídica 3-002-061758, teniendo como misión la enseñanza del francés, la difusión de la cultura francófona y la promoción de la diversidad cultural, organiza en colaboración con la Librería Francesa de Costa Rica, un Concurso de Historieta Regional para América Central llamado “Miradas sobre el mundo a través de la Historieta”, iniciando el **3 de marzo del 2018** y cuya fecha límite para participar se estableció para el **25 de agosto del 2018.**

**Art. 2:** Este concurso es gratuito y abierto a aficionados y profesionales (artistas, escritores, guionistas) mayores de edad.

**Art. 3:** El tema es **“Crónica de viaje”**, todos los estilos y géneros están
autorizados (humorístico, crónica, documental, biográfico, erótico). Los candidatos están invitados a trabajar el tema a partir de la ficción o su experiencia propia.<br>
Los participantes deben enviar por correo electrónico, una “Historieta” original, completa, inédita, con título, en francés o en español, con o sin leyenda. Los documentos enumerados en el artículo Art. 4 deben ser igualmente enviados.

Entendemos por “Historieta”, comúnmente abreviado en francés “BD”, una forma de expresión artística, a menudo designada como el “noveno arte” que utiliza una yuxtaposición de dibujos (u otro tipo de imágenes fijas) articuladas en secuencias narrativas, con frecuencia acompañadas de textos (narraciones, diálogos, onomatopeyas).

**Deberá enviarse un mínimo de 3 y un máximo de 5 páginas.**

**Art. 4:** El expediente de cada candidato o colectivo comprenderá: <br>
1-Los trabajos, entiéndase páginas de la Historieta. El formato de las imágenes enviadas será en forma digital y obligatoriamente:
-Previsto para una impresión en formato A3 (29,7 x 42cm máximo) <br>
-De 2000 píxeles de ancho <br>
-En documento JPG <br>
-Calidad 100 <br>

2-El envío de las páginas de la Historieta deberá acompañarse del documento llamado “Formulario de inscripción” completado por los candidatos (Ver ANEXO 1).

3-Así como los documentos señalados a continuación:
-un curriculum vitae. <br>
-una biografía (10 líneas máximo). <br>
-una fotografía del autor o del colectivo. <br>

Estos documentos no serán tomados en cuenta para la selección pero se utilizarán con fines comunicacionales en caso de ser necesario. Con la intención de evitar pérdidas, se excluye cualquier otra modalidad de participación.

Únicamente las obras seleccionadas serán impresas en un formato A3 y expuestas en la Galería Joven Creación de la Alianza Francesa de Costa Rica.

**Art. 5:** Cada participante debe enviar su expediente por correo electrónico a la sede de su Alianza Francesa de referencia. Solamente los expedientes completos serán aceptados. No será aceptado ningún expediente enviado directamente a la Alianza Francesa de Costa Rica, salvo para el caso de costarricenses o residentes de Costa Rica.

Cada Alianza Francesa de América Central deberá verificar si el expediente está completo. Después de dicha validación, solamente ellas tendrán derecho a enviar los expedientes de cada participante por correo electrónico a la Alianza Francesa de Costa Rica, piloto del concurso “Miradas sobre el mundo a través de la Historieta”.

Todos los trabajos serán presentados al **Gran Jurado**, compuesto por:
-**Nicolas Grivel**, agente literario y creador de la “Nicolas Grivel Agency”,
agencia de derechos especializada en la Tira Cómica.
-**César Maurel**, ilustrador, escritor.<br>
-**Olivia Deroint**, Directora de la Alianza Francesa de Costa Rica. <br>
-**Guy Delisle**, autor canadiense de historietas.

**Art. 6:** Los envíos deben efectuarse por correo electrónico a la dirección de
la Alianza francesa de su país:
Alianza Francesa de Costa Rica: mediateca@alianzafrancesacostarica.com
Alianza francesa de Ciudad Guatemala: concursoafgt@gmail.com
Alianza Francesa de Tegucigalpa: biblioteca@aftegucigalpa.hn
Alianza Francesa de Panamá: asistenteculturalaf@gmail.com
Alianza Francesa de San Salvador: biblioteca@afelsalvador.com
Alianza Francesa de Managua: mediateca@alianzafrancesa.org.ni

Las Alianzas Francesas enviarán su acuso de recibo por correo electrónico.

**Art. 7:** El Gran Jurado seleccionará las 10 mejores Historietas entre las cuales
habrá un laureado según:
-El respeto del tema. <br>
-La originalidad del guión.<br>
-La calidad gráfica.

**Art. 8:** Las 10 obras seleccionadas incluyendo al laureado formarán parte de una exposición llamada: *“Crónica de viaje”* en el seno de la Galería Joven Creación, inaugurada el **jueves 18 de octubre del 2018** en la Alianza Francesa de Costa Rica, en el marco del evento *“LEER ES UNA FIESTA”* y, eventualmente, en las demás Alianzas Francesas Regionales.

El laureado será invitado a la Alianza Francesa de Costa Rica y su premio comprenderá:
- La cobertura de su viaje, alojamiento y per diem por un período de 3
días.
- Un cheque de 500 dólares entregado el 18 de octubre del 2018, día
de la inauguración de la exposición.
- Un acompañamiento personalizado de Nicolas Grivel para promover el trabajo del laureado en el marco de los principales festivales de la Tira Cómica de Europa.

En el caso de que la obra sea colectiva, únicamente el representante será invitado. 

Los nombres de los participantes seleccionados serán anunciados a más tardar el **17 de setiembre del 2018** en el sitio internet de cada Alianza Francesa de América Central participante.

**Art. 9:** El candidato se compromete a ceder sus derechos de autor en beneficio del Concurso : « Miradas sobre el mundo a través de la Historieta”.

**Art. 10:** La Alianza Francesa de Costa Rica se reserva la posibilidad de acortar, prolongar, modificar o anular el presente concurso si las circunstancias así lo exigen o en caso de fuerza mayor. Su responsabilidad no se vería comprometida por éste hecho. Las Alianzas Francesas participantes se comprometen, en caso necesario, a comunicar a los
artistas las informaciones correspondientes a eventuales cambios.

**Art. 11:** El simple hecho de participar en el concurso implica la aceptación, sin reservas, del presente reglamento en su totalidad. Toda declaración inexacta o engañosa, todo fraude conllevará a la descalificación del participante. El artista se compromete igualmente a ser el autor de la integralidad de las creaciones presentadas.',NULL,'<p><img src="/content/images/2018/03/BD-CONCURSO-lo.jpg" alt="" /></p>

<h1 id="miradassobreelmundoatravsdelahistorieta">“Miradas sobre el mundo a través de la Historieta”</h1>

<h3 id="concursoregionalamricacentral">Concurso Regional América Central</h3>

<p><br>  </p>

<h4 id="reglamento">Reglamento:</h4>

<p><br> <br />
<strong>Art.1:</strong> La Alianza Francesa de Costa Rica, asociación costarricense sin fines
de lucro, con cédula jurídica 3-002-061758, teniendo como misión la enseñanza del francés, la difusión de la cultura francófona y la promoción de la diversidad cultural, organiza en colaboración con la Librería Francesa de Costa Rica, un Concurso de Historieta Regional para América Central llamado “Miradas sobre el mundo a través de la Historieta”, iniciando el <strong>3 de marzo del 2018</strong> y cuya fecha límite para participar se estableció para el <strong>25 de agosto del 2018.</strong></p>

<p><strong>Art. 2:</strong> Este concurso es gratuito y abierto a aficionados y profesionales (artistas, escritores, guionistas) mayores de edad.</p>

<p><strong>Art. 3:</strong> El tema es <strong>“Crónica de viaje”</strong>, todos los estilos y géneros están
autorizados (humorístico, crónica, documental, biográfico, erótico). Los candidatos están invitados a trabajar el tema a partir de la ficción o su experiencia propia.<br> <br />
Los participantes deben enviar por correo electrónico, una “Historieta” original, completa, inédita, con título, en francés o en español, con o sin leyenda. Los documentos enumerados en el artículo Art. 4 deben ser igualmente enviados.</p>

<p>Entendemos por “Historieta”, comúnmente abreviado en francés “BD”, una forma de expresión artística, a menudo designada como el “noveno arte” que utiliza una yuxtaposición de dibujos (u otro tipo de imágenes fijas) articuladas en secuencias narrativas, con frecuencia acompañadas de textos (narraciones, diálogos, onomatopeyas).</p>

<p><strong>Deberá enviarse un mínimo de 3 y un máximo de 5 páginas.</strong></p>

<p><strong>Art. 4:</strong> El expediente de cada candidato o colectivo comprenderá: <br>
1-Los trabajos, entiéndase páginas de la Historieta. El formato de las imágenes enviadas será en forma digital y obligatoriamente: <br />
-Previsto para una impresión en formato A3 (29,7 x 42cm máximo) <br>
-De 2000 píxeles de ancho <br>
-En documento JPG <br>
-Calidad 100 <br></p>

<p>2-El envío de las páginas de la Historieta deberá acompañarse del documento llamado “Formulario de inscripción” completado por los candidatos (Ver ANEXO 1).</p>

<p>3-Así como los documentos señalados a continuación: <br />
-un curriculum vitae. <br>
-una biografía (10 líneas máximo). <br>
-una fotografía del autor o del colectivo. <br></p>

<p>Estos documentos no serán tomados en cuenta para la selección pero se utilizarán con fines comunicacionales en caso de ser necesario. Con la intención de evitar pérdidas, se excluye cualquier otra modalidad de participación.</p>

<p>Únicamente las obras seleccionadas serán impresas en un formato A3 y expuestas en la Galería Joven Creación de la Alianza Francesa de Costa Rica.</p>

<p><strong>Art. 5:</strong> Cada participante debe enviar su expediente por correo electrónico a la sede de su Alianza Francesa de referencia. Solamente los expedientes completos serán aceptados. No será aceptado ningún expediente enviado directamente a la Alianza Francesa de Costa Rica, salvo para el caso de costarricenses o residentes de Costa Rica.</p>

<p>Cada Alianza Francesa de América Central deberá verificar si el expediente está completo. Después de dicha validación, solamente ellas tendrán derecho a enviar los expedientes de cada participante por correo electrónico a la Alianza Francesa de Costa Rica, piloto del concurso “Miradas sobre el mundo a través de la Historieta”.</p>

<p>Todos los trabajos serán presentados al <strong>Gran Jurado</strong>, compuesto por: <br />
-<strong>Nicolas Grivel</strong>, agente literario y creador de la “Nicolas Grivel Agency”,
agencia de derechos especializada en la Tira Cómica. <br />
-<strong>César Maurel</strong>, ilustrador, escritor.<br>
-<strong>Olivia Deroint</strong>, Directora de la Alianza Francesa de Costa Rica. <br>
-<strong>Guy Delisle</strong>, autor canadiense de historietas.</p>

<p><strong>Art. 6:</strong> Los envíos deben efectuarse por correo electrónico a la dirección de
la Alianza francesa de su país: <br />
Alianza Francesa de Costa Rica: mediateca@alianzafrancesacostarica.com <br />
Alianza francesa de Ciudad Guatemala: concursoafgt@gmail.com <br />
Alianza Francesa de Tegucigalpa: biblioteca@aftegucigalpa.hn <br />
Alianza Francesa de Panamá: asistenteculturalaf@gmail.com <br />
Alianza Francesa de San Salvador: biblioteca@afelsalvador.com <br />
Alianza Francesa de Managua: mediateca@alianzafrancesa.org.ni</p>

<p>Las Alianzas Francesas enviarán su acuso de recibo por correo electrónico.</p>

<p><strong>Art. 7:</strong> El Gran Jurado seleccionará las 10 mejores Historietas entre las cuales
habrá un laureado según: <br />
-El respeto del tema. <br>
-La originalidad del guión.<br>
-La calidad gráfica.</p>

<p><strong>Art. 8:</strong> Las 10 obras seleccionadas incluyendo al laureado formarán parte de una exposición llamada: <em>“Crónica de viaje”</em> en el seno de la Galería Joven Creación, inaugurada el <strong>jueves 18 de octubre del 2018</strong> en la Alianza Francesa de Costa Rica, en el marco del evento <em>“LEER ES UNA FIESTA”</em> y, eventualmente, en las demás Alianzas Francesas Regionales.</p>

<p>El laureado será invitado a la Alianza Francesa de Costa Rica y su premio comprenderá: <br />
- La cobertura de su viaje, alojamiento y per diem por un período de 3
días. <br />
- Un cheque de 500 dólares entregado el 18 de octubre del 2018, día
de la inauguración de la exposición. <br />
- Un acompañamiento personalizado de Nicolas Grivel para promover el trabajo del laureado en el marco de los principales festivales de la Tira Cómica de Europa.</p>

<p>En el caso de que la obra sea colectiva, únicamente el representante será invitado. </p>

<p>Los nombres de los participantes seleccionados serán anunciados a más tardar el <strong>17 de setiembre del 2018</strong> en el sitio internet de cada Alianza Francesa de América Central participante.</p>

<p><strong>Art. 9:</strong> El candidato se compromete a ceder sus derechos de autor en beneficio del Concurso : « Miradas sobre el mundo a través de la Historieta”.</p>

<p><strong>Art. 10:</strong> La Alianza Francesa de Costa Rica se reserva la posibilidad de acortar, prolongar, modificar o anular el presente concurso si las circunstancias así lo exigen o en caso de fuerza mayor. Su responsabilidad no se vería comprometida por éste hecho. Las Alianzas Francesas participantes se comprometen, en caso necesario, a comunicar a los
artistas las informaciones correspondientes a eventuales cambios.</p>

<p><strong>Art. 11:</strong> El simple hecho de participar en el concurso implica la aceptación, sin reservas, del presente reglamento en su totalidad. Toda declaración inexacta o engañosa, todo fraude conllevará a la descalificación del participante. El artista se compromete igualmente a ser el autor de la integralidad de las creaciones presentadas.</p>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2018-03-23 23:57:25',2,'2018-03-24 00:36:01',2,'2018-03-24 00:34:10',2);
INSERT INTO "posts" VALUES(37,'d83f22c7-5db2-423c-8d4b-0f07e76e3b3d','CURSOS DE FRANCÉS | 1er. NIVEL | 2do. CUATRIMESTRE 2018','cursos-de-frances-1er-nivel-2do-cuatrimestre-2018','![](www.afsps.org/content/images/2018/04/Screen-Shot-2018-04-10-at-3.46.02-PM.png)
#Cursos de francés 1er. Nivel
<br>
###Inicio de clases: 7 de mayo de 2018
###¡Matrícula abierta!
<br>
**PEQUEÑA MATERNAL (4-5 años)** <br>
• Lunes y miércoles <br>
   3:00 – 4:30 p.m.

**GRAN MATERNAL (5-6 años)** <br>
• Martes y jueves <br>
   3:00 – 4:30 p.m.

**NIÑOS (7-9 años)** <br> 
• Lunes y Miércoles <br>
   3:00 – 4:30 p.m.

**PRE-ADOLESCENTES (10-12 años)** <br>
• Lunes y miércoles <br>
   4:30 – 6:00 p.m. <br>
•Martes y jueves <br>
  3:00 – 4:30 p.m.

**ADOLESCENTES (13-14 años)** <br>
• Martes y jueves <br>
   4:30 – 6:00 p.m. <br>
•Viernes <br>
   3:00 – 6:00 p.m.

**ADULTOS (15 años en adelante)** <br>
• Martes y jueves <br>
   6:30 – 8:00 p.m. <br>
• Viernes <br>
   8:30 – 11:30 a.m. <br>
• Viernes <br>
   3:00 – 6:00 p.m. <br>
• Sábados <br>
   12:00 – 3:00 p.m.
_________________________________________
##Cursos especializados de francés:
**FONÉTICA Y CONVERSACIÓN** <br>
-          A partir del nivel 7  <br>
-          De 14 años en adelante. <br>

• Martes <br>
   6:00 – 7:30 p.m.<br>
• Jueves <br>
   6:00 – 7:30 p.m.<br>
• Viernes<br>
   6:00 – 7:30 p.m.<br>

**FRANCÉS PARA PADRES** <br>
• Lunes y Miércoles <br>
   4:30 – 5:30 p.m. <br>
• Martes y jueves <br>
   4:30 – 5:30 p.m. <br>
_________________________________________

##Cursos libres de arte
####Inicio de clases: 1er. día de cada mes

**Guitarra** <br>
De 10 años en adelante:
• Miércoles - 6:00 a 8:00 p.m. <br>
• Sábado - 8:00 a 10:00 a.m.

**Pintura** <br>
• Martes 3:00 a 5:00 p.m. <br>

8-13 años:
• Miércoles 3:00 a 5:00 p.m. <br>
14 años en adelante:
• Miércoles 5:00 a 7:00 p.m.

**Violín** <br>
De 5 años en adelante: 
• Viernes 3:00 a 4:30 p.m.

**Piano** <br>
De 5 años en adelante:
• Miércoles 3:00 a 4:30 p.m. <br>
• Viernes 3:00 a 4:30 p.m. <br>
• Sábado 11:00 am a 12:30 pm.
_________________________________________
## +Info en:
####+504 2566 3733 | +504 2566 3743 <br>
####alianzafrancesasps@gmail.com',NULL,'<p><img src="/content/images/2018/04/Screen-Shot-2018-04-10-at-3.46.02-PM.png" alt="" /></p>

<h1 id="cursosdefrancs1ernivel">Cursos de francés 1er. Nivel</h1>

<p><br>  </p>

<h3 id="iniciodeclases7demayode2018">Inicio de clases: 7 de mayo de 2018</h3>

<h3 id="matrculaabierta">¡Matrícula abierta!</h3>

<p><br> <br />
<strong>PEQUEÑA MATERNAL (4-5 años)</strong> <br>
• Lunes y miércoles <br>
   3:00 – 4:30 p.m.</p>

<p><strong>GRAN MATERNAL (5-6 años)</strong> <br>
• Martes y jueves <br>
   3:00 – 4:30 p.m.</p>

<p><strong>NIÑOS (7-9 años)</strong> <br> 
• Lunes y Miércoles <br>
   3:00 – 4:30 p.m.</p>

<p><strong>PRE-ADOLESCENTES (10-12 años)</strong> <br>
• Lunes y miércoles <br>
   4:30 – 6:00 p.m. <br>
•Martes y jueves <br>
  3:00 – 4:30 p.m.</p>

<p><strong>ADOLESCENTES (13-14 años)</strong> <br>
• Martes y jueves <br>
   4:30 – 6:00 p.m. <br>
•Viernes <br>
   3:00 – 6:00 p.m.</p>

<p><strong>ADULTOS (15 años en adelante)</strong> <br>
• Martes y jueves <br>
   6:30 – 8:00 p.m. <br>
• Viernes <br>
   8:30 – 11:30 a.m. <br>
• Viernes <br>
   3:00 – 6:00 p.m. <br>
• Sábados <br>
   12:00 – 3:00 p.m.</p>

<hr />

<h2 id="cursosespecializadosdefrancs">Cursos especializados de francés:</h2>

<p><strong>FONÉTICA Y CONVERSACIÓN</strong> <br>
-          A partir del nivel 7  <br>
-          De 14 años en adelante. <br></p>

<p>• Martes <br>
   6:00 – 7:30 p.m.<br>
• Jueves <br>
   6:00 – 7:30 p.m.<br>
• Viernes<br>
   6:00 – 7:30 p.m.<br></p>

<p><strong>FRANCÉS PARA PADRES</strong> <br>
• Lunes y Miércoles <br>
   4:30 – 5:30 p.m. <br>
• Martes y jueves <br>
   4:30 – 5:30 p.m. <br></p>

<hr />

<h2 id="cursoslibresdearte">Cursos libres de arte</h2>

<h4 id="iniciodeclases1erdadecadames">Inicio de clases: 1er. día de cada mes</h4>

<p><strong>Guitarra</strong> <br>
De 10 años en adelante: <br />
• Miércoles - 6:00 a 8:00 p.m. <br>
• Sábado - 8:00 a 10:00 a.m.</p>

<p><strong>Pintura</strong> <br>
• Martes 3:00 a 5:00 p.m. <br></p>

<p>8-13 años: <br />
• Miércoles 3:00 a 5:00 p.m. <br>
14 años en adelante: <br />
• Miércoles 5:00 a 7:00 p.m.</p>

<p><strong>Violín</strong> <br>
De 5 años en adelante: <br />
• Viernes 3:00 a 4:30 p.m.</p>

<p><strong>Piano</strong> <br>
De 5 años en adelante: <br />
• Miércoles 3:00 a 4:30 p.m. <br>
• Viernes 3:00 a 4:30 p.m. <br>
• Sábado 11:00 am a 12:30 pm.</p>

<hr />

<h2 id="infoen">+Info en:</h2>

<h4 id="5042566373350425663743br">+504 2566 3733 | +504 2566 3743 <br></h4>

<h4 id="alianzafrancesaspsgmailcom">alianzafrancesasps@gmail.com</h4>',NULL,NULL,0,0,'published','en_US','public',NULL,NULL,2,'2018-04-10 21:31:37',2,'2018-04-11 00:43:38',2,'2018-04-10 21:47:03',2);
CREATE UNIQUE INDEX "posts_slug_unique" on "posts" ("slug");
COMMIT;
