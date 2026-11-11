---
title: "클래스 ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator 클래스. 백엔드 복합 바코드(예: SwissQR 이미지 생성)를 위한 ComplexBarcodeGenerator"
type: docs
weight: 510
url: /ko/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

백엔드 복합 바코드(예: SwissQR) 이미지 생성을 위한 ComplexBarcodeGenerator.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | ComplexBarcodeGenerator의 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | 생성 매개변수. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | 현재 설정으로 복합 바코드 이미지를 생성합니다. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | 현재 설정으로 복합 바코드 이미지를 생성하고 저장합니다. |

## 예제

이 샘플은 SwissQR 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // 필드 나머지를 초기화합니다
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### 또 보기

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


