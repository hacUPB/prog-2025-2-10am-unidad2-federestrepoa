# actividad 2 
Inicio
Leer base, altura
Calcular área = (base * altura) / 2
Mostrar área
Fin
Claro, aquí tienes una versión **más corta y sencilla** para tu bitácora:



# Símbolos del Diagrama de Flujo

| Símbolo     | Nombre     | Función                                 |
| --------------- | ---------------- | ------------------------------------------- |
| 🔷 Óvalo        | Inicio / Fin     | Marca el comienzo o el final del algoritmo. |
| ▭ Rectángulo    | Proceso          | Indica una operación o cálculo.             |
| ⬚ Paralelogramo | Entrada / Salida | Leer datos o mostrar resultados.            |
| 🔺 Rombo        | Decisión         | Representa una pregunta con dos opciones.   |
| ➝ Flecha        | Flujo            | Muestra el orden de ejecución.              |

---

Fuente: Normas ANSI e ISO sobre diagramas de flujo.
<img width="233" height="403" alt="image" src="https://github.com/user-attachments/assets/2b40f1a2-a0d4-4f8a-af3e-b47637377d59" />

## Ejercicio 2

Analicemos el siguiente problema y representemos su solución mediante un algoritmo secuencial.

- Construye un algoritmo que, al recibir como datos **el ID** del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.

  ## solucion
```
inicio 
leer id ,s1,s2,s3,s4,s5,s6
total = s1 + s2 +s3 + s4 + s5 +s5 + s6
promedio = total / 6
escribir ID, total, promedio
fin
```
# diagrama de flujo
<img width="222" height="552" alt="ejercicio2 drawio" src="https://github.com/user-attachments/assets/d08e76d5-3eee-4b7e-929c-0669e59c55aa" />

# actividad de casa 

## pseudocodgio 

```

inicio
leer n1, n2, n3, n4, n5, n6
promedio= (n1 + n2 + n3 + n3 + n5 + n6) /6
nota_necesaria = (3.0 - (promedio * 0.7)) / 0.3
escribir "debes sacar" , nota_necesaria, "wn la nota 7 para aprobar con 3.0"
fin

```

## diagrama de flujo 

<img width="934" height="751" alt="image" src="https://github.com/user-attachments/assets/2e3b9264-842f-4de8-b4fe-64262280b525" />

# ejercicio 3 

## analisis

|Variables| Tipo| Comentario|
|---------|-----|----------|
|Lapices  | Entrada| Cantidad de lapices|
|precio  | Salida| Precio total de los lapices|
|Valor_unidad| Intermedia | Valor unitario de cada lapiz|
|85, 90 | Constantes| No cambian|

## pseudo codigo

```
Inicio
Leer lapices
Si lapices >= 1000 Entonces
        valor_unidad = 85
Sino
        valor_unidad = 90
Fin Si

total = lapices * valor_unidad

    Escribir "El valor total es: ", precio
Fin

```



# ejercicio 4

##analisis

|Variables| Tipo| Comentario|
|---------|-----|----------|
| Total_compra | Entrada | Valor de la compra |
| Descuento    | Salida  | Descuento segun el valor de la compra |
| precio-final | Salida | Valora a pagar |
| 15%, 8%, $250000 | Constantes | Descuentos y valor limite |

## pseudocodigo 

```
inicio
leer total_compra
si total_compra > 250000:
     descuento = total_compra * 0.15
si no
      descuento = total_compra * 0.08
fin si
precio_total = total_compra - descuento
escribir "valor a pagar:", precio_final
```
# ejercicio 5

## analisis

|Variables| Tipo| Comentario|
|---------|-----|-----------|
|alumnos | Entrada| Cantidad de alumnos|
|costo_alumno | Salida| Costo segun la cantidad de alumnos|
|costo_total  | Salida| Costo total a pagar|
|100_65$, 50-99_70$, 30-49_95$, 1-30_4000$(sin importar la cantidad de alumnos)| Constantes| cantidad de alumnos y costo por alumno según la cantidad|

## pseudocodigo




# Tarea 

## pseudocodigo

```
INICIO

Entrada de datos
Leer fecha_dia, fecha_mes, fecha_año
Leer nacimiento_dia, nacimiento_mes, nacimiento_año

 Cálculo inicial de la edad
edad = fecha_año - nacimiento_año

 Ajuste si el cumpleaños aún no ha llegado este año
Si (fecha_mes < nacimiento_mes) O (fecha_mes = nacimiento_mes Y fecha_dia < nacimiento_dia) Entonces
    edad = edad - 1
FinSi

 Salida
Mostrar "La edad es: ", edad

FIN
```
## diagrama de flujo
<img width="616" height="643" alt="image" src="https://github.com/user-attachments/assets/accc8be5-eef2-4d69-acee-1687d80a0b93" />


