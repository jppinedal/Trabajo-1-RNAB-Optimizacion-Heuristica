# Redes Neuronales y Algoritmos Bioinspirados

![logoUN](https://github.com/user-attachments/assets/6a75b35f-c2f7-425e-8a39-6d1384be3244)

Semestre 2024-2S

> [!NOTE]  
> [Enlace al informe completo](https://candy-monkey-1cd.notion.site/Redes-Neuronales-y-Algoritmos-Bioinspirados-Optimizaci-n-Heur-stica-1897a8b98a19807ca935c1f93c771812)

# Optimización Heurística

## Descripción
En este proyecto buscamos comparar diferentes métodos de optimización, tanto tradicionales como heurísticos, se abordan dos tipos de problemas principales:

### Objetivos
1. Analizar el rendimiento de diferentes métodos de optimización
2. Comparar métodos tradicionales vs heurísticos
3. Evaluar el impacto de la dimensionalidad en los algoritmos

## 1. Optimización Numérica
Implementación de optimización para dos funciones de prueba:
- Función de Rosenbrock (función del valle)
- Función de Rastrigin (función multimodal)

### Métodos Utilizados
1. **Método Tradicional**
   - Descenso por Gradiente

2. **Métodos Heurísticos**
   - Algoritmos Evolutivos
   - Optimización por Enjambre de Partículas
   - Evolución Diferencial

## 2. Optimización Combinatoria
Solución al problema del vendedor viajero (TSP) para las 32 capitales de México.

### Métodos Utilizados
- Algoritmo de Colonia de Hormigas
- Algoritmo Genético

### Factores Considerados
- Tiempo de trabajo del vendedor
- Consumo de combustible
- Costos de peajes
- Distancia total del recorrido

## Conclusiones Generales

### Métodos Heurísticos
- No dependen del cálculo del gradiente
- Son menos propensos a quedar atrapados en mínimos locales
- Mostraron mejor rendimiento general en ambas funciones

### Método de Descenso por Gradiente
- La calidad del resultado depende en gran medida del punto de partida
- Tiende a quedar atrapado en mínimos locales
- Aprovecha la información del gradiente para dirigir la búsqueda
- Eficiente cuando la solución inicial está cerca del óptimo global


## Integrantes:
  - Valentina Ospina Narvaez - vospinan@unal.edu.co
  - Andrés Felipe Parra Naranjo - aparran@unal.edu.co
  - Juan Camilo Torres Arboleda - jutorresar@unal.edu.co
  - Juan Pablo Pineda Lopera - jppinedal@unal.edu.co
