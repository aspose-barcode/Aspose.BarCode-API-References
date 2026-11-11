---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "LuminanceFrame yapıcı. Satırlar arasında boşluk olmadan yeni bir LuminanceFrame sınıfı örneği oluşturur. Ardışık satırlar arasındaki mesafe genişliğe eşittir."
type: docs
weight: 10
url: /tr/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Satırlar arasında boşluk olmadan yeni bir [`LuminanceFrame`](../) sınıfı örneği oluşturur. Ardışık satırlar arasındaki mesafe *width*'e eşittir.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | Byte[] | Piksel başına bir bayt içeren parlaklık verisi. |
| width | Int32 | Çerçevenin genişliği piksel olarak. |
| height | Int32 | Çerçevenin yüksekliği piksel olarak. |
| rotationDegrees | Int32 | Çerçeveyi dik konumda göstermek için gereken saat yönünde dönüş. Desteklenen değerler 0, 90, 180 ve 270'tir. Varsayılan değer 0'dır. |

### Ayrıca Bakınız

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Belirtilen satır adımıyla yeni bir [`LuminanceFrame`](../) sınıfı örneği oluşturur.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | Byte[] | Piksel başına bir bayt içeren parlaklık verisi. |
| width | Int32 | Çerçevenin genişliği piksel olarak. |
| height | Int32 | Çerçevenin yüksekliği piksel olarak. |
| rowStride | Int32 | İki yan yana satırın başlangıçları arasındaki bayt cinsinden mesafe. Değer *width* değerinden daha az olamaz. |
| rotationDegrees | Int32 | Çerçeveyi dik konumda göstermek için gereken saat yönünde döndürme. Desteklenen değerler 0, 90, 180 ve 270. |

### Ayrıca Bakınız

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


