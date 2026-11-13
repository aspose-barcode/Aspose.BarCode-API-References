---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

用于后端条码图像生成的 BarcodeGenerator。

BarcodeGenerator 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| BarcodeGenerator(type) | 初始化 BarcodeGenerator 类的新实例 |
| BarcodeGenerator(type, code_text) | 初始化 BarcodeGenerator 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| parameters | 生成参数。 |
| barcode_type | 条码符号类型。 |
| code_text | 待编码的文本。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| set_code_text(code_bytes) | 将 codetext 设置为字节序列。 |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | 以特定格式将条码图像保存到流中。 |
| save(filename, format) | 以特定格式将条码图像保存到指定文件。 |
| save(filename) | 以特定格式将条码图像保存到指定文件。 |
| export_to_xml(xml_file) | 将 BarCode 属性导出到指定的 xml 文件 |
| export_to_xml(xml) | 将 BarCode 属性导出到指定的 xml 流 |
| import_from_xml(xml_file) | 从指定的 xml 文件导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| import_from_xml(xml) | 从指定的 xml 流导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| generate_bar_code_image() | 根据当前设置生成条码图像。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

