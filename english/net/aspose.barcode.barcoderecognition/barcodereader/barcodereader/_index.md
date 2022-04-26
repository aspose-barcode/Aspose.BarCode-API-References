---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader constructor (1 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class with default values. Requires to set image (SetBitmapImage()) before to call ReadBarCodes() method.

```csharp
public BarCodeReader()
```

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (2 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class from an image.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | A Bitmap instance containing the image |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (3 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image. |
| decodeTypes | BaseDecodeType[] | Decode types. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (4 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image. |
| type | BaseDecodeType | The decode type1. It can be single or multy |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (5 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image. |
| area | Rectangle | The area for recognition. |
| decodeTypes | BaseDecodeType[] | Decode types. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (6 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image. |
| area | Rectangle | The area for recognition. |
| type | BaseDecodeType | The decode type. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (7 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image to read |
| areas | Rectangle[] | The array of recognition areas |
| decodeTypes | BaseDecodeType[] | The decode types applicable for all the areas specified. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (8 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Bitmap | The image to read |
| areas | Rectangle[] | The array of recognition areas |
| type | BaseDecodeType | The decode type applicable for all the areas specified. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (9 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class from file.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The filename. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (10 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The filename. |
| decodeTypes | BaseDecodeType[] | Decode types. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (11 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The filename. |
| type | BaseDecodeType | The decode type. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (12 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (13 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| type | BaseDecodeType | The decode type. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader constructor (14 of 14)

Initializes a new instance of the [`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| decodeTypes | BaseDecodeType[] | Decode types. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namespace [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assembly [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
