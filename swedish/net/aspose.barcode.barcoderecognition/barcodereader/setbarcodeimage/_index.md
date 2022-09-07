---
title: SetBarCodeImage
second_title: Aspose.BarCode för .NET API-referens
description: Ställer in bitmappsbild för igenkänning. Måste anropas före metoden ReadBarCodes.
type: docs
weight: 110
url: /sv/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Ställer in bitmappsbild för igenkänning. Måste anropas före metoden ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | Bitmap | Bitmappsbilden för igenkänning. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Ställer in bitmappsbild och områden för igenkänning. Måste anropas före metoden ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | Bitmap | Bitmappsbilden för igenkänning. |
| areas | Rectangle[] | områdeslista för erkännande |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Ställer in bitmappsbild och område för igenkänning. Måste anropas före metoden ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | Bitmap | Bitmappsbilden för igenkänning. |
| area | Rectangle | område för erkännande |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

Ställer in bildfil för igenkänning. Måste anropas före metoden ReadBarCodes().

```csharp
public void SetBarCodeImage(string filename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | String | Bildfilen för igenkänning. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Ställer in bildström för igenkänning. Måste anropas före metoden ReadBarCodes().

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Bildströmmen för igenkänning. |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* class [BarCodeReader](../../barcodereader)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* hopsättning [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
