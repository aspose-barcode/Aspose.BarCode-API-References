---
title: "BarCodeResult"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.barcoderecognition/barcoderesult/
---

## BarCodeResult class

存储已识别条码的数据，例如 [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) 类型、字符串 codetext、<br/>            [BarCodeRegionParameters](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderegionparameters/) 区域以及其他参数

BarCodeResult 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| BarCodeResult(result) | 初始化 BarCodeResult 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| reading_quality | 获取读取质量。适用于 1D 和邮政条形码。 |
| confidence | 获取已识别条形码的识别置信度水平 |
| code_text | 获取代码文本 |
| code_bytes | 获取已编码的代码字节 |
| code_type | 获取条形码类型 |
| code_type_name | 获取条形码类型的名称 |
| 区域 | 获取条形码区域 |
| 扩展 | 获取已识别条形码的扩展参数 |
| iso_symbol_quality | 获取已识别条形码的 ISO/IEC 符号质量评估结果。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_code_text(encoding) | 获取带有编码的代码文本。 |
| equals(other) | 返回一个值，指示此实例是否等于指定的 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) 值。 |
| clone() | 创建 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) 类的副本。 |

### 另见

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

