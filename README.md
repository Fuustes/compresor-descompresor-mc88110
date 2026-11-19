# Compresor/descompresor en ensamblador Motorola 88110

Proyecto de **Estructura de Computadores** (ETSIINF-UPM, curso 2025-26). Es un compresor y descompresor de cadenas escrito en **ensamblador del Motorola 88110**, organizado en subrutinas:

- `LongCad`, `BuscaChar`, `BuscaCoincidenCad`, `BuscaMax`: tratamiento de cadenas.
- `PoneBitA1` y lectura de bits: manejo del mapa de bits.
- `Comprime` y `descomprime`: algoritmo principal.
- `PPAL.88k`: programa principal y macros.

`Memoria.pdf` incluye el diseño, las pruebas y el registro de horas.

## Ejecución
Se necesita el simulador del 88110 de la asignatura (no se incluye en el repositorio). Con él:
```
mc88110.bat PPAL.88k
```

## Autor
Mario Fustes González
