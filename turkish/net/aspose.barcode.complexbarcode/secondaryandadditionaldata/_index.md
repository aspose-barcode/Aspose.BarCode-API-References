---
title: "Sınıf SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData sınıfı. HIBC LIC ikincil ve ek verileri depolamak için sınıf"
type: docs
weight: 770
url: /tr/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

HIBC LIC ikincil ve ek verileri depolamak için sınıf.

```csharp
public class SecondaryAndAdditionalData
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Üretim tarihini tanımlar. Bu alanı kullanmamak için üretim tarihi DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Son kullanım tarihini belirler. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Son kullanım tarihi biçimini belirler. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Lot veya batch numarasını belirler. Lot/batch numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Miktarı belirler, 0 ile 500 arasında tam sayı olmalıdır. Bu alan kullanılmayacaksa miktar -1 olarak ayarlanabilir. Varsayılan değer: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Seri numarasını belirler. Seri numarası, en fazla 18 sembol uzunluğunda alfanümerik bir dize olmalıdır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Bu örneğin belirtilen `SecondaryAndAdditionalData` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | HIBC LIC spesifikasyonuna göre dize biçiminden ikincil ve ek destek verilerini oluşturur. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Verileri HIBC LIC spesifikasyonuna göre dize biçimine dönüştürür. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


