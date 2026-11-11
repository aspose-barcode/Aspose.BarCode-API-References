---
title: "DecodeType.Parse"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "DecodeType yöntemi. Bir SingleDecodeType'ın dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir."
type: docs
weight: 960
url: /tr/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
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


