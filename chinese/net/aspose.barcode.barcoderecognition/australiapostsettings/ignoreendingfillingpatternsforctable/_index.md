---
title: IgnoreEndingFillingPatternsForCTable
second_title: Aspose.BarCode for .NET API 参考
description: 强制AustraliaPost解码器在解码为CTable方法时忽略Customer Information Field中最后的填充模式的标志 CTable编码方法在编码表中没有任何间隙并且填充模式的序列333被解码为字母z
type: docs
weight: 30
url: /zh/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

强制AustraliaPost解码器在解码为CTable方法时忽略Customer Information Field中最后的填充模式的标志。 CTable编码方法在编码表中没有任何间隙，并且填充模式的序列“333”被解码为字母“z”。

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### 适当的价值

强制 AustraliaPost 解码器在 CTable 方法解码期间忽略最后填充模式的标志

### 例子

此示例展示了如何使用 CTable 解释类型和忽略填充模式生成和识别澳大利亚邮政条形码。

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

### 也可以看看

* class [AustraliaPostSettings](../../australiapostsettings)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../australiapostsettings)
* 部件 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
