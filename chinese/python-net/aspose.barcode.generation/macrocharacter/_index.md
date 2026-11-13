---
title: "宏字符"
second_title: "Aspose.Sildes for Python via .NET API 参考文档"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/macrocharacter/
---

## MacroCharacter enumeration

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。<br/>            05 宏字符被翻译为 "[)>\u001E05\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。<br/>            06 宏字符被翻译为 "[)>\u001E06\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。

## Members
| 成员名称 | 描述 |
| :- | :- |
| NONE | 未将任何宏字符添加到条形码数据中 |
| MACRO05 | 在第一个位置添加了 05 宏字符到条形码数据中。<br/>            GS1 数据标识符 ISO 15434<br/>            该字符被翻译为 "[)>\u001E05\u001D" 作为解码数据头，"\u001E\u0004" 作为解码数据尾。 |
| MACRO06 | 在第一个位置添加了 06 宏字符到条形码数据中。<br/>            ASC MH10 数据标识符 ISO 15434<br/>            该字符被翻译为 "[)>\u001E06\u001D" 作为解码数据头，"\u001E\u0004" 作为解码数据尾。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

