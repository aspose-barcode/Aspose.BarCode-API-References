---
title: "枚举"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 3300
url: /zh/cpp/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enum




```cpp
enum class ChecksumValidation
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 默认 | 0 | 如果规范要求校验和——将进行校验。 |
| 开启 | 1 | 如果可能，始终校验校验和。 |
| 关闭 | 2 | 不校验校验和。 |

## 备注


在识别 1D 和邮政条码时启用校验和验证。

默认情况下，对于必须包含校验和的符号视为 Yes，对于仅可能包含校验和的符号视为 No。

从不使用校验和：Codabar、PatchCode、Pharmacode、DataLogic2of5

可能使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

始终使用校验和：其余符号

此示例展示 ChecksumValidation 对识别质量和结果的影响
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //校验和已禁用
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //校验和已启用
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
