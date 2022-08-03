---
title: SetBarCodeImage
second_title: Aspose.BarCode für .NET-API-Referenz
description: Legt ein Bitmap-Bild für die Erkennung fest. Muss vor der Methode ReadBarCodes aufgerufen werden.
type: docs
weight: 110
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Legt ein Bitmap-Bild für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | Bitmap | Das Bitmap-Bild für die Erkennung. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Legt Bitmap-Bild und Erkennungsbereiche fest. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | Bitmap | Das Bitmap-Bild für die Erkennung. |
| areas | Rectangle[] | Bereichsliste zur Anerkennung |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Legt Bitmap-Bild und Erkennungsbereich fest. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | Bitmap | Das Bitmap-Bild für die Erkennung. |
| area | Rectangle | Bereich für Anerkennung |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

Legt die Bilddatei für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Die Bilddatei für die Erkennung. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Legt den Bildstrom für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Bildstrom zur Erkennung. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
