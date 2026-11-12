---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para color CMYK."
type: docs
weight: 180
url: /es/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Clase para color CMYK. Una instancia nula significa que CMYK no se usa y se utiliza el color RGB predeterminado.

```js
new CMYKColor(c, m, y, k)
```

Inicializa una nueva instancia de la clase CMYKColor a partir de valores CMYK. Se espera que los valores CMYK estén en el rango 0–100.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | número | – Valor de cian [0, 100] |
| m | número | – Valor de magenta [0, 100] |
| y | número | – Valor de amarillo [0, 100] |
| k | número | – Valor de negro [0, 100] |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Analiza una cadena CMYK con el formato "C_M_Y_K" en una instancia de CMYKColor. |
| [formatCMYK()](#formatcmyk) | Formatea este CMYKColor en una cadena "C_M_Y_K", multiplicando cada componente interno (0–1) por 100 y redondeando. |
| [toString()](#tostring) | Opcional: una representación legible por humanos. |

### parseCMYK(str) (static) {#parsecmyk}

Analiza una cadena CMYK con el formato "C_M_Y_K" en una instancia de CMYKColor.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | string | – una cadena como "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formatea este CMYKColor en una cadena "C_M_Y_K", multiplicando cada componente interno (0–1) por 100 y redondeando.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Opcional: una representación legible por humanos.
