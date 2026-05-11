¿Por qué los enlaces son verdes y no rojos?
Porque en el código del enlace se está usando un selector más específico para el color verde (como apuntar directamente a la etiqueta del enlace), mientras que el rojo se intenta aplicar de forma general o por herencia. En CSS, una regla específica siempre le gana a una regla general.

Hacer que los enlaces sean rojos
Para lograrlo, se debe cambiar la propiedad de color directamente en el selector que controla los enlaces, asegurándose de que esa nueva regla tenga la misma o mayor importancia que la que los ponía verdes.

Rehacer el HTML usando <div> en lugar de <ul> y <li>. ¿Qué pasa?
Al cambiar las etiquetas de lista por bloques normales, el navegador deja de aplicar el formato automático de lista. Esto causa que desaparezcan los puntos (viñetas) y que el espacio o margen que tenían los elementos cambie, haciendo que el contenido se vea como bloques de texto simples uno tras otro.

Comentar el CSS que no se puede tocar y reescribir este CSS usando una clase por selector para que se vea igual.
Al hacer esto, el diseño se mantiene idéntico visualmente, pero el código se vuelve más limpio y profesional. Al usar una clase específica, se tiene un control total sobre el estilo sin depender de la estructura de las etiquetas (como las listas), facilitando que cualquier cambio futuro se aplique a todos los elementos al mismo tiempo.