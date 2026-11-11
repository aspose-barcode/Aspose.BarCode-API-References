---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarcodeGenerator metodu. Kod metnini bayt dizisi olarak ayarlar"
type: docs
weight: 100
url: /tr/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

codetext'i bayt dizisi olarak ayarla.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeBytes | Byte[] | Kod metninin baytları |

### Ayrıca Bakınız

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyorsa, işlev otomatik olarak bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler.

Bu işlev yalnızca 2D barkodlarla kullanılmak üzere tasarlanmıştır (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, vb.). Ulusal veya özel kodlamalar kullanarak Unicode metninin manuel kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) kodlaması önerilir.

Bu işlevi 1D barkodlarla, GS1 uyumlu barkodlarla (2D dahil) veya HIBC barkodlarla (2D dahil) kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | Dize | CodeText dizesi |
| kodlama | Kodlama | Uygulanan kodlama |

## Örnekler

Bu örnek, farklı kodlamalar kullanarak 2D barkodlar için Unicode kodlu metni ayarlayan `SetCodeText` kullanımını gösterir:

```csharp
[C#]
//UTF-8 BOM ile QR Kod metnini kodlayın
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Shift-JIS (Japon kodlaması) kullanarak DataMatrix metnini kodlayın
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Ayrıca Bakınız

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyor ve **insertBOM** `true` olarak ayarlanmışsa, işlev bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler.

Bu işlev yalnızca 2D barkodlarla kullanılmak üzere tasarlanmıştır (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, vb.). Ulusal veya özel kodlamalar kullanarak Unicode metninin manuel kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) kodlaması önerilir.

Bu işlevi 1D barkodlarla, GS1 uyumlu barkodlarla (2D dahil) veya HIBC barkodlarla (2D dahil) kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | Dize | CodeText dizesi |
| kodlama | Kodlama | Uygulanan kodlama |
| insertBOM | Boolean | Belirtilen kodlama bunu desteklediğinde (ör. UTF-8, UTF-16, UTF-32) bayt sırası işareti (BOM) eklenip eklenmeyeceğini gösterir. `true` olarak ayarlanırsa BOM eklenir; `false` ise kodlama normalde bir BOM kullansa bile eklenmez. |

## Örnekler

Bu örnek, 2D barkodlar için `SetCodeText` kullanımını BOM ile veya BOM olmadan göstermektedir.

```csharp
[C#]
//UTF-8 BOM ile codetext'i kodlayın
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//UTF-8 BOM olmadan codetext'i kodlayın
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Ayrıca Bakınız

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


