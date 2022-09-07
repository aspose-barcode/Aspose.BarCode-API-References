---
title: SetBarCodeImage
second_title: Aspose.BarCode for .NET API Referansı
description: Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes yönteminden önce çağrılmalıdır.
type: docs
weight: 110
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| value | Bitmap | Tanıma için bitmap görüntüsü. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Tanıma için bitmap görüntüsünü ve alanları ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| value | Bitmap | Tanıma için bitmap görüntüsü. |
| areas | Rectangle[] | tanıma için alanlar listesi |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Tanıma için bitmap görüntüsünü ve alanını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| value | Bitmap | Tanıma için bitmap görüntüsü. |
| area | Rectangle | tanıma alanı |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

Görüntü dosyasını tanıma için ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(string filename)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filename | String | Tanıma için görüntü dosyası. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Tanıma için görüntü akışını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Tanıma için görüntü akışı. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
