# Backend

Este es el backend de la aplicación construido con NestJS y TypeScript.

## Requisitos

- Node.js
- MongoDB

## Instalación

Primero, instala las dependencias del proyecto:

```bash
npm install
```

## Configuración

Crea un archivo `.env` en la raíz del proyecto y configura las variables de entorno necesarias. Aquí hay un ejemplo de cómo podría verse:

```env
DATABASE_URL=mongodb://localhost:27017/mi-proyecto
```

## Ejecución

Para iniciar el servidor, ejecuta el siguiente comando:

```bash
npm run start
```

El servidor se iniciará en `http://localhost:3000`.

## Pruebas

Para ejecutar las pruebas, usa el siguiente comando:

```bash
npm run test
```

## Despliegue

Para desplegar la aplicación, puedes usar cualquier servicio de hosting que soporte Node.js, como Heroku o AWS.

## Documentación

Para más detalles sobre cómo trabajar con NestJS, consulta la [documentación oficial](https://nestjs.com/).