# Lustre Atelier — Landing de Auto Detailing

Landing page de una sola página para un estudio de **estética automotriz artesanal y de lujo**. Fondo oscuro, acentos dorados, animaciones suaves y diseño adaptable a celular, tablet y escritorio.

## Secciones

- **Navbar** fija con efecto vidrio y menú móvil.
- **Hero** a pantalla completa con zoom lento del fondo, entrada escalonada y contadores animados.
- **Paquetes**: 3 tarjetas de precios; el Tratamiento Cerámico Pro va destacado.
- **Proceso artesanal**: línea de tiempo de 4 pasos, horizontal en escritorio y vertical en móvil, que se dibuja al hacer scroll.
- **Resultados reales**: comparador Antes/Después que se arrastra con mouse, dedo o teclado.
- **Testimonios** de clientes.
- **Reserva**: datos de contacto y formulario con validación.
- **Footer** y botón flotante de WhatsApp.

## Tecnologías

Todo está en un solo archivo `index.html`, sin instalación ni proceso de compilación:

- [Tailwind CSS](https://tailwindcss.com/) (vía CDN)
- Google Fonts: Montserrat e Inter
- [Font Awesome 6](https://fontawesome.com/) (vía CDN)
- JavaScript nativo (`IntersectionObserver`, Pointer Events)

## Verlo en local

Abre `index.html` con doble clic en cualquier navegador moderno.

## Publicarlo con GitHub Pages

1. Sube el repositorio a GitHub.
2. En el repositorio entra a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos la página estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Antes de usarla con clientes reales

Algunos datos del sitio son de ejemplo y hay que reemplazarlos:

- [ ] Número de WhatsApp en la constante `WA_NUMBER` (script del bloque 3).
- [ ] Teléfono, correo, dirección y enlace de Google Maps en la sección **Reserva**.
- [ ] Precios de los paquetes.
- [ ] Testimonios: los nombres y las reseñas son ficticios.
- [ ] Nombre y logo del negocio ("Lustre Atelier").
- [ ] Enlaces a redes sociales en el footer.
- [ ] Fotos del comparador Antes/Después: hoy es la misma imagen con un filtro.
- [ ] El formulario **no envía datos a ningún servidor**: muestra la confirmación y ofrece continuar por WhatsApp. Para recibir las solicitudes, conéctalo a un servicio como Formspree o a un backend propio (busca el `setTimeout` marcado en el script).

## Créditos

Fotografías de [Unsplash](https://unsplash.com/).
