# Refs

Guarda referencias de diseño de cualquier web (Instagram, YouTube, Pinterest, Behance, Dribbble, TikTok, X, Vimeo…) con un clic desde el navegador, y organízalas en colecciones en una app de escritorio.

- Todo se guarda **en tu ordenador**: no hay cuentas ni nube.
- Funciona con **Windows 10 y 11** y con navegadores basados en Chromium: **Brave, Chrome, Edge, Opera, Arc**.
- No descarga vídeos: guarda el enlace y una miniatura. Los de YouTube y Vimeo se reproducen al pasar el ratón.

## Privacidad

Refs no tiene servidores, cuentas ni estadísticas de uso. Lo que guardas (enlaces, notas y miniaturas) se queda en una carpeta de tu ordenador y no se envía a ningún sitio. La extensión solo lee la página que estás guardando, cuando tú lo pides. Las vistas previas de YouTube y Vimeo se reproducen desde esas webs, como cualquier vídeo incrustado.

## Instalar Refs

Son dos piezas: la **app** y la **extensión** del navegador. Las dos se descargan de la página [Releases](../../releases/latest).

### 1. La app

1. En [Releases](../../releases/latest), descarga **`Refs_…_x64-setup.exe`**.
2. Ábrelo. Como la app no tiene firma digital, Windows puede mostrar un aviso azul («Windows protegió su PC»). Pulsa **Más información** y luego **Ejecutar de todas formas**.
3. Sigue el instalador. No pide permisos de administrador.
4. Abre **Refs** desde el menú Inicio. Tiene que estar abierta al menos una vez para que la extensión la encuentre.

### 2. La extensión

1. En [Releases](../../releases/latest), descarga **`Refs-extension-….zip`**.
2. Descomprímelo en una carpeta que no vayas a borrar, por ejemplo `Documentos\Refs-extension`. El navegador la carga desde ahí cada vez que arranca.
3. En la barra de direcciones del navegador, escribe:
   - Brave: `brave://extensions`
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
4. Activa el **Modo de desarrollador** (interruptor arriba a la derecha; en Edge está a la izquierda).
5. Pulsa **Cargar descomprimida** y elige la carpeta del paso 2: la que contiene `manifest.json`.
6. Fija la extensión: pulsa el icono de puzle de la barra del navegador y luego la chincheta junto a **Refs**.

### Comprobar que funciona

1. Abre cualquier post, por ejemplo de Instagram o Behance.
2. Pulsa el icono de Refs en la barra del navegador. Arriba del popup debe salir un punto verde y «Conectado con Refs».
3. Pulsa **Guardar**. La referencia aparece en la app, en **Por revisar**.

También puedes hacer clic derecho sobre una página, un enlace o una imagen y elegir **Guardar en Refs**.

Si el popup dice que no encuentra la app, abre Refs, ve a **Ajustes** y pulsa **Reparar conexión**.

## Usar Refs

- **Por revisar:** todo lo que guardas entra aquí hasta que lo metes en una colección.
- **Colecciones:** arrastra una referencia a una colección, o selecciónala y pulsa `M`.
- **Buscar:** la barra de arriba busca por nombre, nota o enlace. El menú de la derecha filtra por la plataforma de origen.
- **Atajos:** `Ctrl+F` buscar · `M` mover a una colección · `R` marcar como revisada · `Supr` enviar a la papelera · doble clic para abrir el original.
- **Ajustes:** tema (claro, oscuro o el de Windows), arrancar con Windows, la papelera y la carpeta donde están tus referencias.

## Actualizar

Descarga el instalador de la versión nueva y ábrelo: sustituye a la anterior y conserva tus referencias. Si la versión nueva trae extensión nueva, descomprímela en la misma carpeta (sustituyendo los archivos) y pulsa el botón de recargar de Refs en la página de extensiones.

## Desinstalar

Desde **Configuración de Windows → Aplicaciones → Aplicaciones instaladas → Refs → Desinstalar**. El desinstalador ofrece una casilla para borrar los datos de la aplicación: **si la marcas, se borran también todas tus referencias**. Sin marcarla, quedan en `%APPDATA%\com.refs.desktop`.

La extensión se quita desde la página de extensiones del navegador.

## Licencia

Refs es gratuito para uso personal. El código y el diseño son del autor: no se pueden copiar, modificar ni redistribuir sin permiso. Se ofrece tal cual, sin garantía. Detalles en [`LICENSE`](LICENSE).
