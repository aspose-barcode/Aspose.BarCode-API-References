---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour la couleur CMYK."
type: docs
weight: 180
url: /fr/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Classe pour la couleur CMYK. Une instance nulle signifie que le CMYK n'est pas utilisé, et que la couleur RGB par défaut est utilisée.

```js
new CMYKColor(c, m, y, k)
```

Initialise une nouvelle instance de la classe CMYKColor à partir des valeurs CMYK. Les valeurs CMYK sont attendues dans la plage 0–100.

| Paramètre | Type | Description |
| --- | --- | --- |
| c | nombre | – Valeur cyan [0, 100] |
| m | nombre | – Valeur magenta [0, 100] |
| y | nombre | – Valeur jaune [0, 100] |
| k | nombre | – Valeur noir [0, 100] |

## Méthodes

| Nom | Description |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Analyse une chaîne CMYK de la forme "C_M_Y_K" en une instance CMYKColor. |
| [formatCMYK()](#formatcmyk) | Formate ce CMYKColor en une chaîne "C_M_Y_K", en multipliant chaque composant interne (0–1) par 100 et en arrondissant. |
| [toString()](#tostring) | Facultatif : une représentation lisible par l'homme. |

### parseCMYK(str) (static) {#parsecmyk}

Analyse une chaîne CMYK de la forme "C_M_Y_K" en une instance CMYKColor.

| Paramètre | Type | Description |
| --- | --- | --- |
| str | chaîne | – une chaîne comme "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formate ce CMYKColor en une chaîne "C_M_Y_K", en multipliant chaque composant interne (0–1) par 100 et en arrondissant.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Facultatif : une représentation lisible par l'homme.
