## (¡OH NO! Estoy en un isekai serie B)

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 

**Titulo** : ¡OH NO! Estoy en un isekai serie B

**Web:**   (sankyuku.github.com)

**Autor:**  (Claudia Alcántara López)

**Resumen** : Se trata de un juego inspirado en los RPG (Role-playing video game o Videojuego de rol) pero más sencillo que estos, donde tomaremos el control de un personaje que ha acabado en un mundo desconocido, género conocido como ''isekai''.

**Estilo/género:**  Juego

**Logotipo** : (insertar imagen y breve justificación, si  tiene) 

(insertar imágenes a resolucion de 100px alto)

**Resolución:** 800x600px responsivo

**Probado en:** Google Chrome y firefox (PC)

**Tamaño proyecto:** 15.7 MB

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA) 

**Fecha** : 19/06/2021

**Medios** :

- Github: https://github.com/Sankyuku
- Twitter: https://twitter.com/Sankyuku
- Instagram: https://www.instagram.com/sankyuku/


![girl](https://github.com/mgea/cmi20/blob/master/WalkingGirl_front01.png)

# 2. Memoria del proyecto 

### 2.1 Storyboard: 
El jugador encarna a una persona que ha acabado misteriosamente en un mundo desconocido. Tras deambular durante horas, entra a un bosque, donde ve a lo lejos una persona. A partir de aquí la historia se bifurca. El jugador podrá acercarse a esta persona desconocida o bien seguir un desvío en el camino.

Si te acercas a la primera persona, te encontrarás con una bruja y una caballera y te verás en el apuro de pelear contra monstruos.

En cambio, si tomas el desvío, encontrarás a una científica que pondrá a prueba tu inteligencia.

¿Qué camino tomarás?


### 2.2. Esquema de navegación 



(imagen con las distintas pantallas de navegación, usa draw.io o cualquier programa de dibujo)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)
- [Saga Dragon Quest](https://es.wikipedia.org/wiki/Dragon_Quest_(videojuego) referente de las características típocas de un RPG. 
- [The Rising of The Shield Hero](https://es.wikipedia.org/wiki/The_Rising_of_the_Shield_Hero) como ejemplo de isekai donde no eres poderoso desde el primer momento y no todos son agradables. 
- [Saga Ace Attorney](https://es.wikipedia.org/wiki/Ace_Attorney) para la optimización de los talksprites (los sprites que se muestran en las conversaciones) y gran parte de la música. 
- [IB](https://en.wikipedia.org/wiki/Ib_(video_game), donde tus acciones y las direcciones que tomas te llevan a un final u otro.


**Motivación de la propuesta** 

Todos sabemos que en ocasiones los guiones se van por las ramas, especialmente en el género ''isekai'' ¿Qué tal si nos reímos un poco de ello? Todo lo que pasa tiene su explicación y no sólo por haber acabado en otro mundo significa que vayas a ser el próximo dios. La motivación principal detrás de esta propuesta es crear un juego corto pero divertido, en el que también poder presentar superficialmente algunos de mis personajes originales a modo de spin-off.


**Publico / audiencia**

- Apto para todos los públicos.
- Orientado especialmente a los fans de los videojuegos y/o productos audiovisuales japoneses.


### Etapa 2: Desarrollo / actividades realizadas

(qué soluciones has planteado y cómo se han resuelto: juego, galería de fotos, grabación de video, etc.)

- Juego: El juego completo consta de 4 grandes elementos: el desplazamiento a través de sprites, los diálogos que se asemejan más a las visual novel que a los RPG (solo que sin decisiones dentro de estos), las peleas y el quizz.
El desplazamiento de los sprites funciona con las flechas del teclado. Esta fase es importante porque según tu camino acabarás en una ruta u otra. Para esto, he usado 3 colisiones de sprites: Una para la ruta 1, otra para que lleve a la zona 2 donde con la última colisión,inicia la ruta 2.
Lo diálogos tienen un simple sistema en el que se usa un botón invisible del mismo tamaño que el bocadillo para seguir avanzando. Esta solución es muy conocida entre gente acostumbrada a estos juegos, por eso puse una flecha que sirviera de guía para quien no estuviese seguro de qué hacer. Además de esto, los talksprites van cambiando según lsa emociones de los personajes, simplemente se cambia de imagen según avanza la película.
Las 2 peleas se basan en el mismo mecanismo: hay variables de vida y daño, una vez la vida es 0, la barra de vida queda vacía y el juego avanza. Cada personaje tiene un rango de daño diferente para que resulte más interesante.
Por último, el quizz consta de variables ''aciertos'' y ''fallos'' que van sumando según las respuestas. Está resuelto de manera en que haya dos posibles desenlaces de los eventos.

- Video: El video utilizado es una intro del juego Dragon Quest XI, ya que aun no siendo exactamente el mundo ni la situación, el ambiente es parecido y es la mayor inspiración en este trabajo. La inserción del video no es a través de youtube, sino del propio mp4.

- Instrucciones y ayuda al usuario: En la primera ruta no se corre ningún peligro, solo hay que pegar y disfrutar. Aunque las preguntas de la ruta 2 son complejas, está programado para que solo haya un escenario en el que se obtenga el final ''malo''.

- Menús y elementos de navegación: En la intro hay un botón de skip para saltar esta introducción, que pierde sentido tras la primera vez.
Una vez en el menú, aparecen los botones clave: créditos, iniciar viaje y galería. A estos se les suman los botones de control de volumen.
Créditos lleva a la información del proyecto. Iniciar viaje hará que comience el juego. Y finalmente, en la galería podremos observar los bocetos y diseños completos de los personajes, así como el video mencionado anteriormente, que da ambiente al juego. En la galería contamos con botones de avance y retroceso, así como un botón para volver al inicio, tanto en la galería como en los créditos, por si se pulsase sin querer. El del volumen es otro elemento presente en todas las pantallas, exceptuando la introducción y la galería (en este caso, por el bien del diseño y la composición).
- etc.



### Etapa 3: Problemas identificados

En la ruta 2, el sprite del jugador parece sufrir de un fallo que le dificulta el desplazamiento. El motivo es desconocido, ya que tras revisar el código con el profesor no se pudo llegar a una conclusión definitiva de a qué se debía esto. Mi principal sospecha es que se trata de un error del programa Hippani, ya que en esos mismos fotogramas, en ocasiones da problemas al abrirse en el reproductor que no se dan al exportarse.

Cuando juegas la ruta 1 y la repites sin reiniciar la pestaña del navegador, la barra de vida de los enemigos está vacía y su contador de vida está al 0, sin embargo, al pulsar los botones de pelea, estos funcionan perfectamente y la vida es restada como si hubiese mostrado 100 desde el principio.


# 4. Conclusiones 

Me ha gustado el desarrollo de este trabajo, aunque en ocasiones ha sido frustrante ya que en mi mente tenía ideas muy claras pero me costaba traducirlas a lenguaje informático. Prácticamente he podido ir solucionando poco a poco todos los problemas que he ido encontrando, por lo que en un futuro me gustaría poder pulir al completo este trabajo y corregir esos pocos fallos que se han resistido.

Hippani como programa no me ha disgustado, sin embargo, es muy molesto que muchos de los fallos sean del propio programa y/o su reproductor, ya que generan frustraciones mal enfocadas. De cualquier forma, su interfaz me ha facilitado mucho la programación, aún siendo principiante. En cuanto a esto, debido al enfoque que le di a mi juego,he tenido que buscar por mí misma algunas soluciones, por lo que me ha servido para aprender más allá del ''pause();'' y ''resume();''

En el futuro me gustaría seguir haciendo pequeños proyectos similares a este. 

# 5 Referencias 

**Artículos y blogs ** 

- Fisher, J. (2018, 10 septiembre). How DRAGON QUEST Helped Create the RPG Genre We Know And Love. Geek and Sundry. https://geekandsundry.com/how-dragon-quest-helped-create-the-rpg-genre-we-know-and-love/

**Recursos y materiales audiovisuales:**

* Musica: Dragon Quest IX - Assemble, People https://youtu.be/JwGzCsPj1-I, Phoenix Wright: Trials and Tribulations OST - Larry Butz Theme ~ When Something Smells, It's Usually Me https://youtu.be/Ry87VcpXwjo, Ace Attoney: Apollo Justice OST - Klavier Theme ~ Guilty Love https://youtu.be/pUwJfVn9Nq4, Ace Attoney: Apollo Justice OST - Trucy Theme ~ Child of Magic  https://youtu.be/5IrepeWqkIM, Ace Attoney: Apollo Justice OST - Lamiroir's Theme ~ "Landscape Painter in Sound" https://youtu.be/SsDnF8W0MB0, Another Code: Two Memories ~ Sayoko's wish https://youtu.be/mlaV4jt37k8
* Imágenes:  Elaboradas y diseñadas por mí.
* Tipografía: VCR OSD Mono https://www.dafont.com/es/vcr-osd-mono.font

**Herramientas utilizadas**

- Hippani Animator 5.1
- Procreate
- Clip Studio Paint PRO



(imagen de la licencia, copiar y pegar aquí la correcta)

https://creativecommons.org/licenses/?lang=es

Junio 2021
