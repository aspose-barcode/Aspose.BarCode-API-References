---
title: BarcodeGenerator
second_title: .NET API 참조용 Aspose.BarCode
description: 백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.
type: docs
weight: 700
url: /ko/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.

지원되는 기호: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | BarcodeGenerator. 의 인스턴스를 생성합니다. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | BarcodeGenerator. 의 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | 바코드 기호 유형. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | 인코딩할 텍스트입니다. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | 생성 매개변수. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | 지정된 xml-stream에서 BarCode 속성을 가져오고 BarcodeGenerator 인스턴스를 생성합니다. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | 지정된 xml 파일에서 BarCode 속성을 가져오고 BarcodeGenerator 인스턴스를 생성합니다. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF 캔버스에 바코드 이미지를 그립니다. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | 바코드 속성을 xml-stream specified 로 내보냅니다. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | BarCode 속성을 xml 파일로 내보냅니다. |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | 현재 설정에서 바코드 이미지를 생성합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | 바코드 이미지를 특정 파일에 저장합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | 특정 형식으로 스트리밍할 바코드 이미지를 저장합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | 바코드 이미지를 특정 파일에 특정 형식으로 저장합니다. |

### 예

이 샘플은 바코드 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
