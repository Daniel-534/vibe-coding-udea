# Procedimiento para la creación de material educativo (tipo guía de estudio):

A continuación se explica el procedimiento de un caso concreto, luego se replica lo miso para el tema que se desee.

En el caso de construcción de material de clse para criptografía (Teórico y práctico con python)
* Se le pidió a Claude, la creación de un plan de 10 clases en criptografía, con la estructura de Main Topic -> Breve descripción. Se le especificó el hecho de que debe ser un plan que cubra temas desde lo introductorio hasta temas medianamente avanzados y aplicables en la actualidad.
* La anterior solicitud se realizó varias veces, para elegir el plan que más se acomodara a mis intereses actuales.
* Se agrega el plan de clases al repositorio de github en el `README.md` del directorio en el que estarán ubicadas las clases.
* Se usa el Agente de Github Copilot para indicarle que lea el contenido del `README.md` y basado en eso, construya la primera clase de manera extensa, con teoría, práctica, ejercicios propuestos y citar todas las referencias utilizadas.
* Es recomendable pedir una sola clase en cada solicitud, ya que de lo contrario se puede saturar el agente y al final obtener time limit exceed o algo similar.
* Cuando termine, la solicitud, debes entrar a la sección de agentes, te ubicas en la sesión creada, das click en `Create pull request`, esto te llevará a una pestaña donde se explica todo lo que el agente hizo. Para agregar esto a nuestro repositorio, bajas en la pestaña y haces `Ready for review > Merge pull request > Confirm merge`
