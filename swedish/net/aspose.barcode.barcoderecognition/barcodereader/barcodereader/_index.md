---
title: BarCodeReader
second_title: Aspose.BarCode för .NET API-referens
description: Initierar en ny instans avBarCodeReaderaspose.barcode.barcoderecognition/barcodereader klass med standardvärden. Kräver att ställa in bild SetBitmapImage innan metoden ReadBarCodes anropas.
type: docs
weight: 10
url: /sv/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) klass med standardvärden. Kräver att ställa in bild (SetBitmapImage()) innan metoden ReadBarCodes() anropas.

```csharp
public BarCodeReader()
```

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) klass från en bild.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | En bitmappsinstans som innehåller bilden |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden. |
| decodeTypes | BaseDecodeType[] | Avkoda typer. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden. |
| type | BaseDecodeType | Avkodningstyp1. Det kan vara singel eller flerfaldig |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden. |
| area | Rectangle | Området för erkännande. |
| decodeTypes | BaseDecodeType[] | Avkoda typer. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden. |
| area | Rectangle | Området för erkännande. |
| type | BaseDecodeType | Avkodningstypen. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden att läsa |
| areas | Rectangle[] | Uppsättningen av igenkänningsområden |
| decodeTypes | BaseDecodeType[] | De avkodningstyper som gäller för alla angivna områden. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Bitmap | Bilden att läsa |
| areas | Rectangle[] | Uppsättningen av igenkänningsområden |
| type | BaseDecodeType | Avkodningstypen som gäller för alla angivna områden. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) klass från fil.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Filnamnet. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Filnamnet. |
| decodeTypes | BaseDecodeType[] | Avkoda typer. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Filnamnet. |
| type | BaseDecodeType | Avkodningstypen. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |
| type | BaseDecodeType | Avkodningstypen. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Initierar en ny instans av[`BarCodeReader`](../../barcodereader) class.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |
| decodeTypes | BaseDecodeType[] | Avkoda typer. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
