# Manuales de Usuario Interactivos — FLK Developments

**POS Restaurantes · POS Encomiendas · POS Supermercado (Retail)**  
**Versión indicada en los manuales:** 1 · Octubre de 2026

## Descripción general

Este repositorio reúne tres **manuales de usuario interactivos**, desarrollados como páginas web para orientar a los clientes de **FLK Developments** en el uso de sus sistemas POS. Cada manual presenta instrucciones paso a paso, organizadas por módulos, y videos tutoriales que permiten observar los procedimientos descritos.

Los manuales están diseñados para que las personas puedan localizar rápidamente una función, leer las instrucciones y consultar una demostración audiovisual cuando esté disponible. El contenido busca ser claro tanto para usuarios nuevos como para quienes necesitan resolver dudas durante sus tareas habituales.

> **Alcance:** estos archivos son **documentación web de los sistemas POS**, no el código fuente de las aplicaciones que efectúan ventas, pagos, facturación, reservas o movimientos de inventario. Los procedimientos descritos corresponden al contenido de los manuales entregados y pueden requerir ajustes cuando cambie el sistema real.

## Manuales incluidos

| Manual | Módulos | Archivo HTML propuesto |
| --- | ---: | --- |
| **POS Restaurantes** | 15 | `manual-restaurantes.html` |
| **POS Encomiendas** | 18 | `guia-de-encomiendas.html` |
| **POS Supermercado / Retail** | 18 | `guia-de-supermercado.html` |
| **Total** | **51** | Tres páginas de documentación |

### 1. POS Restaurantes

Guía para la administración de las operaciones de un restaurante. Incluye acceso al sistema, componentes de la barra superior, selección de sucursal, **sitio del cliente** y los siguientes módulos:

1. Panel de control
2. Menú
3. Mesas
4. Solicitudes de Mesero
5. Reservaciones
6. Punto de Venta (POS)
7. Órdenes
8. Clientes
9. Personal
10. Ejecutivo de Entregas
11. Pagos
12. Informes
13. Caja
14. Inventario
15. Configuraciones

Entre otros temas, describe la organización de productos y categorías, las mesas y códigos QR, las reservas, la preparación de órdenes, los cobros y las consultas de información del restaurante.

### 2. POS Encomiendas

Guía para los procesos de recepción, documentación, traslado, seguimiento y cobro de encomiendas. Contiene los siguientes módulos:

1. Inicio
2. Facturas / Encomiendas
3. Mi ruta
4. Cierres de envío
5. Caja
6. Cotizaciones
7. Clientes
8. Crédito y cuentas por cobrar
9. Reportes
10. Pendientes de envío a Hacienda
11. Sucursales
12. Cajas
13. Tarifario
14. Rutas
15. Tipos de bulto
16. Impuestos
17. Usuarios
18. Actividad de usuarios

Además, documenta el acceso al sistema, la creación y consulta de guías, la administración de sucursales y rutas, así como procesos de caja y comprobantes electrónicos.

### 3. POS Supermercado / Retail

Guía orientada al punto de venta y a las operaciones de inventario y atención de un comercio minorista. Incluye los siguientes módulos:

1. Inicio y panel de control
2. Punto de venta
3. Proveedores
4. Productos
5. Kardex
6. Existencias
7. Categorías
8. Panel de control de inventario
9. Movimientos de inventario
10. Informes de inventario
11. Cuentas por cobrar
12. Ventas
13. Cotizaciones
14. Clientes
15. Personal
16. Ejecutivo de entregas
17. Pagos
18. Informes

Entre sus procedimientos se encuentran la búsqueda y registro de productos y proveedores, consultas de existencias, movimientos de inventario, ventas y generación de reportes. El manual incluye explicaciones del **Kardex** y de la gestión de stock.

## Funcionalidades comunes de los manuales

- **Índice lateral de navegación:** accesos a las secciones de cada manual.
- **Buscador:** permite filtrar los módulos del índice mediante palabras clave.
- **Tarjetas de tareas:** contienen procedimientos explicados paso a paso.
- **Videos tutoriales:** botones «Ver video» que abren un reproductor en una ventana emergente.
- **Navegación contextual:** resaltado del módulo visible, enlaces para volver al índice y botón de regreso al inicio.
- **Ayuda complementaria:** secciones de solución de problemas, preguntas frecuentes y glosario.
- **Diseño adaptable:** presentación en computadoras y pantallas pequeñas, con reglas CSS para impresión.
- **Identidad visual:** encabezado, logotipo de FLK Developments y pie de página.

La ubicación y cantidad de botones de video dependen de cada página: algunos aparecen asociados a un módulo completo y otros a tareas particulares. **Un botón no garantiza que el MP4 correspondiente ya esté incluido en la carpeta del repositorio.**

## Tecnologías utilizadas

| Tecnología | Uso dentro de los manuales |
| --- | --- |
| **HTML5** | Estructura de las páginas, módulos, tarjetas de instrucciones, botones y cuadros de diálogo. |
| **CSS3** | Colores, tipografía, menú lateral, diseño responsive, animaciones y estilos de impresión. |
| **JavaScript nativo** | Buscador, detección del módulo en pantalla, reproducción de videos y botón de volver arriba. |
| **MP4 / imágenes** | Demostraciones en video, logotipo y favicon, cuando los recursos están disponibles. |

El material revisado no requiere instalar un framework ni una base de datos para mostrar las páginas del manual.

## Organización del repositorio

Dado que los tres manuales forman parte de **un mismo repositorio**, se recomienda mantener **un único README.md en la carpeta principal** y separar los recursos de cada manual en subcarpetas. De esta forma, un archivo `style.css`, un `app.js` o un video llamado `inicio.mp4` no se confunde con el de otra guía.

**Estructura recomendada (organización propuesta, no estructura verificada del repositorio actual):**

```text
manuales-flk/
├── README.md
├── restaurantes/
│   ├── manual-restaurantes.html
│   ├── style.css
│   ├── app.js
│   ├── imagenes/
│   │   ├── logo.png
│   │   └── logoblanco.svg
│   └── videos/
│       └── ... archivos MP4 utilizados por Restaurantes
├── encomiendas/
│   ├── guia-de-encomiendas.html
│   ├── style.css
│   ├── app.js
│   ├── imagenes/
│   │   ├── logo.png
│   │   └── logoblanco.svg
│   └── videos/
│       └── ... archivos MP4 utilizados por Encomiendas
└── supermercado/
    ├── guia-de-supermercado.html
    ├── style.css
    ├── app.js
    ├── imagenes/
    │   ├── logo.png
    │   └── logoblanco.svg
    └── videos/
        └── ... archivos MP4 utilizados por Supermercado
```

> Si actualmente los tres HTML están **directamente en la misma carpeta**, también pueden mantenerse allí; sin embargo, todos hacen referencia a `style.css`, `app.js`, `imagenes/` y `videos/` mediante rutas relativas. Esta organización plana puede crear conflictos entre archivos con el mismo nombre. **No mueva ni renombre archivos en el repositorio sin actualizar sus rutas y comprobar que las tres páginas funcionen.**

### Archivos revisados y nombres recomendados

| Manual | HTML recibido | CSS recibido | JS recibido |
| --- | --- | --- | --- |
| Restaurantes | `manual-restaurantes(1).html` | `style(7).css` | `app(1).js` |
| Encomiendas | `guia-de-encomiendas(1).html` | `style(8).css` | `app(2).js` |
| Supermercado | `guia-de-supermercado.html` | `style (4).css` | `app(3).js` |

Dentro de **cada subcarpeta**, el CSS debe llamarse `style.css` y el JavaScript `app.js`, porque esos nombres están indicados en los HTML. Los HTML pueden conservar su nombre original, aunque es recomendable quitar el sufijo `(1)` para facilitar su identificación.

**Observación de los archivos entregados:** las tres copias de `app.js` tienen el mismo contenido. Los CSS de Encomiendas y Supermercado también coinciden entre sí; el de Restaurantes tiene diferencias. Se mantiene la propuesta de carpetas separadas para evitar depender de que estos archivos siempre sean idénticos. Si el equipo decide compartir un único CSS o JavaScript, tendrá que ajustar las rutas de los tres HTML y probarlos.

## Cómo visualizar los manuales

1. Abra la carpeta del repositorio en **Visual Studio Code** o en el explorador de archivos.
2. Compruebe que cada HTML encuentre su `style.css` y su `app.js`, y que las carpetas `imagenes/` y `videos/` estén en la ubicación indicada por sus rutas.
3. Abra el HTML del manual que necesite en un navegador como Chrome, Edge o Firefox.
4. Utilice el buscador o el índice lateral para llegar al módulo de interés.
5. Lea los pasos correspondientes y seleccione **Ver video** si el tutorial está disponible.

Para trabajar durante la edición puede utilizar **Live Server** en Visual Studio Code. Es opcional y no se necesita un backend para consultar el contenido estático.

## Cómo realizar modificaciones

### Editar textos, pasos y módulos

Abra el archivo HTML del manual correspondiente. Las secciones principales se organizan mediante `<section class="module">` y las instrucciones de cada tarea suelen estar en `<article class="task">`.

- Para corregir una instrucción, modifique el texto dentro de la tarjeta correspondiente.
- Para incorporar un módulo, cree una sección con un `id` único y añada su enlace al menú lateral (`href="#id-del-modulo"`).
- Mantenga actualizado el atributo `data-search`, que permite encontrar la sección desde el buscador.
- Si cambia la cantidad de módulos o tarjetas, actualice los contadores que aparecen en la página.
- Respete las clases, identificadores y enlaces que utiliza JavaScript, salvo que vaya a actualizarlos también.

### Modificar estilos y colores

Abra el `style.css` del manual que desea editar. En el bloque `:root` se encuentran variables como `--azul`, `--azul-boton`, `--texto`, `--fondo` y `--borde`. Cambiar estas variables permite ajustar la apariencia principal sin reescribir todos los estilos. Compruebe el resultado en escritorio y móvil.

### Actualizar imágenes y logotipos

Los HTML revisados hacen referencia al logotipo `imagenes/logo.png` y al favicon `imagenes/logoblanco.svg`. Si se cambia la ubicación, extensión o nombre, deben modificarse también las referencias dentro del HTML.

**Detalle técnico:** el favicon tiene extensión `.svg`, pero algunos HTML lo declaran como `image/png`; al revisarlo puede corregirse a `type="image/svg+xml"`.

### Agregar o sustituir un video

1. Coloque el archivo MP4 en la carpeta `videos/` del manual correspondiente.
2. Localice en su HTML el botón con la clase `video-btn`.
3. Actualice el atributo `data-video` con la ruta y el nombre exactos.
4. Compruebe que el video se abre, reproduce, pausa y cierra correctamente.

Ejemplo:

```html
<button class="video-btn"
        data-title="Punto de venta"
        data-video="videos/pos.mp4"
        type="button">
  ▶ Ver video
</button>
```

Evite cambiar nombres de MP4 sin actualizar los enlaces. Las mayúsculas, los espacios y los guiones de las rutas pueden afectar la reproducción.

### Funciones JavaScript

`app.js` incluye la lógica del buscador, los botones de video, la selección del módulo visible y el botón para subir al inicio. Después de modificar sus selectores o funciones, pruebe **cada uno de los tres manuales** si comparten ese código.

### Actualizar información de contacto

Revise el pie de página de cada HTML. Al modificar teléfonos, correos o redes sociales, actualice tanto el texto visible como el valor del enlace (`href`) correspondiente.

## Solución de problemas

| Situación | Verificación recomendada |
| --- | --- |
| La página se abre sin diseño | Compruebe que el HTML encuentre su archivo `style.css`. |
| No funcionan el buscador o los botones | Revise que `app.js` esté cargando y que los identificadores utilizados existan. |
| Un video no abre o muestra un aviso | Confirme la existencia del MP4, su extensión, su ruta `data-video` y su compatibilidad con el navegador. |
| El logo o favicon no se ve | Verifique las imágenes y las rutas dentro del HTML. |
| Un enlace del índice no lleva al módulo | Confirme que el `href` del enlace coincida con el `id` de la sección. |
| El buscador no encuentra un módulo | Revise el texto de `data-search` de la sección correspondiente. |
| Los cambios no se reflejan | Actualice el navegador sin caché y asegúrese de editar los archivos correctos. |
| El cambio de estilo en un manual afecta a otro | Compruebe si ambos están cargando el mismo `style.css` y separe o ajuste las rutas cuando sea necesario. |

## Mantenimiento y control de calidad

- Mantener una copia de respaldo antes de introducir cambios importantes.
- Conservar una nomenclatura consistente para HTML, CSS, JavaScript, imágenes y videos.
- Verificar que el contenido del manual coincida con la versión vigente del sistema POS.
- Revisar ortografía, claridad de las instrucciones y correspondencia entre narración y acciones mostradas en los videos.
- Probar buscador, navegación, enlaces, reproducción multimedia y botones en las tres páginas.
- Comprobar visualización en computadora y en dispositivos móviles.
- Actualizar la fecha y versión de cada guía cuando se publique una nueva revisión.
- Registrar observaciones y cambios pendientes hasta recibir la revisión y aprobación final correspondiente.

## Estado de la documentación

Este README reúne información de los **tres manuales HTML** y sus archivos CSS y JavaScript entregados para revisión. Las imágenes y los videos se mencionan según las rutas utilizadas en el código, pero no se adjuntaron como colección completa en esta revisión; **su disponibilidad y reproducción deben comprobarse en el repositorio real**.

El material puede requerir nuevos ajustes de contenido, video o presentación de acuerdo con las observaciones que realice el equipo responsable. Por ello, **la existencia de este README no implica que todos los manuales estén aprobados o finalizados**.

## Créditos y uso

**Empresa:** FLK Developments  
**Proyecto:** Manuales de Usuario Interactivos para POS Restaurantes, POS Encomiendas y POS Supermercado (Retail)  
**Versión indicada en los HTML:** 1 · Octubre de 2026

Documentación destinada a facilitar el uso y el mantenimiento de las guías web de FLK Developments. Los archivos proporcionados no especifican una licencia de código abierto; no se presume autorización de redistribución.
