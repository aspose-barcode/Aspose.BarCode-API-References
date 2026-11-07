---
title: "enum"
linktitle: "MaxiCodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode enkoding untuk barcode MaxiCode dalam C++."
type: docs
weight: 7600
url: /id/cpp/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enum


Mode enkoding untuk barcode MaxiCode.

```cpp
enum class MaxiCodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Mode2 | 2 | Mode 2 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. Memiliki kode pos 9 digit (hanya digunakan di USA). |
| Mode3 | 3 | Mode 3 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. Memiliki kode pos alfanumerik 6 karakter, digunakan di seluruh dunia. |
| Mode4 | 4 | Mode 4 mengkodekan data dalam pesan pertama dan kedua, dengan koreksi ECC pendek. |
| Mode5 | 5 | Mode 5 mengkodekan data dalam pesan pertama dan kedua, dengan koreksi ECC panjang. |
| Mode6 | 6 | Mode 6 mengkodekan data dalam pesan pertama dan kedua, dengan koreksi ECC pendek. Digunakan untuk mengkodekan perangkat. |

## Catatan


Contoh ini menunjukkan cara menghasilkan barcode MaxiCode menggunakan ComplexBarcodeGenerator
```cpp
[C#]
//Mode 2 dengan pesan kedua standar
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 2 dengan pesan kedua terstruktur
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 3 dengan pesan kedua standar
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 3 dengan pesan kedua terstruktur
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
