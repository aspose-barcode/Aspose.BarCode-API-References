---
title: "类 BarCodeReader"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader 类。BarCodeReader 封装了一幅可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。"
type: docs
weight: 70
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。

```csharp
public class BarCodeReader : Component
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | 使用默认值初始化 `BarCodeReader` 类的新实例。调用 ReadBarCodes() 方法之前，需要先设置图像 (SetBitmapImage())。 |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | 从图像初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | 从亮度帧初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_18)(string) | 从文件初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | 初始化 `BarCodeReader` 类的新实例。 |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | 初始化 `BarCodeReader` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | 获取或设置用于识别的条码解码类型。必须在调用 [`ReadBarCodes`](./readbarcodes/) 之前进行设置。 |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | 主要的 BarCode 解码参数。包含对已识别数据产生影响的参数。 |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | 获取已识别的 [`BarCodeResult`](../barcoderesult/) 数组 |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | 获取已识别的条码数量 |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或者手动配置各个选项。QualitySettings 的默认值为 NormalQuality。 |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | 获取或设置识别过程的超时时间（毫秒）。 |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | 获取使用处理器核心的设置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | 从指定的 xml 流导入 BarCode 属性并将其应用于当前的 BarCodeReader 实例。 |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | 从指定的 xml 文件导入 BarCode 属性并将其应用于当前的 BarCodeReader 实例。 |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | 该函数请求从其他线程终止当前的识别会话。Abort 是不可阻塞的方法，调用后立即返回控制权。该方法应在识别过程过长时使用。 |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | 将 BarCode 属性导出到指定的 xml 流 |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | 将 BarCode 属性导出到指定的 xml 文件 |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | 从图像读取 [`BarCodeResult`](../barcoderesult/)。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | 设置用于识别的位图图像。必须在调用 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | 设置用于识别的亮度帧。必须在调用 [`ReadBarCodes`](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | 设置用于识别的图像流。必须在调用 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | 设置用于识别的图像文件。必须在调用 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | 设置用于识别的位图图像和区域。必须在调用 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | 设置用于识别的位图图像和多个区域。必须在调用 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | 设置用于识别的亮度帧和区域。必须在调用 [`ReadBarCodes`](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | 设置用于识别的亮度帧和多个区域。必须在调用 [`ReadBarCodes`](./readbarcodes/) 方法之前调用。 |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | 设置用于识别的 [`SingleDecodeType`](../singledecodetype/) 类型数组。必须在调用 ReadBarCodes() 方法之前调用。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

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

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


