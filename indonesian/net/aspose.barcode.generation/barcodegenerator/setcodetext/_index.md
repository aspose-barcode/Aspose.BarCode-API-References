---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Metode BarcodeGenerator. Atur codetext sebagai urutan byte"
type: docs
weight: 100
url: /id/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Atur codetext sebagai urutan byte.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeBytes | Byte[] | Byte codetext |

### Lihat Juga

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Mengenkripsi **codeText** Unicode menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya, fungsi secara otomatis menyisipkan sebuah [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Fungsi ini hanya ditujukan untuk digunakan dengan barcode 2D (misalnya, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Ini memungkinkan enkoding manual teks Unicode menggunakan enkoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, enkoding [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) direkomendasikan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang mematuhi GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | String | String CodeText |
| encoding | Encoding | Encoding yang diterapkan |

## Contoh

Contoh ini menunjukkan cara menggunakan `SetCodeText` untuk mengatur teks ber-enkoding Unicode bagi barcode 2D dengan menggunakan enkoding yang berbeda:

```csharp
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

//Enkode teks DataMatrix menggunakan Shift-JIS (enkoding Jepang)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Lihat Juga

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Mengenkripsi **codeText** Unicode menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya dan **insertBOM** diatur ke `true`, fungsi menyertakan sebuah [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Fungsi ini hanya ditujukan untuk digunakan dengan barcode 2D (misalnya, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Ini memungkinkan enkoding manual teks Unicode menggunakan enkoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, enkoding [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) direkomendasikan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang mematuhi GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | String | String CodeText |
| encoding | Encoding | Encoding yang diterapkan |
| insertBOM | Boolean | Menunjukkan apakah akan menyisipkan byte order mark (BOM) ketika encoding yang ditentukan mendukungnya (mis., UTF-8, UTF-16, UTF-32). Jika diatur ke `true`, BOM akan ditambahkan; jika `false`, BOM akan dihilangkan meskipun encoding biasanya menggunakannya. |

## Contoh

Contoh ini menunjukkan cara menggunakan `SetCodeText` dengan atau tanpa BOM untuk barcode 2D.

```csharp
[C#]
//Enkode codetext menggunakan UTF-8 dengan BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Enkode codetext menggunakan UTF-8 tanpa BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Lihat Juga

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


