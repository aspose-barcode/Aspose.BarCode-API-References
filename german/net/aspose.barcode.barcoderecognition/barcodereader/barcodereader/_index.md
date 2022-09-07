---
title: BarCodeReader
second_title: Aspose.BarCode für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonBarCodeReaderaspose.barcode.barcoderecognition/barcodereader Klasse mit Standardwerten. Erfordert das Setzen eines Bildes SetBitmapImage vor dem Aufruf der Methode ReadBarCodes.
type: docs
weight: 10
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse mit Standardwerten. Erfordert das Setzen eines Bildes (SetBitmapImage()) vor dem Aufruf der Methode ReadBarCodes().

```csharp
public BarCodeReader()
```

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

## BarCodeReader(Bitmap) {#constructor_1}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse aus einem Bild.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Eine Bitmap-Instanz, die das Bild enthält |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das Bild. |
| decodeTypes | BaseDecodeType[] | Typen entschlüsseln. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das Bild. |
| type | BaseDecodeType | Der Dekodierungstyp1. Es kann einfach oder mehrfach sein |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das Bild. |
| area | Rectangle | Der Bereich für Anerkennung. |
| decodeTypes | BaseDecodeType[] | Typen entschlüsseln. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das Bild. |
| area | Rectangle | Der Bereich für Anerkennung. |
| type | BaseDecodeType | Der Dekodierungstyp. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das zu lesende Bild |
| areas | Rectangle[] | Die Reihe der Erkennungsbereiche |
| decodeTypes | BaseDecodeType[] | Die Dekodierungstypen gelten für alle angegebenen Bereiche. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Bitmap | Das zu lesende Bild |
| areas | Rectangle[] | Die Reihe der Erkennungsbereiche |
| type | BaseDecodeType | Der Dekodierungstyp, der für alle angegebenen Bereiche gilt. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse aus Datei.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Dateiname. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Dateiname. |
| decodeTypes | BaseDecodeType[] | Typen entschlüsseln. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | String | Der Dateiname. |
| type | BaseDecodeType | Der Dekodierungstyp. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| type | BaseDecodeType | Der Dekodierungstyp. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Initialisiert eine neue Instanz von[`BarCodeReader`](../../barcodereader) Klasse.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| decodeTypes | BaseDecodeType[] | Typen entschlüsseln. |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
