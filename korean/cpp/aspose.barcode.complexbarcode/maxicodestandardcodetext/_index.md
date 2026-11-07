---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext 클래스"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext 클래스. C++에서 모드 4, 5 및 6용 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 2000
url: /ko/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


모드 4, 5 및 6용 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [MaxiCodeStandardCodetext](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto. |
| [get_Message](./get_message/)() const | 메시지를 가져옵니다. |
| [get_Mode](./get_mode/)() | MaxiCode 모드를 가져옵니다. 표준 코드텍스트는 모드 4, 5 및 6에서만 사용할 수 있습니다. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 코드텍스트를 구성합니다 |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetMode](./getmode/)() const override | MaxiCode 모드를 가져옵니다. |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode 인코드 모드를 설정합니다. 기본값: Auto. |
| [set_Message](./set_message/)(System::String) | 메시지를 설정합니다. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | MaxiCode 모드를 설정합니다. 표준 코드텍스트는 모드 4, 5 및 6에서만 사용할 수 있습니다. |
## 비고


//Mode 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## 또 보기

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
