# Club-De-Programación-J-V-2020

      NOTA: Los ejercicios a resolver serán considerados según tu conocimiento previo, es decir de acuerdo al semestre y carrera cursada.

1.- Para resolver un laberinto se deben contemplar las siguientes restricciones:
Se puede avanzar hacia el norte, sur, este u oste del lugar dónde te encuentres siempre y cuando no exista una barrera que te impida el paso. 

      Realizar el pseudocódigo que te permita encontrar la salida de un laberinto.
      (Tomar como referencia el laberinto de la laberinto.jpg, de este mismo repositorio).

2.- Realizar el pseudocódigo que permita encontrar la palabra CAPITANAMERICA
Restricciones:
Iniciar a buscar la palabra en la flecha de color rojo. (Como se muestra en la crucigrama.jpg, dentro de este mismo repositorio).
Contempla los espacios y movimientos disponibles permitidos en la estructura.
Verifica que las letras coinciden con la palabra que se necesita encontrar.
Para encontrar la palabra debes evaluar la letra en cada casilla, las casillas a evaluar deben ser consecutivas ya sea de forma horizontal o vertical, no debes saltar una casilla, y en la forma en que inicias a buscar ya sea horizontal o vertical, cambiará según las letras y casillas disponibles que se vayan presentando. 

      Nota. Es de gran aporte el ejercicio anterior, para ubicar tus posiciones.
      Indicaciones.
      El pseudocódigo debe contemplar que debe iniciar de manera horizontal, de no coincidir las letras en el recorrido, debe tomar un camino diferente.
      Buscar una casilla donde tome otra ruta para buscar la palabra, es decir, cambiar la orientación, según una casilla disponible que  alterne el recorrido, para esto contempla el norte, sur, este u oeste de cada casilla y si es necesario retroceder.
      Para decidir tomar un cambio de dirección evalúa las letras por las que vas avanzando y si algunas coinciden, considera las casillas que se anteponen y/o anteceden.

3.- Dados dos números entre el 1 y el 9, multiplicar ambos números y obtener los números por los cuales al multiplicarlos te da el resultado de la multiplicación inicial.
Ejemplo:

      Números de entrada:    2     y    8
      Resultado de la multiplicación de ambos:   2x8=16
      Datos de salida:  
      2*8
      4*4
      8*2
      16*1
      
4.- Pedir desde teclado n cantidad de números, guardarlos en un arreglo, para después guardar en un segundo arreglo únicamente los números pares. Imprimir ambos arreglos.
      Ejemplo:
      
      Datos de entrada: 1,5,8,4,9,3,2
      Datos de salida: 
            Arreglo original:  [1,5,8,4,9,3,2]
            Aregglo de numeros pares: [8,4,2]
            
5.- En una empresa hay tres cajas de seguridad con un NIP de seguridad de 4 cifras, los NIP se generan solos, únicamente cada usuario debe escribir su nombre completo, y la contraseña se generará de la siguiente manera: 
Dígito 1: Total de letras de su primer nombre.
Digito 2: Lugar que ocupa en el abecedario la primera letra del apellido paterno, si ocupa dos dígitos, selecciona el primero de ellos.
Dígito 3: Total de letras del apellido materno.
Digito 4: Total de palabras que abarca su nombre completo.
Crear 3 NIPs de usuarios diferentes, y mostrar en pantalla el NIP de cada usuario.
Ejemplo:

      Datos de entrada: María Duran León
      Digito 1: Cantidad de letras de María: 5
      Digito 2: Lugar que ocupa en el abecedario la letra D: 4
      Dígito 3: Total de letras del apellido materno: 4
      Dígito 4:  Total de palabras que contiene el nombre: 3
      NIP: 5443
      SALIDA María Duran León  --> NIP:5443


6.- Realizar un programa que escriba en letras los números que contenga de 1 a 3 dígitos.
Tip: Utiliza prefijos, para otorgar los nombres y cualquier estructura que se te facilite.
Ejemplo:

      1-Uno              10-Diez               100-Cien
      2-Dos              12-Doce               101-Ciento uno
      3-Tres             21-Veintiuno          300-Trescientos 
      4-Cuatro           21-treinta y dos      999-Novecientos noventa y nueve
      .......           .....                  1000-mil
      
      
