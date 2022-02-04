# Manga OnlineViewer
### Installation

##### [Main Reader](https://github.com/TagoDR/MangaOnlineViewer/raw/master/Manga_OnlineViewer.user.js)
##### [Adult Reader](https://github.com/TagoDR/MangaOnlineViewer/raw/master/Manga_OnlineViewer_Adult.user.js)
##### Official Source: [GitHub](https://github.com/TagoDR/MangaOnlineViewer)

### Navegadores compatibles
Firefox y Chrome con [Tampermonkey](https://tampermonkey.net/) o [Violentmonkey](https://violentmonkey.github.io/).
Otros navegadores con otros complementos también pueden funcionar, pero no son oficialmente compatibles.

#### Marcador móvil
*La configuración no se puede guardar, es posible que deba solicitar una página de escritorio*:
###### Lector principal:
```
javascript:(function(){["https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jszip/3.5.0/jszip.min.js", "https://cdnjs.cloudflare.com/ajax/libs/nprogress/0.2.0/nprogress.min.js", "https://cdn.jsdelivr.net/npm/sweetalert2@10.16.6/dist/sweetalert2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/color-scheme/1.0.1/color-scheme.min.js", "https://cdnjs.cloudflare.com/ajax/libs/ramda/0.27.0/ramda.min.js", "https://cdnjs.cloudflare.com/ajax/libs/unveil2/2.0.8/jquery.unveil2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/4.1.4/imagesloaded.pkgd.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery-minicolors/2.3.5/jquery.minicolors.min.js", "https://cdn.jsdelivr.net/gh/TagoDR/MangaOnlineViewer@latest/Manga_OnlineViewer.user.min.js"].map( s => document.body.appendChild(document.createElement('script')).src=s)})();
```
###### Lector adulto:
```
javascript:(function(){["https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jszip/3.5.0/jszip.min.js", "https://cdnjs.cloudflare.com/ajax/libs/nprogress/0.2.0/nprogress.min.js", "https://cdn.jsdelivr.net/npm/sweetalert2@10.16.6/dist/sweetalert2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/color-scheme/1.0.1/color-scheme.min.js", "https://cdnjs.cloudflare.com/ajax/libs/ramda/0.27.0/ramda.min.js", "https://cdnjs.cloudflare.com/ajax/libs/unveil2/2.0.8/jquery.unveil2.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/4.1.4/imagesloaded.pkgd.min.js", "https://cdnjs.cloudflare.com/ajax/libs/jquery-minicolors/2.3.5/jquery.minicolors.min.js", "https://cdn.jsdelivr.net/gh/TagoDR/MangaOnlineViewer@latest/Manga_OnlineViewer_Adult.user.min.js"].map( s => document.body.appendChild(document.createElement('script')).src=s)})();
```

### Descripción
MangaOnlineViewer ayuda a acelerar la lectura al cargar todas las páginas (imágenes) del capítulo actual del manga en una página en una estructura de tipo lista.
Tenga en cuenta que en algunos sitios, MangaOnlineViewer puede utilizar más recursos.  Solo abra una pestaña para cada sitio a la vez y espere a que la página se cargue por completo.
Intentaré mantener este script actualizado, sin embargo, casi nunca visito algunos de los sitios admitidos.  Si el script ya no funciona para un sitio, publique el problema en el área Problemas/Comentarios y tenga paciencia.

Permito que este script se publique o se use en cualquier lugar siempre que se me dé crédito y se me proporcione un enlace a este sitio.  Permito que partes de mi guión se usen libremente.

### Sitios de manga admitidos
- [Asura Scans](https://www.asurascans.com/) / [Flame Scans](https://flamescans.org/) _[English]_
- [Batoto](http://bato.to/) _[English]_
- [DisasterScans](https://disasterscans.com/) _[English]_
- [Dynasty-Scans](https://dynasty-scans.com/) _[English]_
- [FoOlSlide]() _[English]_ **Obs: Any Scanlator site that uses FoOLSlide**
- [Funmanga](http://funmanga.com/) _[English]_
- [HatigarmScans](https://hatigarmscanz.net/home) _[English]_
- [KomiRaw](https://komiraw.com/) _[English]_
- [LHTranslation](http://lhtranslation.net/) _[English]_
- [MangaDex](https://mangadex.org/) _[English]_
- [MangaDoom](https://mngdoom.com/) _[English]_
- [MangaFox](http://fanfox.net/) _[English]_
- [MangaFreak](https://mangafreak.net/) _[English]_
- [MangaHaus](https://manhuaus.com) / [Isekai Scan](https://isekaiscan.com/) / [Comic Kiba](https://comickiba.com/) / [Zinmanga](https://zinmanga.com/) / [mangatx](https://mangatx.com/) / [Toonily](https://toonily.net/) / [Mngazuki](https://mangazuki.me/) / [ReaperScans](https://reaperscans.com/) _[English]_ **Obs: Any Site that uses Madara Wordpress Plugin**
- [MangaHere](http://www.mangahere.cc/) _[English]_
- [MangaHub](https://mangahub.io/) _[English]_
- [MangaInn](http://www.mangainn.net/) _[English]_
- [MangaKakalot](https://mangakakalot.com/page) / [MangaNelo](http://www.manganelo.com/) _[English]_
- [MangaLyght](http://manga.lyght.net/) _[English]_
- [MangaNato](http://www.manganato.com/) _[English]_
- [MangaPark](http://mangapark.net/) _[English]_
- [MangaSee](https://mangasee123.com/) / [Manga4life](https://manga4life.com/) _[English]_
- [MangaTown](http://www.mangatown.com/) _[English]_
- [NineManga](http://ninemanga.com/) _[English]_
- [ReadManga Today](http://www.readmng.com/) _[English]_
- [RawDevart](https://rawdevart.com) _[Original]_
- [SenManga(Raw)](http://raw.senmanga.com/) _[Original]_
- [Leitor](https://leitor.net/) _[Portuguese]_
- [UnionMangas](https://unionleitor.top/) _[Portuguese]_
- [TuMangaOnline](https://lectortmo.com/) _[Spanish]_

### Sitios de cómics compatibles
- [ComiCastle](http://www.comicastle.org/) _[English]_
- [ReadComicsOnline](http://readcomicsonline.ru/) _[English]_

### Sitios hentai admitidos
> Adult Script available **_only_** on [Github](https://github.com/TagoDR/MangaOnlineViewer)
- [8Muses](https://comics.8muses.com/) _[English]_
- [9Hentai](https://9hentai.ru) _[English]_
- [ASMHentai](https://asmhentai.com/) _[English]_
- [BestPornComix](https://www.bestporncomix.com) _[English]_
- [DoujinMoeNM](https://doujins.com/) _[English]_
- [ExHentai](https://exhentai.org/) / [e-Hentai](https://e-hentai.org/) _[English]_ **Obs: May get your IP Banned, use with moderation**
- [HBrowser](http://www.hbrowse.com/) _[English]_
- [HentaIHere](https://www.hentaihere.com/) _[English]_
- [Hentai2Read](http://hentai2read.com/) _[English]_
- [HentaiFox](http://www.hentaifox.com/) _[English]_
- [HentaiHand](https://hentaihand.com/) _[English]_
- [HentaiMimi](https://hentaimimi.com/) _[English]_
- [Imhentai](http://imhentai.xxx/) _[English]_
- [KingComix](https://kingcomix.com/) _[English]_
- [MultPorn](https://multporn.net/) _[English]_
- [MyHentaiGallery](https://www.myhentaigallery.com) _[English]_
- [PornComixOnline](https://www.porncomixone.net) _[English]_
- [Pururin](http://pururin.io/) _[English]_
- [Simply-Hentai](http://simply-hentai.com/) _[English]_
- [Tsumino](http://tsumino.com/) _[English]_
- [hitomi](https://hitomi.la/) _[English]_
- [nHentai.com](https://nhentai.com/) _[English]_
- [nHentai.net](https://nhentai.net/) / [nHentai.xxx](https://nhentai.xxx/) _[English]_
- [xyzcomics](http://xyzcomics.com/) _[English]_
- [TMOHentai](http://tmohentai.com/) _[Spanish]_
- [vermangasporno](https://vermangasporno.com/) / [vercomicsporno](https://vercomicsporno.com/) _[Spanish]_

### Teclas de acceso directo
  <kbd class='dark'>Numpad 5</kbd>/<kbd class='dark'>/</kbd>: Open Settings<br/>
  <kbd class='dark'>Numpad +</kbd>/<kbd class='dark'>=</kbd>: Global Zoom in pages (enlarge)<br/>
  <kbd class='dark'>Numpad -</kbd>/<kbd class='dark'>-</kbd>: Global Zoom out pages (reduce)<br/>
  <kbd class='dark'>Numpad /</kbd>/<kbd class='dark'>9</kbd>: Global Restore pages to original<br/>
  <kbd class='dark'>Numpad *</kbd>/<kbd class='dark'>0</kbd>: Global Fit window width<br/>
  <kbd class='dark'>V</kbd>: Vertical Mode<br/>
  <kbd class='dark'>C</kbd>: WebComic Mode<br/>
  <kbd class='dark'>N</kbd>: Right to Left Mode<br/>
  <kbd class='dark'>B</kbd>: Left to Right Mode<br/>
  <kbd class='dark'>→</kbd>/<kbd class='dark'>D</kbd>/<kbd class='dark'>Numpad 6</kbd>/<kbd class='dark'>.</kbd> : Next Chapter<br/>
  <kbd class='dark'>←</kbd>/<kbd class='dark'>A</kbd>/<kbd class='dark'>Numpad 4</kbd>/<kbd class='dark'>,</kbd> : Previous Chapter<br/>
  <kbd class='dark'>↑</kbd>/<kbd class='dark'>W</kbd>/<kbd class='dark'>Numpad 8</kbd>: Scroll  Up<br/>
  <kbd class='dark'>↓</kbd>/<kbd class='dark'>S</kbd>/<kbd class='dark'>Numpad 2</kbd>: Scroll  Down<br/>

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
1. El sitio debe tener mangas raros/únicos (Significado: no está disponible en otros sitios, o es un
   mejor calidad)
2. El sitio debe ser lo suficientemente fuerte o, de lo contrario, mi secuencia de comandos puede fallar.
3. El sitio no debe ser exclusivo de un puñado de títulos de manga (Significado: no pequeños scanlators)

### Descargo de responsabilidad
En caso de que el propietario/administrador de uno de los sitios compatibles no quiera que mi script se ejecute en su sitio, lo desactivaré de forma predeterminada.  Obligar a los usuarios a activarlo manualmente.
