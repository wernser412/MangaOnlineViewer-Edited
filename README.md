# Manga OnlineViewer
## Leer
No es un script originado por mi, solo edito y traduzco el script.

Script original por [TagoDR](https://github.com/TagoDR/MangaOnlineViewer)

## Descripción

Carga todas las páginas de un capítulo en una vista agradable, lo que permite una lectura más rápida y cómoda, sin necesidad de esperar a que se carguen las páginas.


:exclamation: **Atención**: Algunos sitios requieren que vuelva a cargar la página (F5) o abra el capítulo en una nueva pestaña para que se inicie el script.

## Instalación

#### [Link](https://github.com/wernser412/MangaOnlineViewer-edited/raw/main/Manga%20OnlineViewer%20Edited.user.js)


## Navegadores compatibles

Firefox y Chrome con [Tampermonkey](https://tampermonkey.net/) o [Violentmonkey](https://violentmonkey.github.io/).
Otros navegadores con otros complementos también pueden funcionar, pero no son oficialmente compatibles.

### Marcador móvil

_La configuración no se puede guardar, es posible que deba solicitar una página de escritorio_:

Bookmarklet parece funcionar solo en Chrome, abra el capítulo y luego use la barra de búsqueda para activar su bookmarklet.

##### Lector principal:

```JS
javascript:(function(){["https://cdnjs.cloudflare.com/ajax/libs/tinycolor/1.6.0/tinycolor.min.js", "https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/5.0.0/imagesloaded.pkgd.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jszip/3.9.1/jszip.min.js", "https://cdnjs.cloudflare.com/ajax/libs/nprogress/0.2.0/nprogress.min.js", "https://cdnjs.cloudflare.com/ajax/libs/limonte-sweetalert2/11.4.8/sweetalert2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.21/lodash.min.js", "https://cdn.jsdelivr.net/npm/hotkeys-js@3.10.3/dist/hotkeys.min.js", "https://cdn.jsdelivr.net/npm/range-slider-input@2.4.4/dist/rangeslider.nostyle.umd.min.js", "https://cdn.jsdelivr.net/gh/TagoDR/MangaOnlineViewer@latest/dist/Manga_OnlineViewer.user.min.js"].map( s => document.body.appendChild(document.createElement('script')).src=s)})();
```

### Sitios de manga admitidos

- [Batoto](http://bato.to/) _[English]_
- [BilibiliComics](https://www.bilibilicomics.com/) _[English]_
- [Dynasty-Scans](https://dynasty-scans.com/) _[English]_
- [Asura Scans](https://asura.nacm.xyz/) / [Flame Scans](https://flamescans.org/) / [Realm Scans](https://realmscans.com/) / [Voids-Scans](https://void-scans.com/) / [Luminous Scans](https://luminousscans.com/) / [Shimada Scans](https://shimadascans.com/) / [Night Scans](https://nightscans.org/) / [ManhwaFreak](https://manhwafreak.com/) / [OzulScansEn](https://ozulscansen.com/) _[English]_
- [INKR](https://inkr.com/) _[English]_
- [LHTranslation](https://lhtranslation.net/) _[English]_
- [LynxScans](https://lynxscans.com/) _[English]_
- [MangaBuddy](https://mangabuddy.com/) _[English]_
- [MangaDex](https://mangadex.org/) _[English]_
- [MangaFox](https://fanfox.net/) / [MangaHere](https://www.mangahere.cc/) _[English]_
- [MangaFreak](https://mangafreak.net/) _[English]_
- [Mangago](https://www.mangago.me/) _[English]_
- [MangaHub](https://mangahub.io/) _[English]_
- [MangaKakalot](https://mangakakalot.com/page) / [MangaNelo](https://www.manganelo.com/) / [MangaNato](https://www.manganato.com/) _[English]_
- [MangaPark](https://mangapark.net/) _[English]_
- [Mangareader](https://mangareader.to) _[English]_ **Obs: Some galleries will not be usable**
- [MangaSee](https://mangasee123.com/) / [Manga4life](https://manga4life.com/) _[English]_
- [MangaToons](https://mangatoon.mobi/) _[English]_
- [MangaTown](https://www.mangatown.com/) _[English]_
- [ManhuaScan](https://manhuascan.io/) _[English]_
- [MReader](https://www.mreader.co/) / [MangaGeko](https://www.mangageko.com/) _[English]_
- [NaniScans](https://naniscans.com/) _[English]_
- [NineManga](https://ninemanga.com/) _[English]_
- [PandaManga](https://www.pandamanga.com/) _[English]_
- [ReadManga Today](https://www.readmng.com/) / [Funmanga](https://funmanga.com/) / [MangaDoom](https://mngdoom.com/) / [MangaInn](https://www.mangainn.net/) _[English]_
- [ReaperScans](https://reaperscans.com/) _[English]_
- [KLManga](https://tapas.io/) _[English]_
- [TenManga](https://www.tenmanga.com/) _[English]_
- [WebNovel](https://www.webnovel.com/) _[English]_
- [WebToons](https://www.webtoons.com/) _[English]_
- [Manga33](https://manga33.com/) _[English]_
- [ZeroScans](https://zeroscans.com/) _[English]_
- [FoOlSlide](#) / [Kireicake](https://reader.kireicake.com) _[English]_ **Obs: Any Site that uses FoOLSlide**
- [Madara WordPress Plugin](#) / [MangaHaus](https://manhuaus.com) / [Isekai Scan](https://isekaiscan.com/) / [Comic Kiba](https://comickiba.com/) / [Zinmanga](https://zinmanga.com/) / [mangatx](https://mangatx.com/) / [Toonily](https://toonily.net/) / [Mngazuki](https://mangazuki.me/) / [JaiminisBox](https://jaiminisbox.net) / [DisasterScans](https://disasterscans.com/) / [ManhuaPlus](https://manhuaplus.com/) / [TopManhua](https://www.topmanhua.com/) / [NovelMic](https://novelmic.com/) / [Reset-Scans](https://reset-scans.com/) / [LeviatanScans](https://leviatanscans.com/) / [Dragon Tea](https://dragontea.ink/) _[English]_ **Obs: Any Site that uses Madara Wordpress Plugin**
- [Leitor](https://leitor.net/) _[Portuguese]_
- [mangahosted](https://mangahosted.com/) _[Portuguese]_
- [UnionMangas](https://unionleitor.top/) _[Portuguese]_
- [KLManga](https://klmanga.com/) _[Raw]_
- [RawDevart](https://rawdevart.com) _[Raw]_
- [SenManga(Raw)](https://raw.senmanga.com/) _[Raw]_
- [InManga](https://inmanga.com//) _[Spanish]_
- [MangasIn](https://mangas.in/) _[Spanish]_
- [MangaTigre](https://www.mangatigre.net/) _[Spanish]_
- [OlympusScans](https://olympusscans.com/) _[Spanish]_
- [TuMangaOnline](https://lectortmo.com/) _[Spanish]_
- [TuManhwas](https://tumanhwas.com/) _[Spanish]_
- [YugenMangas](https://yugenmangas.lat/) _[Spanish]_

### Sitios de cómics compatibles

- [ComiCastle](http://www.comicastle.org/) _[English]_
- [ReadComicsOnline](http://readcomicsonline.ru/) _[English]_

### Sitios agregados por wernser412

- [Animalsside](https://lectortmo.com/) _[Spanish]_
- [Checkingcars](https://lectortmo.com/) _[Spanish]_
- [Cocinaconlupita](https://lectortmo.com/) _[Spanish]_
- [Feelthecook](https://lectortmo.com/) _[Spanish]_
- [Fitfooders](https://lectortmo.com/) _[Spanish]_
- [Keepfooding](https://lectortmo.com/) _[Spanish]_
- [Lupitaalosfogones](https://lupitaalosfogones.com/) _[Spanish]_
- [Motoroilblood](https://lectortmo.com/) _[Spanish]_
- [recetasdelupita](https://lectortmo.com/) _[Spanish]_
- [Techinroll](https://lectortmo.com/) _[Spanish]_
- [Worldrecipes]( worldrecipesu.com/) _[Spanish]_

### Teclas de acceso directo

-   <span>Desplazarse hacia arriba:</span> <span><kbd class="dark">up</kbd> / <kbd class="dark">W</kbd> / <kbd class="dark">num_8</kbd></span>
-   <span>Desplazarse hacia abajo:</span> <span><kbd class="dark">down</kbd> / <kbd class="dark">S</kbd> / <kbd class="dark">num_2</kbd></span>
-   <span>Siguiente capítulo:</span> <span><kbd class="dark">right</kbd> / <kbd class="dark">/</kbd> / <kbd class="dark">D</kbd> / <kbd class="dark">num_6</kbd></span>
-   <span>Capítulo previo:</span> <span><kbd class="dark">left</kbd> / <kbd class="dark">;</kbd> / <kbd class="dark">A</kbd> / <kbd class="dark">num_4</kbd></span>
-   <span>Agrandar:</span> <span><kbd class="dark">-</kbd> / <kbd class="dark">num_add</kbd> / <kbd class="dark">E</kbd></span>
-   <span>Restaurar:</span> <span><kbd class="dark">=</kbd> / <kbd class="dark">num_subtract</kbd> / <kbd class="dark">Q</kbd></span>
-   <span>Restaurar:</span> <span><kbd class="dark">9</kbd> / <kbd class="dark">num_divide</kbd> / <kbd class="dark">R</kbd></span>
-   <span>Ajuste ancho:</span> <span><kbd class="dark">0</kbd> / <kbd class="dark">num_multiply</kbd> / <kbd class="dark">F</kbd></span>
-   <span>Altura de ajuste:</span> <span><kbd class="dark">H</kbd></span>
-   <span>Ajustes:</span> <span><kbd class="dark">num_divide</kbd> / <kbd class="dark">num_5</kbd> / <kbd class="dark">X</kbd></span>
-   <span>WebComic:</span> <span><kbd class="dark">C</kbd></span>
-   <span>Vertical:</span> <span><kbd class="dark">V</kbd></span>
-   <span>De izquierda a derecha:</span> <span><kbd class="dark">N</kbd></span>
-   <span>De derecha a izquierda:</span> <span><kbd class="dark">B</kbd></span>

## Características

-   Ver modos:
    -   Vertical [Default]
    -   Fluido de izquierda a derecha
    -   Fluido de derecha a izquierda
-     Páginas de marcadores (para reanudar la lectura)
-   Temas completos y personalizables
-   Zoom de imágenes globales e individuales
    -   En (Global uno puede estirar las imágenes más allá del ancho de la ventana)
    -   Fuera
    -   Restaurar original (alternar ancho de ajuste si es demasiado grande)
    -   Ajuste ancho
    -   Ajustar ancho si es demasiado grande [Predeterminado activado]
    -   Altura de ajuste (con páginas de desplazamiento)
    -   Esconder
-   Imágenes de recarga automática
    -   Contador de imágenes cargadas
    -   Recarga de imagen individual, por si acaso
-   Teclas de acceso directo
-   Ir a página
-   Temporizador de carga de imagen [Default 1s](Some sites require longer timers. eg.:ExHentai,e-hentai)
-   Navegación de miniaturas [Default on]
-   Descargar todas las imágenes como archivo ZIP [Automatic Default off]
-   Imágenes de carga diferida [Default off]

## Reglas para agregar nuevos sitios de Manga

1. El sitio debe tener mangas raros/únicos (Significado: no está disponible en otros sitios, o es un mejor calidad)
2. El sitio debe ser lo suficientemente fuerte o, de lo contrario, mi secuencia de comandos puede fallar.
3. El sitio no debe ser exclusivo de un puñado de títulos de manga (Significado: no pequeños scanlators)

## Permisos 

Permito que este script se publique o se use en cualquier lugar siempre que se me dé crédito y se me proporcione un enlace a este sitio.  Permito que partes de mi guión se usen libremente.

## Descargo de responsabilidad

En caso de que el propietario/administrador de uno de los sitios compatibles no quiera que mi script se ejecute en su sitio, lo desactivaré de forma predeterminada.  Obligar a los usuarios a activarlo manualmente.
