---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "GS1DigitalLink yöntemi. Sıkıştırılmamış bir GS1 Digital Link URI'sini ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür"
type: docs
weight: 190
url: /tr/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Sıkıştırılmamış bir GS1 Digital Link URI'sini ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Dize | Ayrıştırılacak GS1 Digital Link URI'si. |
| sonuç | GS1DigitalLink& | Bu yöntem true döndürdüğünde, ayrıştırılmış GS1 Digital Link'i içerir; aksi takdirde null. |
| validationResult | GS1ValidationResult& | Doğrulama sonucunu içerir, ya da *value* null olduğunda null. |

### Dönüş Değeri

True when parsing succeeds; otherwise false.

### Ayrıca Bakınız

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


