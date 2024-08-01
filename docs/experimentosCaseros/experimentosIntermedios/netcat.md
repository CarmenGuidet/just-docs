---
layout: default
title: Comunicación Entre Dos Ordenadores Usando Netcat
parent: Experimentos Intermedios
nav_order: 4
grand_parent: Experimentos Caseros
---

## Proyecto: Comunicación Entre Dos Ordenadores Usando Netcat

## Descripción del experimento
Este experimento enseña cómo establecer una comunicación entre dos ordenadores en la misma red utilizando la herramienta `netcat` (también conocida como `nc`). `Netcat` es una utilidad de red que lee y escribe datos a través de conexiones de red utilizando los protocolos TCP o UDP. Es útil para pruebas de red, transferencias de archivos y depuración de servicios.

### Tema
- **Tema objetivo:** Redes informáticas, comunicación y transferencia de datos.

### Duración estimada
- **Tiempo de duración del experimento:** Aproximadamente 20 minutos.

### Edades Objetivo
- **Edad recomendada:** A partir de 14 años (con supervisión de un adulto).

### Estándares
- Comprender el uso del comando `netcat` para establecer conexiones de red.
- Aprender a enviar y recibir datos entre dos ordenadores.
- Reconocer la importancia de las herramientas de red en la comunicación y diagnóstico.

## Preparación
### Materiales
- Dos ordenadores conectados a la misma red (pueden ser Windows, macOS o Linux)
- `netcat` instalado en ambos ordenadores (en Linux y macOS generalmente está preinstalado; en Windows, puede descargarse desde [Netcat for Windows](https://eternallybored.org/misc/netcat/))

### Recursos de apoyo
- [Fundamentos de redes informáticas](docs/principiosFisicos/redes.md)
- [Instalación y uso de Netcat](https://www.tecmint.com/netcat-nc-command-examples/)

## Instrucciones
### Pasos

#### Configuración en el ordenador receptor
1. **Abrir la terminal:**
   - En Windows, abre PowerShell.
   - En macOS o Linux, abre la Terminal.

2. **Ejecutar el comando `netcat`:**
   - Escribe `nc -l -p 12345` y presiona `Enter`.
   - Esto abrirá un puerto de escucha (12345) en el ordenador receptor, esperando conexiones entrantes.

#### Configuración en el ordenador emisor
1. **Obtener la dirección IP del ordenador receptor:**
   - En el ordenador receptor, escribe `ipconfig` (Windows) o `ifconfig` (macOS/Linux) en la terminal para encontrar la dirección IP.

2. **Abrir la terminal:**
   - En Windows, abre PowerShell.
   - En macOS o Linux, abre la Terminal.

3. **Ejecutar el comando `netcat`:**
   - Escribe `nc [IP_del_receptor] 12345` y presiona `Enter`.
   - Reemplaza `[IP_del_receptor]` con la dirección IP del ordenador receptor.

#### Enviar un mensaje
1. **En el ordenador emisor:**
   - Escribe un mensaje en la terminal y presiona `Enter`. El mensaje se enviará al ordenador receptor.

2. **En el ordenador receptor:**
   - Observa el mensaje recibido en la terminal.

### Interpretación de los resultados
- **Comunicación exitosa:** Si el mensaje enviado desde el ordenador emisor aparece en la terminal del ordenador receptor, la comunicación fue exitosa.
- **Errores de conexión:** Si hay errores, verifica la dirección IP y asegúrate de que los puertos no estén bloqueados por un firewall.

### Actividades complementarias (opcional)
- **Transferencia de archivos:** Usa `netcat` para transferir archivos entre los ordenadores. En el emisor, usa `nc [IP_del_receptor] 12345 < archivo.txt` y en el receptor, usa `nc -l -p 12345 > archivo.txt`.
- **Explorar otras opciones de `netcat`:** Investiga cómo usar `netcat` para escanear puertos (`nc -z -v [IP] [puerto_inicial]-[puerto_final]`).
- **Simular un servidor y cliente de chat:** Configura `netcat` para simular una comunicación bidireccional entre dos ordenadores.