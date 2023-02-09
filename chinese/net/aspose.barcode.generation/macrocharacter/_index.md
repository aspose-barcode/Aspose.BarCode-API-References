---
title: MacroCharacter
second_title: Aspose.BarCode for .NET API 参考
description: 宏字符 05 和 06 值用于在特殊模式下获得更紧凑的编码 05 宏字符被转换为gtu001E05u001D作为解码数据头u001Eu0004作为解码数据尾 06 宏字符被翻译成gtu001E06u001D作为解码数据头和u001Eu0004作为解码数据尾
type: docs
weight: 790
url: /zh/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

宏字符 05 和 06 值用于在特殊模式下获得更紧凑的编码。 05 宏字符被转换为“[)&gt;\u001E05\u001D”作为解码数据头，“\u001E\u0004”作为解码数据尾。 06 宏字符被翻译成“[)&gt;\u001E06\u001D”作为解码数据头和“\u001E\u0004”作为解码数据尾。

```csharp
public enum MacroCharacter
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 没有宏字符被添加到条形码数据 |
| Macro05 | `5` | 05 宏字符被添加到条形码数据的第一个位置。 GS1 数据标识符 ISO 15434 字符被转换为“[)&gt;\u001E05\u001D”作为解码数据头，“\u001E\u0004”作为解码数据尾。 |
| Macro06 | `6` | 06 宏字符被添加到条形码数据的第一个位置。 ASC MH10 数据标识符 ISO 15434 字符被转换为“[)&gt;\u001E06\u001D”作为解码数据头，“\u001E\u0004”作为解码数据尾。 |

### 也可以看看

* 命名空间 [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->