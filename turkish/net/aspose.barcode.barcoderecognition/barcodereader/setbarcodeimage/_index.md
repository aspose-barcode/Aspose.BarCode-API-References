---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader yöntemi. Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes yönteminden önce çağrılmalıdır."
type: docs
weight: 120
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Bitmap | Tanıma için bitmap görüntüsü. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

Tanıma için bitmap görüntüsü ve alanları ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Bitmap | Tanıma için bitmap görüntüsü. |
| alanlar | Rectangle[] | tanıma için alan listesi |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

Tanıma için bitmap görüntüsü ve alanı ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Bitmap | Tanıma için bitmap görüntüsü. |
| alan | Rectangle | tanıma için alan |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

Tanıma için görüntü dosyasını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(string filename)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | Dize | Tanıma için görüntü dosyası. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

Tanıma için görüntü akışını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Tanıma için görüntü akışı. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

Tanıma için luminance çerçevesini ve alanı ayarlar. [`ReadBarCodes`](../readbarcodes/) yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Tanıma için luminance çerçevesi. |
| alan | Rectangle | Tanıma için alan. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirli bir alanında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

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

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

Tanıma için luminance çerçevesini ve alanları ayarlar. [`ReadBarCodes`](../readbarcodes/) yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Tanıma için luminance çerçevesi. |
| alanlar | Rectangle[] | Tanıma alanlarının dizisi. |

## Örnekler

Bu örnek, bir luminance çerçevesinin belirtilen alanlarında Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

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

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

Tanıma için luminance çerçevesini ayarlar. [`ReadBarCodes`](../readbarcodes/) yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | LuminanceFrame | Tanıma için luminance çerçevesi. |

## Örnekler

Bu örnek, bir luminance çerçevesinde Code39 ve Code128 barkodlarını nasıl tespit edeceğinizi gösterir.

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

### Ayrıca Bakınız

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


