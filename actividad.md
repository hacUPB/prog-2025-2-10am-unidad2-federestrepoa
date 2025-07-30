# actividad respresentacion de datos mundo digital 
 1 archivo txt:  52,38 KB
 2 datos punto flotante: 21,73 KB
 3 datos enteros: 13,47 KB 

TOTAL: 87,65 KB

1. ¿Por qué las computadoras usan binario?
Porque las computadoras trabajan con circuitos eléctricos que sólo pueden tener dos estados: encendido (1) o apagado (0). Usar el sistema binario facilita representar datos con estos dos estados, haciendo el procesamiento más rápido y confiable.

2. Convierte 10011011 a decimal y hexadecimal:

* Decimal:
   128 + 0 + 0 + 16 + 8 + 0 + 2 + 1 = 155
* Hexadecimal:
  Dividiendo en dos grupos de 4 bits: 1001 y 1011 = 9 y B = 9B

3. ¿Cómo se representa una imagen PNG en disco?
Un PNG es un archivo que guarda la imagen en forma de bytes organizados en bloques llamados chunks. Tiene una cabecera con información como tamaño y color, los datos comprimidos (usando un algoritmo sin pérdida), y un código de verificación para asegurar que no haya errores.

4. ¿Qué pasa si guardas un número mayor que un byte (más de 255) como 300? ¿Cómo lo maneja Python?
Un byte solo puede guardar valores de 0 a 255. Guardar 300 en un byte no es posible sin pérdida. En lenguajes con límite fijo, podría “desbordar” y dar un valor incorrecto. Pero en Python, los enteros pueden crecer sin límite de tamaño (más bytes), así que puedes guardar 300 sin problema, aunque usa más memoria.

