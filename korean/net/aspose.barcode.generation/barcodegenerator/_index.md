---
title: "클래스 BarcodeGenerator"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.BarcodeGenerator 클래스. 백엔드 바코드 이미지 생성을 위한 BarcodeGenerator"
type: docs
weight: 1000
url: /ko/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.

지원되는 심볼: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR 코드 ...

```csharp
public sealed class BarcodeGenerator : Component
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | BarcodeGenerator의 인스턴스를 생성합니다. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | BarcodeGenerator의 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | 바코드 심볼 유형. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | 인코딩될 텍스트. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | 생성 매개변수. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | 지정된 xml-stream에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | 지정된 xml-file에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF 캔버스에 바코드 이미지를 그립니다. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | 지정된 xml 스트림으로 BarCode 속성을 내보냅니다 |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | 지정된 xml 파일로 BarCode 속성을 내보냅니다 |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | 현재 설정으로 바코드 이미지를 생성합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | 바코드 이미지를 특정 파일에 저장합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | 바코드 이미지를 특정 형식의 스트림에 저장합니다. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | 바코드 이미지를 특정 형식의 특정 파일에 저장합니다. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | codetext를 바이트 시퀀스로 설정합니다. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | 지정된 **encoding**을 사용하여 Unicode **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8은 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 이를 지원하는 경우, 함수가 자동으로 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)를 삽입합니다. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | 지정된 **encoding**을 사용하여 Unicode **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8은 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 이를 지원하고 **insertBOM**이 `true`로 설정된 경우, 함수가 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)를 포함합니다. |

## 예제

이 샘플은 바코드 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


