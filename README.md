<p align="center"><img src="images/banner.png" alt="VeloxDM" width="100%"></p>

<p align="center">Gestor de descargas con segmentación dinámica, colas, planificador, video, BitTorrent y extensión de navegador.</p>

<p align="center"><a href="https://github.com/Softsoto/VeloxDM/releases/latest"><b>Descargar</b></a> · <a href="https://sotomontes.com/#veloxdm">Ver en sotomontes.com</a> · <a href="#cómo-se-usa">Cómo se usa</a> · <a href="#temas">Temas</a> · <a href="#cómo-funciona-por-dentro">Cómo funciona</a> · <a href="#novedades">Novedades</a></p>

| Ficha técnica | |
|---|---|
| **Autor** | Sebastian Sotomontes |
| **Tipo** | Gestor de descargas |
| **Plataforma** | Windows 10 y 11 (64 bits) |
| **Versión** | 0.6.0 |
| **Estado** | Funcional |
| **Stack** | C# · .NET 10 · WebView2 |
| **Precio** | Gratis |
| **Código** | Privado. El instalador se obtiene desde Releases. |

---

## Qué es

VeloxDM es un gestor de descargas para Windows pensado para bajar archivos grandes sin perder el progreso. Divide cada descarga en varias conexiones que trabajan en paralelo y, cuando una termina, ayuda a la más lenta para que el total baje lo más rápido posible. Reanuda después de un corte de internet, un reinicio o un apagón, sin empezar de cero.

Además de archivos normales por **HTTP, HTTPS y FTP**, baja **vídeo** de YouTube y más de mil sitios (con la calidad que elijas), **torrents**, y **paquetes de enlaces** de sitios de alojamiento. Se integra con tu navegador mediante una extensión, así que las descargas se capturan solas —con su sesión, cookies y referer— sin que tengas que copiar nada a mano.

<p align="center"><img src="images/captura.jpg" alt="Captura de VeloxDM" width="100%"></p>

## Novedades

**Versión 0.6.0**

- **Diez temas visuales**, cada uno con sus colores, sus iconos de barra y una escena animada en la franja inferior: Clásico, Rock, Años 90, Retro, Synthwave, Sakura, Cyberpunk y tres estilos Rejilla (azul, ámbar y violeta). Los tienes todos más abajo, en [Temas](#temas).
- **Creador de temas**: un editor para hacer el tuyo propio —paleta de colores, tipo de letra, tus propias imágenes como iconos y una imagen o escena de fondo— con vista previa en vivo.
- **MediaFire**: ahora recorre las subcarpetas; cada una entra como su propio paquete.
- Los enlaces de carpeta y las direcciones escritas sin `https://` se reconocen y abren el capturador de enlaces.
- **Guía de la extensión** del navegador al terminar de instalar (Edge, Chrome y Brave).

**Antes**

- Si un sitio exige una verificación, la descarga abre tu navegador para que la resuelvas tú; nada se salta.
- Tabla de 1311 sitios de alojamiento y motores por plataforma.
- Capturador de enlaces propio con complementos por sitio.
- Barra de progreso de vídeo con el tamaño total desde el inicio.

## Cómo se usa

1. Instala VeloxDM y añade la extensión a tu navegador. Desde ese momento las descargas se capturan solas, con su sesión, cookies y referer.
2. Para bajar algo a mano, pulsa **Añadir URL**, pega el enlace y elige carpeta y categoría. En los vídeos eliges también la calidad.
3. Sigue el avance en la ventana principal. Al abrir una descarga ves cómo progresa cada conexión y puedes pausarla o cambiar su velocidad.
4. Agrupa las descargas en **colas** y abre el **planificador** para decidir qué días y a qué horas corren, y qué hacer al terminar.
5. Para muchos enlaces, pega un texto o una página en el **capturador de enlaces**: revisa cuáles siguen vivos y los agrupa en paquetes con su carpeta y contraseña.
6. En **Opciones** configuras límites, cuota de datos, velocidad por horario, proxy, sonidos y control desde el móvil; y en **Opciones → Apariencia** eliges el **estilo** o abres el **creador de temas**.

<p align="center"><img src="images/principal.png" alt="Ventana principal" width="100%"><br><sub>Ventana principal</sub></p>

<p align="center"><img src="images/segmentos.png" alt="Progreso por conexiones" width="100%"><br><sub>Progreso por conexiones</sub></p>

<p align="center"><img src="images/video.png" alt="Elegir calidad de un vídeo" width="100%"><br><sub>Elegir calidad de un vídeo</sub></p>

<p align="center"><img src="images/opciones.png" alt="Límites y horarios" width="100%"><br><sub>Límites y horarios</sub></p>

## Temas

VeloxDM trae diez estilos. Cada uno no solo cambia los colores: también cambia los **iconos de la barra de herramientas** y añade una **escena animada en pixel art** en la parte de abajo de la ventana. El estilo claro u oscuro de Windows se sigue respetando salvo donde el tema fija sus propios colores. Se eligen en **Opciones → Apariencia → Estilo**.

<table>
<tr>
<td width="50%" valign="top"><img src="images/temas/theme-clasico.png" width="100%"><br><b>Clásico</b><br><sub>La interfaz de siempre, limpia, en claro u oscuro según Windows.</sub></td>
<td width="50%" valign="top"><img src="images/temas/theme-rock.png" width="100%"><br><b>Rock</b><br><sub>Negro, hueso y rojo sangre; metal gastado, letra condensada y un concierto con luces y público al fondo.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="images/temas/theme-90s.png" width="100%"><br><b>Años 90</b><br><sub>El escritorio gris de siempre, bordes en relieve y una avioneta con pancarta cruzando el cielo.</sub></td>
<td width="50%" valign="top"><img src="images/temas/theme-retro.png" width="100%"><br><b>Retro</b><br><sub>Los setenta: crema, naranja quemado y mostaza, letra serif, con dunas y un sol a franjas.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="images/temas/theme-synthwave.png" width="100%"><br><b>Synthwave</b><br><sub>Atardecer ochentero en morado, magenta y cian, con sol a franjas y una rejilla en fuga.</sub></td>
<td width="50%" valign="top"><img src="images/temas/theme-sakura.png" width="100%"><br><b>Sakura</b><br><sub>Rosa y ciruela, con un cerezo que deja caer sus pétalos abajo a la derecha.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="images/temas/theme-cyberpunk.png" width="100%"><br><b>Cyberpunk</b><br><sub>Noche de neón bajo la lluvia, con dos siluetas iluminadas sobre la calle mojada.</sub></td>
<td width="50%" valign="top"><img src="images/temas/theme-tronblue.png" width="100%"><br><b>Rejilla azul</b><br><sub>Estilo Tron: negro absoluto, rejilla de luz y dos motos que dejan su estela.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="images/temas/theme-tronamber.png" width="100%"><br><b>Rejilla ámbar</b><br><sub>La misma rejilla Tron, en ámbar incandescente.</sub></td>
<td width="50%" valign="top"><img src="images/temas/theme-tronviolet.png" width="100%"><br><b>Rejilla violeta</b><br><sub>La misma rejilla Tron, en violeta.</sub></td>
</tr>
</table>

### Creador de temas

¿Ninguno te encaja? Haz el tuyo. El **creador de temas** (Opciones → Apariencia → *Crear o editar temas…*) tiene una paleta de 17 colores, esquema claro u oscuro, redondez y tipo de letra; te deja **subir tus propias imágenes** como iconos de cada botón y poner de fondo una **escena integrada o tu propia imagen** (PNG, JPG o GIF animado). «Empezar desde» copia cualquier estilo existente como punto de partida, y todo se ve en una **vista previa en vivo** mientras lo editas. Tus temas aparecen luego junto a los demás en el selector de estilo.

<p align="center"><img src="images/creador.png" alt="Creador de temas" width="100%"><br><sub>Creador de temas con vista previa en vivo</sub></p>

## Funciones

- **HTTP, HTTPS y FTP** con hasta 32 conexiones y segmentación dinámica.
- **Vídeo** de YouTube y más de 1000 sitios, con calidad a elegir, MP4 o solo audio, además de HLS y DASH.
- **BitTorrent**: enlaces magnet y archivos `.torrent`, con selección de archivos.
- **Extensión de navegador** para Chrome, Edge, Brave, Vivaldi y Opera.
- **Colas y planificador** con días, horas y acciones al terminar.
- **Capturador de enlaces** y paquetes con carpeta y contraseña.
- **Después de descargar**: verificación de sumas, descompresión y antivirus.
- **Control desde el móvil** en la red local con PIN.
- **Temas**: diez estilos con iconos y escena animada propios, más un creador para hacer el tuyo.

## Detalles

- Reanuda tras cortes de internet, reinicios o apagones.
- Hasta 32 conexiones por archivo con segmentación dinámica.
- Los archivos por partes se descomprimen solos al terminar, probando tu lista de contraseñas.
- Si un sitio pide una verificación, VeloxDM abre la página para que la resuelvas tú; nada se salta.
- La apariencia es tuya: diez temas de serie y un creador para diseñar los que quieras, sin tocar código.
- Línea de comandos para usarlo desde scripts.

## Cómo funciona por dentro

### Arquitectura

```mermaid
flowchart LR
  EXT["Extensión MV3<br/>Chrome · Edge · Brave"] -->|"native messaging"| NH["NativeHost"]
  NH -->|"tubería con nombre"| APP
  subgraph APP["VeloxDM.exe"]
    UI["Ventanas WinForms + WebView2<br/>www/"] <--> DM["DownloadManager<br/>colas · planificador · límites"]
    DM --> HTTP["Downloader<br/>HTTP/HTTPS segmentado"]
    DM --> FTP["FtpDownloader"]
    DM --> HLS["HlsDownloader<br/>m3u8 · AES-128"]
    DM --> YT["YtDlp<br/>YouTube y +1000 sitios"]
    DM --> BT["TorrentDownloader<br/>MonoTorrent"]
    DM --> RS["RemoteServer<br/>control desde el móvil"]
  end
```

### Estructura

| Ruta | Contenido |
|---|---|
| `src/VeloxDM/Core/Downloader.cs` | Motor HTTP(S): segmentación dinámica, archivo temporal disperso, reanudación |
| `src/VeloxDM/Core/FtpDownloader.cs` | FTP con la misma segmentación (REST) |
| `src/VeloxDM/Core/HlsDownloader.cs` | HLS: variantes, segmentos en paralelo, AES-128, remux a MP4 |
| `src/VeloxDM/Core/YtDlp.cs` | Motor yt-dlp (sondeo de calidades, progreso, unión con ffmpeg) |
| `src/VeloxDM/Core/TorrentDownloader.cs` | BitTorrent (MonoTorrent), límites compartidos con el resto |
| `src/VeloxDM/Core/DownloadManager.cs` | Lista, colas, planificador, velocidad, acciones al terminar |
| `src/VeloxDM/Core/SiteGrabber.cs` | Capturador de sitios |
| `src/VeloxDM/Core/RemoteServer.cs` | Control remoto HTTP en la red local |
| `src/VeloxDM/Core/LinkGrabber.cs` | Capturador de enlaces: análisis de texto y páginas, comprobación, paquetes |
| `src/VeloxDM/Core/Hosters.cs`, `FilePlatforms.cs` | Complementos de sitios y motores de plataformas compartidas |
| `src/VeloxDM/Core/Packages.cs` | Fin de paquete: descompresión, contraseñas y aviso |
| `src/VeloxDM/Core/Themes.cs` | Temas de usuario: paleta, iconos y fondo propios |
| `src/VeloxDM/Core/ClickNLoad.cs` | Receptor Click'n'Load |
| `src/VeloxDM/Core/NativeHost.cs`, `Ipc.cs` | Host de native messaging y tubería con la app |
| `src/VeloxDM/Ui/`, `src/VeloxDM/www/` | Ventanas WinForms + WebView2 y su interfaz HTML/JS (temas, iconos y escenas incluidos) |
| `installer/VeloxDM.iss` | Instalador Inno Setup (por usuario, sin administrador) |

### Cómo captura el navegador

La extensión pausa la descarga en `downloads.onDeterminingFilename` y se la entrega a la app por native messaging con URL, cookies, referer, user-agent y cabeceras. Si la app no responde, reanuda la descarga en el navegador, así nunca se pierde un archivo.

**Créditos:** usa yt-dlp, MonoTorrent y ffmpeg.

---

<sub>© 2026 Sebastian Sotomontes. Todos los derechos reservados.</sub>
