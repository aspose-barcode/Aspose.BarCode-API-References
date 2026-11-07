---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext 클래스"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext 클래스. C++에서 모드 2와 3용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스."
type: docs
weight: 2200
url: /ko/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


모드 2 및 3용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [MaxiCodeStructuredCodetext](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_CountryCode](./get_countrycode/)() const | 3자리 국가 코드를 식별합니다. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto. |
| [get_PostalCode](./get_postalcode/)() const | 우편 번호를 식별합니다. 모드 2에서는 9자리, 모드 3에서는 6개의 영숫자 기호여야 합니다. |
| [get_SecondMessage](./get_secondmessage/)() const | 바코드의 두 번째 메시지를 식별합니다. |
| [get_ServiceCategory](./get_servicecategory/)() const | 3자리 서비스 카테고리를 식별합니다. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 코드텍스트를 구성합니다 |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | MaxiCode 모드를 가져옵니다. |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | 3자리 국가 코드를 식별합니다. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode 인코드 모드를 설정합니다. 기본값: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | 우편 번호를 식별합니다. 모드 2에서는 9자리, 모드 3에서는 6개의 영숫자 기호여야 합니다. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | 바코드의 두 번째 메시지를 식별합니다. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | 3자리 서비스 카테고리를 식별합니다. |
## 비고


이 샘플은 원시 MaxiCode 코드텍스트를 [MaxiCodeStructuredCodetext](./) 인스턴스로 디코딩하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## 또 보기

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
