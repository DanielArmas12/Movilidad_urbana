# Movilidad Urbana

**Equipo 12**
- Daniel Jose Armas Azar
- Vladimir Piñera Reyes

## Descripción del proyecto

Este proyecto busca dar una solución al problema de movilidad urbana en México. Durante las últimas décadas ha existido un incremento alarmante en el uso de automóviles: los kilómetros recorridos en coche se triplicaron entre 1990 y 2010, aumentando impactos negativos como el smog, los accidentes, las enfermedades y la congestión vehicular. A través de este proyecto buscamos reducir la congestión vehicular simulando gráficamente el tráfico con un sistema multiagentes.

## Estrategias evaluadas

Como equipo, buscamos representar una estrategia que ataque directamente la congestión vehicular. Las opciones que estamos evaluando son:

- **Asignación de estacionamientos:** se busca controlar y asignar los espacios disponibles en una zona de la ciudad con un modelo de precio dinamico, para que los coches no tengan que dar múltiples vueltas buscando un lugar y donde a horas picos el precio es mas caro
- **Implementación de parquímetros:** se busca un sistema de parquímetros que incentive una mayor rotación en el uso de cada cajón, permitiendo que los espacios se liberen y ocupen con mayor frecuencia en lugar de permanecer ocupados por periodos prolongados
- **Vehículo compartido:** se busca compartir el vehículo con otras personas, reduciendo así la cantidad de vehículos en las calles
- **Semáforos coordinados:** se busca que los semáforos ajusten sus tiempos según la cantidad de coches que están pasando por un lado o esperando del otro junto con un aprendizaje adaptativo donde ajustan patrones según hora del día e histórico
- **Carriles reversibles:** se busca modificar temporalmente el sentido de algunos carriles según su flujo. Si en un sentido el flujo es bajo y en el otro hay tráfico, se habilitaría un carril extra para reducir la congestión

## Metodología

El reto se resuelve en 4 etapas:

1. Modelación de agentes
2. Modelación gráfica en tres dimensiones
3. Interacción entre agentes
4. Animación gráfica en tres dimensiones

La solución se modela con un sistema multiagentes y una visualización 3D, donde cada agente puede percibir, decidir y actuar sobre su entorno.
