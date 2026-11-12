---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Указывает различные типы режимов автоматического масштабирования."
type: docs
weight: 20
url: /ru/nodejs/global/autosizemode/
---

## AutoSizeMode

Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию — AutoSizeMode.NONE.

## Значения

| Имя | Описание |
| --- | --- |
| NONE | Автоматическое изменение размера отключено. Значение по умолчанию. |
| NEAREST | Штрихкод изменяется до ближайшего наименьшего возможного размера, указанного свойствами BarCodeWidth и BarCodeHeight. |
| INTERPOLATION | Изменяет размер штрихкода до указанного с небольшим масштабированием, но в некоторых случаях может быть слегка искажён из‑за использования интерполяции при масштабировании. Размер можно задать свойствами BarcodeGenerator.BarCodeWidth и BarcodeGenerator.BarCodeHeight. |
