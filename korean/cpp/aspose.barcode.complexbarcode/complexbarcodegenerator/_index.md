---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator 클래스"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator 클래스. C++에서 백엔드 복합 바코드(예: SwissQR) 이미지 생성을 위한 ComplexBarcodeGenerator."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | [ComplexBarcodeGenerator](./) 인스턴스를 생성합니다. |
| [Dispose](./dispose/)() override | 사용 중인 모든 리소스를 정리합니다. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 현재 설정으로 복합 바코드 이미지를 생성합니다. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) 매개변수. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |
| [Save](./save/)(System::String) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |
## 비고


이 샘플은 SwissQR 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // 나머지 필드를 초기화합니다
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
