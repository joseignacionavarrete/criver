# Criver — Opt-in

Clon estático de la landing de opt-in de [criver.agency/opt-in](https://criver.agency/opt-in).

La página está renderizada del lado del servidor (Nuxt) y es autocontenida: los estilos van en línea, las tipografías se cargan desde Google Fonts y las imágenes desde los CDN públicos originales.

## Estructura

- `index.html` — la página completa.

## Despliegue

Sitio 100% estático. Vercel sirve `index.html` en la raíz sin configuración adicional.

```bash
vercel --prod
```
