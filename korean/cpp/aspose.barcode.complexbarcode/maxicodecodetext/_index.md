---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext 클래스"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext 클래스. C++에서 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스입니다."
type: docs
weight: 1600
url: /ko/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | 코드텍스트를 구성합니다 |
| virtual [GetMode](./getmode/)() const | MaxiCode 모드를 가져옵니다. |
| virtual [InitFromString](./initfromstring/)(System::String) | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode 인코드 모드를 설정합니다. 기본값: Auto. |
## 비고


이 샘플은 원시 MaxiCode 코드텍스트를 [MaxiCodeCodetext](./) 인스턴스로 디코딩하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
