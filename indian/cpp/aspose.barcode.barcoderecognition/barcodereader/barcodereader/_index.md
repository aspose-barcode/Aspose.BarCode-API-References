---
title: "constructor"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " कंस्ट्रक्टर। BarCodeReader क्लास का एक नया इंस्टेंस डिफ़ॉल्ट मानों के साथ प्रारंभ करता है। C++ में ReadBarCodes() मेथड को कॉल करने से पहले इमेज (SetBitmapImage()) सेट करना आवश्यक है।"
type: docs
weight: 1400
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader::BarCodeReader() constructor


डिफ़ॉल्ट मानों के साथ [BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है। [ReadBarCodes()](../readbarcodes/) मेथड को कॉल करने से पहले इमेज (SetBitmapImage()) सेट करना आवश्यक है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader()
```

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
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस इमेज से प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | इमेज को समाहित करने वाला एक Bitmap इंस्टेंस |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | छवि। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | छवि। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार1। यह एकल या बहु हो सकता है। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | छवि। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | छवि। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | पढ़ने के लिए छवि |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान क्षेत्रों की सरणी |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | निर्दिष्ट सभी क्षेत्रों के लिए लागू डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इमेज | System::SharedPtr\<System::Drawing::Bitmap\> | पढ़ने के लिए छवि |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान क्षेत्रों की सरणी |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | निर्दिष्ट सभी क्षेत्रों के लिए लागू डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String) constructor


फ़ाइल से [BarCodeReader](../) वर्ग का नया उदाहरण आरंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | System::String | फ़ाइलनाम। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | System::String | फ़ाइलनाम। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | System::String | फ़ाइलनाम। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | स्ट्रीम। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | स्ट्रीम। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | स्ट्रीम। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान क्षेत्रों की सरणी। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्रों | System::ArrayPtr\<System::Drawing::Rectangle\> | पहचान क्षेत्रों की सरणी। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ़्रेम के निर्दिष्ट क्षेत्रों में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम के निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| क्षेत्र | System::Drawing::Rectangle | पहचान के लिए क्षेत्र। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम के निर्दिष्ट क्षेत्र में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::SharedPtr<BaseDecodeType> type)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| प्रकार | System::SharedPtr\<BaseDecodeType\> | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | डिकोड प्रकार। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>) constructor


ल्यूमिनेंस फ्रेम से [BarCodeReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्रेम | System::SharedPtr\<LuminanceFrame\> | पढ़ने के लिए ल्यूमिनेंस फ़्रेम। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि ल्यूमिनेंस फ्रेम में Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
