---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для цвета CMYK."
type: docs
weight: 180
url: /ru/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Класс для цвета CMYK. Нулевой экземпляр означает, что CMYK не используется, а применяется цвет по умолчанию RGB.

```js
new CMYKColor(c, m, y, k)
```

Инициализирует новый экземпляр класса CMYKColor из значений CMYK. Значения CMYK ожидаются в диапазоне 0–100.

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | число | – Значение Cyan [0, 100] |
| m | число | – Значение Magenta [0, 100] |
| y | число | – Значение Yellow [0, 100] |
| k | число | – Значение Black [0, 100] |

## Методы

| Имя | Описание |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Разберите строку CMYK формы "C_M_Y_K" в экземпляр CMYKColor. |
| [formatCMYK()](#formatcmyk) | Отформатируйте этот CMYKColor в строку "C_M_Y_K", умножая каждый внутренний компонент (0–1) на 100 и округляя. |
| [toString()](#tostring) | Необязательно: человекочитаемое представление. |

### parseCMYK(str) (static) {#parsecmyk}

Разберите строку CMYK формы "C_M_Y_K" в экземпляр CMYKColor.

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | string | – строка вида "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Отформатируйте этот CMYKColor в строку "C_M_Y_K", умножая каждый внутренний компонент (0–1) на 100 и округляя.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Необязательно: человекочитаемое представление.
