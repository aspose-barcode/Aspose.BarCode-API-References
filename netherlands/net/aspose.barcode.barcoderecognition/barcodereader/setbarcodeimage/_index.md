---
title: SetBarCodeImage
second_title: Aspose.BarCode voor .NET API-referentie
description: Stelt bitmapafbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodesmethode.
type: docs
weight: 110
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Stelt bitmapafbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmapafbeelding voor herkenning. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
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
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Stelt bitmapafbeelding en gebieden voor herkenning in. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmapafbeelding voor herkenning. |
| areas | Rectangle[] | gebieden lijst voor erkenning |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
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
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Stelt bitmapafbeelding en gebied in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Bitmap | De bitmapafbeelding voor herkenning. |
| area | Rectangle | ruimte voor herkenning |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
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
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

Stelt afbeeldingsbestand in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

```csharp
public void SetBarCodeImage(string filename)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | String | Het afbeeldingsbestand voor herkenning. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Stelt beeldstroom in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De beeldstroom voor herkenning. |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
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
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
