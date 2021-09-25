---
layout: post
title: "Metadatos sobre la postal de Federico García Lorca"
date: 2021-09-22
author: Mila Dvorquez-Herrera
---

Doublin Core es un recurso de metadatos con 15 elementos que se utilizan para catalogar fuentes para bibliotecas e incluso museos y crea un índice digital completo para motores de búsqueda. Los recursos que utilizan Doublin Core pueden ser digitales como videos o imágenes o físicos como libros o obras de arte. También se puede describir como un estilo de metadatos que utiliza un marco de descripción de recursos al tiempo que proporciona un foro abierto. 

Aquí está la enlace para la postal que es digitalizada por la biblioteca de la Universidad de Miami: https://merrick.library.miami.edu/cdm/compoundobject/collection/chc5324/id/31/rec/19

La etiqueta de apertura del código refleja nuestra definición del formato de los datos como estilo XML. 

Las etiquetas de metadatos describen el proceso de creación de un término para identificar palabras claves dentro de los archivos digitales de la publicación; en este caso sería la postal: 

```
<?xml version="1.0"?>
<metadata xmlns:dc="http://purl.org/dc/elements/1.1/">
(...)
</metadata>
```

Al mirar la postal digitalizada decidimos nombrarla de la siguiente manera porque define el autor, el recibidor y la fecha: 

```
    <dc:title> 
        Postal de Federico García Lorca a Jose María Chacón (1942)
    </dc:title> 
 ```

El remitente y autor de la postal es Lorca por lo que está justificado llamarlo el creador de la publicación:

```
    <dc:creator> 
        García Lorca, Federico
    </dc:creator> 
 ```
 
Las palabras clave que solíamos describir la postal son los siguientes porque el origen de la tarjeta es Madrid, la parte escrita es una forma de correspondencia, es una postal y el autor es Lorca.

Como tal, esta descripción se ajusta a las etiquetas de tema porque abarcan el significado de la publicación: 

```
    <dc:subject> 
        Madrid
    </dc:subject>
    <dc:subject> 
        correspondencia
    </dc:subject>
    <dc:subject> 
        postales
    </dc:subject>
    <dc:subject> 
        Federico García Lorca
    </dc:subject>
```

Cuando miramos la publicación, encontramos que presentaba un mensaje personal en un lado de la tarjeta, por ejemplo, en el otro lado, con una imagen de Lanjaron. 

Como tal, decidimos describirlo como una tarjeta destinada a un amigo cercano de Lorca: 

```
    <dc:description> 
        Carta personal con un dibujo de una flor de García Lorca desde Lanjaron a su amigo, Jose María Chacón en Madrid
    </dc:description>
 ```
 
En el lado de la postal con la imagen de Lanjaron, hay escrito que dice "Edición Jose Galvez" que determinamos que es el editor.

Por lo tanto, cae bajo esta etiqueta: 

```
    <dc:publisher> 
        Edición Jose Galvez
    </dc:publisher>
```  


El contribuyente es el receptor de la postal:

```
    <dc:contributor> 
        Jose María Chacón
    </dc:contributor>
```
   
La fecha en que se envió la postal: 

```
    <dc:date> 
        1924-09-17
    </dc:date>
```   

El tipo de publicación: 

```
    <dc:type> 
        Imagen
    </dc:type>
```

El formato de la imagen es:

```
    <dc:format> 
        jpg
    </dc:format>
```

La postal se puede encontrar aquí: 

```
    <dc:identifier> 
        https://merrick.library.miami.edu/cdm/compoundobject/collection/chc5324/id/31/rec/19
    </dc:identifier>
 ```  

La fuente de la publicación: 

```
    <dc:source> 
        University of Miami Libraries Digital Collections
    </dc:source>
```

El idioma de la postal está en: 

```
    <dc:language> 
        SPA
    </dc:language>
```   

La fecha y el país de origen de la publicación: 

```
    <dc:coverage> 
        1898-1936
    </dc:coverage>
    <dc:coverage> 
        España
    </dc:coverage>
 ```
 
La publicación es gratuita para que el público acceda: 

```
    <dc:rights> 
        Dominio público
    </dc:rights>
```

Añade una conclusión: ¿qué te pareció el ejercicio? ¿cuáles crees que són los desafíos a los que se enfrenta un bibliotecario? etc. 
