---
title: "BarCodeReader"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。

BarCodeReader 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| BarCodeReader() | 使用默认值初始化 [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 类的新实例。<br/>            在调用 ReadBarCodes() 方法之前，需要先设置图像 (SetBitmapImage())。 |
| BarCodeReader(image) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, area, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, area, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, areas, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(image, areas, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(filename) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(filename, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(filename, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(stream) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(stream, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(stream, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, areas, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, areas, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, area, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, area, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, type) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame, decode_types) | 初始化 BarCodeReader 类的新实例 |
| BarCodeReader(frame) | 初始化 BarCodeReader 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| processor_settings | 获取使用处理器核心的设置。 |
| timeout | 获取或设置识别过程的超时时间（毫秒）。 |
| found_bar_codes | 获取已识别的 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) 数组 |
| found_count | 获取已识别的条形码计数 |
| quality_settings | QualitySettings 允许手动配置识别质量和速度。<br/>            您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、<br/>            HighQuality、MaxBarCodes，或者手动配置各个选项。<br/>            QualitySettings 的默认值是 NormalQuality。 |
| barcode_settings | 主要的 BarCode 解码参数。包含对已识别数据产生影响的参数。 |
| bar_code_read_type | 获取或设置用于识别的条码解码类型。<br/>            必须在调用 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 之前设置。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| set_bar_code_image(value) | 设置用于识别的位图图像。 <br/>            必须在调用 ReadBarCodes() 方法之前调用。 |
| set_bar_code_image(value, areas) | 设置用于识别的位图图像和区域。 <br/>            必须在调用 ReadBarCodes() 方法之前调用。 |
| set_bar_code_image(value, area) | 设置用于识别的位图图像和区域。 <br/>            必须在调用 ReadBarCodes() 方法之前调用。 |
| set_bar_code_image(filename) | 设置用于识别的图像文件。 <br/>            必须在调用 ReadBarCodes() 方法之前调用。 |
| set_bar_code_image(stream) | 设置用于识别的图像流。 <br/>            必须在调用 ReadBarCodes() 方法之前调用。 |
| set_bar_code_image(frame, area) | 设置用于识别的亮度帧和区域。必须在调用 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 方法之前调用。 |
| set_bar_code_image(frame, areas) | 设置用于识别的亮度帧和多个区域。必须在调用 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 方法之前调用。 |
| set_bar_code_image(frame) | 设置用于识别的亮度帧和区域。必须在调用 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 方法之前调用。 |
| export_to_xml(xml_file) | 将 BarCode 属性导出到指定的 xml 文件 |
| export_to_xml(xml_stream) | 将 BarCode 属性导出到指定的 xml 流 |
| import_from_xml(xml_file) | 从指定的 xml 文件导入 BarCode 属性并将其应用于当前的 BarCodeReader 实例。 |
| import_from_xml(xml_stream) | 从指定的 xml 流导入 BarCode 属性并将其应用于当前的 BarCodeReader 实例。 |
| abort() | 该函数请求从其他线程终止当前的识别会话。Abort 是不可阻塞的方法，调用后立即返回控制。<br/>            当识别过程过长时应使用此方法。 |
| read_bar_codes() | 从图像中读取 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s。 |
| set_bar_code_read_type(barcode_types) | 设置 [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) 类型数组用于识别。<br/> 必须在调用 ReadBarCodes() 方法之前调用。 |

### 另见

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

