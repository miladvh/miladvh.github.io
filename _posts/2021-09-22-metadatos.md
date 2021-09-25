---
layout: post
title: "Metadatos sobre la postal de Federico García Lorca"
date: 2021-09-22
author: Mila Dvorquez-Herrera
---

Doublin Core es un recurso de metadatos con 15 elementos que se utilizan para catalogar fuentes para bibliotecas e incluso museos y crea un índice digital completo para motores de búsqueda. Los recursos que utilizan Doublin Core pueden ser digitales como videos o imágenes o físicos como libros o obras de arte. También se puede describir como un estilo de metadatos que utiliza un marco de descripción de recursos al tiempo que proporciona un foro abierto. 

Aquí está el enlace para la postal que es digitalizada por la biblioteca de la Universidad de Miami:
[la postal](https://merrick.library.miami.edu/cdm/compoundobject/collection/chc5324/id/31/rec/19)



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


Se determina que el colaborador es el recipiente de la postal porque es la otra parte presenete en esta publicación.

La participación de María Chacón hace de la postal una representación de correspondencia entre dos amigos:

```
    <dc:contributor> 
        Jose María Chacón
    </dc:contributor>
```
   
La fecha es cuando envió la postal porque encontramos una marca de tiempo que nos permitió inferir que ahora estaba en tránsito y por lo tanto una forma de correspondencia realizada: 

```
    <dc:date> 
        1924-09-17
    </dc:date>
```   

Había una lista de tipos de publicación que determinamos que era una imagen porque era una versión cargada digitalmente de la postal: 

```
    <dc:type> 
        Imagen
    </dc:type>
```

El formato de la imagen es un jpg porque el archivo de la postal denota esta versión (.jpg):

```
    <dc:format> 
        jpg
    </dc:format>
```

El identificador es el enlace a la postal en el sitio web de la biblioteca de la Universidad de Miami porque está contenido en una determinada colección de su catálogo: 

```
    <dc:identifier> 
        https://merrick.library.miami.edu/cdm/compoundobject/collection/chc5324/id/31/rec/19
    </dc:identifier>
 ```  

La fuente de la publicación es la biblioteca de la Universidad de Miami tal como lo publican digitalmente: 

```
    <dc:source> 
        University of Miami Libraries Digital Collections
    </dc:source>
```

El idioma de la postal está en español por lo que se identifica como tal: 

```
    <dc:language> 
        SPA
    </dc:language>
```   

Se determina que la fecha que cubre la postal es la vida de Lorca y el país de origen de la publicación se menciona para dar una ubicación físi ca al archivo: 

```
    <dc:coverage> 
        1898-1936
    </dc:coverage>
    <dc:coverage> 
        España
    </dc:coverage>
 ```
 
La publicación es gratuita para que el público acceda, lo que significa que los derechos son de dominio público: 

```
    <dc:rights> 
        Dominio público
    </dc:rights>
```

Añade una conclusión: ¿qué te pareció el ejercicio? ¿cuáles crees que són los desafíos a los que se enfrenta un bibliotecario? etc. 
