---
title: "Enum AztecEncodeMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.Generation.AztecEncodeMode. Mode enkoding untuk kode batang Aztec"
type: docs
weight: 940
url: /id/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Mode enkoding untuk kode batang Aztec.

```csharp
public enum AztecEncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | In Auto mode, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika sebuah karakter ditemukan yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| Extended | `3` | Mode Extended yang mendukung beberapa mode ECI. |
| Binary | `4` | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | `5` | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika sebuah karakter ditemukan yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap perhatikan bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |

## Contoh

```csharp
[C#]
//Mode Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Mode Extended
//buat kode teks
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//hasilkan kode teks
string codetext = textBuilder.GetExtendedCodetext();    

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Lihat Juga

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


