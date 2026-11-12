---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza)."
type: docs
weight: 370
url: /it/nodejs/global/inverseimagemode/
---

## InverseImageMode

Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza). Questo esempio mostra come utilizzare la modalità InverseImage let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valori

| Nome | Descrizione |
| --- | --- |
| NONE | Nessun bordo che racchiude il codice a barre |
| FRAME | FRAME che racchiude il codice a barre |
| BAR | Due barre orizzontali che racchiudono il codice a barre |
| FRAME_OUT | FRAME che racchiude il codice a barre |
| BAR_OUT | Due barre orizzontali che racchiudono il codice a barre |
