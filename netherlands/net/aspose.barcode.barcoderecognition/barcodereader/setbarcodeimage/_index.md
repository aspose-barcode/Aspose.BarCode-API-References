---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader-methode. Stelt bitmap-afbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes-methode."
type: docs
weight: 120
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

Stelt bitmap‑afbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()‑methode.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmap-afbeelding voor herkenning. |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(bmp);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

Stelt bitmapafbeelding en gebieden in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmap-afbeelding voor herkenning. |
| gebieden | Rectangle[] | lijst met gebieden voor herkenning |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) });
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)})
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

Stelt bitmapafbeelding en gebied in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmap-afbeelding voor herkenning. |
| gebied | Rectangle | gebied voor herkenning |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height));
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

Stelt het afbeeldingsbestand in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode.

```csharp
public void SetBarCodeImage(string filename)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | String | Het afbeeldingsbestand voor herkenning. |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

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

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

Stelt de afbeeldingsstroom in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | De afbeeldingsstroom voor herkenning. |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(fstr);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(fstr)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

Stelt het luminanceframe en gebied in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](../readbarcodes/) methode.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frame | LuminanceFrame | Het luminanceframe voor herkenning. |
| gebied | Rectangle | Het gebied voor herkenning. |

## Voorbeelden

Dit voorbeeld toont hoe u Code39- en Code128-barcodes kunt detecteren in een opgegeven gebied van een luminanceframe.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, new Rectangle(0, 0, width, height));
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Zie ook

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

Stelt het luminanceframe en de gebieden in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](../readbarcodes/) methode.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frame | LuminanceFrame | Het luminanceframe voor herkenning. |
| gebieden | Rectangle[] | De array van herkenningsgebieden. |

## Voorbeelden

Dit voorbeeld toont hoe u Code39- en Code128-barcodes kunt detecteren in opgegeven gebieden van een luminanceframe.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, areas);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Zie ook

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

Stelt het luminanceframe in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](../readbarcodes/) methode.

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frame | LuminanceFrame | Het luminanceframe voor herkenning. |

## Voorbeelden

Dit voorbeeld toont hoe u Code39- en Code128-barcodes kunt detecteren in een luminanceframe.

```csharp
int width = 1920;
int height = 1080;
int rowStride = 2048;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height, rowStride, 90);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Zie ook

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


