---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert."
type: docs
weight: 160
url: /de/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Modus, der die zusätzliche Erkennung von Farbbalkencodes in Farbbildern aktiviert oder deaktiviert. Dieses Beispiel zeigt, wie man den ComplexBackground mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Werte

| Name | Beschreibung |
| --- | --- |
| C_TABLE | Verwenden Sie C_TABLE, um die Kundeninformation zu interpretieren. Erlaubt A..Z, a..z, 1..9, Leerzeichen und #-Zeichen. |
| N_TABLE | Verwenden Sie N_TABLE, um die Kundeninformation zu interpretieren. Erlaubt Ziffern. |
| OTHER | Die Kundeninformation nicht interpretieren. Erlaubt nur das Symbol 0, 1, 2 oder 3. |
