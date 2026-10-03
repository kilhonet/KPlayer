# KPlayer

**Un reproductor de vídeo gratuito y limpio, sin anuncios.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, prevalece la [versión en coreano](README.ko.md).

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Source](https://img.shields.io/badge/source-GPL--2.0--or--later-lightgrey)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kplayer?lang=es)

![Captura de pantalla de KPlayer](images/kplayer-en.webp)

## Descripción general

KPlayer es un reproductor de vídeo y música sin anuncios ni elementos superfluos. Está basado en el motor multimedia de código abierto **libmpv**, así que reproduce directamente 38 formatos — 23 de vídeo, 12 de audio y 3 de listas de reproducción — sin instalar ningún códec.

En la ventana solo se ve el vídeo; los controles aparecen abajo únicamente cuando mueves el ratón. Suelta un archivo en la ventana y empieza a reproducirse, y cuando abres un episodio de una serie, los siguientes episodios de la misma carpeta se añaden a la lista en orden.

Todos los atajos de teclado y las acciones del ratón se pueden cambiar a tu gusto, y los subtítulos se pueden personalizar al detalle: fuente, color, contorno y posición.

## Funciones

- **38 formatos** — 23 formatos de vídeo, entre ellos MP4, MKV, AVI, MOV, WMV, WebM, TS, M2TS, VOB y RM/RMVB; 12 formatos de audio, entre ellos MP3, FLAC, AAC, M4A, WAV, OGG, Opus, WMA, APE y DSF; y 3 formatos de lista de reproducción (M3U, M3U8, PLS).
- **Sin códecs que instalar** — incluye todo lo necesario para reproducir.
- **Aceleración por hardware** — reproduce con fluidez incluso vídeo de alta resolución.
- **Arrastrar y soltar** — suelta en la ventana principal para sustituir la lista y reproducir al instante, o en la ventana de la lista de reproducción para añadir a la lista. Si sueltas una carpeta, solo se añaden sus archivos multimedia.
- **Siguientes episodios añadidos automáticamente** — al abrir un archivo, los archivos relacionados de la misma carpeta (Episodio 1, Episodio 2…) se añaden a la lista en orden.
- **Lista de reproducción** — reordenar arrastrando, repetición (todo o uno), reproducción aleatoria, y la lista se recuerda al cerrar el programa.
- **Subtítulos** — mostrar/ocultar, cambio de pista, fuente, tamaño, color, negrita, contorno, sombra, posición y alineación, y selección automática del idioma de subtítulos según el idioma de visualización de Windows.
- **Control de reproducción** — saltos entre capítulos, avance fotograma a fotograma, velocidad (0.25×–4.0×), capturas de pantalla (JPG/PNG).
- **Panel de información** — pulsa `TAB` para ver de un vistazo los datos del archivo, el códec, la resolución, los fotogramas y el audio.
- **Normalización de volumen** — reduce la diferencia entre los sonidos bajos y los altos (intensidad ajustable).
- **Atajos y ratón personalizables** — asigna teclas a 30 acciones y elige qué hacen el clic, el doble clic, el botón central y la rueda.
- **Asociaciones de archivos** — registra las extensiones una por una en la configuración y abre directamente el selector de aplicaciones predeterminadas de Windows.
- **Aspecto limpio** — ventana oscura sin bordes, siempre visible, recuerda la posición y el tamaño de la ventana.

## Descarga / Instalación

| Paquete | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/kplayer?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/kplayer?lang=es&nosetup) |

Para la versión portátil, descomprime el ZIP donde quieras y ejecuta `KPlayer.exe`.

Al terminar la instalación, el instalador asocia a KPlayer los archivos más comunes, como MP4, MKV, AVI, MOV, WMV, WebM, TS, MP3, FLAC, M4A y WAV. La versión portátil no toca las asociaciones; si las necesitas, regístralas tú mismo en Configuración → **Asociaciones**.

## Uso

### Primeros pasos

1. Al iniciar KPlayer aparece la pantalla de inicio con el **logotipo de KPlayer** en el centro.
2. Arrastra un archivo de vídeo o de música a la ventana. También puedes hacer clic en el logotipo o pulsar `Ctrl+O` para elegir un archivo.
3. La reproducción empieza al instante. Mueve el ratón y los controles aparecen abajo; déjalo quieto un momento y desaparecen.
4. `Space` pausa, `←` `→` saltan 5 segundos, `↑` `↓` ajustan el volumen. `Enter` o un doble clic pasan a pantalla completa, y `ESC` vuelve atrás.
5. El botón de lista de reproducción abajo a la derecha abre la ventana de la lista, y el botón del engranaje junto a él abre la configuración.

### La ventana

**Ventana de reproducción**

| Elemento | Qué hace |
|---|---|
| Barra superior | Nombre del archivo en reproducción. A la derecha: chincheta (siempre visible) · minimizar · pantalla completa · cerrar |
| Barra de progreso | Haz clic o arrastra para desplazarte. Al pasar el ratón, un globo muestra el tiempo en ese punto; si el archivo tiene capítulos, aparecen sus marcas |
| ⏮ ▶ ⏭ | Archivo anterior / reproducir-pausa / archivo siguiente |
| Altavoz | Haz clic para silenciar. Al pasar el ratón se despliega la barra de volumen |
| Tiempo | Posición actual / duración total |
| Subtítulos | Mostrar/ocultar subtítulos — solo aparece en archivos con subtítulos |
| Engranaje | Configuración |
| Lista | Abrir/cerrar la ventana de la lista de reproducción |

Arrastra cualquier parte de la ventana para moverla y arrastra un borde para cambiar su tamaño. Al cambiar el volumen o la velocidad, el nuevo valor se muestra un momento en el centro de la pantalla.

**Menú contextual (clic derecho)**

| Menú | Qué hace |
|---|---|
| Abrir archivo / Abrir carpeta | Elegir un archivo o una carpeta, añadirlo a la lista y reproducirlo |
| Tamaño de pantalla | 50% · 100% · 150% · 200% del tamaño del vídeo, Pantalla completa, Pantalla completa (estirada) |
| Creado por Kilho | Abre el sitio web |

**Ventana de la lista de reproducción**

| Botón | Qué hace |
|---|---|
| Repetir | Cada pulsación alterna Sin repetición → Repetir todo → Repetir uno |
| Aleatorio | Activa/desactiva la reproducción aleatoria |
| + | Añadir — Archivo / Carpeta |
| − | Eliminar — Archivos seleccionados / Archivos no seleccionados / Todo / Archivos ausentes |

Haz doble clic en un elemento para reproducirlo; la tecla `Delete` quita de la lista los elementos seleccionados (los archivos no se borran). El elemento en reproducción se muestra en otro color.

### Cómo…

**Ver una serie en orden desde el episodio 1**
Basta con abrir un episodio. KPlayer busca en la misma carpeta los archivos cuyo nombre continúa con un número (`Episodio 1`·`Episodio 2`, `S01E01`·`S01E02`, etc.) y los añade a la lista en orden numérico — `2` va antes que `10`. Si abres el episodio 3, la lista empieza en el episodio 1, pero la reproducción empieza en el episodio 3.
- Al abrir un vídeo no se cuelan los archivos de música de la misma carpeta, y al abrir música no se cuelan los vídeos.
- Para añadir todos los archivos del mismo tipo de la carpeta, pon Configuración → **General → Añadir archivos de la carpeta** en **Todos los archivos**; para añadir solo el archivo que abriste, ponlo en **Desactivado**.

**Empezar una lista nueva / añadir al final de la lista**
Si sueltas archivos en la **ventana principal**, la lista actual se vacía y se sustituye por los archivos soltados, que empiezan a reproducirse al instante. Si los sueltas en la **ventana de la lista de reproducción**, la lista actual se conserva, se añaden al final y la reproducción empieza por el primero añadido. Un archivo que ya está en la lista nunca se añade dos veces.

**Añadir una carpeta entera**
Arrastra una carpeta a la ventana o haz clic derecho → **Abrir carpeta**. KPlayer busca también en las subcarpetas y añade a la lista solo los archivos que puede reproducir; las imágenes, los documentos y otros archivos se descartan automáticamente.

**Abrir varios archivos desde el Explorador**
Selecciona varios archivos en el Explorador y pulsa Enter: todos van a una sola ventana de KPlayer ya abierta, el primer archivo se reproduce y el resto se añade a la lista. Lo que ocurre cuando KPlayer ya está abierto se elige en Configuración → **General → Si ya se está ejecutando**.
- **Reproducir en la instancia abierta** (predeterminado) — el archivo recién abierto se reproduce al instante en la ventana ya abierta.
- **Añadir a la lista abierta** — sigue reproduciendo lo que estabas viendo y solo lo añade a la lista. Útil para ir juntando canciones mientras escuchas música.
- **Permitir varias** — abre una ventana nueva para cada archivo. Sirve para comparar dos vídeos uno al lado del otro.

**Abrir listas de reproducción M3U o PLS**
Abre o suelta un archivo de lista de reproducción y las pistas que contiene se añaden a la lista y se reproducen desde la primera. Funcionan las rutas escritas en relación con la ubicación del archivo de lista, y también las listas guardadas en el Bloc de notas con nombres en otros alfabetos.

**Escuchar música en orden aleatorio**
Activa el botón **Aleatorio** en la ventana de la lista de reproducción. Ninguna pista se repite hasta que se ha reproducido toda la lista; tras una vuelta completa, la lista se vuelve a mezclar y la reproducción continúa. El botón anterior (⏮) retrocede por el orden en que realmente escuchaste. Pasa el ratón sobre el botón para ver una descripción del modo actual.

**Repetir una pista / repetir toda la lista sin fin**
Pulsa el botón **Repetir** en la ventana de la lista de reproducción para cambiar a **Repetir uno** o **Repetir todo**. Repetir uno tiene prioridad aunque la reproducción aleatoria esté activada. Con Sin repetición, la reproducción se detiene al final de la lista con el último fotograma en pantalla.

**Cambiar el orden de la lista**
Agarra un elemento y arrástralo hacia arriba o hacia abajo. Puedes seleccionar varios elementos con `Ctrl` o `Shift` y moverlos a la vez. Si arrastras hasta el borde de la lista, se desplaza sola.

**Mantener en la lista archivos de una memoria USB o una unidad de red**
Al desconectar la unidad, sus archivos no desaparecen de la lista; esos elementos se muestran con su ruta completa. Cuando llega su turno, aparece brevemente el aviso "Archivo no encontrado" en pantalla y KPlayer pasa al archivo siguiente. Al volver a conectar la unidad, los elementos vuelven a mostrarse como antes por sí solos. Para quitar solo los archivos que de verdad ya no existen, usa **− → Archivos ausentes** en la ventana de la lista de reproducción.

**Conservar la lista para la próxima vez**
Con Configuración → **General → Guardar lista** activado (predeterminado), la lista que tenías al cerrar KPlayer vuelve en el siguiente inicio. Aunque inicies KPlayer con doble clic en un archivo del Explorador, se reproduce ese archivo y no la primera pista de la lista anterior. Para empezar siempre con una lista vacía, ponlo en **Desactivado**.

**Activar los subtítulos**
Los subtítulos empiezan desactivados. Al abrir un archivo con subtítulos aparece abajo el **botón de subtítulos**; haz clic en él o pulsa `V`. Los archivos de subtítulos con el mismo nombre que el vídeo (`película.srt`, `película.es.srt`, etc.) se cargan automáticamente.
- Para mostrar siempre los subtítulos, pon Configuración → **Subtítulos → Mostrar subtítulos de forma predeterminada** en **Activado**.
- Si hay varias pistas de subtítulos, cámbialas con `J` / `Shift+J`.
- En los MKV con varias pistas, KPlayer elige primero los subtítulos en el idioma de visualización de Windows y, si no los hay, en inglés. Si prefieres otros idiomas, escríbelos en el orden que quieras en **Idiomas de subtítulos preferidos**, por ejemplo `ja,jpn,en,eng`.

**Hacer los subtítulos más legibles o cambiar su tamaño y posición**
En Configuración → **Subtítulos** puedes cambiar el tamaño, la fuente, la negrita, el color del texto, el grosor y el color del contorno, la sombra, la posición vertical y la alineación. Los cambios se ven al instante en la reproducción, así que puedes ajustarlos mientras miras. Para bajar los subtítulos a la franja negra bajo el vídeo, ajusta **Posición vertical**.
Para los subtítulos con efectos y estilos (ASS), como los de karaoke, pon **Estilo del archivo de subtítulos** en **Activado** y se verán como los define el archivo de subtítulos.

**Ver clases y reuniones más rápido**
`C` acelera 0.1×, `X` ralentiza, `]` / `[` cambian la velocidad un 10% y `Z` vuelve a 1.0×. El rango va de 0.25× a 4×, y cada vez que la cambias, la velocidad actual aparece un momento en el centro de la pantalla.

**Encontrar la escena exacta**
`Shift+←` / `Shift+→` se desplazan exactamente 1 segundo, y `,` / `.` avanzan o retroceden un fotograma. En los vídeos con capítulos, `Ctrl+←` / `Ctrl+→` saltan entre capítulos, y los capítulos también se marcan en la barra de progreso.

**Guardar una escena como imagen**
Pulsa `S` y la escena actual se guarda en el **Escritorio** con un número añadido al nombre del archivo, como `video.mp4-0001.jpg`. Cambia la carpeta y el formato (JPG/PNG) en Configuración → **General → Carpeta de capturas / Formato**. Elige PNG para guardar sin pérdida de calidad.

**Ver en una ventana pequeña mientras trabajas**
Pulsa el botón de la **chincheta** en la barra superior y la ventana queda siempre por encima de las demás (también la ventana de la lista de reproducción). Reduce la ventana al tamaño que quieras y déjala en una esquina de la pantalla. Con clic derecho → **Tamaño de pantalla → 50%** la reduces de golpe a la mitad del tamaño del vídeo.

**Elegir el tamaño de la ventana al abrir un vídeo**
Elígelo en Configuración → **General → Tamaño de ventana al reproducir**.
- **Mantener el último tamaño** (predeterminado) — el tamaño que usas siempre.
- **Ajustar al vídeo** — ajusta la ventana al tamaño original de cada vídeo. Si es mayor que la pantalla, la reduce para que quepa manteniendo la proporción.
- **Pantalla completa** — empieza en pantalla completa en cuanto se abre un vídeo.

La posición y el tamaño de la ventana se recuerdan al cerrar KPlayer, y si ese monitor se ha desconectado, la ventana se abre en una pantalla visible.

**Llenar la pantalla con un vídeo de otra proporción**
Con clic derecho → **Tamaño de pantalla → Pantalla completa (estirada)** el vídeo se estira a todo el monitor sin franjas negras. Al salir de pantalla completa vuelve a la proporción original. Si lo usas a menudo, asigna el doble clic a **Pantalla completa estirada / restaurar** en Configuración → **Ratón**.

**Igualar el volumen que cambia de un vídeo a otro**
La **normalización de volumen** está activada por defecto: sube los diálogos bajos y reduce los efectos fuertes. Para reducir más la diferencia, pon Configuración → **Audio → Intensidad de normalización** en **Alta**; para oír el sonido original, pon **Usar normalización de volumen** en **Desactivado**. El volumen al iniciar se define en **Volumen predeterminado**.
Si subes el volumen mientras está silenciado, el silencio se quita automáticamente.

**Desplazarse con la rueda en lugar de cambiar el volumen (cambiar las acciones del ratón)**
En Configuración → **Ratón**, elige una función para Clic simple botón izquierdo, Doble clic botón izquierdo, Clic botón central, Rueda arriba y Rueda abajo. Por ejemplo, pon la rueda en **Avanzar / Retroceder**, el clic simple en **Reproducir/Pausa** y el botón central en **Reproducir siguiente archivo**.

**Usar las teclas a las que estás acostumbrado**
En Configuración → **Atajos**, elige una acción, haz clic en el cuadro de abajo y pulsa la tecla (o combinación de teclas) que quieras. **Borrar** quita una tecla y **Atajos predeterminados** restaura los originales. También puedes asignar teclas a **Lista de reproducción**, **Configuración** y **Siempre visible**, que no tienen tecla por defecto. Los atajos predeterminados son:

| Tecla | Acción |
|---|---|
| `Space` | Reproducir/Pausa |
| `Enter` | Pantalla completa (`ESC` para salir) |
| `←` / `→` | Retroceder 5 s / Avanzar 5 s |
| `Shift+←` / `Shift+→` | Retroceder 1 s (exacto) / Avanzar 1 s (exacto) |
| `Ctrl+←` / `Ctrl+→` | Capítulo anterior / Capítulo siguiente |
| `,` / `.` | Fotograma anterior / Fotograma siguiente |
| `↑` / `↓` | Volumen +5 / −5 |
| `0` / `9` | Volumen +2 / −2 |
| `M` | Silencio |
| `Page Up` / `Page Down` | Archivo anterior / Archivo siguiente |
| `V` | Mostrar/ocultar subtítulos |
| `J` / `Shift+J` | Siguiente pista de subtítulos / Pista de subtítulos anterior |
| `S` | Captura de pantalla |
| `X` / `C` | Velocidad −0.1 / +0.1 |
| `[` / `]` | Velocidad −10% / +10% |
| `Z` | Velocidad 1.0x |
| `Ctrl+O` | Abrir archivo |
| `TAB` | Panel de información (fijo) |

**Ver los datos del archivo (códec, resolución, tasa de bits)**
Pulsa `TAB` durante la reproducción para ver en una sola pantalla el nombre, el formato y el tamaño del archivo, el códec de vídeo, la resolución y los fotogramas por segundo, si se usa decodificación por hardware, el códec de audio, los canales y la frecuencia de muestreo, la pista de subtítulos y el volumen. Se actualiza cada segundo; pulsa `TAB` otra vez para cerrarlo.

**Abrir los archivos de vídeo con KPlayer al hacer doble clic**
En Configuración → **Asociaciones**, marca las extensiones que quieras. **Tipos principales** marca solo los formatos más usados y **Seleccionar todo** marca los 38; cada extensión se registra en cuanto la marcas. Los archivos registrados por KPlayer reciben un icono propio de su extensión.
En Windows 10 y 11 tienes que elegir tú mismo la aplicación predeterminada, así que junto a las extensiones cuya aplicación predeterminada es otro programa aparece la marca **[Sin aplicar]**. Haz clic en esa marca para abrir directamente el selector de aplicaciones predeterminadas de Windows y elige KPlayer. Con **Abrir la configuración de aplicaciones predeterminadas de Windows** abres la configuración de Windows para cambiarlas todas a la vez.
- Si mueves la carpeta portátil a otro lugar, las asociaciones se ajustan a la nueva ubicación la próxima vez que ejecutes KPlayer.
- Al desinstalar la versión instalada, todas las asociaciones que registró KPlayer vuelven a su estado anterior.

**Restablecer la configuración**
Pulsa **Predeterminados** en la parte inferior de la configuración para devolver todos los ajustes, los atajos y las acciones del ratón a sus valores predeterminados. Las asociaciones de archivos no cambian.

**Ajustar la salida de vídeo a tu tarjeta gráfica**
En Configuración → **Vídeo**, elige **Decodificación por hardware** (Automático (seguro) / Automático / No usar), **Controlador de salida**, **API gráfica** (Automático / Direct3D 11 / OpenGL / Vulkan), **Sincronización de pantalla**, **Escalador** y **Desentrelazado**. En la mayoría de los casos, los valores predeterminados son los mejores. Los ajustes de esta tarjeta se aplican la próxima vez que inicies KPlayer.

## Configuración

Los ajustes se cambian en las tarjetas de la ventana de configuración y se guardan al instante (la tarjeta **Vídeo** se aplica al reiniciar).

| Tarjeta | Elemento | Predeterminado |
|---|---|---|
| General | Modo de repetición · Reproducción aleatoria | Sin repetición · Desactivado |
| | Guardar lista | Activado |
| | Añadir archivos de la carpeta | Solo archivos relacionados |
| | Si ya se está ejecutando | Reproducir en la instancia abierta |
| | Carpeta de capturas · Formato | Escritorio · JPG |
| | Siempre visible | Desactivado |
| | Tamaño de ventana al reproducir | Mantener el último tamaño |
| Vídeo | Decodificación por hardware · Controlador de salida · API gráfica · Sincronización de pantalla · Escalador · Desentrelazado | Automático (seguro) · gpu · Automático · Remuestreo de pantalla · lanczos · Automático |
| Audio | Volumen predeterminado | 100 |
| | Usar normalización de volumen · Intensidad de normalización | Activado · Media |
| Subtítulos | Mostrar subtítulos de forma predeterminada | Desactivado |
| | Tamaño de los subtítulos · Idiomas de subtítulos preferidos | 55 · Idioma de visualización de Windows + inglés |
| | Fuente · Negrita · Color del texto · Grosor del contorno · Color del contorno · Sombra · Posición vertical · Alineación | (Predeterminado) · Desactivado · Blanco · 3 · Negro · 0 · 100 · Centro |
| | Estilo del archivo de subtítulos | Desactivado |
| Asociaciones | Registro por extensión · Selector de aplicaciones predeterminadas | El instalador registra los tipos principales |
| Atajos | Teclas de 30 acciones | Tabla anterior |
| Ratón | Clic simple · Doble clic · Botón central · Rueda arriba/abajo | No hacer nada · Pantalla completa / restaurar · No hacer nada · Subir volumen / Bajar volumen |

La configuración y la lista de reproducción se guardan en la misma carpeta que el programa, así que si mueves la carpeta portátil entera, se van con ella.

El idioma de la interfaz sigue el idioma de visualización de Windows (coreano, inglés, japonés, chino, ruso, italiano, francés, español y árabe; para otros idiomas, inglés).

## Requisitos

- Windows 10 o Windows 11, **64 bits**
- No hay que instalar códecs ni otros componentes.
- La conexión a Internet se usa solo para avisar de versiones nuevas.

## Actualizaciones

KPlayer **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; si decides descargarla, se abre la página de descarga y el programa se cierra. Las versiones nuevas se publican manualmente tras una verificación interna y se anuncian en la [página de KPlayer](https://kilho.net/kplayer). Consulta el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Compilar desde el código fuente

El código es público en [github.com/newkilho/KPlayer](https://github.com/newkilho/KPlayer). Se compila con [Lazarus](https://www.lazarus-ide.org/) 4.x (FPC 3.2.2, Win64) y necesita:

- [LibMPVDelphi](https://github.com/nbuyer/libmpvdelphi) — las unidades de enlace con libmpv
- `laz.virtualtreeview_package` — el paquete Virtual Treeview incluido con Lazarus
- `libmpv-2.dll` junto a `KPlayer.exe` en tiempo de ejecución

Copia `Const-sample.inc` como `Const.inc` y compila con `lazbuild KPlayer.lpi`. Sin embargo, una biblioteca compartida (klib) que se encarga de la comprobación de actualizaciones, la traducción y otras tareas está fuera del repositorio, por lo que el ejecutable no puede compilarse solo con el repositorio.

## Contribuir

Los informes de errores y las sugerencias son bienvenidos mediante GitHub Issues o el [foro](https://kilho.top/forum/qna).

## Licencia

El programa KPlayer es **Freeware**. Úsalo gratis y sin restricciones donde quieras — en casa, en el trabajo, en escuelas y en organismos públicos — y redistribúyelo libremente en cualquier lugar.

El código fuente se publica bajo la **GNU GPL v2 o posterior**. Los componentes de código abierto utilizados, incluido el motor de reproducción libmpv (GPL-2.0-or-later), figuran en `THIRD-PARTY-NOTICES.txt` en la carpeta de instalación.

## Enlaces

- Sitio web: <https://kilho.net/kplayer>
- Código fuente: <https://github.com/newkilho/KPlayer>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
