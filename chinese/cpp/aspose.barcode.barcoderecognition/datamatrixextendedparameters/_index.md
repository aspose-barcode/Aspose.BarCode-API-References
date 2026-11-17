---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters 类"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters 类。存储在 C++ 中的 DataMatrix 识别条形码的特殊数据。"
type: docs
weight: 1500
url: /zh/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


存储已识别条形码的 [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) 的特殊数据

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | 获取 [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) 结构化追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | 获取 [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) 结构化追加模式条形码的数量。默认值为 -1。计数必须在 1 到 35 之间。 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | 获取 [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) 结构化追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [DataMatrixExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取 [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) 原始值
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
