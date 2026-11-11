---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BaseDecodeType yöntemi. Bir SingleDecodeType'ın string temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir"
type: docs
weight: 40
url: /tr/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | Dize | Dönüştürmek için "EAN8" veya "EAN13" veya "CodaBar"... biçiminde bir SingleDecodeType içeren bir string. |
| sonuç | SingleDecodeType& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir SingleDecodeType döndürülür; aksi takdirde belirsiz tip döner: DecodeType.None. |

### Dönüş Değeri

**true** if parsingType was converted successfully; otherwise, **false**.

### Ayrıca Bakınız

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | Dize | Dönüştürmek için bir MultiDecodeType temsili içeren bir string. |
| sonuç | MultiDecodeType& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir MultiDecodeType döndürülür; aksi takdirde belirsiz tip döner: new MultiDecodeType(DecodeType.None) |

### Dönüş Değeri

**true** if parsingType was converted successfully; otherwise, **false**.

### Ayrıca Bakınız

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

BaseDecodeType'ın dize temsilini, somut tür belirlenerek örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir.

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | Dize | Dönüştürmek için bir MultiDecodeType temsili içeren bir string. |
| sonuç | BaseDecodeType& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir MultiDecodeType döndürülür; aksi takdirde belirsiz tip döner: DecodeType.None. |

### Dönüş Değeri

**true** if parsingType was converted successfully; otherwise, **false**.

### Ayrıca Bakınız

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


