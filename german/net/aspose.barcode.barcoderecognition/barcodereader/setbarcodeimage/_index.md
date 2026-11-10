---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Methode. Legt das Bitmap-Bild für die Erkennung fest. Muss vor der ReadBarCodes-Methode aufgerufen werden."
type: docs
weight: 120
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

Setzt das Bitmap-Bild für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | Bitmap | Das Bitmap-Bild für die Erkennung. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

Setzt das Bitmap-Bild und die Bereiche für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | Bitmap | Das Bitmap-Bild für die Erkennung. |
| Bereiche | Rectangle[] | Liste von Bereichen für die Erkennung |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

Setzt das Bitmap-Bild und den Bereich für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | Bitmap | Das Bitmap-Bild für die Erkennung. |
| Bereich | Rectangle | Bereich für die Erkennung |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

Setzt die Bilddatei für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(string filename)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | String | Die Bilddatei für die Erkennung. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

Setzt den Bild-Stream für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Strom | Der Bild-Stream für die Erkennung. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

Legt den LuminanceFrame und den Bereich für die Erkennung fest. Muss vor der [`ReadBarCodes`](../readbarcodes/)-Methode aufgerufen werden.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame für die Erkennung. |
| Bereich | Rectangle | Der Bereich für die Erkennung. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem angegebenen Bereich eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

Legt den LuminanceFrame und die Bereiche für die Erkennung fest. Muss vor der [`ReadBarCodes`](../readbarcodes/)-Methode aufgerufen werden.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame für die Erkennung. |
| Bereiche | Rectangle[] | Das Array der Erkennungsbereiche. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in angegebenen Bereichen eines LuminanceFrames erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

Legt den Luminanzrahmen für die Erkennung fest. Muss vor der [`ReadBarCodes`](../readbarcodes/) Methode aufgerufen werden.

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Frame | LuminanceFrame | Der LuminanceFrame für die Erkennung. |

## Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes in einem LuminanceFrame erkannt werden können.

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

### Siehe auch

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


