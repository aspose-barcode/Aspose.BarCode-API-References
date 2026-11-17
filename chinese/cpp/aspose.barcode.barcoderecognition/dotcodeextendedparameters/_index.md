---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters 类"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters 类。 在 C++ 中存储 DotCode 识别条码的特殊数据。"
type: docs
weight: 2000
url: /zh/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


存储已识别的 DotCode 条码的特殊数据。

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | 获取 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | 获取 DotCode 结构化追加模式条码的计数。默认值为 -1。计数必须在 1 到 35 之间。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [DotCodeExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取 DotCode 原始值
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
