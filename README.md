# LooksBooks

Aca dejemos todo lo que vamos anontando mas una fecha para ir viendo como avanzamos :D
  - 26/10/2018 
  - Estoy pensando en usar REACT.JS para la parte mas visual con JS y por debajo JAVA con SPRING y para SQL POSTGRESQL que es ultra usado ahora y piden saber en artas pegas.
  - usar el entorno vs code con github para los cambios...igualmente puedes usar otro tipo de enterono y conectarlo creo que no habria dramas.

  - 30/10/2018
  - Establecimos los framework a usar y los lenguajes, se usara JS para el front y java para el back.
  - Los framework que usaremos son Hibernate para las llamas y solicitudes SQL, Spring para el MVC de Java y React para el front con JS
  - Finalmente usaremos PostreSQL para las bases de datos relacionales.
  
  - Definimos las funcionalidades de la aplicacion:
      - Agregar amigos.
      - Ver perfil.
      - Preferencias de libros o categorias.
      - Logros por antiguedad, libros, prestamos, etc.
      - Gps para calcular las distancias de las personas y hacer algo como tinder.
        - Intentar agregar Base de datos libre de libros.
  
  - El flujo de la aplicacion sera
      - Primero al registrarse se debara ingresar 3 o libros para intercambiar, registrandolos y asignando una categoria a dicho libro.
      - Luego al buscar libro se podran filtrar tanto por nombre de libro o por categoria.
      - Al encontrar un libro deseado se enviara una solicitud para intercambio, no se mostrara perfil ni usuario...solo el libro.
      - Al enviar la solicitud el usuario poseedor del libro buscado puede ver cuales son los libros que intercambia el solicitante.
      - Si acepta un libro de los que el solicitante ofrece se acepta el pedido y en ese momento se dan a conocer los perfiles para concretar el intercambio.
      - Cuando se acepta se da un tiempo limite para realizar el intercambio (dos dias por ejemplo).
      - La aplicacion pregunta si se realizo el intercambio, si se realiza se traspasan los libros entre los perfiles para mostrar los que tiene asignado e intercambiado, si no se realiza se cancela el intercambio.
      - Al recibir el libro en el intercambio se puede "esconder" o dejar libre para prestamo para que asi aparesca en las busquedas de otros usuarios.
