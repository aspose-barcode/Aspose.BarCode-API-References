---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "AustraliaPostSettings 属性。此标志强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中的最后填充模式。CTable 编码方法在编码表中没有任何间隙，序列 333 的填充模式被解码为字母 z"
type: docs
weight: 30
url: /zh/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

此标志强制 AustraliaPost 解码器在使用 CTable 方法解码时忽略客户信息字段中的最后填充模式。CTable 编码方法的编码表中没有任何间隙，填充模式序列 “333” 被解码为字母 “z”。

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

此标志强制 AustraliaPost 解码器在 CTable 方法解码期间忽略最后的填充模式

## 示例

此示例展示如何使用 CTable 解释类型生成并识别 Australia Post 条形码，同时忽略填充模式。

```csharp
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

### 另见

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


