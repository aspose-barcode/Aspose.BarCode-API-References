---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters 클래스"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters 클래스. C++에서 인식된 Code128 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 1300
url: /ko/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Code128 인식 바코드의 특수 데이터를 저장합니다.

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | 인식된 Code128 바코드의 [Code128DataPortion](../code128dataportion/) 배열을 가져옵니다. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [Code128ExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


인식된 바코드의 영역 및 바코드 각도를 나타냅니다.

이 샘플은 code128 원시 값을 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
