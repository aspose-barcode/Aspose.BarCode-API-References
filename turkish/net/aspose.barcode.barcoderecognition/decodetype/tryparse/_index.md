---
title: "DecodeType.TryParse"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "DecodeType yöntemi. Bir SingleDecodeType'ın dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir."
type: docs
weight: 980
url: /tr/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | Dize | Dönüştürmek için "EAN8" veya "EAN13" veya "CodaBar"... biçiminde bir SingleDecodeType içeren bir string. |
| sonuç | SingleDecodeType& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir SingleDecodeType döndürülür; aksi takdirde belirsiz tip döndürülür: DecodeType.None. |

### Dönüş Değeri

**true** if parsingType was converted successfully; otherwise, **false**.

### Ayrıca Bakınız

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse}

MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | Dize | Dönüştürmek için "AllSupportedTypes" veya "EAN8,EAN13,CodaBar" biçiminde bir dize. |
| sonuç | MultiDecodeType& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir MultiDecodeType döndürülür; aksi takdirde belirsiz tip döner: new MultiDecodeType(DecodeType.None) |

### Dönüş Değeri

**true** if parsingType was converted successfully; otherwise, **false**.

### Ayrıca Bakınız

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


