# Frontend

Este es el frontend de nuestra aplicación, construido con Next.js y TypeScript.

## Requisitos

- Node.js
- npm

## Instalación

Primero, instale las dependencias del proyecto:

```bash
npm install
```

## Uso

Para iniciar el servidor de desarrollo:

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) en su navegador para ver el resultado.

## Estructura del proyecto

- `pages`: Este directorio contiene todas las páginas de la aplicación. Cada archivo corresponde a una ruta en la URL.
- `components`: Este directorio contiene componentes de React reutilizables.
- `public`: Este directorio contiene todos los archivos estáticos como imágenes.
- `styles`: Este directorio contiene todos los archivos de estilos.

## Pruebas

Para ejecutar las pruebas:

```bash
npm run test
```

## Construcción

Para construir la aplicación para producción:

```bash
npm run build
```

Esto creará una versión optimizada de la aplicación en el directorio `.next`.

## Despliegue

Para desplegar la aplicación, primero debe construirla con `npm run build`, luego puede usar `npm start` para iniciar el servidor de producción.