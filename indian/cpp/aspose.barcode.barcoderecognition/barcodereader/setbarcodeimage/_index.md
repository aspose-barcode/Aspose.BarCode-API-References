---
title: "विधि"
linktitle: "SetBarCodeImage"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। पहचान के लिए बिटमैप इमेज सेट करता है। C++ में ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है।"
type: docs
weight: 1500
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>) method


पहचान के लिए बिटमैप इमेज सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल करना आवश्यक है।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::SharedPtr\<System::Drawing::Bitmap\> | पहचान के लिए बिटमैप इमेज। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल करना आवश्यक है।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::SharedPtr\<System::Drawing::Bitmap\> | पहचान के लिए बिटमैप इमेज। |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान के लिए क्षेत्रों की सूची |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) method


पहचान के लिए बिटमैप छवि और क्षेत्र सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::Drawing::Rectangle area)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::SharedPtr\<System::Drawing::Bitmap\> | पहचान के लिए बिटमैप इमेज। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::String) method


पहचान के लिए इमेज फ़ाइल सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::String filename)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | System::String | पहचान के लिए इमेज फ़ाइल। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::IO::Stream\>) method


पहचान के लिए इमेज स्ट्रीम सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::IO::Stream> stream)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | पहचान के लिए इमेज स्ट्रीम। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) method


पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्र सेट करता है। इसे [ReadBarCodes](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पहचान के लिए ल्यूमिनेंस फ्रेम। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम के निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्रों को सेट करता है। इसे [ReadBarCodes](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पहचान के लिए ल्यूमिनेंस फ्रेम। |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान क्षेत्रों की सरणी। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>) method


पहचान के लिए ल्यूमिनेंस फ्रेम सेट करता है। इसे [ReadBarCodes](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पहचान के लिए ल्यूमिनेंस फ्रेम। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
