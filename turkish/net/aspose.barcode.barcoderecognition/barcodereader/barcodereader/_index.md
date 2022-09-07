---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API Referansı
description: Yeni bir örneğini başlatırBarCodeReaderaspose.barcode.barcoderecognition/barcodereader varsayılan değerlere sahip sınıf. ReadBarCodes yöntemini çağırmadan önce görüntünün SetBitmapImage ayarlanmasını gerektirir.
type: docs
weight: 10
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) varsayılan değerlere sahip sınıf. ReadBarCodes() yöntemini çağırmadan önce görüntünün (SetBitmapImage()) ayarlanmasını gerektirir.

```csharp
public BarCodeReader()
```

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) bir görüntüden sınıf.

```csharp
public BarCodeReader(Bitmap image)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | Resmi içeren bir Bitmap örneği |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | Görüntü. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | Görüntü. |
| type | BaseDecodeType | Kod çözme tipi1. Tek veya çok olabilir |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | Görüntü. |
| area | Rectangle | Tanıma alanı. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | Görüntü. |
| area | Rectangle | Tanıma alanı. |
| type | BaseDecodeType | Kod çözme türü. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | okunacak resim |
| areas | Rectangle[] | Tanıma alanları dizisi |
| decodeTypes | BaseDecodeType[] | Belirtilen tüm alanlar için geçerli kod çözme türleri. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | Bitmap | okunacak resim |
| areas | Rectangle[] | Tanıma alanları dizisi |
| type | BaseDecodeType | Belirtilen tüm alanlar için geçerli kod çözme türü. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) dosyadan sınıf.

```csharp
public BarCodeReader(string filename)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filename | String | Dosya adı. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filename | String | Dosya adı. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filename | String | Dosya adı. |
| type | BaseDecodeType | Kod çözme türü. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış. |
| type | BaseDecodeType | Kod çözme türü. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Yeni bir örneğini başlatır[`BarCodeReader`](../../barcodereader) sınıf.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Akış. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
