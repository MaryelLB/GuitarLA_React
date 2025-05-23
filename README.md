# 🎸 GuitarLA - Tienda de Guitarras con React

[![React Version](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![Vite Version](https://img.shields.io/badge/Vite-4.0.0-purple.svg)](https://vitejs.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Demo](https://img.shields.io/badge/🚀_Live_Demo-FF6B00?style=flat&logo=vercel)](https://jade-pony-251be1.netlify.app/)

Un e-commerce moderno de guitarras desarrollado con React, que incluye catálogo de productos, blog musical y carrito de compras.

![image](https://github.com/user-attachments/assets/835f404d-c506-42cb-af05-f6f3afb89eff)

## ✨ Características principales

- 🛒 **Sistema de carrito de compras** completo
- 📦 Catálogo de productos con filtrado
- ✍️ Sección de blog con artículos musicales
- 🚀 Rendimiento optimizado con Vite
- 📱 Diseño 100% responsive
- 🎨 Animaciones CSS fluidas
- 🔄 Estados de carga y manejo de errores

## 🛠 Stack tecnológico

### Frontend
- **React 18** - Biblioteca principal
- **Vite** - Bundler y entorno de desarrollo
- **React Router v6** - Navegación SPA
- **Context API** - Gestión de estado global
- **CSS Modules** - Estilos componentizados
- **Custom Hooks** - Lógica reutilizable

### Backend (Mock)
- **JSON Server** - API simulada
- **Axios** - Peticiones HTTP

## 🏗 Estructura del proyecto

```bash
src/
├── assets/            # Imágenes y recursos estáticos
├── components/        # Componentes reutilizables
│   ├── Guitarra.jsx   # Componente de producto
│   ├── Post.jsx       # Componente de artículo de blog
│   ├── Layout.jsx     # Layout principal
│   └── ...           # Otros componentes
├── context/           # Contextos globales
│   └── CarritoContext.jsx
├── hooks/             # Custom hooks
│   ├── useGuitarras.js
│   └── usePosts.js
├── pages/             # Vistas/páginas
│   ├── Inicio.jsx
│   ├── Blog.jsx
│   ├── Tienda.jsx
│   └── ...
├── styles/            # Estilos CSS Modules
│   ├── global.css
│   ├── guitarras.module.css
│   └── ...
├── App.jsx            # Componente raíz
└── main.jsx           # Punto de entrada
