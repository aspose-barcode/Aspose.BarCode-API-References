---
title: "AztecEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API 参考文档"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/aztecencodemode/
---

## AztecEncodeMode enumeration

Aztec 条码的编码模式。

## Members
| 成员名称 | 描述 |
| :- | :- |
| AUTO | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。<br/>Unicode 字符会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。<br/>如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| EXTENDED |  |
| BINARY | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。<br/>如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。<br/>如果发现字符不受所选 ECI 编码支持，则会抛出异常。<br/>请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

