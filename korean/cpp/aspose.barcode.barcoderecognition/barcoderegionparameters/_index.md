---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters 클래스. C++에서 인식된 바코드의 영역과 바코드 각도를 나타냅니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


인식된 바코드의 영역 및 바코드 각도를 나타냅니다.

```cpp
class BarCodeRegionParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Angle](./get_angle/)() const | 바코드의 각도(0-360)를 가져옵니다. |
| [get_Points](./get_points/)() const | 바코드 영역을 둘러싸는 [Point](../) 배열을 가져옵니다. |
| [get_Quadrangle](./get_quadrangle/)() const | [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/)으로 둘러싸인 바코드 영역을 가져옵니다. |
| [get_Rectangle](./get_rectangle/)() const | **System::Drawing::Rectangle**로 둘러싸인 바코드 영역을 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [BarCodeRegionParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 바코드 각도와 둘러싸는 사변형 값을 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
