---
title: <data>
slug: Web/HTML/Element/data
tags:
  - Elemento
  - HTML
  - Referencia
  - Web
translation_of: Web/HTML/Element/data
original_slug: Web/HTML/Elemento/data
---
## Resúmen

El **Elemento HTML `<data>`** vincula un contenido dado con una traducción legible por una máquina. Si el contenido está relacionado con `time-` o `date-`, debe usarse el elemento {{HTMLElement("time")}}.

| [Categorías de contenido](/es/docs/HTML/Content_categories) | [Flow content](/es/docs/HTML/Content_categories#Flow_content), [phrasing content](/es/docs/HTML/Content_categories#Phrasing_content), palpable content. |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Contenido permitido                                                                   | [Phrasing content](/es/docs/HTML/Content_categories#Phrasing_content).                                                                                                                         |
| Omisión de etiqueta                                                                   | {{no_tag_omission}}                                                                                                                                                                                                                  |
| Elementos permitidos                                                                  | Any element that accepts [phrasing content](/es/docs/HTML/Content_categories#Phrasing_content).                                                                                                |
| interfaz DOM                                                                          | {{domxref("HTMLDataElement")}}                                                                                                                                                                                                  |

## Atributos

Este elemento incluye [Atributos globales](/es/docs/HTML/Global_attributes)

- {{htmlattrdef("value")}}
  - : This attribute specifies the machine-readable translation of the content of the element.

## Ejemplo

El siguiente ejemplo muestra nombres de productos pero también asocia a cada uno con su código UPC.

```html
<p>New Products</p>
<ul>
 <li><data value="3967381398">Mini Ketchup</data></li>
 <li><data value="3967381399">Jumbo Ketchup</data></li>
 <li><data value="3967381400">Mega Jumbo Ketchup</data></li>
</ul>
```

## Especificaciones

| Specification                                                                                                            | Status                           | Comment                                         |
| ------------------------------------------------------------------------------------------------------------------------ | -------------------------------- | ----------------------------------------------- |
| {{SpecName('HTML WHATWG', 'text-level-semantics.html#the-data-element', '&lt;data&gt;')}} | {{Spec2('HTML WHATWG')}} | No change from {{SpecName('HTML5 W3C')}} |
| {{SpecName('HTML5 W3C', 'text-level-semantics.html#the-data-element', '&lt;data&gt;')}}     | {{Spec2('HTML5 W3C')}}     | Initial definition.                             |

## Compatibilidad de navegador

{{Compat("html.elements.data")}}

## Ver también

- The HTML {{HTMLElement("time")}} element.

{{HTMLRef}}
