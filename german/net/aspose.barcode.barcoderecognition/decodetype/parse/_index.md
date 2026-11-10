---
title: "DecodeType.Parse"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "DecodeType-Methode. Wandelt die Zeichenkettenrepräsentation eines SingleDecodeType in dessen Instanz um. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 960
url: /de/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | String | Eine Zeichenkette, die einen SingleDecodeType im Format "EAN8" oder "EAN13" oder "CodaBar"... enthält, um ihn zu konvertieren. |
| Ergebnis | SingleDecodeType& | Ein tatsächlicher SingleDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: DecodeType.None. |

### Rückgabewert

**true** if parsingType was converted successfully; otherwise, **false**.

### Siehe auch

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


