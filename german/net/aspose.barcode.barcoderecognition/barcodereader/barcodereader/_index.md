---
title: "BarCodeReader.BarCodeReader"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader constructor. Initialisiert eine neue Instanz der BarCodeReader-Klasse mit Standardwerten. Erfordert, dass das Bild SetBitmapImage gesetzt wird, bevor die Methode ReadBarCodes aufgerufen wird."
type: docs
weight: 10
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse mit Standardwerten. Erfordert, dass das Bild (SetBitmapImage()) gesetzt wird, bevor die Methode ReadBarCodes() aufgerufen wird.

```csharp
public BarCodeReader()
```

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_8}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse aus einem Bild.

```csharp
public BarCodeReader(Bitmap image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Eine Bitmap-Instanz, die das Bild enthält |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das Bild. |
| decodeTypes | BaseDecodeType[] | Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das Bild. |
| Typ | BaseDecodeType | Der Dekodierungstyp1. Er kann einfach oder mehrfach sein. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das Bild. |
| Bereich | Rectangle | Der Bereich für die Erkennung. |
| decodeTypes | BaseDecodeType[] | Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das Bild. |
| Bereich | Rectangle | Der Bereich für die Erkennung. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das zu lesende Bild |
| Bereiche | Rectangle[] | Das Array der Erkennungsbereiche |
| decodeTypes | BaseDecodeType[] | Die Dekodierungstypen, die für alle angegebenen Bereiche gelten. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bild | Bitmap | Das zu lesende Bild |
| Bereiche | Rectangle[] | Das Array der Erkennungsbereiche |
| Typ | BaseDecodeType | Der Dekodierungstyp, der für alle angegebenen Bereiche gilt. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse aus einer Datei.

```csharp
public BarCodeReader(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | String | Der Dateiname. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | String | Der Dateiname. |
| decodeTypes | BaseDecodeType[] | Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | String | Der Dateiname. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Strom | Der Stream. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Strom | Der Stream. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Strom | Der Stream. |
| decodeTypes | BaseDecodeType[] | Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| Bereiche | Rectangle[] | Das Array der Erkennungsbereiche. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in angegebenen Bereichen eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| Bereiche | Rectangle[] | Das Array der Erkennungsbereiche. |
| decodeTypes | BaseDecodeType[] | Die Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in angegebenen Bereichen eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| Bereich | Rectangle | Der Bereich für die Erkennung. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem angegebenen Bereich eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| Bereich | Rectangle | Der Bereich für die Erkennung. |
| decodeTypes | BaseDecodeType[] | Die Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem angegebenen Bereich eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| Typ | BaseDecodeType | Der Dekodierungstyp. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem LuminanceFrame erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse.

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |
| decodeTypes | BaseDecodeType[] | Die Dekodierungstypen. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem LuminanceFrame erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

Initialisiert eine neue Instanz der [`BarCodeReader`](../)-Klasse aus einem LuminanceFrame.

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame zum Lesen. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem LuminanceFrame erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


