---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters 클래스"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters 클래스. C++에서 인식된 DotCode 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 2000
url: /ko/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


DotCode 인식 바코드의 특수 데이터를 저장합니다.

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 코드가 바코드 리더기의 초기화 또는 재프로그램을 위한 지시로 다음 데이터를 해석하도록 리더기에 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode 구조 추가 모드 바코드의 개수를 가져옵니다. 기본값은 -1이며, 개수는 1에서 35 사이의 값이어야 합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [DotCodeExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
