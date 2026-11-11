---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarcodeGeneratorElement özelliği. QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 1290
url: /tr/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '%' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Bayt modunda 0x1D karakteri olarak kodlanır ve '%' karakterleri de veri olarak korunması için Bayt modunda kodlanır.

Bu seçenek, Bayt seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '%' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### Ayrıca Bakınız

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


