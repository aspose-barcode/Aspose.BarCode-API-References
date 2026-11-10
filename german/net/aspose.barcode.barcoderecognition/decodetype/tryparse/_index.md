---
title: "DecodeType.TryParse"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "DecodeType-Methode. Wandelt die Zeichenkettenrepräsentation eines SingleDecodeType in dessen Instanz um. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 980
url: /de/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
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

---

## TryParse(string, out MultiDecodeType) {#tryparse}

Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | String | Eine Zeichenkette im Format entweder "AllSupportedTypes" oder "EAN8,EAN13,CodaBar", die konvertiert werden soll. |
| Ergebnis | MultiDecodeType& | Ein tatsächlicher MultiDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: new MultiDecodeType(DecodeType.None) |

### Rückgabewert

**true** if parsingType was converted successfully; otherwise, **false**.

### Siehe auch

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


