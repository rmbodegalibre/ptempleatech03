# ptempleatech03
Prueba Técnica EmpleaTech 03 Frontend
Desarrollo Web Frontend – BookVerse (Educación)
Sobre nosotros: BookVerse es una startup que promueve la lectura digital ofreciendo una plataforma amigable, moderna y funcional para usuarios de todas las edades.
Reto técnico: Diseñar una SPA que consuma una API de libros, implemente modo oscuro y tenga navegación por categorías.
Objetivo: Evaluar tu dominio en React, manejo de estados, APIs, estilos y UX básica.

Insumo:

●	API productos - FakeStore

Tecnologías sugeridas:


Mockup (estructura esperada):

●	Header con logo ficticio (color #004080)
●	Cards de productos con imagen, título, precio y botón
●	Toggle modo claro/oscuro
●	Footer con contacto y redes sociales

Colores:

●	Principal: #004080
●	Secundario: #FF6B6B
●	Fondo claro: #F9F9F9 / oscuro: #1E1E1E

Fuente: Montserrat o Roboto

Parte teórica (preguntas abiertas):

1.	¿Qué es el Virtual DOM?
2.	Props vs State en React
3.	Buenas prácticas CSS
4.	¿Cómo implementas accesibilidad (a11y)?
5.	¿Por qué responsividad es importante?

Parte práctica:

●	SPA funcional con consumo de API
●	Navegación interna
●	Tema claro/oscuro
 
Entregables:

●	Repositorio GitHub
●	Deploy en Netlify/Vercel
●	README con instrucciones

## INICIO DE DESARROLLO

1. Inicialmente desde el IDE VSCode sobre Linux Ubuntu 20.04 LTS se crea la estructura del proyecto bajo el directorio "bookverse"
2. Se instala dependencia adicional axios para la API
3. Se instala dependencia adicional react-router-dom para la navegación
4. Se instala dependencia adicional Material-UI para componentes y modo oscuro
5. El comando para esta instalación de dependencias adicionales es:
npm install axios react-router-dom @mui/material @emotion/react @emotion/styled

La estructura de las carpetas es:
src/
├── components/
│   ├── Header.jsx
│   ├── BookCard.jsx
│   ├── Footer.jsx
├── pages/
│   ├── Home.jsx
│   ├── Categories.jsx
├── App.js
├── App.css
├── index.js

## POSIBLES ERRORES
npm ERR! code ENOSPC
npm ERR! syscall write
npm ERR! errno -28
npm ERR! nospc There appears to be insufficient space on your system to complete the operation.

--> Este tipo de errores ocurre cuando el espacio en disco es insuficiente

# Solución
