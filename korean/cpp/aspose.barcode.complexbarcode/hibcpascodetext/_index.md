---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext 클래스"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext 클래스. C++에서 HIBC PAS 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 1100
url: /ko/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


HIBC PAS 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | 새 레코드를 추가합니다. |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | 새 레코드를 추가합니다. |
| [Clear](./clear/)() | 레코드 목록을 지웁니다. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [HIBCPASCodetext](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_BarcodeType](./get_barcodetype/)() const | 바코드 유형을 가져옵니다. HIBC PAS 코드텍스트는 HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS 및 HIBCQRPAS 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | 데이터 위치를 식별합니다. |
| [GetBarcodeType](./getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 코드텍스트를 구성합니다 |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetRecords](./getrecords/)() | 레코드 목록을 가져옵니다. |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트로부터 인스턴스를 초기화합니다. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 바코드 유형을 설정합니다. HIBC PAS 코드텍스트는 HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS 및 HIBCQRPAS 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | 데이터 위치를 식별합니다. |
## 비고


이 샘플은 [HIBCPASCodetext](./)를 사용하여 HIBC PAS를 인코딩 및 디코딩하는 방법을 보여줍니다.
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
