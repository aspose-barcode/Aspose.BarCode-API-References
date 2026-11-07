---
title: "metode"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Mengatur codetext sebagai urutan byte dalam C++."
type: docs
weight: 700
url: /id/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Atur codetext sebagai urutan byte.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Byte dari codetext |

## Lihat Juga

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | System::String | String CodeText |
| enkoding | System::SharedPtr\<System::Text::Encoding\> | Encoding yang diterapkan |
## Catatan


Mengenkripsi Unicode **codeText** menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya, fungsi secara otomatis menyisipkan [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Fungsi ini hanya ditujukan untuk digunakan dengan barcode 2D (mis., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Ini memungkinkan enkoding manual teks Unicode menggunakan encoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, encoding [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) disarankan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang mematuhi GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.


Contoh ini menunjukkan cara menggunakan **SetCodeText** untuk mengatur teks ber-encoding Unicode pada barcode 2D dengan berbagai encoding:


```cpp
[C#]
//Enkode teks QR Code menggunakan UTF-8 dengan BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Enkode teks DataMatrix menggunakan Shift-JIS (encoding Jepang)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Lihat Juga

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | System::String | String CodeText |
| enkoding | System::SharedPtr\<System::Text::Encoding\> | Encoding yang diterapkan |
| insertBOM | bool | Menunjukkan apakah akan menyisipkan byte order mark (BOM) ketika encoding yang ditentukan mendukungnya (mis., UTF-8, UTF-16, UTF-32). Jika disetel ke **true**, BOM akan ditambahkan; jika **false**, BOM akan dihilangkan meskipun encoding biasanya menggunakannya. |
## Catatan


Mengenkripsi Unicode **codeText** menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya dan **insertBOM** disetel ke **true**, fungsi menyertakan [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Fungsi ini hanya ditujukan untuk digunakan dengan barcode 2D (mis., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Ini memungkinkan enkoding manual teks Unicode menggunakan encoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, encoding [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) disarankan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang mematuhi GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.


Contoh ini menunjukkan cara menggunakan **SetCodeText** dengan atau tanpa BOM untuk barcode 2D.


```cpp
[C#]
    //Enkode teks kode menggunakan UTF-8 dengan BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Enkode teks kode menggunakan UTF-8 tanpa BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Lihat Juga

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
