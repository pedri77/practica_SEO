# OPTIMIZACIÓN ONPAGE

## Factores

### Etiquetas

<title>Descripción única de mi contenido engloba a todo el documento</title>
<meta name=“description” content=“¿Qué es una description?Toda la información sobre las etiquetas description y como se deben usar, Sigue leyendo en Keepcoding.io”/>
<meta name=“keywords” content=“uso solo una palabra, ya no posiciona”/>

### Jerarquia de etiquetas de Encabezado

h1
h3
h3
...
h6

### Factores OnPage para imágenes

• Nombre descriptivo
• Imágenes originales
• Uso de alt – En caso de error de carga
• Uso de title – Título en amarillo
• Cuida el peso de la imagen
• Incluye las dimensiones de la imagen
• Tráfico a través de Google Image – Cuida el SEO • <img src=“” alt=“” title=“”>

### Metakeywords

• Abuso por parte de los webmaster (Keyword Stuffing)
• Google no las tiene en cuenta desde 2009
• Te ayuda a conocer las palabras clave de tus
competidores

### URLs

Las urls deben ser únicas
• Mejor absolutas que relativas
• Sin mayúsculas
• Sin barra bajas
• Con guión medio
• Los espacios son guiones medios
• Sin caracteres especiales como “ñ”, o “^”...
• Urls que sean contenedor de contenido dinámico
• NO se borran si tienen tráfico o tienen enlaces, se redireccionan con
un 301

### Dofollow vs Nofollow

• <a rel="nofollow" target="_blank" title="marca" href="http://www.marca.com" id="logo-el-mundo" class="ir">Marca</a>
• Es una etiqueta exclusiva para enlaces
• Nofollow = no sigo rastreando y no paso autoridad
• Usamos nofollow cuando hay enlaces de pago

### Metas Fundamentales OG
<!-- Open Graph data -->
<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# article:
http://ogp.me/ns/article#">
<meta property="og:title" content="Your Title Here" />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://example.com/" />
<meta property="og:image" content="https://example.com/image.jpg" /> <meta property="og:description" content="Your Description Here" /> <meta property="og:site_name" content="Your Site Name, i.e. Moz" /> <meta property="fb:app_id" content="Your FB_APP_ID" />

### Relevancia web

1. Title
2. H1,h2,h3...h6 
3. Contenido
4. Description
5. Url
6. In Links & Out Links
7. Alt image & Title

### Breadcrumbs o Migas de Pan

### Códigos de Estado HTTP

200 OK/Success
301 Redirección Permanente
302 Redirección Temporal
404 No encontrada
403 Forbidden
410 Ya no disponible - Ni está ni se la espera
500 Error del Servidor
503 Servicio no disponible – Importante!! Para que Google entienda que estamos trabajando en el Servidor

# Canonical

2 o + URL distintas, y mismo contenido
Elegir URL preferida = https://example.com/
Colocar este código en el <head> para indicar nuestra URL preferida:
<link rel="canonical" href="http://www.cuidateplus.com/alimentacion/diccionario/leche.html" />

# Hreflang

Dadas 2 urls con contenido traducido a otro idioma debemos indicárselo a google, en la cabecera HTML.

ESTRUCTURA de URLs para diferentes idiomas

@antoniovanlook
 
Utilizamos subdirectorios gTLDS

http://www.dominio.com/en/

META ETIQUETAS –> rel="alternate" hreflang="x" Etiquetas para señalar diferentes idiomas o regiones
En la cabecera de cada versión de HTML <head> se deben identificar todas las versiones incluso en la que estás

Contenido duplicado por idioma https://www.sistrix.es/hreflang-guide/hreflang-validator/ 

## Robots.txt

Localización en: http://www.midominio.com/robots.txt User-agent: *
Disallow: /example.html
Más información: http://www.robotstxt.org/robotstxt.html

### Estándares de exclusión a Robots

X-Robots
Localización: Se envía en la cabecera HTTP (HTTP headers)
X-Robots-Tag: noindex
Más información http://noarchive.net/xrobots/

Meta Robots
Localizado en: <head> del Html
<meta name="NOMBRE DEL ROBOT" content="ARGUMENTO" />
Más información http://www.robotstxt.org/meta.html

Argumentos:

• nofollow (no sigas los links)
• noindex (no indexes)
• noarchive (no archives)
• noODP (No muestres la descripción de Open Directory Project)
• ...O combinados (noindex, nofollow)
• Si la etiqueta de robots <META> no esta definida, la forma predeterminada seria "INDEX,FOLLOW"

Buenas prácticas Robots.txt:

• Solo los Meta Robots y X-Robots quitan las URLs de los resultados de búsqueda, el robots.txt no pemite la entrada
• No bloquees archivos CSS ni JavaScript en el robots.txt
• Robots.txt es usado para que no rastree no para que no indexe

User Agents más importantes:

User Agents más importantes
• Googlebot
• Google-News
• Googlebot-Mobile
• Googlebot-image
• Googlebot-Video
• AdsBot-Google
• BaiduSpider
• FacebookExternalHit • BingBot
• Yandexbot
• Applebot
• Twitterbot

## Importante contenido único por URL

Causas habituales de contenido duplicado: 

-Uso de http y https
-Uso de www. y sin www.
-Subdominios en preproducción
-Url con identificador de sesión y sin identificador -Contenido distinto con una misma URL

Uso de http y https (Protocolo de seguridad)
-Recomendación todo bajo https://
-Redirección 301 de http:// a https://
-Mensaje de sitio no seguro si no está bien hecho el protocolo https://
-AMP exige https://
-Un archivo robots.txt por cada protocolo
-En Search Console también lo trata como un sitio diferente, comprobamos la indexación de http:// y https://
-Elegimos la opción que preferimos y redireccionamos permanentemente la otra. Ejemplo: midominio.com lo redireccionamos a con www.midominio.com -Creamos en Search Console una vista por cada opción y controlamos que no se
indexen urls con la opción que redireccionamos
-Si ya hemos indexado con www. y sin www. elegiremos la opción con mejores enlaces y mayor número de urls indexadas
-Corregir enlaces internos a la versión elegida
-Enlaces externos pedir que te lo cambien si se puede

## Migraciones

Es un cambio critico ya que es igual que hacer una migración, en caso de que no funcionen bien las redirecciones podemos perder todo el tráfico SEO
• Realizamos redirección 301 al 100% de los archivos: jpg, pdf, html, css, js, php...
• Todos los enlaces internos también tienen que estar cambiados
• Google recomienda que mejor se haga todo a la vez y no por carpetas, subdominios o fases
• Si encuentra algo de contenido sin el certificado de seguridad, mostrará el sitio como no
seguro
• Recomendación todo bajo https://
• Redirección 301 de http:// a https://
• AMP exige https://
• En Search Console también lo trata como un sitio diferente, comprobamos la indexación de
http:// y https://

## Paginado

¿Cómo indicamos el Paginado?
NO hacemos nadaNormalmente Google entiende los paginados y devolverá el resultado principal.
Mostramos todo el contenido en una sola página
La experiencia de usuario nos dice que el usuario espera encontrar todo el contenido en una sola página.
Tenemos complementos que apoyan a la página principal y como solo queremos mostrar el contenido principal estos complementos llevan la etiqueta rel=“canonical”
Usamos la etiqueta rel=“next” y rel=“prev”.

<link href="URL" rel="next">
<link href="URL" rel="prev">

Cada página de la paginación debe tener:

• Título, h1, description únicos (igual que og:title, og:description, twitter:title,
twitter:description)
• Canonical a su propia URL

## Sitemap

“El Sitemap es una manera sencilla de decirle a los motores de búsqueda, las páginas que están disponibles para su rastreo”
• Es una lista en formato XML con las URLs • Se añade a la raíz en el servidor
• No asegura la indexación
• Incluye metadatos para cada URL
• Última actualización
• Frecuencia en los cambios
• Importancia de rastreo relativa a otras URLs

## La importancia del WPO
 




