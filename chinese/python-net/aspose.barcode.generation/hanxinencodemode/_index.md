---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API 参考文档"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

汉信码编码模式。建议在使用 ASCII / 中文字符时使用 Auto，或在使用 Unicode 字符时使用 Unicode。

## Members
| 成员名称 | 描述 |
| :- | :- |
| AUTO | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。<br/>            根据 HanXin 条码规范，Unicode 字符使用 GB18030 编码。 |
| BINARY | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。<br/>如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。<br/>如果发现字符不受所选 ECI 编码支持，则会抛出异常。<br/>请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |
| UNICODE | Unicode 模式提供了一种在 Han Xin Code 中使用 UTF8 编码/字符集表示任何文本数据的方式。 |
| URI | URI 模式表示在 Han Xin Code 中表示的数据是统一资源标识符（URI）<br/>            参考 RFC 3986。 |
| EXTENDED | Extended 模式允许内部模式的组合：Auto、Binary、Text、Numeric、URI、Unicode、ECI、Common Chinese Region One、<br/>            Common Chinese Region Two、GB18030 Two Byte、GB18030 Four Byte。<br/>            可以使用前缀和双反斜杠手动构建 Codetext，例如：@"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c"，或使用 HanXinExtCodetextBuilder。<br/>            如果 Codetext 包含 ECI 片段，则在该 ECI 片段之后的 Codetext 中只能出现以下模式：<br/>            Auto、Binary、Text、Numeric、URI、ECI。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

