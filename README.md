# Kit de Ventas · Banco Nacional de Costa Rica

Sitio estático de una sola página (`index.html`) con el Kit de Ventas del BNCR.

## Ver en línea

La página se publica mediante **GitHub Pages**. Una vez habilitado Pages en la rama correspondiente, el sitio estará disponible en:

```
https://rblancod.github.io/BNCR/
```

### Cómo habilitar GitHub Pages

1. En GitHub, ir a **Settings → Pages**.
2. En **Build and deployment → Source**, seleccionar **Deploy from a branch**.
3. Elegir la rama (por ejemplo `main` tras hacer merge) y la carpeta `/ (root)`.
4. Guardar. En unos minutos la página estará en línea en la URL anterior.

## Notas

- El archivo `index.html` es autónomo: incluye todos los estilos, scripts y recursos (imágenes/PDF) embebidos en base64.
- El archivo `.nojekyll` evita el procesamiento de Jekyll en GitHub Pages.
