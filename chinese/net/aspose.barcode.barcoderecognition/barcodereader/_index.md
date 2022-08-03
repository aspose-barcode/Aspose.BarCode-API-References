---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API 参考
description: BarCodeReader 封装了一张可能包含一个或多个条形码的图像然后它可以执行 ReadBarCodes 操作来检测条形码
type: docs
weight: 60
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader 封装了一张可能包含一个或多个条形码的图像，然后它可以执行 ReadBarCodes 操作来检测条形码。

```csharp
public class BarCodeReader : Component
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | 初始化[`BarCodeReader`](../barcodereader)具有默认值的类。 需要在调用 ReadBarCodes() 方法之前设置图像 (SetBitmapImage())。 |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | 初始化[`BarCodeReader`](../barcodereader)图像中的类. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_11)(string) | 初始化[`BarCodeReader`](../barcodereader)文件中的类. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | 初始化[`BarCodeReader`](../barcodereader)类. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | 初始化[`BarCodeReader`](../barcodereader)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | 主要条码解码参数。包含影响识别数据的参数。 |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | 得到认可[`BarCodeResult`](../barcoderesult)数组 |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | 获取识别的条形码计数 |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings 允许手动配置识别质量和速度。 您可以通过嵌入式预设快速设置 QualitySettings：HighPerformance、NormalQuality、 HighQuality、MaxBarCodes 或者您可以手动配置单独的选项。 QualitySettings 的默认值为 NormalQuality。 |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | 获取或设置识别过程的超时时间，以毫秒为单位。 |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | 获取使用处理器内核的设置。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | 从指定的 xml 流导入 BarCode 属性并将它们应用到当前 BarCodeReader 实例。 |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | 从指定的 xml 文件导入 BarCode 属性并将它们应用到当前 BarCodeReader 实例。 |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | 函数请求从其他线程终止当前识别会话。 Abort 是不可阻塞的方法，并在调用后立即返回控制。 识别过程过长时应使用该方法。 |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | 将条形码属性导出到指定的 xml 流 |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | 将条形码属性导出到指定的 xml 文件 |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | 读取[`BarCodeResult`](../barcoderesult) 来自图像. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | 设置用于识别的位图图像。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | 设置用于识别的图像流。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | 设置用于识别的图像文件。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | 设置位图图像和识别区域。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | 设置位图图像和识别区域。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | 设置识别的解码类型。 必须在 ReadBarCodes() 方法之前调用。 |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | 套[`SingleDecodeType`](../singledecodetype)类型数组进行识别。 必须在 ReadBarCodes() 方法之前调用。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
