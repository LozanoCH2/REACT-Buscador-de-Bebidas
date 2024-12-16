# Buscador de Bebidas - React y TypeScript

Este proyecto es una aplicación web que permite buscar recetas de bebidas basadas en un ingrediente y categoría específicos, proporcionando una experiencia interactiva y organizada. Fue desarrollado con **React** y **TypeScript**, integrando herramientas como **React Router DOM**, **Zod**, y **Zustand** para la gestión del estado, validación y consumo de datos de la API.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Aprendizajes Clave](#aprendizajes-clave)
- [Créditos](#créditos)

---

## Descripción del Proyecto

El **Buscador de Bebidas** permite a los usuarios:

1. **Buscar Bebidas**: Ingresar un ingrediente y seleccionar una categoría para obtener una lista de bebidas que cumplan con estos criterios.
2. **Consultar Detalles de las Bebidas**:
   - Imagen de la bebida.
   - Ingredientes y cantidades.
   - Instrucciones detalladas para la preparación.
3. **Administrar Favoritos**:
   - Agregar bebidas a la sección de favoritos.
   - Eliminar bebidas de los favoritos.
4. **Navegación entre Páginas**:
   - Página principal (**Index**) para buscar bebidas.
   - Página de favoritos (**Favorite**) para consultar las bebidas guardadas.

Este proyecto está conectado a una API de bebidas y utiliza **Zod** para validar y manejar de forma segura la información obtenida. Además, se utilizó **Zustand** para gestionar el estado de la aplicación mediante un enfoque modular basado en "slices".

---

## Tecnologías Utilizadas

- **React**: Biblioteca para la creación de interfaces de usuario.
- **TypeScript**: Tipado estático para mejorar la calidad y seguridad del código.
- **React Router DOM**: Librería para implementar navegación y rutas dentro de la aplicación.
- **Tailwind CSS**: Framework CSS para diseño moderno y responsivo.
- **Axios**: Cliente HTTP para gestionar la conexión con la API de bebidas.
- **Zustand**: Librería para la gestión del estado global con un enfoque modular.
- **Zod**: Herramienta para la creación y validación de esquemas de datos.

---

## Instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/LozanoCH2/REACT-Buscador-de-Bebidas.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd REACT-Buscador-de-Bebidas
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

---

## Funcionalidades

- **Búsqueda de Bebidas**:
  - Filtra bebidas por ingrediente y categoría.
  - Muestra un listado de bebidas con su imagen y nombre.
- **Detalles de Bebidas**:
  - Consulta ingredientes, cantidades, y pasos para preparar la bebida.
- **Gestión de Favoritos**:
  - Agrega o elimina bebidas de la sección de favoritos.
- **Navegación entre Páginas**:
  - Página de inicio para realizar búsquedas.
  - Página de favoritos para consultar las bebidas guardadas.
- **Diseño Responsivo**: Interfaz adaptable a dispositivos móviles y de escritorio.

---

## Aprendizajes Clave

Este proyecto fue una experiencia significativa para mejorar mis habilidades con React y TypeScript, destacando:

1. **React Router DOM**:
   - Implementación de rutas dinámicas y navegación entre múltiples páginas (Index y Favorite).
   - Comprensión del flujo de una SPA (Single Page Application) basada en rutas.
2. **Gestión Modular del Estado con Zustand**:
   - Creación de un store global (`useAppStore`) utilizando un enfoque basado en _slices_.
   - Cada módulo funcional (como búsqueda o favoritos) tiene su propio slice, mejorando la escalabilidad y mantenimiento del código.
   - Uso de Zustand para simplificar la manipulación del estado global sin necesidad de pasar props entre componentes.
3. **Validación de Datos con Zod**:
   - Creación de esquemas para validar datos provenientes de la API.
   - Mejora en la consistencia y seguridad del manejo de la información en la aplicación.
4. **Optimización de la Arquitectura del Proyecto**:
   - Separación de lógica en servicios, validaciones, y componentes para mejorar la organización del código.
   - Modularización del estado para cada funcionalidad específica.
5. **Diseño Moderno y Experiencia de Usuario**:
   - Uso de Tailwind CSS para un diseño atractivo y responsivo.

---

## Créditos

Este proyecto fue desarrollado como parte del curso **React y TypeScript** impartido por **codigoconjuan**. Agradezco al curso por las enseñanzas y el enfoque práctico en el desarrollo con estas tecnologías.

- [Curso de React y TypeScript - codigoconjuan](https://codigoconjuan.com)

---

## Enlace al Proyecto

Puedes probar el proyecto en el siguiente enlace:  
🔗 **[Buscador de Bebidas](https://react-buscadorbebidas.netlify.app)**

---

Este proyecto fue una excelente oportunidad para profundizar en el uso de React Router DOM, Zustand, y Zod, consolidando mi comprensión de cómo manejar rutas y estado global de manera eficiente en aplicaciones React. ¡Espero que disfrutes explorando el buscador de bebidas tanto como yo disfruté desarrollarlo!
