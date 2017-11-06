# Reglas basadas en las oficiales de YII Framework

## General
- Etiqueta de apertura **<?php**.
- Etiqueta de cierre **?>**.
- Siempre tiene que tener cierre, no usar otras variaciones.
- Se evitarán los 'echo' lo máximo posible, y se usará `<?= valor =>`.

## Archivos
- UTF-8.
- Etiquetas de apertura **<?php**.
- Deben usar el final de línea unix **LF**.

## Líneas
- Menos de 120 de longitud.
- Como máximo 80 carácteres.
- No puede haber espacios al final de una línea.
- Espacios de 4 para cada nivel de sangría (no tabulaciones).

## Variables
- Todas en minúsculas.

## Clases
- Declaradas en **StudlyCaps** donde cada palabra comienza por mayúsculas.
- Class constants MUST be declared in all upper case with underscore separators.
- Llaves delimitadora de bloque no debe estar en la misma línea de la declaración, poner las llaves debajo.
- Al crear una clase siempre hay que poner paréntesis aunque no tenga argumentos pasados al constructor.
- Las palabras clave **extends** e **implements** siempre se declaran en la misma línea que el nombre de la clase.

## Métodos
- Nombres declarados en **camelCase**.

## Datos
- Usar la forma abreviada de palabras clave de tipo, es decir, **bool** en lugar de **boolean**, **int** en lugar de **integer**.

## Estructuras de control
- Espacio entre palabra clave y paréntesis.
- No debe hacer espacio entre el parentesis de aperture y cierre y el contenido del mismo.
- Si debe tener un espacio entre el paréntesis de cierre y el corsé de apertura.
- El corsé de cierre debe estar una línea después del cuerpo de instrucciones.

## PHP junto a HTML
- Se usarán las formas alternativas de las estructuras de control.
- Se separará totalmente el HTML del PHP usando etiquetas php independientes en cada línea.

Ejemplo:
```php
<?php for ($i = 1; $i <= 100; $i++): ?>
    <?= $i ?><br/>
<?php endfor ?>
```
