---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori."
type: docs
weight: 160
url: /it/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. Questo esempio mostra come utilizzare la modalità ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valori

| Nome | Descrizione |
| --- | --- |
| C_TABLE | Usa C_TABLE per interpretare le informazioni del cliente. Consente A..Z, a..z, 1..9, spazio e il simbolo #. |
| N_TABLE | Usa N_TABLE per interpretare le informazioni del cliente. Consente cifre. |
| OTHER | Non interpretare le informazioni del cliente. Consente solo il simbolo 0, 1, 2 o 3. |
