---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters 클래스"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters 클래스. C++에서 인식된 1D 바코드의 별도 코드텍스트와 체크섬과 같은 특수 데이터를 저장합니다."
type: docs
weight: 2700
url: /ko/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


별도의 코드 텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다.

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | 1D 바코드의 체크섬을 가져옵니다. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [get_Value](./get_value/)() const | 체크섬이 없는 1D 바코드의 코드텍스트를 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [OneDExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 1D 바코드 값과 체크섬을 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
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
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
