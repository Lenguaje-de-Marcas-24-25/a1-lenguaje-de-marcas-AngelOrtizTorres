# A1. Lenguajes de marcas

**1. Indica qué es un lenguaje de marcas**

Es un conjunto de reglas y símbolos utilizados para definir la estructura y presentación de datos en un documento.

**2. Características generales de los lenguajes de marcas.**

- Texto plano
- Compactibilidad
- Independencia del dispositivo final
- Especialización
- Flexibilidad

**3. Clasifica los lenguajes de marcas e identifica los más relevantes.**

- De presentación
- Descriptivo, estructural o semántico
- Híbrido

 Lenguajes mas relevantes:

*HTML:* El lenguaje fundamental para la web.

*XML:* Muy relevante en el intercambio de datos entre sistemas.

*JSON:* Aunque no es exactamente un lenguaje de marcado, su popularidad en APIs y transmisión de datos es enorme.

*Markdown:* Extremadamente utilizado para documentación, blogs y colaboración en plataformas como GitHub.

*iCalendar:* Estándar para la gestión y sincronización de calendarios entre dispositivos.

**4. Indica los distintos ámbitos de aplicación de los lenguajes de marcas.**

➢ Desarrollo web 

➢ Ámbito científico 

➢ Gráficos vectoriales

➢ Metainformación 

➢ Bases de datos 

➢ Intercambio de información 

➢ Mensajería


**5. Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:**

- HTML 

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Título de la página</title>
</head>
<body>

</body>
</html>

```
- iCalendar
```iCalendar
BEGIN:VCALENDAR
VERSION:2.0
PRODID:-//Mi Empresa//Mi Producto//ES
BEGIN:VEVENT
UID:123456789@example.com
DTSTAMP:20241002T120000Z
DTSTART:20241015T090000Z
DTEND:20241015T100000Z
SUMMARY:Reunión de equipo
DESCRIPTION:Reunión semanal para discutir el progreso de los proyectos.
LOCATION:Oficina Principal
END:VEVENT
END:VCALENDAR
```
- vCard 
```vCard
BEGIN:VCARD
VERSION:3.0
FN:Manolo Lama
N:Lama;Manolo;;;
ORG:Mi Empresa
TITLE:Gerente de Ventas
TEL;WORK;VOICE:+34 123 456 789
EMAIL:manolo.lama@example.com
ADR;WORK:;;Calle Falsa 123;Madrid;;28000;España
URL:http://www.miempresa.com
END:VCARD
```  

- KML
```XML
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Document>
    <name>Ejemplo de KML</name>
    <Placemark>
      <name>Ubicación Ejemplo</name>
      <description>Este es un punto de interés.</description>
      <Point>
        <coordinates>-3.703790,40.416775,0</coordinates>
      </Point>
    </Placemark>
  </Document>
</kml>
```
- RSS
```xml
<?xml version="1.0" encoding="UTF-8" ?>
<rss version="2.0">
  <channel>
    <title>Ejemplo de RSS</title>
    <link>http://www.ejemplo.com</link>
    <description>Este es un canal RSS de ejemplo.</description>
    <language>es-es</language>
    <pubDate>Mon, 02 Oct 2024 12:00:00 +0000</pubDate>
    
    <item>
      <title>Título de la primera entrada</title>
      <link>http://www.ejemplo.com/entrada1</link>
      <description>Descripción de la primera entrada en el RSS.</description>
      <pubDate>Mon, 02 Oct 2024 09:00:00 +0000</pubDate>
      <guid>http://www.ejemplo.com/entrada1</guid>
    </item>
    
    <item>
      <title>Título de la segunda entrada</title>
      <link>http://www.ejemplo.com/entrada2</link>
      <description>Descripción de la segunda entrada en el RSS.</description>
      <pubDate>Tue, 03 Oct 2024 10:00:00 +0000</pubDate>
      <guid>http://www.ejemplo.com/entrada2</guid>
    </item>
  </channel>
</rss>
```