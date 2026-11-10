---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader मेथड। पहचान के लिए बिटमैप इमेज सेट करता है। ReadBarCodes मेथड को कॉल करने से पहले इसे बुलाना आवश्यक है।"
type: docs
weight: 120
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

मान्यता के लिए बिटमैप इमेज सेट करता है। ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है।

```csharp
public void SetBarCodeImage(Bitmap value)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप इमेज। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप इमेज। |
| क्षेत्रों | Rectangle[] | पहचान के लिए क्षेत्रों की सूची |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

पहचान के लिए बिटमैप इमेज और क्षेत्र सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | Bitmap | पहचान के लिए बिटमैप इमेज। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

पहचान के लिए इमेज फ़ाइल सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(string filename)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | स्ट्रिंग | पहचान के लिए इमेज फ़ाइल। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

पहचान के लिए इमेज स्ट्रीम सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।

```csharp
public void SetBarCodeImage(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | पहचान के लिए इमेज स्ट्रीम। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

पहचान के लिए ल्यूमिनेंस फ़्रेम और क्षेत्र सेट करता है। [`ReadBarCodes`](../readbarcodes/) मेथड को कॉल करने से पहले इसे बुलाना आवश्यक है।

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पहचान के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के एक निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

पहचान के लिए ल्यूमिनेंस फ़्रेम और क्षेत्रों को सेट करता है। [`ReadBarCodes`](../readbarcodes/) मेथड को कॉल करने से पहले इसे बुलाना आवश्यक है।

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पहचान के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्रों | Rectangle[] | पहचान क्षेत्रों की सरणी। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

पहचान के लिए ल्यूमिनेंस फ़्रेम सेट करता है। [`ReadBarCodes`](../readbarcodes/) मेथड को कॉल करने से पहले इसे बुलाना आवश्यक है।

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पहचान के लिए ल्यूमिनेंस फ़्रेम। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


