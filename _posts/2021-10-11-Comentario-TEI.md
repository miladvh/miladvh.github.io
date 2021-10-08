---
layout: post
title: "Comentario de La Text Encoding Intiative"
date: 2021-10-11
author: Mila Dvorquez-Herrera
---

# La Text Encoding Intiative (TEI)

**TEI** es un marco de trabajo utilizado para marcar digitalmente textos de diferentes discplinas y se basa en el lenguaje de marcado, *XML*.

Algunos principios básicos del **TEI** son que es *independiente* de cualquier plataforma o programa en particular, se utiliza para *estructurar* textos de manera eficiente y procesada, y se puede *personalizar* para su área de estudio. 


## Declaración XML 

En el prólogo nos dice que estamos tratando con un documento XML y que usa un Unicode, como UTF-8 cuál es el tipo de codificación más común. 
```
<?xml version="1.0" encoding="UTF-8"?>
```
## Asociación al esquema .rng


```
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_lite.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>
<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_lite.rng" type="application/xml"
schematypens="http://purl.oclc.org/dsdl/schematron"?>
```
## Elemento raiz & Espacio de nombre	
```
<TEI xmlns="http://www.tei-c.org/ns/1.0"></TEI> 
```
## Encabezado
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
## Texto
 
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