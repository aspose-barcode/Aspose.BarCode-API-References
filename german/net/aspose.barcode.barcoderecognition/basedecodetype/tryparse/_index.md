---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BaseDecodeType-Methode. Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist"
type: docs
weight: 40
url: /de/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

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
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | String | Eine Zeichenkette, die eine MultiDecodeType-Darstellung zum Konvertieren enthält. |
| Ergebnis | MultiDecodeType& | Ein tatsächlicher MultiDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: new MultiDecodeType(DecodeType.None) |

### Rückgabewert

**true** if parsingType was converted successfully; otherwise, **false**.

### Siehe auch

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | String | Eine Zeichenkette, die eine MultiDecodeType-Darstellung zum Konvertieren enthält. |
| Ergebnis | BaseDecodeType& | Ein tatsächlicher MultiDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: DecodeType.None. |

### Rückgabewert

**true** if parsingType was converted successfully; otherwise, **false**.

### Siehe auch

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


