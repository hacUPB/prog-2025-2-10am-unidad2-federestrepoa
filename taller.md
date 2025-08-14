# ejercicio 1: verficacion de pseso aeronave
```
INICIO
    LEER peso_aeronave
    LEER peso_combustible
    LEER peso_carga
    LEER limite_max

    peso_total = peso_aeronave + peso_combustible + peso_carga

    SI peso_total <= limite_max ENTONCES
        ESCRIBIR "Listo para despegar. Peso total = ", peso_total
    SINO
        exceso = peso_total - limite_max
        ESCRIBIR "Excede el límite por ", exceso, " kg. Reducir carga/combustible."
    FIN SI
FIN
```

# ejercicio 2:control de temperatura
```
INICIO
    LEER temperatura
    LEER T_min
    LEER T_seg
    LEER T_crit

    SI temperatura > T_crit ENTONCES
        ESCRIBIR "Peligro: sobrecalentamiento"
    SINO SI temperatura < T_min ENTONCES
        ESCRIBIR "Motor frío – Calentar antes de operar"
    SINO SI temperatura <= T_seg ENTONCES
        ESCRIBIR "Operación normal"
    SINO
        ESCRIBIR "Precaución: cercana a crítico"
    FIN SI
FIN
```
# ejercicio 3: resgistro de altitudes de vuelo 
```
INICIO
    altitudes = lista vacía

    PARA i = 1 HASTA 6 HACER
        ESCRIBIR "Ingrese altitud del minuto ", i*10
        LEER alt
        AGREGAR alt A altitudes
    FIN PARA

    ESCRIBIR "Altitudes registradas (cada 10 min): ", altitudes
FIN

```
# ejercicio 4: deteccion de turbulencias
```
INICIO
    umbral = 1.5   
    aceleración_vertical_en_g 
    turbulencias_detectadas = 0

    PARA segundo = 1 HASTA 120 HACER
        LEER  aceleración_vertical_en_g 
        SI  aceleración_vertical_en_g  > umbral ENTONCES
            ESCRIBIR "Turbulencia detectada en segundo ", segundo
            turbulencias_detectadas = turbulencias_detectadas + 1
        FIN SI
    FIN PARA

    ESCRIBIR "Total de turbulencias detectadas: ", turbulencias_detectadas
FIN
```






