# Web App Mis Videos
### Proyecto final. Programción web. Laura Cristina Ortiz Olmos.
# Descripcion de Web App.
En este reositorio se aprendio a crear una aplicación web Backend y Frontend, utilizando Nodejs, Mysql, Express y otras tecnologías de Javascript. En este ejemplo creamos una aplicacion de videos, con un Login y Registro utilizando Mysql, ademas de proteger nuestras rutas del servidor y estilizar nuestra aplicación con CSS, Bootstrap4, y Handlebars.
El diseño de esta app web cuenta con una barra de navegación con cuatro apartados: "Inicio", "Contacto", "Iniciar sesión" y "Registrarse".                                                                                                                            La página principal está dividida en secciones.
La primera nos muestra un listado de vídeos, los vídeos mostrados tiene información que el usuario ha ingresado como: "Nombre", "Red social" y "Categoría", también en cada uno de los videos mostrados en el listado viene el usuario y una calificación.                  En la siguiente sección se encuentran los datos del alumno, como "Nombre", "Formación", "Dirección" y "Redes sociales".
En "Registrarse" el diseño nos muestra un formulario con alguno datos para poder crear una cuenta dentro de la web app.                El apartado "Iniciar sesión" muestra un formulario que como su nombre lo indica permite al usuario ingresar a su perfil. Una vez inicida la sesión en la barra de navegación se muestra una lista desplegable "Opciones" y en esta tenemos dos alternativas ir al "Perfil" o "Cerrar sesión". Dentro de "Perfil" en la sección "Panel de control" podemos realizar algunas acciones como "Agregar un vídeo" o "Ir a mis videos" este apartado está pensando para que el usuario pueda realizar alguna acciones como "Agregar", "Borrar" o "Editar" algún vídeo.                                                                                                                               Para poder calificar un vídeo se necesita haber ingresado, sin este requisito no es posible dar una calificación a alguno de los videos que se muestran.                                                                                                                     Para poder acceder a los datos desde cualquier aplicación del listado de los vídeos se se tiene una API Rest que permite mostrar los vídeos con fecha de captura mas reciente y generando una cadena JSON 100% valida.                                                      En esta aplicación se hace uso de NodeJS,Express, Passport.js como middleware de autenticación para Node.js, CSS, Bootstrap4, y Handlebars para estilizar la webapp y librerías de express para conexión a Mysql.

# Handlebars.js
Handlebars.js es un motor de plantillas muy popular que es potente, fácil de utilizar y que cuenta con una gran comunidad. Se basa en el lenguaje de plantillas Mustache, pero lo mejora de distintas maneras. Handlebars, tiene la funcionalidad de separar el diseño HTML del resto de tu Javascript, para así escribir código mucho más limpio.

# Passport.js
Passport es el middleware de autenticación para Node.js . Extremadamente flexible y modular, Passport se puede colocar discretamente en cualquier aplicación web basada en Express . Un conjunto integral de estrategias admite la autenticación utilizando un nombre de usuario y contraseña.

# timeago.js
timeago.js es una pequeña biblioteca (2kb) utilizada para formatear la fecha, por ejemplo: 'hace 3 horas'. 
Sin dependencia y admite la actualización automática de marcas de tiempo difusas. 
(por ejemplo, "hace 4 minutos" o "hace aproximadamente 1 día").

# bcryptjs.
Bcrypt es una función de hashing de passwords diseñado por Niels Provos y David Maxieres, basado en el cifrado de Blowfish. Se usa por defecto en sistemas OpenBSD y algunas distribuciones Linux y SUSE. Lleva incorporado un valor llamado salt, que es un fragmento aleatorio que se usará para generar el hash asociado a la password, y se guardará junto con ella en la base de datos. Así se evita que dos passwords iguales generen el mismo hash y los problemas que ello conlleva, por ejemplo, ataque por fuerza bruta a todas las passwords del sistema a la vez.

# Nodejs.
Es un entorno de tiempo de ejecución de JavaScript (de ahí su terminación en .js haciendo alusión al lenguaje JavaScript). Este entorno de tiempo de ejecución en tiempo real incluye todo lo que se necesita para ejecutar un programa escrito en JavaScript. La idea principal de Node.js es usar el modelo de entrada y salida sin bloqueo y controlado por eventos para seguir siendo liviano y eficiente frente a las aplicaciones en tiempo real de uso de datos que se ejecutan en los dispositivos. Es una plataforma que no dominará el mundo del desarrollo web pero si que satisface las necesidades de una gran mayoría de programadores.

# Mysql FreeHosting.
Todas las páginas y blogs que se muestran en la red han de tener un dominio y un hosting. El dominio es el nombre que va a tener la web en Internet, y el hosting es el espacio o el lugar en el que vas a alojar tu página, por lo que también es conocido como alojamiento web. Existen diferentes tipos de hosting y se diferencian en el espacio de almacenamiento o en si son de pago o gratuitos.

FreeMysqlHosting es un alojamiento web gratuito que con solo registarse te permite tener acceso a una base de datos remota. En este freehosting no pagaras nada, y si tienes más de un correo electrónico, puedes crearte varias cuentas y disponer de varios planes de hosting gratuito a la vez.

# Api Rest.
REST es el estándar más lógico, eficiente y habitual en la creación de APIs para servicios de Internet.
REST es cualquier interfaz entre sistemas que use HTTP para obtener datos o generar operaciones sobre esos datos en todos los formatos posibles, como XML y JSON. Es una alternativa en auge a otros protocolos estándar de intercambio de datos como SOAP (Simple Object Access Protocol), que disponen de una gran capacidad pero también mucha complejidad. 
Hoy en día las API REST están en un gran apogeo ya que la mayoría hace uso de esta tecnología para poder como menciono, enviar y recibir datos de forma sencilla y rápida, aunque una tecnología que está en crecimiento es el GraphQL que busca reemplazar a las API REST para hacerlas aún más sencillas y a la vez más robustas.
Las API REST aprovechan los métodos HTTP, desde un simple POST o GET hasta métodos personalizados, sin embargo, nosotros veremos únicamente POST, GET, PUT y DELETE en su forma más sencilla y las Headers que son para autenticación, decirle qué tipo de dato va.

# Caracteristicas Rest.
* Protocolo cliente/servidor sin estado: cada petición HTTP contiene toda la información necesaria para ejecutarla, lo que permite que ni cliente ni servidor necesiten recordar ningún estado previo para satisfacerla. Aunque esto es así, algunas aplicaciones HTTP incorporan memoria caché. 
* Las operaciones más importantes relacionadas con los datos en cualquier sistema REST y la especificación HTTP son cuatro: POST (crear), GET (leer y consultar), PUT (editar) y DELETE (eliminar).
* Los objetos en REST siempre se manipulan a partir de la URI. 
* Interfaz uniforme.
* Sistema de capas: arquitectura jerárquica entre los componentes.

# Resultado.
![Captura de pantalla (242)](https://user-images.githubusercontent.com/61463784/83242846-b001db00-a162-11ea-9905-4fab96896acb.png)
![Captura de pantalla (247)](https://user-images.githubusercontent.com/61463784/83242860-b5f7bc00-a162-11ea-9952-995bcb2c9e42.png)
![Captura de pantalla (248)](https://user-images.githubusercontent.com/61463784/83242866-b85a1600-a162-11ea-8edc-db24e5f5524c.png)
![Captura de pantalla (249)](https://user-images.githubusercontent.com/61463784/83242907-c3ad4180-a162-11ea-96ff-4dc14cd2a465.png)
![Captura de pantalla (250)](https://user-images.githubusercontent.com/61463784/83242956-d58ee480-a162-11ea-9dc0-9056c2ecda76.png)
![Captura de pantalla (251)](https://user-images.githubusercontent.com/61463784/83242976-dcb5f280-a162-11ea-9dc6-f034503d3d0d.png)
![Captura de pantalla (252)](https://user-images.githubusercontent.com/61463784/83242980-de7fb600-a162-11ea-9a71-cde9808cc1e3.png)
![Captura de pantalla (253)](https://user-images.githubusercontent.com/61463784/83242995-e3446a00-a162-11ea-88b0-e05911a3b270.png)

