1. Contexto (Javi)
El trabajo trata sobre la gestión de eventos y asistentes. Los eventos son clases que se dan en un centro educativo y los asistentes son los alumnos que van a esas clases.

2.Estructura del XML (Diego)
El XML tiene como elemento principal <eventos>, dentro del cual hay varios <evento>.
Cada evento tiene un código, un nombre, un día de la semana y  los asistentes.
Los asistentes tienen un id, un nombre y una edad.

3. DTD (Javier) y README
El DTD sirve para validar la estructura del XML. Verifica que los elementos estén bien ordenados, que puedan repetirse los eventos y los asistentes, y que los atributos código e id sean obligatorios.

4. XSD (Diego)
El XSD valida lo mismo que el DTD, pero además controla los tipos de datos. Por ejemplo, comprueba que la edad sea un número y que el orden de los elementos sea correcto.

5. Dificultades(Javi)
La principal dificultad fue hacer que el XML, el DTD y el XSD coincidan correctamente, sobre todo con el orden de los elementos y los atributos obligatorios.