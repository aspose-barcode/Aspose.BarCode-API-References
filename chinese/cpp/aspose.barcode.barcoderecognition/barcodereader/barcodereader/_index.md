---
title: "constructor"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 构造函数。使用默认值初始化 BarCodeReader 类的新实例。需要在 C++ 中调用 ReadBarCodes() 方法之前设置图像（SetBitmapImage()）。"
type: docs
weight: 1400
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader::BarCodeReader() constructor


使用默认值初始化 [BarCodeReader](../) 类的新实例。需要在调用 [ReadBarCodes()](../readbarcodes/) 方法之前设置图像（SetBitmapImage()）。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader()
```

## 备注


此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>) constructor


从图像初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 包含图像的 Bitmap 实例 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 图像。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 图像。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型1。它可以是单个或多个。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 图像。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 图像。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 要读取的图像 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 识别区域的数组 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 适用于所有指定区域的解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 图像 | System::SharedPtr\<System::Drawing::Bitmap\> | 要读取的图像 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 识别区域的数组 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 适用于所有指定区域的解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String) constructor


从文件初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | System::String | 文件名。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | System::String | 文件名。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | System::String | 文件名。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 流。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 流。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 流。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 识别区域的数组。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 识别区域的数组。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| 类型 | System::SharedPtr\<BaseDecodeType\> | 解码类型。 |
## 备注



此示例展示了如何在亮度帧中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 解码类型。 |
## 备注



此示例展示了如何在亮度帧中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>) constructor


从亮度帧初始化 [BarCodeReader](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 要读取的亮度帧。 |
## 备注



此示例展示了如何在亮度帧中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
