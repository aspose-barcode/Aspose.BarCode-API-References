---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeResult 方法。获取带有编码的代码文本"
type: docs
weight: 130
url: /zh/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

获取带编码的代码文本。

```csharp
public string GetCodeText(Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 编码 | 编码 | 代码文本的编码。 |

### 返回值

包含已识别代码文本的字符串。

## 示例

此示例展示了如何使用 `GetCodeText`：

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### 另见

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


