---
title: "constructor"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " منشئ. يهيئ نسخة جديدة من فئة BarCodeReader بالقيم الافتراضية. يتطلب تعيين الصورة (SetBitmapImage()) قبل استدعاء طريقة ReadBarCodes() في C++."
type: docs
weight: 1400
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader::BarCodeReader() constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../) بالقيم الافتراضية. يتطلب تعيين الصورة (SetBitmapImage()) قبل استدعاء طريقة [ReadBarCodes()](../readbarcodes/).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader()
```

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
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../) من صورة.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | كائن Bitmap يحتوي على الصورة |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز1. يمكن أن يكون فرديًا أو متعددًا |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة. |
| منطقة | System::Drawing::Rectangle | المنطقة للتعرف. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة. |
| منطقة | System::Drawing::Rectangle | المنطقة للتعرف. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة للقراءة |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | المصفوفة الخاصة بمناطق التعرف |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز المتاحة لجميع المناطق المحددة. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | System::SharedPtr\<System::Drawing::Bitmap\> | الصورة للقراءة |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | المصفوفة الخاصة بمناطق التعرف |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز المتاح لجميع المناطق المحددة. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String) constructor


يُنشئ نسخة جديدة من الفئة [BarCodeReader](../) من ملف.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | System::String | اسم الملف. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | System::String | اسم الملف. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | System::String | اسم الملف. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | الدفق. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | الدفق. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | الدفق. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
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

## انظر أيضًا

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | المصفوفة الخاصة بمناطق التعرف. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يوضح هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في المناطق المحددة لإطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| مناطق | System::ArrayPtr\<System::Drawing::Rectangle\> | المصفوفة الخاصة بمناطق التعرف. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يوضح هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في المناطق المحددة لإطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| منطقة | System::Drawing::Rectangle | المنطقة للتعرف. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في منطقة محددة من إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| منطقة | System::Drawing::Rectangle | المنطقة للتعرف. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في منطقة محددة من إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::SharedPtr<BaseDecodeType> type)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| نوع | System::SharedPtr\<BaseDecodeType\> | نوع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


يهيئ نسخة جديدة من فئة [BarCodeReader](../).

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | أنواع فك الترميز. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>) constructor


ينشئ مثيلاً جديداً من الفئة [BarCodeReader](../) من إطار الإضاءة.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | System::SharedPtr\<LuminanceFrame\> | إطار الإضاءة للقراءة. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف الباركود Code39 و Code128 في إطار الإضاءة.
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

## انظر أيضًا

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
