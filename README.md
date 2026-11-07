# RADAR DE COMPRAS — sitio web inicial

Sitio editorial estático en español, adaptable a móviles y preparado para GitHub Pages.

## Contenido
- Página de inicio y navegación por categorías.
- Diez guías originales de compra en páginas separadas.
- Páginas de quiénes somos, criterios editoriales, aviso de afiliación, privacidad y contacto.
- Diseño adaptable, logotipo vectorial, favicon, sitemap y robots.txt.
- No contiene enlaces comerciales ni enlaces de afiliado ficticios.

## Publicación con GitHub Pages
El repositorio es `pattyruizp-star/radar-de-compras`. El sitio se extrae desde `site-source/` y se publica mediante el workflow `.github/workflows/pages.yml`.

1. Abre **Settings → Pages**.
2. En **Build and deployment → Source**, selecciona **GitHub Actions** y guarda.
3. Abre **Actions → Publish Radar de Compras**.
4. Selecciona **Run workflow** y confirma **Run workflow** en la rama `main`.
5. Cuando el flujo termine correctamente, la dirección del sitio será:

   https://pattyruizp-star.github.io/radar-de-compras/

GitHub indica que el sitio puede tardar unos minutos en quedar visible después del despliegue.

## Antes de solicitar Amazon Associates
- Confirma que todas las páginas están disponibles públicamente y revisa cada guía.
- Configura un correo o canal de contacto real y agrega el perfil Pinterest cuando exista.
- No afirmes pruebas de producto que no hayas realizado.
- No añadas enlaces de afiliado hasta tener autorización y un identificador válido.
- Cuando corresponda, incorpora la declaración requerida por el programa y una divulgación clara junto a cada enlace.
- Comprueba las condiciones vigentes para el país y mercado al que solicites ingresar.

## Edición
El paquete del sitio está guardado en partes Base64 dentro de `site-source/` y se extrae automáticamente durante la publicación. Para editar el contenido, es más práctico trabajar con el ZIP de origen, actualizarlo y volver a cargar el paquete. Los archivos de la web incluyen `index.html`, `styles.css`, `script.js`, las diez guías y las páginas informativas.
