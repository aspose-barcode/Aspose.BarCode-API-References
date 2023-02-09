---
title: BarCodeReader
second_title: Aspose.BarCode untuk .NET API Referensi
description: Menginisialisasi instance baru dariBarCodeReaderaspose.barcode.barcoderecognition/barcodereader/ kelas dengan nilai default. Diperlukan untuk menyetel gambar SetBitmapImage sebelum memanggil metode ReadBarCodes.
type: docs
weight: 10
url: /id/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas dengan nilai default. Diperlukan untuk menyetel gambar (SetBitmapImage()) sebelum memanggil metode ReadBarCodes().

```csharp
public BarCodeReader()
```

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas dari gambar.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Contoh Bitmap yang berisi gambar |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Foto. |
| decodeTypes | BaseDecodeType[] | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Foto. |
| type | BaseDecodeType | Jenis dekode1. Itu bisa tunggal atau banyak |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Foto. |
| area | Rectangle | Area untuk pengakuan. |
| decodeTypes | BaseDecodeType[] | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Foto. |
| area | Rectangle | Area untuk pengakuan. |
| type | BaseDecodeType | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Gambar untuk dibaca |
| areas | Rectangle[] | Array area pengenalan |
| decodeTypes | BaseDecodeType[] | Jenis dekode berlaku untuk semua area yang ditentukan. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | Bitmap | Gambar untuk dibaca |
| areas | Rectangle[] | Array area pengenalan |
| type | BaseDecodeType | Jenis dekode berlaku untuk semua area yang ditentukan. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas dari file.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filename | String | Nama file. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filename | String | Nama file. |
| decodeTypes | BaseDecodeType[] | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filename | String | Nama file. |
| type | BaseDecodeType | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran. |
| type | BaseDecodeType | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Menginisialisasi instance baru dari[`BarCodeReader`](../) kelas.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran. |
| decodeTypes | BaseDecodeType[] | Jenis dekode. |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Lihat juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
