---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QrParametersUI özelliği. QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar."
type: docs
weight: 30
url: /tr/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '%' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Bayt modunda 0x1D karakteri olarak kodlanır ve '%' karakterleri de veri olarak korunması için Bayt modunda kodlanır.

Bu seçenek, Bayt seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '%' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Ayrıca Bakınız

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


