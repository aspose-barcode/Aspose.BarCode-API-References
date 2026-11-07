---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class. Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode dalam C++."
type: docs
weight: 1600
url: /id/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Mendapatkan mode enkoding MaxiCode. Nilai default: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan tipe barcode. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Menyusun codetext |
| virtual [GetMode](./getmode/)() const | Mendapatkan mode MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Menginisialisasi instance dari codetext yang disusun. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Mengatur mode enkoding MaxiCode. Nilai default: Auto. |
## Catatan


Contoh ini menunjukkan cara mendekode codetext MaxiCode mentah menjadi instance [MaxiCodeCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
