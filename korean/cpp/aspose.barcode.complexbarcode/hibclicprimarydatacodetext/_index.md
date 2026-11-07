---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext 클래스"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext 클래스. HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하는 클래스이며, C++에서 기본 데이터를 저장합니다."
type: docs
weight: 900
url: /ko/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


주요 데이터를 저장하는 HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [HIBCLICPrimaryDataCodetext](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | 바코드 유형을 가져옵니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | 기본 데이터를 식별합니다. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 코드텍스트를 구성합니다 |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 바코드 유형을 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | 기본 데이터를 식별합니다. |
## 비고


이 샘플은 [HIBCLICPrimaryDataCodetext](./)를 사용하여 HIBC LIC를 인코딩하고 디코딩하는 방법을 보여줍니다.
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## 또 보기

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
