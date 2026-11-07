---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext 클래스"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext 클래스. C++에서 HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스입니다."
type: docs
weight: 800
url: /ko/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | 바코드 유형을 가져옵니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | 코드텍스트를 구성합니다 |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 바코드 유형을 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
## 비고


이 샘플은 원시 HIBC LIC 코드텍스트를 [HIBCLICComplexCodetext](./) 인스턴스로 디코딩하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
