# Despliegue en GitHub Pages

## Objetivo

GitHub Pages permite publicar el sitio estático generado por Docusaurus.

## Proceso de despliegue

1. Subir el código a un repositorio de GitHub.
2. Configurar `url` y `baseUrl` en `docusaurus.config.ts`.
3. Crear un workflow de GitHub Actions.
4. Ejecutar `npm run build`.
5. Publicar la carpeta `build/`.

## Comprobaciones

Se comprobará que la portada carga correctamente, los documentos son accesibles y los enlaces y estilos funcionan.

## Actualización

Cada cambio enviado a la rama principal podrá activar el workflow para publicar una nueva versión.

## Resultado esperado

La documentación estará disponible en una URL pública.
