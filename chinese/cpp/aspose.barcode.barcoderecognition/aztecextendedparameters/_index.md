---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters 类。存储在 C++ 中识别的 Aztec 条码的特殊数据。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


存储 Aztec 识别条码的特殊数据

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | 获取 Aztec 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 0。 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | 获取 Aztec 结构化追加模式条码的数量。默认值为 0。计数必须在 1 到 26 之间。 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | 获取 Aztec 结构化追加模式的文件 ID。默认值为空字符串 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [AztecExtendedParameters](./) 的人类可读字符串表示形式。 |
## 备注


此示例展示如何获取 Aztec 原始值
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
