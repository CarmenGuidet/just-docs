---
layout: default
title: Rastrear la Ruta a un Sitio Web con Traceroute
parent: Experimentos Intermedios
nav_order: 3
grand_parent: Experimentos Caseros
---

# Rastrear la Ruta a un Sitio Web con Traceroute

## Descripción del experimento
Este experimento enseña cómo utilizar el comando `traceroute` (o `tracert` en Windows) para rastrear la ruta que los paquetes de datos toman desde tu ordenador hasta un sitio web. Este comando es útil para diagnosticar problemas de red y entender cómo se enrutan los datos en Internet.

### Tema
- **Tema objetivo:** Redes informáticas y diagnóstico de rutas de datos.

### Duración estimada
- **Tiempo de duración del experimento:** Aproximadamente 10 minutos.

### Edades Objetivo
- **Edad recomendada:** A partir de 12 años (con supervisión de un adulto).

### Estándares
- Comprender el uso del comando `traceroute` (o `tracert` en Windows) en la terminal.
- Aprender a interpretar los resultados del comando para identificar problemas de red.
- Reconocer la importancia del diagnóstico de rutas de datos en redes informáticas.

## Preparación
### Materiales
- Un ordenador con acceso a Internet
- Sistema operativo Windows, macOS o Linux

### Recursos de apoyo
- [Fundamentos de redes informáticas]({% link docs/principiosFisicos/redes.md %})

## Instrucciones
### Pasos
#### En Windows:
1. **Abrir el Símbolo del sistema:**
   - Presiona `Win + R` para abrir el cuadro de diálogo "Ejecutar".
   - Escribe `cmd` y presiona `Enter` para abrir el Símbolo del sistema.

2. **Ejecutar el comando `tracert`:**
   - En el Símbolo del sistema, escribe `tracert www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran cada salto (router) entre tu ordenador y el sitio web.

#### En macOS:
1. **Abrir la Terminal:**
   - Ve a `Aplicaciones` > `Utilidades` > `Terminal`.

2. **Ejecutar el comando `traceroute`:**
   - En la Terminal, escribe `traceroute www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran cada salto (router) entre tu ordenador y el sitio web.

#### En Linux:
1. **Abrir la Terminal:**
   - Dependiendo de la distribución, abre la Terminal desde el menú de aplicaciones o usando `Ctrl + Alt + T`.

2. **Ejecutar el comando `traceroute`:**
   - En la Terminal, escribe `traceroute www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran cada salto (router) entre tu ordenador y el sitio web.

### Interpretación de los resultados
- **Cada salto:** Representa un router en la ruta desde tu ordenador hasta el destino. 
- **Tiempo de respuesta:** El tiempo que tarda un paquete en llegar al router y volver.
- **Asteriscos:** Indican que no se recibió respuesta de ese router, lo que puede ser debido a configuraciones de red que bloquean la respuesta.


### Actividades complementarias (opcional)
- **Traceroute a diferentes sitios web:** Repite el comando `traceroute` con diferentes sitios web (por ejemplo, `traceroute www.yahoo.com`) para comparar las rutas.
- **Traceroute a una dirección IP:** Intenta hacer `traceroute` a una dirección IP específica (por ejemplo, `traceroute 8.8.8.8` que es un servidor DNS de Google).
- **Exploración del comando `traceroute`:** Investiga otras opciones del comando `traceroute`, como ajustar el número máximo de saltos (`traceroute -m 20 www.google.com` en macOS/Linux).
