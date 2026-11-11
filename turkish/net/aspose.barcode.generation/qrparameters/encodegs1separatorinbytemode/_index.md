---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QrParameters özelliği. QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını belirten bir değeri alır veya ayarlar."
type: docs
weight: 30
url: /tr/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '%' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Bayt modunda 0x1D karakteri olarak kodlanır ve '%' karakterleri de veri olarak korunması için Bayt modunda kodlanır.

Bu seçenek, Bayt seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '%' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Ayrıca Bakınız

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


