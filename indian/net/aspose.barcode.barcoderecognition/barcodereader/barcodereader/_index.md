---
title: "BarCodeReader.BarCodeReader"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader कंस्ट्रक्टर। डिफ़ॉल्ट मानों के साथ BarCodeReader क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। ReadBarCodes मेथड को कॉल करने से पहले इमेज SetBitmapImage सेट करना आवश्यक है।"
type: docs
weight: 10
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

[`BarCodeReader`](../) क्लास का नया इंस्टेंस डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है। ReadBarCodes() मेथड को कॉल करने से पहले इमेज (SetBitmapImage()) सेट करना आवश्यक है।

```csharp
public BarCodeReader()
```

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

## BarCodeReader(Bitmap) {#constructor_8}

एक छवि से [`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | छवि शामिल करने वाला Bitmap उदाहरण |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | छवि। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | छवि। |
| प्रकार | BaseDecodeType | डिकोड type1। यह एकल या बहु हो सकता है। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | छवि। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | छवि। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | पढ़ने के लिए छवि |
| क्षेत्रों | Rectangle[] | पहचान क्षेत्रों की सरणी |
| decodeTypes | BaseDecodeType[] | निर्दिष्ट सभी क्षेत्रों के लिए लागू डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छवि | Bitmap | पढ़ने के लिए छवि |
| क्षेत्रों | Rectangle[] | पहचान क्षेत्रों की सरणी |
| प्रकार | BaseDecodeType | निर्दिष्ट सभी क्षेत्रों के लिए लागू डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

फ़ाइल से [`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(string filename)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | स्ट्रिंग | फ़ाइलनाम। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | स्ट्रिंग | फ़ाइलनाम। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | स्ट्रिंग | फ़ाइलनाम। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | स्ट्रीम। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | स्ट्रीम। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | स्ट्रीम। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

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

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्रों | Rectangle[] | पहचान क्षेत्रों की सरणी। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्रों | Rectangle[] | पहचान क्षेत्रों की सरणी। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के एक निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्र | Rectangle | पहचान के लिए क्षेत्र। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम के एक निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| प्रकार | BaseDecodeType | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

[`BarCodeReader`](../) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

ल्यूमिनेंस फ़्रेम से [`BarCodeReader`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है।

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | LuminanceFrame | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |

## उदाहरण

यह नमूना दिखाता है कि ल्यूमिनेंस फ़्रेम में Code39 और Code128 बारकोड कैसे पता लगाए जाएँ।

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

### और देखें

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


