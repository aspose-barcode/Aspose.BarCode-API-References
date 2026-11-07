---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters 클래스"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters 클래스. C++에서 인식된 Aztec 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Aztec 인식 바코드의 특수 데이터를 저장합니다.

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 코드가 바코드 리더기의 초기화 또는 재프로그램을 위한 지시로 다음 데이터를 해석하도록 리더기에 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 0입니다. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 0이며, 카운트는 1에서 26 사이의 값이어야 합니다. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec 구조 추가 모드의 파일 ID를 가져옵니다. 기본값은 빈 문자열입니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [AztecExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 Aztec 원시 값을 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
