---
title: "Aspose::BarCode::Generation::BarcodeGenerator 클래스"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::BarcodeGenerator 클래스. C++에서 백엔드 바코드 이미지 생성을 위한 BarcodeGenerator."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | 다음의 인스턴스를 생성합니다: [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | 다음의 인스턴스를 생성합니다: [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | 사용 중인 모든 리소스를 정리합니다. |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) 속성을 지정된 xml 파일로 내보냅니다 |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) 속성을 지정된 xml 스트림으로 내보냅니다 |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 현재 설정으로 바코드 이미지를 생성합니다. |
| [get_BarcodeType](./get_barcodetype/)() | 바코드 심볼 유형. |
| [get_CodeText](./get_codetext/)() | 인코딩할 텍스트. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) 매개변수. |
| static [ImportFromXml](./importfromxml/)(System::String) | 지정된 xml 파일에서 [BarCode](../../aspose.barcode/) 속성을 가져와 [BarcodeGenerator](./) 인스턴스를 생성합니다. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 지정된 xml 스트림에서 [BarCode](../../aspose.barcode/) 속성을 가져와 [BarcodeGenerator](./) 인스턴스를 생성합니다. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | 바코드 이미지를 지정된 형식으로 스트림에 저장합니다. |
| [Save](./save/)(System::String, BarCodeImageFormat) | 바코드 이미지를 지정된 형식으로 특정 파일에 저장합니다. |
| [Save](./save/)(System::String) | 바코드 이미지를 특정 파일에 저장합니다. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | 바코드 심볼 유형. |
| [set_CodeText](./set_codetext/)(System::String) | 인코딩할 텍스트. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | 코드텍스트를 바이트 시퀀스로 설정합니다. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## 비고


지원되는 심볼: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

이 샘플은 바코드 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
