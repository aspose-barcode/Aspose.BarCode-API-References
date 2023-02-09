---
title: TryParse
second_title: Aspose.BarCode for .NET API Referansı
description: SingleDecodeTypeın dize temsilini örneğine dönüştürür. Dönüş değeri dönüşümün başarılı veya başarısız olduğunu gösterir.
type: docs
weight: 810
url: /tr/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüşümün başarılı veya başarısız olduğunu gösterir.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parsingType | String | Dönüştürülecek "Dizin:-1; Ad:Yok" biçiminde bir dize. |
| result | SingleDecodeType& | Gerçek bir SingleDecodeType, dönüştürme başarıyla tamamlandığında döner; |

### Geri dönüş değeri

**doğru** s başarıyla dönüştürülmüşse; aksi halde, **yanlış**.

### Ayrıca bakınız

* class [SingleDecodeType](../../singledecodetype)
* class [DecodeType](../../decodetype)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../decodetype)
* toplantı [Aspose.BarCode](../../../)

---

## TryParse(string, out MultyDecodeType) {#tryparse}

Bir MultyDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüştürmenin başarılı veya başarısız olduğunu gösterir.

```csharp
public static bool TryParse(string parsingType, out MultyDecodeType result)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parsingType | String | Dönüştürülecek "AllSupportedTypes" veya "EAN8,EAN13,CodaBar" biçiminde bir dize. |
| result | MultyDecodeType& | Dönüştürme başarıyla tamamlandığında gerçek bir MultyDecodeType döndürülür; |

### Geri dönüş değeri

**doğru** s başarıyla dönüştürülmüşse; aksi halde, **yanlış**.

### Ayrıca bakınız

* class [MultyDecodeType](../../multydecodetype)
* class [DecodeType](../../decodetype)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../decodetype)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->