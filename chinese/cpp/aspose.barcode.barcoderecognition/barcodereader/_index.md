---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader 类"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader 类。BarCodeReader 封装了一幅可能包含一个或多个条形码的图像，然后可以在 C++ 中执行 ReadBarCodes 操作来检测条形码。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Abort](./abort/)() | 该函数请求从其他线程终止当前的识别会话。Abort 是不可阻塞的方法，调用后立即返回控制权。应在识别过程过长时使用此方法。 |
| [BarCodeReader](./barcodereader/)() | 使用默认值初始化 [BarCodeReader](./) 类的新实例。调用 [ReadBarCodes()](./readbarcodes/) 方法前，需要先设置图像 (SetBitmapImage())。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 从图像初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::String) | 从文件初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [BarCodeReader](./) 类的新实例。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | 从亮度帧初始化 [BarCodeReader](./) 类的新实例。 |
| [Dispose](./dispose/)() override | 释放资源 |
| [ExportToXml](./exporttoxml/)(System::String) | 将 [BarCode](../../aspose.barcode/) 属性导出到指定的 xml 文件 |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | 将 [BarCode](../../aspose.barcode/) 属性导出到指定的 xml 流 |
| [get_BarCodeReadType](./get_barcodereadtype/)() | 获取用于识别的条形码解码类型。必须在调用 [ReadBarCodes](./readbarcodes/) 前设置。 |
| [get_BarcodeSettings](./get_barcodesettings/)() | 主要的 [BarCode](../../aspose.barcode/) 解码参数。包含影响识别数据的参数。 |
| [get_FoundBarCodes](./get_foundbarcodes/)() | 获取已识别的 [BarCodeResult](../barcoderesult/) 数组 |
| [get_FoundCount](./get_foundcount/)() | 获取已识别的条形码数量 |
| static [get_ProcessorSettings](./get_processorsettings/)() | 获取使用处理器核心的设置。 |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) 允许手动配置识别质量和速度。您可以通过内置预设快速设置 [QualitySettings](../qualitysettings/)：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或者手动配置各个选项。[QualitySettings](../qualitysettings/) 的默认值是 NormalQuality。 |
| [get_Timeout](./get_timeout/)() | 获取识别过程的超时时间（毫秒）。 |
| static [ImportFromXml](./importfromxml/)(System::String) | 从指定的 xml 文件导入 [BarCode](../../aspose.barcode/) 属性并将其应用于当前的 [BarCodeReader](./) 实例。 |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 从指定的 xml 流导入 [BarCode](../../aspose.barcode/) 属性并将其应用于当前的 [BarCodeReader](./) 实例。 |
| [ReadBarCodes](./readbarcodes/)() | 从图像中读取 [BarCodeResult](../barcoderesult/)。 |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | 设置用于识别的条码解码类型。必须在调用 [ReadBarCodes](./readbarcodes/) 之前设置。 |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) 允许手动配置识别质量和速度。您可以通过内置预设快速设置 [QualitySettings](../qualitysettings/)：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或者手动配置各个选项。[QualitySettings](../qualitysettings/) 的默认值是 NormalQuality。 |
| [set_Timeout](./set_timeout/)(int32_t) | 设置识别过程的超时时间（毫秒）。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 设置用于识别的位图图像。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 设置用于识别的位图图像和区域。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | 设置用于识别的位图图像和区域。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | 设置用于识别的图像文件。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | 设置用于识别的图像流。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | 设置用于识别的亮度帧和区域。必须在调用 [ReadBarCodes](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 设置用于识别的亮度帧和多个区域。必须在调用 [ReadBarCodes](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | 设置用于识别的亮度帧。必须在调用 [ReadBarCodes](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | 设置用于识别的 [SingleDecodeType](../singledecodetype/) 类型数组。必须在调用 [ReadBarCodes()](./readbarcodes/) 方法之前调用。 |
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

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
