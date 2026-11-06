---
title: "method"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。此标志强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中的最后填充模式。CTable 编码方法在编码表中没有任何间隙，序列 \\\"333\\\" 的填充模式在 C++ 中被解码为字母 \\\"z\\\"。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中最后的填充模式的标志。CTable 编码方法在编码表中没有任何间隙，填充模式序列 \"333\" 被解码为字母 \"z\"。

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## 备注


此标志强制 AustraliaPost 解码器在 CTable 方法解码期间忽略最后的填充模式。

此示例展示了如何使用 CTable 解释类型生成和识别 Australia Post 条形码，并忽略填充模式。
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## 另见

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
