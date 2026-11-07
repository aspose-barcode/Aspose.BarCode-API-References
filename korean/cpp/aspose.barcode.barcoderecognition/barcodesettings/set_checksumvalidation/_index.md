---
title: "메서드"
linktitle: "set_ChecksumValidation"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::BarCodeRecognition::BarcodeSettings 클래스의 set_ChecksumValidation 메서드를 사용하는 방법."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_checksumvalidation/
---
## BarcodeSettings::set_ChecksumValidation method




```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_ChecksumValidation(Aspose::BarCode::BarCodeRecognition::ChecksumValidation value)
```

## 비고


1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다.

기본값은 체크섬이 반드시 포함되어야 하는 심볼에는 Yes로, 체크섬이 선택적인 경우 No로 처리됩니다.

체크섬을 사용하지 않음: Codabar, PatchCode, Pharmacode, DataLogic2of5

체크섬 사용 가능: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

체크섬을 항상 사용: 나머지 심볼

이 샘플은 ChecksumValidation이 인식 품질 및 결과에 미치는 영향을 보여줍니다.
```cpp
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


1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다.
## 또 보기

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
