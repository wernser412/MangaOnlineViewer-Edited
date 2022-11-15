# Manga OnlineViewer
### Leer
No es un script originado por mi, solo edito y traduzco el script.

Script original por [TagoDR](https://github.com/TagoDR/MangaOnlineViewer)

## Descripción

Carga todas las páginas de un capítulo en una vista agradable, lo que permite una lectura más rápida y cómoda, sin necesidad de esperar a que se carguen las páginas.


:exclamation: **Atención**: Algunos sitios requieren que vuelva a cargar la página (F5) o abra el capítulo en una nueva pestaña para que se inicie el script.

## Instalación

##### [Main Reader](https://github.com/wernser412/MangaOnlineViewer-edited/raw/main/Manga%20OnlineViewer%20Edited.user.js)
##### [Adult Reader](https://github.com/wernser412/MangaOnlineViewer-edited/raw/main/Manga%20OnlineViewer%20Edited.user.js)
##### Official Source: [GitHub](https://github.com/wernser412)

### Navegadores compatibles
Firefox y Chrome con [Tampermonkey](https://tampermonkey.net/) o [Violentmonkey](https://violentmonkey.github.io/).
Otros navegadores con otros complementos también pueden funcionar, pero no son oficialmente compatibles.

### Marcador móvil

*La configuración no se puede guardar, es posible que deba solicitar una página de escritorio*:

Bookmarklet parece funcionar solo en Chrome, abra el capítulo y luego use la barra de búsqueda para activar su bookmarklet.

###### Lector principal:

```JS
javascript:(function(){["https://cdnjs.cloudflare.com/ajax/libs/tinycolor/1.4.2/tinycolor.min.js", "https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/5.0.0/imagesloaded.pkgd.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jszip/3.9.1/jszip.min.js", "https://cdnjs.cloudflare.com/ajax/libs/nprogress/0.2.0/nprogress.min.js", "https://cdnjs.cloudflare.com/ajax/libs/limonte-sweetalert2/11.4.35/sweetalert2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.21/lodash.min.js", "https://cdn.jsdelivr.net/gh/TagoDR/MangaOnlineViewer@latest/Manga_OnlineViewer.user.min.js"].map( s => document.body.appendChild(document.createElement('script')).src=s)})();
```

###### Lector adulto:

```JS
javascript:(function(){["https://cdnjs.cloudflare.com/ajax/libs/tinycolor/1.4.2/tinycolor.min.js", "https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/5.0.0/imagesloaded.pkgd.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jszip/3.9.1/jszip.min.js", "https://cdnjs.cloudflare.com/ajax/libs/nprogress/0.2.0/nprogress.min.js", "https://cdnjs.cloudflare.com/ajax/libs/limonte-sweetalert2/11.4.35/sweetalert2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.21/lodash.min.js", "https://cdn.jsdelivr.net/gh/TagoDR/MangaOnlineViewer@latest/Manga_OnlineViewer_Adult.user.min.js"].map( s => document.body.appendChild(document.createElement('script')).src=s)})();
```

### Sitios de manga admitidos

- [Asura Scans](https://beta.asurascans.com/) _[English]_
- [Batoto](http://bato.to/) _[English]_
- [Dynasty-Scans](https://dynasty-scans.com/) _[English]_
- [Asura Scans](https://www.asura.gg/) / [Flame Scans](https://flamescans.org/) / [Realm Scans](https://realmscans.com/) / [Voids-Scans](https://void-scans.com/) / [Luminous Scans](https://luminousscans.com/) _[English]_
- [LHTranslation](https://lhtranslation.net/) _[English]_
- [MangaBuddy](https://mangabuddy.com/) _[English]_
- [MangaDex](https://mangadex.org/) _[English]_
- [MangaFox](https://fanfox.net/) / [MangaHere](https://www.mangahere.cc/) _[English]_
- [MangaFreak](https://mangafreak.net/) _[English]_
- [Mangago](https://www.mangago.me/) _[English]_
- [MangaHub](https://mangahub.io/) _[English]_
- [MangaKakalot](https://mangakakalot.com/page) / [MangaNelo](https://www.manganelo.com/) / [MangaNato](https://www.manganato.com/) _[English]_
- [MangaPark](https://mangapark.net/) _[English]_
- [MReader](https://www.mreader.co/) _[English]_
- [Mangareader](https://mangareader.to) _[English]_ **Obs: Some galleries will not be usable**
- [MangaSee](https://mangasee123.com/) / [Manga4life](https://manga4life.com/) _[English]_
- [MangaTown](https://www.mangatown.com/) _[English]_
- [ManhuaScan](https://manhuascan.io/) _[English]_
- [NineManga](https://ninemanga.com/) _[English]_
- [PandaManga](https://www.pandamanga.com/) _[English]_
- [ReadManga Today](https://www.readmng.com/) / [Funmanga](https://funmanga.com/) / [MangaDoom](https://mngdoom.com/) / [MangaInn](https://www.mangainn.net/) _[English]_
- [ReaperScans](https://reaperscans.com/) _[English]_
- [ShimadaScans](https://shimadascans.com/) _[English]_
- [KLManga](https://tapas.io/) _[English]_
- [TenManga](https://www.tenmanga.com/) _[English]_
- [WebToons](https://www.webtoons.com/) _[English]_
- [Manga33](https://manga33.com/) _[English]_
- [ZeroScans](https://zeroscans.com/) _[English]_
- [FoOlSlide](#) / [Kireicake](https://reader.kireicake.com) _[English]_ **Obs: Any Site that uses FoOLSlide**
- [Madara WordPress Plugin](#) / [MangaHaus](https://manhuaus.com) / [Isekai Scan](https://isekaiscan.com/) / [Comic Kiba](https://comickiba.com/) / [Zinmanga](https://zinmanga.com/) / [mangatx](https://mangatx.com/) / [Toonily](https://toonily.net/) / [Mngazuki](https://mangazuki.me/) / [JaiminisBox](https://jaiminisbox.net) / [DisasterScans](https://disasterscans.com/) / [ManhuaPlus](https://manhuaplus.com/) _[English]_ **Obs: Any Site that uses Madara Wordpress Plugin**
- [Leitor](https://leitor.net/) _[Portuguese]_
- [mangahosted](https://mangahosted.com/) _[Portuguese]_
- [UnionMangas](https://unionleitor.top/) _[Portuguese]_
- [KLManga](https://klmanga.com/) _[Raw]_
- [RawDevart](https://rawdevart.com) _[Raw]_
- [SenManga(Raw)](https://raw.senmanga.com/) _[Raw]_
- [InManga](https://inmanga.com//) _[Spanish]_
- [MangaTigre](https://www.mangatigre.net/) _[Spanish]_
- [TuMangaOnline](https://lectortmo.com/) _[Spanish]_

### Sitios de cómics compatibles

- [ComiCastle](http://www.comicastle.org/) _[English]_
- [ReadComicsOnline](http://readcomicsonline.ru/) _[English]_

### Sitios hentai admitidos

> Adult Script available **_only_** on [Github](https://github.com/TagoDR/MangaOnlineViewer)

- [BestPornComix](https://www.bestporncomix.com) _[English]_
- [DoujinMoeNM](https://doujins.com/) _[English]_
- [8Muses](https://comics.8muses.com/) _[English]_
- [ExHentai](https://exhentai.org/) / [e-Hentai](https://e-hentai.org/) _[English]_ **Obs: May get your IP Banned, use with moderation**
- [HBrowser](https://www.hbrowse.com/) _[English]_
- [Hentai2Read](https://hentai2read.com/) _[English]_
- [HentaiFox](https://www.hentaifox.com/) _[English]_
- [HentaiHand](https://hentaihand.com/) / [nHentai.com](https://nhentai.com) _[English]_
- [HentaIHere](https://www.hentaihere.com/) _[English]_
- [hitomi](https://hitomi.la/) _[English]_
- [Imhentai](https://imhentai.xxx/) _[English]_
- [KingComix](https://kingcomix.com/) _[English]_
- [Luscious](https://luscious.net/) _[English]_
- [MultPorn](https://multporn.net/) _[English]_
- [MyHentaiGallery](https://www.myhentaigallery.com) _[English]_
- [Nana](https://nana.my.id/) _[English]_
- [nHentai.net](https://nhentai.net/) / [nHentai.xxx](https://nhentai.xxx/) _[English]_
- [9Hentai](https://9hentai.to) _[English]_
- [OmegaScans](https://omegascans.org/) _[English]_
- [PornComixOnline](https://www.porncomixone.net) _[English]_
- [Pururin](https://pururin.to/) _[English]_
- [Simply-Hentai](https://simply-hentai.com/) _[English]_
- [3Hentai](https://3hentai.net/) _[English]_
- [Tsumino](http://tsumino.com/) _[English]_
- [xyzcomics](https://xyzcomics.com/) _[English]_
- [wnacg](https://wnacg.com/) _[English,Raw,Chinese]_
- [GNTAI.net](https://www.gntai.net/) _[Spanish]_
- [TMOHentai](https://tmohentai.com/) _[Spanish]_
- [vermangasporno](https://vermangasporno.com/) / [vercomicsporno](https://vercomicsporno.com/) _[Spanish]_

### Sitios Agregados por wernser412

- [Almtechnews](https://lectortmo.com/) _[Spanish]_
- [Animalcanine](https://lectortmo.com/) _[Spanish]_
- [Animation2you](https://lectortmo.com/) _[Spanish]_
- [Animationforyou](https://lectortmo.com/) _[Spanish]_
- [Anitoc](https://lectortmo.com/) _[Spanish]_
- [Cook2love](https://lectortmo.com/) _[Spanish]_
- [Cooker2love](https://lectortmo.com/) _[Spanish]_
- [Cookermania](https://lectortmo.com/) _[Spanish]_
- [Cookerready](https://lectortmo.com/) _[Spanish]_
- [Dariusmotor](https://lectortmo.com/) _[Spanish]_
- [Enginepassion](https://lectortmo.com/) _[Spanish]_
- [Fanaticmanga](https://lectortmo.com/) _[Spanish]_
- [Gamesnk](https://lectortmo.com/) _[Spanish]_
- [Infogames2you](https://lectortmo.com/) _[Spanish]_
- [Infopetworld](https://lectortmo.com/) _[Spanish]_
- [Mangalong](https://lectortmo.com/) _[Spanish]_
- [Mistermanga](https://lectortmo.com/) _[Spanish]_
- [Motorbakery](https://lectortmo.com/) _[Spanish]_
- [Motornk](https://lectortmo.com/) _[Spanish]_
- [Motorpi](https://lectortmo.com/) _[Spanish]_
- [Mygamesinfo](https://lectortmo.com/) _[Spanish]_
- [Mynewsrecipes](https://lectortmo.com/) _[Spanish]_
- [Myotakuinfo](https://lectortmo.com/) _[Spanish]_
- [Otakuworldgames](https://lectortmo.com/) _[Spanish]_
- [Otakworld](https://lectortmo.com/) _[Spanish]_
- [Panicmanga](https://lectortmo.com/) _[Spanish]_
- [Recipesaniki](https://lectortmo.com/) _[Spanish]_
- [Recipesdo](https://lectortmo.com/) _[Spanish]_
- [Recipesist](https://lectortmo.com/) _[Spanish]_
- [Recipesnk](https://lectortmo.com/) _[Spanish]_
- [Vgmotor](https://lectortmo.com/) _[Spanish]_
- [Vsrecipes](https://lectortmo.com/) _[Spanish]_
- [Worldmangas](https://lectortmo.com/) _[Spanish]_
- [Wtechnews](https://lectortmo.com/) _[Spanish]_

### Teclas de acceso directo

  <kbd class='dark'>Numpad 5</kbd>/<kbd class='dark'>/</kbd>: Abrir Settings<br/>
  <kbd class='dark'>Numpad +</kbd>/<kbd class='dark'>=</kbd>: Global Zoom in pages (enlarge)<br/>
  <kbd class='dark'>Numpad -</kbd>/<kbd class='dark'>-</kbd>: Global Zoom out pages (reduce)<br/>
  <kbd class='dark'>Numpad /</kbd>/<kbd class='dark'>9</kbd>: Global Restore pages to original<br/>
  <kbd class='dark'>Numpad *</kbd>/<kbd class='dark'>0</kbd>: Global Fit window width<br/>
  <kbd class='dark'>V</kbd>: Vertical Mode<br/>
  <kbd class='dark'>C</kbd>: WebComic Mode<br/>
  <kbd class='dark'>N</kbd>: Modo de derecha a izquierda<br/>
  <kbd class='dark'>B</kbd>: Modo de izquierda a derecha<br/>
  <kbd class='dark'>→</kbd>/<kbd class='dark'>D</kbd>/<kbd class='dark'>Numpad 6</kbd>/<kbd class='dark'>.</kbd> : Siguiente capítulo<br/>
  <kbd class='dark'>←</kbd>/<kbd class='dark'>A</kbd>/<kbd class='dark'>Numpad 4</kbd>/<kbd class='dark'>,</kbd> : Capítulo anterior<br/>
  <kbd class='dark'>↑</kbd>/<kbd class='dark'>W</kbd>/<kbd class='dark'>Numpad 8</kbd>: Desplazarse hacia arriba<br/>
  <kbd class='dark'>↓</kbd>/<kbd class='dark'>S</kbd>/<kbd class='dark'>Numpad 2</kbd>: Desplazarse hacia abajo<br/>

### Características

- Ver modos:
  - Vertical [Default]
  - WebComic
  - Fluido de izquierda a derecha
  - Fluido de derecha a izquierda
- Páginas de marcadores (para reanudar la lectura)
- Temas completos y personalizables
- Zoom de imágenes globales e individuales
  - En (Global uno puede estirar las imágenes más allá del ancho de la ventana)
  - Fuera
  - Restaurar original (alternar ancho de ajuste si es demasiado grande)
  - Ajuste ancho
  - Ajustar ancho si es demasiado grande [Predeterminado activado]
  - Altura de ajuste (con páginas de desplazamiento)
  - Esconder
- Imágenes de recarga automática
  - Contador de imágenes cargadas
  - Recarga de imagen individual, por si acaso
- Teclas de acceso directo
- Ir a página
- Temporizador de carga de imagen [Default 1s](Some sites require longer timers. eg.:ExHentai,e-hentai)
- Navegación de miniaturas [Default on]
- Descargar todas las imágenes como archivo ZIP [Automatic Default off]
- Imágenes de carga diferida [Default off]

### Reglas para agregar nuevos sitios de Manga

1. El sitio debe tener mangas raros/únicos (Significado: no está disponible en otros sitios, o es un mejor calidad)
2. El sitio debe ser lo suficientemente fuerte o, de lo contrario, mi secuencia de comandos puede fallar.
3. El sitio no debe ser exclusivo de un puñado de títulos de manga (Significado: no pequeños scanlators)

## Permisos 

Permito que este script se publique o se use en cualquier lugar siempre que se me dé crédito y se me proporcione un enlace a este sitio.  Permito que partes de mi guión se usen libremente.

### Descargo de responsabilidad

En caso de que el propietario/administrador de uno de los sitios compatibles no quiera que mi script se ejecute en su sitio, lo desactivaré de forma predeterminada.  Obligar a los usuarios a activarlo manualmente.
