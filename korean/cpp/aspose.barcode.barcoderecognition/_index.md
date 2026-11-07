---
title: "Aspose::BarCode::BarCodeRecognition 네임스페이스"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::BarCodeRecognition 네임스페이스를 사용하는 방법."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode.barcoderecognition/
---



## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | AustraliaPost 심볼로지에서 사용되는 고객 정보 필드 디코딩을 위한 공개 인터페이스. 구현은 사용자가 제공해야 합니다. |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 디코딩 매개변수. AustraliaPost 심볼로지의 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec 인식 바코드의 특수 데이터를 저장합니다. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 인식된 바코드의 확장 매개변수를 저장합니다. |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/)는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이후 바코드를 감지하기 위해 ReadBarCodes 작업을 수행할 수 있습니다. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 인식된 바코드의 영역 및 바코드 각도를 나타냅니다. |
| [BarCodeResult](./barcoderesult/) | 인식된 바코드 데이터를 저장합니다. 예: [SingleDecodeType](./singledecodetype/) 유형, **System::String** 코드텍스트, [BarCodeRegionParameters](./barcoderegionparameters/) 영역 및 기타 매개변수 |
| [BarcodeSettings](./barcodesettings/) | 주요 [BarCode](../aspose.barcode/) 디코딩 매개변수. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [BaseDecodeType](./basedecodetype/) | [MultiDecodeType](./multidecodetype/) 및 [SingleDecodeType](./singledecodetype/)의 기본 클래스. |
| [BaseExtendedParameters](./baseextendedparameters/) | 인식된 바코드 저장을 위한 확장 매개변수의 기본 클래스. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 인식된 바코드의 Codabar 추가 정보를 저장합니다. |
| [Code128DataPortion](./code128dataportion/) | Code128 유형 바코드의 하위 유형 데이터를 포함합니다. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Code128 인식 바코드의 특수 데이터를 저장합니다. |
| [DataBarExtendedParameters](./databarextendedparameters/) | 인식된 바코드의 DataBar 추가 정보를 저장합니다. |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 인식된 [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) 바코드의 특수 데이터를 저장합니다. |
| [DecodeType](./decodetype/) | 읽을 바코드 유형을 지정합니다. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | BarCodeException에서 상속받은 [BarCodeReader](./barcodereader/)에 의해 발생하는 일반 예외. |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | 인식 중 타임아웃 초과 시 [BarCodeReader](./barcodereader/)에 의해 발생하는 인식 중단 예외를 나타냅니다. |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | DotCode 인식 바코드의 특수 데이터를 저장합니다. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 인식된 **GS1 Composite Bar** 바코드의 특수 데이터를 저장합니다. |
| [Iso15416Quality](./iso15416quality/) | ISO/IEC 15416 표준에 따라 1D 바코드에 대해 계산된 바코드 품질 등급을 저장합니다. |
| [IsoSymbolQuality](./isosymbolquality/) | ISO/IEC 표준에 따라 바코드 심볼 품질 평가 결과를 저장합니다. |
| [LuminanceFrame](./luminanceframe/) | 8비트 그레이스케일 이미지 프레임을 나타냅니다. 각 픽셀은 밝기 값을 포함하는 1바이트로 표현됩니다. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 인식된 바코드의 MaxiCode 추가 정보를 저장합니다. |
| [MultiDecodeType](./multidecodetype/) | 복합 디코드 유형입니다. |
| [OneDExtendedParameters](./onedextendedparameters/) | 별도의 코드 텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다. |
| [QRExtendedParameters](./qrextendedparameters/) | 인식된 바코드의 [QR](../aspose.barcode.barcoderecognition.qr/) 구조적 추가 정보를 저장합니다. |
| [Quadrangle](./quadrangle/) | 네 개의 [Point](../)으로 구성된 집합을 저장하며, 이는 [Quadrangle](./quadrangle/) 영역을 나타냅니다. |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/)은 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장된 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용해 빠르게 설정할 수 있으며, 개별 옵션을 수동으로 구성할 수도 있습니다. [QualitySettings](./qualitysettings/)의 기본값은 NormalQuality입니다. |
| [SingleDecodeType](./singledecodetype/) | 단일 디코드 유형입니다. 인스턴스를 얻으려면 디코드 유형을 참조하세요. |
## Enums

| 열거형 | 설명 |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Code128 하위 집합의 유형을 포함합니다. |
| [BarCodeConfidence](./barcodeconfidence/) | 인식 신뢰도 수준을 포함합니다. |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| 타입 정의 | 설명 |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
