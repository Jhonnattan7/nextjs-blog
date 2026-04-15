# Portafolio y Blog en Next.js

Este repositorio contiene el proyecto final del tutorial oficial de Next.js, desarrollado como practica para la materia Desarrollo Web II y con el objetivo de ser desplegado en Vercel.

## Descripcion del Proyecto

Es un sitio web de presentacion personal combinado con un blog generado estaticamente. El contenido de las publicaciones se gestiona mediante archivos de texto Markdown locales, los cuales son convertidos a HTML en el proceso de construccion de la aplicacion.

## Tecnologias y Herramientas

- Framework Principal: Next.js (con React)
- Estilos: CSS Modules y Tailwind CSS
- Procesamiento de contenido: gray-matter y remark (para el analisis de archivos Markdown)
- Fechas: date-fns (formateo de fechas localizado al espanol)

## Caracteristicas Implementadas

- Generacion de Sitios Estaticos (SSG): Utilizacion de getStaticProps para obtener y prerenderizar la lista del blog.
- Rutas Dinamicas: Uso de getStaticPaths para definir y construir las paginas individuales de los posts.
- Optimizacion de recursos: Implementacion del componente next/image para las fotos.
- Rutas API: Endpoint basico e ilustrativo en pages/api.
- Paginas de Error: Pagina 404 estatica completamente personalizada.

## Como ejecutarlo localmente

1. Instalar las dependencias:
   npm install

2. Iniciar el servidor de desarrollo:
   npm run dev

3. Abrir http://localhost:3000 en el navegador.

## Autor

Jhonnatan Peñate
Futuro Ingeniero de Software y Negocios Digitales.
