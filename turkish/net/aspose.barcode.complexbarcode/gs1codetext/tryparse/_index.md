---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "GS1Codetext yöntemi. AIvalueAIvalue biçimindeki köşeli parantezli bir GS1 öğe dizesini ayrıştırmayı dener ve yapılandırılmış doğrulama hataları döndürür. Bir değerdeki literal  ,  olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve  kaçış gerektirmez."
type: docs
weight: 140
url: /tr/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Parantezli GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırmayı dener ve yapılandırılmış doğrulama hataları döndürür. Bir değerdeki gerçek '(' karakteri \\( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Dize | Ayrıştırılacak köşeli parantezli GS1 öğe dizesi. |
| sonuç | GS1Codetext& | Bu yöntem true döndürdüğünde, ayrıştırılmış GS1 kod metnini içerir; aksi takdirde null. |
| validationResult | GS1ValidationResult& | Doğrulama sonucunu içerir, ya da *value* null olduğunda null. |

### Dönüş Değeri

True when parsing succeeds; otherwise false.

### Ayrıca Bakınız

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


