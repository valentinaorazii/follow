<?php
 $respuestas = array(
    "Si la belleza fuera un delito, te hubiesen dado cadena perpetua",
     "Hola. Soy un ladrón y lo primero que quiero robar es tu corazón",
     "¿De qué juguetería te escapaste?…",
     "¡Que bombón y yo con diabetes!",
     "Si amarte fuera pecado, tendría el infierno asegurado",
     "Adiós corazón de melón, te espero en la cama sin pantalón",
     "Quisiera ser baldosa para que me pisaras como una diosa",
     "Me gustaría ser aviador para volar en tus sueños",
     "Estoy escribiendo mis memorias, ¿queréis ser parte de mi biografía?"
     );
 $random = array_rand($respuestas);
 echo $respuestas[$random];
?>
