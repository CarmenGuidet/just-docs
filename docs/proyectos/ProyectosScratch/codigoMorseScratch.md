---
layout: default
title: Conversando en código Morse
parent: Proyectos Scratch
nav_order: 2
grand_parent: Proyectos sobre teleco
---

# Proyecto en Scratch: Conversión de Mensajes a Código Morse

## Descripción del Proyecto
Desarrollar un proyecto donde los usuarios puedan ingresar un mensaje y el programa lo convierta en código Morse, mostrando cómo se enviaban los mensajes en el pasado.

## Objetivos del Proyecto
- Permitir a los usuarios ingresar un mensaje de texto.
- Convertir el mensaje ingresado a código Morse.
- Mostrar el mensaje en código Morse en pantalla.
- Explicar cómo se enviaban los mensajes en código Morse en el pasado.

## Materiales y Recursos Necesarios
- Una cuenta en Scratch (https://scratch.mit.edu/)
- Acceso a un dispositivo con conexión a internet.
- Conocimiento básico del entorno de programación Scratch.

## Pasos para Desarrollar el Proyecto

### 1. Crear un Nuevo Proyecto en Scratch
- Ir a la página principal de Scratch.
- Hacer clic en "Crear" para iniciar un nuevo proyecto.

### 2. Diseñar la Interfaz del Usuario
- **Escenario**: Crear un fondo que represente la temática histórica del código Morse (opcional).
- **Personaje**: Elegir o diseñar un sprite que actúe como el presentador del proyecto.

### 3. Agregar un Campo de Entrada para el Mensaje de Usuario
- Utilizar el bloque "Preguntar [¿Cuál es tu mensaje?] y esperar" para solicitar el mensaje del usuario.
- Guardar la respuesta en una variable, por ejemplo, `mensaje`.

### 4. Crear la Lógica de Conversión a Código Morse
- Crear una lista (array) que contenga las letras del alfabeto y sus correspondientes representaciones en código Morse.
- Crear una función que tome cada letra del mensaje ingresado y la convierta a su equivalente en código Morse.
- Almacenar el resultado en una variable, por ejemplo, `mensajeMorse`.

### 5. Mostrar el Mensaje en Código Morse
- Utilizar el bloque "decir [mensajeMorse] por [2] segundos" para mostrar el mensaje convertido en la pantalla.

### 6. (Opcional) Agregar Sonidos para las Señales Morse
- Incluir sonidos para representar los puntos (.) y guiones (-) del código Morse.
- Reproducir los sonidos correspondientes a medida que se muestra el mensaje.

### 7. Explicación Histórica del Código Morse
- Agregar un sprite o un fondo que explique brevemente la historia y el uso del código Morse en el pasado.
- Utilizar bloques de texto y gráficos para enriquecer la explicación.

### 8. Probar y Refinar el Proyecto
- Probar el proyecto con diferentes mensajes para asegurar que la conversión es correcta.
- Ajustar cualquier error y mejorar la presentación visual del proyecto.
