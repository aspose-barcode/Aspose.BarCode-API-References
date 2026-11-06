---
title: "method"
linktitle: "SetBarCodeImage"
second_title: "Aspose.BarCode for C++ API 参考"
description: " method. 设置用于识别的位图图像。必须在 C++ 中调用 ReadBarCodes() 方法之前调用此方法。"
type: docs
weight: 1500
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>) method


设置用于识别的位图图像。必须在调用 [ReadBarCodes()](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::SharedPtr\<System::Drawing::Bitmap\> | 用于识别的位图图像。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


设置用于识别的位图图像和区域。必须在调用 [ReadBarCodes()](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::SharedPtr\<System::Drawing::Bitmap\> | 用于识别的位图图像。 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 用于识别的区域列表 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) method


设置用于识别的位图图像和区域。必须在调用 [ReadBarCodes()](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::Drawing::Rectangle area)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::SharedPtr\<System::Drawing::Bitmap\> | 用于识别的位图图像。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::String) method


设置用于识别的图像文件。必须在调用 [ReadBarCodes()](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::String filename)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 文件名 | System::String | 用于识别的图像文件。 |
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::IO::Stream\>) method


设置用于识别的图像流。必须在调用 [ReadBarCodes()](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 用于识别的图像流。 |
## 备注



此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) method


设置用于识别的亮度帧和区域。必须在调用 [ReadBarCodes](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 用于识别的亮度帧。 |
| 区域 | System::Drawing::Rectangle | 用于识别的区域。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


设置用于识别的亮度帧和多个区域。必须在调用 [ReadBarCodes](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 用于识别的亮度帧。 |
| 区域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 识别区域的数组。 |
## 备注



此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>) method


设置用于识别的亮度帧。必须在调用 [ReadBarCodes](../readbarcodes/) 方法之前调用。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 帧 | System::SharedPtr\<LuminanceFrame\> | 用于识别的亮度帧。 |
## 备注



此示例展示了如何在亮度帧中检测 Code39 和 Code128 条码。
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

## 另见

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
