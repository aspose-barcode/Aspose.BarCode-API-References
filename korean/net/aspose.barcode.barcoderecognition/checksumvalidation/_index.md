---
title: "ChecksumValidation 열거형"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.ChecksumValidation 열거형. 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다."
type: docs
weight: 150
url: /ko/net/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enumeration

1D 및 우편 바코드 인식 중 체크섬 검증을 활성화합니다.

체크섬이 반드시 포함되어야 하는 심볼에 대해서는 기본값이 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다.

체크섬이 사용되지 않음: Codabar, PatchCode, Pharmacode, DataLogic2of5

체크섬을 사용할 수 있습니다: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

체크섬이 항상 사용됩니다: 나머지 심볼

```csharp
public enum ChecksumValidation
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | `0` | 사양에서 체크섬이 요구되는 경우 - 검증됩니다. |
| On | `1` | 가능하면 항상 체크섬을 검증하십시오. |
| Off | `2` | 체크섬을 검증하지 마십시오. |

## 예제

이 샘플은 체크섬 검증이 인식 품질 및 결과에 미치는 영향을 보여줍니다.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //체크섬 비활성화
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
    //체크섬 활성화
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

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


