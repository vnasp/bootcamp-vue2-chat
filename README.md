# Web AppWhats

Proyecto desarrollado como desafío del Bootcamp Frontend Developer de Talento Digital para Chile. Simulación de una interfaz de chat estilo WhatsApp donde dos usuarios aleatorios pueden intercambiar mensajes en tiempo real.

> **Nota:** Este es un proyecto académico, no una aplicación de mensajería real.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/chat-vue2-frontend-user/)

## Funcionalidades

- Carga de 2 usuarios aleatorios desde la API Random User
- Interfaz de chat con burbujas de mensaje diferenciadas por color
- Envío de mensajes en tiempo real entre ambos usuarios
- Avatares y nombres dinámicos desde la API
- Diseño responsivo inspirado en WhatsApp

## Tecnologías

- Vue.js 2
- Axios
- TailwindCSS 3
- Random User API

## Estructura

```
src/
├── App.vue            → Layout principal con paneles de usuario y chat
├── main.js            → Punto de entrada
├── assets/
│   ├── css/styles.css → Estilos con Tailwind y clases personalizadas
│   └── img/           → Imágenes de fondo del chat
└── components/
    └── ChatMessages.vue → Componente de mensajes con props
```
