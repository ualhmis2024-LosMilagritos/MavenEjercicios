# MavenEjercicios

[![Build Status](https://travis-ci.org/ualhmis/mavenEjercicios.svg?branch=master)](https://travis-ci.org/ualhmis/mavenEjercicios)
[![codecov](https://codecov.io/gh/ualhmis/mavenEjercicios/branch/master/graph/badge.svg)](https://codecov.io/gh/ualhmis/mavenEjercicios)
    


Recomendación de proceder en esta práctica:
1. Clona este repositorio en tu PC, y prueba que se construya correctamente en tu Eclipse, ejecutando los goals `clean package`. 
    - Debes configurar correctamente JDK en tu Eclipse tal y como se explica en el guión. Aunque se recomienda JDK8, también funciona con JDK11 y JDK14 (aun no lo hemos validado con JDK13).
    - Para estar seguro de que todo ha ido bien, comprueba que se han ejecutado todos los tests y que en la carpeta `target/site/jacoco` se ha generado el informe de cobertura. 
    - Para comprobar que se generan correctamente los __informes de análisis estático de código__, ejecuta los goals `clean package site`. De esta manera se crea el informe completo `target/site/index.html`. En el enlace _informes del proyecto_ deben aparecer todos.

![alt](images/site-informes-proyecto.png)
    - Si hay errores, el problema es de tu Eclipse: revisa la configuración de JDK.

2. Cuando funcione correctamente, abre el archivo `pom.xml` de este proyecto que tienes clonado y **copia el contenido** completo excepto las primeras lineas, es decir, desde la línea `<properties>` hasta el final, y pégalo en el archivo `pom.xml` de tu proyecto, reemplazando del contenido que tenías por este. Si lo prefieres, ve copiando bloque a bloque de `pom.xml` a medida que se explica en el guión. Pero ten en cuenta: 
    - No es recomendable escribir el código del archivo pom.xml a mano, porque la sintaxis XML es propensa a errores y Eclipse no comprueba gran parte de los errores que puedes cometer.
    - Tampoco es recomendable copiar los bloques de código desde el documento pdf del guión, ya que algunos caracteres no se copian bien del pdf a texto plano (como los guiones '-').

3. Pruébalo poco a poco, es decir, ejecutando  los goals que se indican en cada paso del guión.