---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters 클래스"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters 클래스. 인식된 바코드의 DataBar 추가 정보를 C++에 저장합니다."
type: docs
weight: 1400
url: /ko/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


인식된 바코드의 DataBar 추가 정보를 저장합니다.

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | DataBar 2D 복합 구성 요소 플래그를 가져옵니다. 기본값은 false입니다. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [DataBarExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 DataBar 추가 정보를 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
