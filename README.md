# login-registro

Para realizar el formulario, hemos seguido los requisitos funcionales, usando todos los campos requeridos y hemos añadido un nombre de usuario, marcando qué campos son obligatorios y comprobando con expresiones regulares que los datos introducidos son correctos. También se comprueba que las contraseñas coincidan y que la casilla de política de privacidad esté marcada. También hemos cumplido con los requisitos técnicos, excepto la realización de tests funcionales. La interactividad con el usuario se consigue con el botón reactivo y el marcado en rojo de las casillas erróneas, además de mostrar un mensaje de cómo debe completarse. Cuando todos los datos son correctos, se avisa al usuario mediante un alert. Se ha desactivado el refresco de la página y no se han usado frameworks.

Sobre las recomendaciones WCAG 2.0 hemos tenido en cuenta:<br>
    - Marcar con un asterisco las casillas obligatorias y explicar en una leyenda al comienzo del formulario el significado del símbolo.
    - Las casillas obligatorias tienen la propiedad required.<br>
    - Cuando una casilla es completada de forma no válida, se marca la casilla errónea en rojo y se indica claramente cómo se debe completar correctamente.<br>
    - Botón submit para establecer el cambio de contexto a voluntad del usuario.<br>
    - No establecer límites de tiempo.<br>
    - El campo de correo requiere un formato concreto, así que se proporciona un ejemplo del formato esperado como placeholder.<br>

En cuanto al diseño:
Tiene un diseño simple y plano, con colores básicos y contrastantes. Las casillas están alineadas para mejorar la legibilidad y divididas en dos apartados según su clasificación. El botón reacciona al usuario para mostrar claramente que está funcionando. Las casillas que se completen de forma errónea se marcarán en rojo y se mostrará debajo de ellas un texto explicando cómo debe completarse correctamente también en rojo, para contrastar con el nombre de los elementos y representar que hay algún fallo.

Existen errores de validación sobre el envío del formulario, ya que no se envía realmente a ningún servidor, pero el funcionamiento es correcto.