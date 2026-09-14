# NumPy — Análisis de Consumo Energético

Programación 2, Unidad 2, Tema 1. Análisis del consumo eléctrico semanal de los dispositivos de una oficina usando arreglos de NumPy en lugar de bucles.

## Estructura de los datos

Un arreglo bidimensional `consumo` donde cada fila es un dispositivo y cada columna un día de la semana. Del arreglo se inspeccionan sus dimensiones, su forma, el número total de elementos y el tipo de dato almacenado.

## Análisis

| Indicador | Función |
| --- | --- |
| Consumo total semanal | `sum` sobre todo el arreglo |
| Consumo promedio general | `mean` |
| Consumo máximo registrado | `max` |
| Consumo por dispositivo y por día | Agregaciones por eje |

Sobre los resultados se redacta una interpretación del comportamiento del consumo: el total semanal fue de 326,1 kWh con un promedio de 9,32 kWh por registro, y una dispersión alta que revela que unos pocos dispositivos concentran buena parte del gasto.

## Requisitos

```
pip install numpy
```

## Ejecución

Abrir `Guerra_Paul_Tercera_Autonoma.ipynb` y ejecutar las celdas en orden.

---

**Paúl Andrés Guerra Vicuña** · Programación 2 · Ingeniería en Ciencias de Datos e Inteligencia Artificial · Universidad Nacional de Chimborazo (UNACH)
