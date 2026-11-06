---
title: "طريقة"
linktitle: "SetBarCodeImage"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد صورة البت ماب للتعرف. يجب استدعاؤها قبل طريقة ReadBarCodes() في C++."
type: docs
weight: 1500
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>) method


يحدد صورة البت ماب للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::SharedPtr\<System::Drawing::Bitmap\> | صورة البت ماب للتعرف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


يحدد صورة البت ماب والمناطق للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::SharedPtr\<System::Drawing::Bitmap\> | صورة البت ماب للتعرف. |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | قائمة المناطق للتعرف |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) method


يضبط صورة البت ماب والمساحة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes()](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::Drawing::Rectangle area)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::SharedPtr\<System::Drawing::Bitmap\> | صورة البت ماب للتعرف. |
| منطقة | System::Drawing::Rectangle | المساحة للتعرف |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::String) method


يضبط ملف الصورة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes()](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::String filename)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | System::String | ملف الصورة للتعرف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::IO::Stream\>) method


يضبط دفق الصورة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes()](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::IO::Stream> stream)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | دفق الصورة للتعرف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) method


يضبط إطار الإضاءة والمساحة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للتعرف. |
| منطقة | System::Drawing::Rectangle | المنطقة للتعرف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في منطقة محددة من إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


يضبط إطار الإضاءة والمساحات للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للتعرف. |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | المصفوفة الخاصة بمناطق التعرف. |
## ملاحظات



يوضح هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في المناطق المحددة لإطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>) method


يضبط إطار الإضاءة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](../readbarcodes/) .

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للتعرف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
