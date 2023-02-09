---
title: DotCodeEncodeMode
second_title: Aspose.BarCode untuk .NET API Referensi
description: Mode pengkodean untuk barcode DotCode.
type: docs
weight: 900
url: /id/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Mode pengkodean untuk barcode DotCode.

```csharp
public enum DotCodeEncodeMode
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Auto | `0` | Enkode teks kode dengan nilai yang ditetapkan di properti ECIEncoding. |
| Bytes | `1` | Mengkodekan teks kode sebagai byte biasa. Jika mendeteksi karakter Unicode apa pun, karakter tersebut akan dikodekan sebagai dua byte, byte lebih rendah terlebih dahulu. |
| ExtendedCodetext | `2` | Mode tambahan yang mendukung mode multi ECI. |

### Contoh

```csharp
[C#]
// Mode otomatis dengan makro
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Mode otomatis
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

// mode byte
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

// menyandikan array ke string
StringBuilder strBld = new StringBuilder();
foreach (byte bval in encodedArr)
    strBld.Append((char) bval);
var codetext = strBld.ToString();

using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Bytes;
    generator.Save("test.bmp");
}

// Mode teks kode yang diperluas
//membuat teks kode
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

// menghasilkan teks kode
string codetext = textBuilder.GetExtendedCodetext();    

//menghasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->