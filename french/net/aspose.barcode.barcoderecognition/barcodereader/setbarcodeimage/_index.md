---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode BarCodeReader. Définit l’image bitmap pour la reconnaissance. Doit être appelée avant la méthode ReadBarCodes."
type: docs
weight: 120
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

Définit l'image bitmap pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | Bitmap | L’image bitmap pour la reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

Définit l'image bitmap et les zones pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | Bitmap | L’image bitmap pour la reconnaissance. |
| zones | Rectangle[] | liste des zones pour la reconnaissance |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

Définit l'image bitmap et la zone pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | Bitmap | L’image bitmap pour la reconnaissance. |
| zone | Rectangle | zone pour la reconnaissance |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

Définit le fichier d'image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(string filename)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | String | Le fichier image pour la reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

Définit le flux d'image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux d’image pour la reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

Définit la trame de luminance et la zone pour la reconnaissance. Doit être appelée avant la méthode [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cadre | LuminanceFrame | La trame de luminance pour la reconnaissance. |
| zone | Rectangle | La zone de reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128 dans une zone spécifiée d’une trame de luminance.

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

### Voir aussi

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

Définit la trame de luminance et les zones pour la reconnaissance. Doit être appelée avant la méthode [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cadre | LuminanceFrame | La trame de luminance pour la reconnaissance. |
| zones | Rectangle[] | Le tableau des zones de reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128 dans des zones spécifiées d’une trame de luminance.

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

### Voir aussi

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

Définit la trame de luminance pour la reconnaissance. Doit être appelée avant la méthode [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cadre | LuminanceFrame | La trame de luminance pour la reconnaissance. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128 dans une trame de luminance.

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

### Voir aussi

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


