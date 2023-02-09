---
title: BarCodeReader
second_title: Aspose.BarCode voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetBarCodeReaderaspose.barcode.barcoderecognition/barcodereader/ klasse met standaardwaarden. Vereist het instellen van de afbeelding SetBitmapImage voordat de methode ReadBarCodes wordt aangeroepen.
type: docs
weight: 10
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse met standaardwaarden. Vereist het instellen van de afbeelding (SetBitmapImage()) voordat de methode ReadBarCodes() wordt aangeroepen.

```csharp
public BarCodeReader()
```

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse van een afbeelding.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | Een Bitmap-instantie die de afbeelding bevat |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding. |
| decodeTypes | BaseDecodeType[] | Decodeer typen. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding. |
| type | BaseDecodeType | Het decodeertype1. Het kan enkelvoudig of meervoudig zijn |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding. |
| area | Rectangle | Het gebied voor herkenning. |
| decodeTypes | BaseDecodeType[] | Decodeer typen. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding. |
| area | Rectangle | Het gebied voor herkenning. |
| type | BaseDecodeType | Het decoderingstype. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding om te lezen |
| areas | Rectangle[] | De reeks herkenningsgebieden |
| decodeTypes | BaseDecodeType[] | De decoderingstypen die van toepassing zijn op alle gespecificeerde gebieden. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | Bitmap | De afbeelding om te lezen |
| areas | Rectangle[] | De reeks herkenningsgebieden |
| type | BaseDecodeType | Het decoderingstype dat van toepassing is op alle gespecificeerde gebieden. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse uit bestand.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | String | De bestandsnaam. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | String | De bestandsnaam. |
| decodeTypes | BaseDecodeType[] | Decodeer typen. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | String | De bestandsnaam. |
| type | BaseDecodeType | Het decoderingstype. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |
| type | BaseDecodeType | Het decoderingstype. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Initialiseert een nieuw exemplaar van het[`BarCodeReader`](../) klasse.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |
| decodeTypes | BaseDecodeType[] | Decodeer typen. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
