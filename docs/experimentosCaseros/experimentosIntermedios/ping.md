---
layout: default
title: Verificar la Conectividad a Internet con Ping
parent: Experimentos Intermedios
nav_order: 2
grand_parent: Experimentos Caseros
---

# Verificar la Conectividad a Internet con Ping

## Descripción del experimento

Este experimento enseña cómo utilizar el comando `ping` para verificar la conectividad a Internet y medir el tiempo de respuesta entre tu ordenador y un sitio web.

### Tema
- **Tema objetivo:** Redes informáticas y diagnóstico de conectividad.

### Duración estimada
- **Tiempo de duración del experimento:** Aproximadamente 10 minutos.

### Edades Objetivo
- **Edad recomendada:** A partir de 12 años (con supervisión de un adulto).

### Estándares

- Comprender el uso del comando `ping` en la terminal.
- Aprender a interpretar los resultados del comando `ping`.
- Reconocer la importancia del diagnóstico de conectividad en redes informáticas.

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

2. **Ejecutar el comando `ping`:**
   - En el Símbolo del sistema, escribe `ping www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran el tiempo de respuesta en milisegundos (ms).

#### En macOS:

1. **Abrir la Terminal:**
   - Ve a `Aplicaciones` > `Utilidades` > `Terminal`.

2. **Ejecutar el comando `ping`:**
   - En la Terminal, escribe `ping www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran el tiempo de respuesta en milisegundos (ms).

#### En Linux:

1. **Abrir la Terminal:**
   - Dependiendo de la distribución, abre la Terminal desde el menú de aplicaciones o usando `Ctrl + Alt + T`.

2. **Ejecutar el comando `ping`:**
   - En la Terminal, escribe `ping www.google.com` y presiona `Enter`.
   - Observa los resultados que muestran el tiempo de respuesta en milisegundos (ms).

### Interpretación de los resultados

- **Tiempo de respuesta:** El tiempo que tarda un paquete en ir desde tu ordenador al sitio web y volver. Se mide en milisegundos (ms).
- **Pérdida de paquetes:** Indica si algunos paquetes no llegaron al destino. Una pérdida de paquetes puede señalar problemas de conectividad.

### Actividades complementarias (opcional)

- **Ping a diferentes sitios web:** Repite el comando `ping` con diferentes sitios web (por ejemplo, `ping www.yahoo.com`) para comparar los tiempos de respuesta.
- **Ping a una dirección IP:** Intenta hacer `ping` a una dirección IP específica (por ejemplo, `ping 8.8.8.8` que es un servidor DNS de Google).
- **Exploración del comando `ping`:** Investiga otras opciones del comando `ping`, como limitar el número de paquetes enviados (`ping -c 4 www.google.com` en macOS/Linux) o ajustar el tamaño del paquete.

