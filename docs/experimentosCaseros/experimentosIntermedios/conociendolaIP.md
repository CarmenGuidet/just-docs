---
layout: default
title: Conocer la IP del Ordenador
parent: Experimentos Intermedios
nav_order: 1
grand_parent: Experimentos Caseros
---

# Conocer la IP del Ordenador

## Descripción del experimento
Este experimento permite a los usuarios identificar la dirección IP de su ordenador utilizando herramientas disponibles en el sistema operativo. La dirección IP es una identificación única que se asigna a cada dispositivo conectado a una red, permitiendo la comunicación entre dispositivos.

### Tema
- **Tema objetivo:** Redes informáticas y comunicación de datos.

### Duración estimada
- **Tiempo de duración del experimento:** Aproximadamente 10 minutos.

### Edades Objetivo
- **Edad recomendada:** A partir de 12 años (con supervisión de un adulto).

### Estándares
- Comprender el concepto de dirección IP.
- Aprender a utilizar herramientas de red básicas en el sistema operativo.
- Reconocer la importancia de la dirección IP en la comunicación de redes.

## Preparación

### Materiales

- Un ordenador con acceso a la red
- Sistema operativo Windows, macOS o Linux

### Recursos de apoyo

- [Fundamentos de redes informáticas]({% link docs/principiosFisicos/redes.md %})

## Instrucciones
### Pasos
#### En Windows:

1. **Abrir el Símbolo del sistema:**

   - Presiona `Win + R` para abrir el cuadro de diálogo "Ejecutar".
   - Escribe `cmd` y presiona `Enter` para abrir el Símbolo del sistema.

2. **Ejecutar el comando para conocer la IP:**
   - En el Símbolo del sistema, escribe `ipconfig` y presiona `Enter`.
   - Busca la sección "Adaptador de red inalámbrica" o "Adaptador Ethernet". La dirección IP se mostrará junto a "Dirección IPv4".

#### En macOS:

1. **Abrir la Terminal:**

   - Ve a `Aplicaciones` > `Utilidades` > `Terminal`.

2. **Ejecutar el comando para conocer la IP:**
   - En la Terminal, escribe `ifconfig | grep inet` y presiona `Enter`.
   - Busca la dirección IP en las líneas que contienen `inet`.

#### En Linux:

1. **Abrir la Terminal:**

   - Dependiendo de la distribución, abre la Terminal desde el menú de aplicaciones o usando `Ctrl + Alt + T`.

2. **Ejecutar el comando para conocer la IP:**
   - En la Terminal, escribe `ifconfig` o `ip addr show` y presiona `Enter`.
   - Busca la sección correspondiente a la interfaz de red (`eth0`, `wlan0`, etc.) y encuentra la dirección IP junto a `inet`.

### Actividades complementarias (opcional)

- **Exploración de IP pública:** Visita un sitio web como `whatismyip.com` para conocer la dirección IP pública asignada por tu proveedor de servicios de Internet (ISP).
- **Comprender la diferencia entre IP pública y privada:** Investiga cómo las direcciones IP privadas se utilizan dentro de redes locales y cómo las direcciones IP públicas permiten la comunicación con dispositivos fuera de la red local.
