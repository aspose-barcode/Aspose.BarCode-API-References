---
title: "BarCodeReader.BarCodeReader"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader yapıcı. BarCodeReader sınıfının yeni bir örneğini varsayılan değerlerle başlatır. ReadBarCodes metodunu çağırmadan önce SetBitmapImage ile görüntünün ayarlanması gerekir."
type: docs
weight: 10
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Varsayılan değerlerle yeni bir [`BarCodeReader`](../) sınıfı örneği başlatır. ReadBarCodes() metodunu çağırmadan önce görüntüyü (SetBitmapImage()) ayarlamanız gerekir.

```csharp
public BarCodeReader()
```

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_8}

Bir görüntüden [`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Görüntüyü içeren bir Bitmap örneği |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Görüntü. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Görüntü. |
| tür | BaseDecodeType | Kod çözme tür1. Tek veya çok olabilir. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Görüntü. |
| alan | Rectangle | Tanıma için alan. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Görüntü. |
| alan | Rectangle | Tanıma için alan. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Okunacak görüntü |
| alanlar | Rectangle[] | Tanıma alanlarının dizisi |
| decodeTypes | BaseDecodeType[] | Belirtilen tüm alanlar için geçerli kod çözme türleri. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Bitmap | Okunacak görüntü |
| alanlar | Rectangle[] | Tanıma alanlarının dizisi |
| tür | BaseDecodeType | Belirtilen tüm alanlar için geçerli kod çözme türü. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

Bir dosyadan [`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(string filename)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | Dize | Dosya adı. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | Dize | Dosya adı. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | Dize | Dosya adı. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Akış. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Akış. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Akış. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| alanlar | Rectangle[] | Tanıma alanlarının dizisi. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirtilen alanlarında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| alanlar | Rectangle[] | Tanıma alanlarının dizisi. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirtilen alanlarında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| alan | Rectangle | Tanıma için alan. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirli bir alanında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| alan | Rectangle | Tanıma için alan. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirli bir alanında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| tür | BaseDecodeType | Kod çözme türü. |

## Örnekler

Bu örnek, bir luminance çerçevesinde Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

[`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |
| decodeTypes | BaseDecodeType[] | Kod çözme türleri. |

## Örnekler

Bu örnek, bir luminance çerçevesinde Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

Bir luminance çerçevesinden [`BarCodeReader`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Okunacak parlaklık çerçevesi. |

## Örnekler

Bu örnek, bir luminance çerçevesinde Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


