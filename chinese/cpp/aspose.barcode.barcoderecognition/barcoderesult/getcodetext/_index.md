---
title: "method"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。获取 C++ 中带编码的代码文本。"
type: docs
weight: 1000
url: /zh/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


获取带编码的代码文本。

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| 编码 | System::SharedPtr\<System::Text::Encoding\> | 代码文本的编码。 |

### ReturnValue

包含已识别代码文本的字符串。
## 备注



此示例展示了如何使用 **GetCodeText**：


```cpp
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

## 另见

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
