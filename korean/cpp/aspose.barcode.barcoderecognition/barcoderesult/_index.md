---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult 클래스"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult 클래스. C++에서 SingleDecodeType 유형, System::String codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다."
type: docs
weight: 700
url: /ko/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


인식된 바코드 데이터를 [SingleDecodeType](../singledecodetype/) 유형, **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) 영역 및 기타 매개변수로 저장합니다

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | 해당 [BarCodeResult](./) 클래스의 복사본을 생성합니다. |
| [Clone](./clone/)() override | 해당 [BarCodeResult](./) 클래스의 복사본을 생성합니다. |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | 이 인스턴스가 지정된 [BarCodeResult](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_CodeBytes](./get_codebytes/)() const | 인코딩된 코드 바이트를 가져옵니다 |
| [get_CodeText](./get_codetext/)() const | 코드 텍스트를 가져옵니다 |
| [get_CodeType](./get_codetype/)() const | 바코드 유형을 가져옵니다 |
| [get_CodeTypeName](./get_codetypename/)() | 바코드 유형의 이름을 가져옵니다 |
| [get_Confidence](./get_confidence/)() const | 인식된 바코드의 신뢰도 수준을 가져옵니다 |
| [get_Extended](./get_extended/)() const | 인식된 바코드의 확장 매개변수를 가져옵니다 |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | 인식된 바코드에 대한 ISO/IEC 심볼 품질 평가 결과를 가져옵니다. |
| [get_ReadingQuality](./get_readingquality/)() const | 읽기 품질을 가져옵니다. 1D 및 우편 바코드에 적용됩니다. |
| [get_Region](./get_region/)() const | 바코드 영역을 가져옵니다 |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | 인코딩된 코드 텍스트를 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [BarCodeResult](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 [BarCodeResult](./)을 얻는 방법을 보여줍니다.
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
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
