---
layout: post
title: "Tarea 4. Comentario de La Text Encoding Intiative"
date: 2021-10-11
author: Mila Dvorquez-Herrera
---

<img src="https://images.pexels.com/photos/3861972/pexels-photo-3861972.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="imagen de codificación" width="600"/>

**TEI** es un marco de trabajo utilizado para marcar digitalmente textos de diferentes discplinas y se basa en el lenguaje de marcado, *XML*.

Algunos principios básicos de **TEI** son que es *independiente* de cualquier plataforma o programa en particular, se utiliza para *estructurar* textos de manera eficiente y procesada, y se puede *personalizar* para su área de estudio. 

## Declaración XML 

En el prólogo se nos dice que estamos utilizando un documento **XML** y que contiene *la versión 1.0* del estándar XML. También nos indica qué caracteres de codificación usa el documento. En este caso, el texto está encriptado en Unicode, *UTF-8*, que es la combinación de caracteres más universal y utilizada por casi todos los sistemas de codificación.

```
<?xml version="1.0" encoding="UTF-8"?>
```

## Asociación al esquema .rng

La asociación del modelo de esquema para este documento es el tipo *relaxNG (.rng)*. *RelaxNG* es el lenguaje del esquema que establece un modelo concreto para marcar el texto del documento XML-TEI e identifica una pauta estructurada para el contenido. 

```
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_lite.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
```

## Elemento raíz & Espacio de nombre	

Después del prólogo del documento, el elemento **raíz** en este caso, *TEI*, englobará la totalidad de los elementos XML-TEI; estos incluyen el encabezado y el texto. En términos del espacio de nombre, a través del uso de `xmlns="http://www.tei-c.org/ns/1.0"` estamos identificando todos los elementos y atributos dentro de la raíz como correspondientes a ese espacio de nombre específico. 

```
<TEI xmlns="http://www.tei-c.org/ns/1.0"></TEI> 
```

## Encabezado

Una de las dos grandes secciones del **documento XML-TEI** es el encabezado, que aparece como la etiqueta *teiHeader*. Los metadatos de la información relevante sobre el texto se encuentran en el encabezado que presenta las etiquetas de `fileDesc`, `titleStmt`, `publicationStmt` y `sourceDesc`. 
  
```
  <teiHeader>
      <fileDesc>
         <titleStmt>
            <title>Ejercicio para el curso de SPA 410</title>
         </titleStmt>
         <publicationStmt>
            <p>University of Miami</p>        
         </publicationStmt>
         <sourceDesc>
            <p>Archivo creado digitalmente para nuestro curso SPA410.</p>
         </sourceDesc>
      </fileDesc>
  </teiHeader>
  ```
  
  1. **fileDesc**: En el encabezado, este elemento es el único que es obligatorio e incluye información sobre el fichero XML-TEI así como detalles sobre la fuente primaria. 
  2. **titleStmt**: Este elemento proporciona información sobre el nombre del archivo y se puede anidar en una etiqueta de *título*. En este caso, se nombra como un ejercico para nuestra clase. 
  3. **publicationStmt**: Este elemento nos da información sobre la publicación digital del fichero y utiliza la etiqueta de párrafo. Nuestro ejercicio define a *la Universidad de Miami* como la editorial.
  4. **sourceDesc**: Esto nos da detalles sobre la fuente orginial. En nuestro caso, se define como un archivo digital creado para SPA 410. 
  
## Texto

La segunda sección más grande de un documento XML-TEI es el texto. Dentro del texto hay un subelemento llamado `body`. Esta sección contiene el texto real del documento y es una función obligatoria del cuerpo. Utilizamos una etiqueta de párrafo dentro del elemento del cuerpo para ejemplificar el texto que aparece en cualquier otro documento XML-TEI. La etiqueta *figure* también incluye una URL gráfica que es un enlace de hipertexto que conduce a una imagen y puede eliminarse. 
 
 ```
 <text>
      <body>
         <p>Mi primer párrafo explica el trasfondo de TEI. TEI es un marco de trabajo formado en xml y está definido por pautas generales sobre cómo marcar textos digitales para diferentes disciplinas.</p>
         <figure>
            <graphic url="http://www.tei-c.org/logos/TEI-glow.png"/>
         </figure>
      </body>
  </text>
```

En general, la formación de un documento XML-TEI está estructurada de manera informativa y me ha enseñado cómo se puede adaptar TEI para estudios específicos. 
