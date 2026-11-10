# AMAC

Bolsa de trabajo para personas mayores de la Asociación de Mayores A.C.

## Integrantes

- **Andrea Díaz de León Arrambide**: creó el repositorio, las variables globales y los archivos CSS base, el header y el footer, la página de mis solicitudes y la página de error 404.
- **Roberta Montalvo**: página de inicio (index) y página de vacantes, con sus estilos.
- **María José Paz**: inicio de sesión, registro de candidato y de su experiencia, registro de empresa con su imagen, y páginas de registro pendiente y confirmado, con sus estilos.
- **Jesica Galeana**: páginas de la empresa (vacantes, sin vacantes, solicitudes recibidas, solicitudes por vacante y publicar vacante) y sus componentes en `componentes.css` y `layout.css`.

## Paleta de colores

- `--color-azul-marino`: #202945
- `--color-coral`: #FF815C
- `--color-gris`: #A8A8A8
- `--color-blanco`: #FFFFFF
- `--color-azul-claro`: #CAE4EF
- `--color-amarillo-claro`: #FDDAAD
- `--color-gris-claro`: #F1EFEE

## Tipografía

- `--fuente-base`: "Atkinson Hyperlegible", system-ui, sans-serif
- `--texto-base`: 1.25rem (1.5rem desde 90rem)
- `--texto-h2`: 1.75rem (2rem desde 90rem)
- `--texto-h1`: 2.25rem (2.5rem desde 90rem)

## Componentes reutilizables

Estructura (`layout.css`)

- `.header`, `.barra`, `.logo`, `.hamburguesa` y `.menu`: encabezado fijo con menú para celular y desktop.
- `.pie`, `.pie-contenido`, `.pie-titulo`, `.pie-lista` y `.pie-enlace`: pie de página.
- `.principal` y `.contenedor`: ancho máximo y márgenes del contenido.
- `.encabezado-pagina` y `.titulo-pagina`: título de cada página.
- `.encabezado-pagina-accion`: título con un botón o una flecha a un lado.
- `.grid`: lista de tarjetas.
- `.herramientas` y `.filtros`: zona del buscador y los filtros.

Componentes (`componentes.css`)

- `.btn` con `.btn-primario`, `.btn-secundario`, `.btn-terciario`, `.btn-contacto` y `.btn-auto`: botones.
- `.botones`: fila de botones.
- `.tarjeta`, `.tarjeta-contenido`, `.tarjeta-acciones` y `.tarjeta-seccion`: tarjetas de vacantes y solicitudes.
- `.estado` con `.estado-pendiente`, `.estado-aceptada`, `.estado-rechazada`, `.estado-revision`, `.estado-cancelada`, `.estado-activa`, `.estado-pausada` y `.estado-cerrada`: etiquetas de estado.
- `.aviso` y `.aviso-info`: mensajes amarillos y azules.
- `.desplegable`: lista que se abre con una flecha.
- `.decision`, `.ocultar-si-decide`, `.mostrar-si-acepta` y `.mostrar-si-rechaza`: botones de aceptar y rechazar sin JavaScript.
- `.campos`, `.campo`, `.campo-completo`, `.opciones` y `.opcion`: formularios.
- `.buscador`: barra de búsqueda.
- `.vacante` y `.vacante-ampliada`: vacante en lista y en detalle.
- `.etiqueta`: etiqueta de categoría.
- `.icono` e `.ilustracion`: íconos e imágenes centradas.
- `.pagina-error`: página 404.


## Video Demo
https://drive.google.com/file/d/1hcQJlLkcX3JcrBFonZCoWHwkV35dDtyS/view?usp=sharing

## Vercel
https://amac-web-eta.vercel.app 

## Capturas

![Lighthouse-solicitudes-vacantes-mobile](capturas/Lighthouse-solicitudes-vacantes-mobile.png)
![Lighthouse-solicitudes-vacantes-desktop](capturas/Lighthouse-solicitudes-vacantes-desktop.png)
![Lighthouse-empresa-sin-vacantes-desktop](capturas/Lighthouse-empresa-sin-vacantes-desktop.png)
![Lighthouse-empresa-sin-vacantes-mobile](capturas/Lighthouse-empresa-sin-vacantes-mobile.png)
![Lighthouse-empresa-vacantes-desktop](capturas/Lighthouse-empresa-vacantes-desktop.png)
![Lighthouse-empresa-vacantes-mobile](capturas/Lighthouse-empresa-vacantes-mobile.png)
![Lighthouse-publicar-vacante-desktop](capturas/Lighthouse-publicar-vacante-desktop.png)
![Lighthouse-publicar-vacante-mobile](capturas/Lighthouse-publicar-vacante-mobile.png)
![Lighthouse-solicitudes-recibidas-mobile](capturas/Lighthouse-solicitudes-recibidas-mobile.png)
![Lighthouse-solicitudes-recibidas-desktop](capturas/Lighthouse-solicitudes-recibidas-desktop.png)
![Experiencia_lighthouse_dektop](capturas/Experiencia_lighthouse_desktop.png)
![crear_cuenta_empresa_lighthouse_fdesktop](capturas/crear_cuenta_empresa_lighthouse_fdesktop.png)
![crear_cuenta_lighthouse_movil](capturas/crear_cuenta_lighthouse_movil.png)
![cuenta_creada_lighthouse_desktop](capturas/cuenta_creada_lighthouse_desktop.png)
![cuenta_empresa_lighthouse_movil](capturas/cuenta_empresa_lighthouse_movil.png)
![cuenta_registrada_lighthouse_movil](capturas/cuenta_registrada_lighthouse_movil.png)
![experiencia_lighthouse_movil](capturas/experiencia_lighthouse_movil.png)
![imagen_empresa_lighthouse_desktop](capturas/imagen_empresa_lighthouse_desktop.png)
![imagen_empresa_lighthouse_movil](capturas/imagen_empresa_lighthouse_movil.png)
![inicio_sesion_desktop_lighthouse](capturas/inicio_sesion_desktop_lighthouse.png)
![inicio_sesion_lighthouse_movil](capturas/inicio_sesion_lighthouse_movil.png)
![lighthouse-index-movil](capturas/lighthouse-index-movil.png)
![lighthouse-index-desktop](capturas/lighthouse-index-desktop.png)
![lighthouse-vacantes-movil](capturas/lighthouse-vacantes-movil.png)
![lighthouse-vacantes-desktop](capturas/lighthouse-vacantes-desktop.png)
![lighthouse-vacantes-movil](capturas/lighthouse-vacantes-movil.png)
![lighthouse-vacantes-desktop](capturas/lighthouse-vacantes-desktop.png)
![mis-solicitudes(desktop-analisis)](capturas/mis-solicitudes(desktop-analisis).png)
![mis-solicitudes(movil-analisis)](capturas/mis-solicitudes(movil-analisis).png)

![recibimos_tu_registro_lighthouse_desktop](capturas/recibimos_tu_registro_lighthouse_desktop.png)
![registro_lighthouse_desktop](capturas/registro_lighthouse_desktop.png)
![registro_recibido_lighthouse_movil](capturas/registro_recibido_lighthouse_movil.png)

### index.html en celular
![index-movil](capturas/index-movil.png)

### index.html en desktop
![index-desktop](capturas/index-desktop.png)


### index.html en celular
![index-desktop](capturas/index-desktop.png)
