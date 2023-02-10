---
title: SetBarCodeImage
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: पहचन के लए बटमैप छव सेट करत है क ReadBarCodes वध से पहले कल कय जन चहए
type: docs
weight: 110
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

पहचान के लिए बिटमैप छवि सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Bitmap value)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप छवि। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

पहचान के लिए बिटमैप छवि और क्षेत्र सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप छवि। |
| areas | Rectangle[] | मान्यता के लिए क्षेत्रों की सूची |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

पहचान के लिए बिटमैप छवि और क्षेत्र सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप छवि। |
| area | Rectangle | मान्यता के लिए क्षेत्र |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

पहचान के लिए छवि फ़ाइल सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(string filename)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | String | मान्यता के लिए छवि फ़ाइल। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

पहचान के लिए इमेज स्ट्रीम सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | पहचान के लिए इमेज स्ट्रीम. |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
