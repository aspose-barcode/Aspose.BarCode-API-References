---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition은 1D/2D 바코드 인식을 위한 도구를 포함합니다."
type: docs
weight: 20
url: /ko/net/aspose.barcode.barcoderecognition/
---
**Aspose.BarCode.BarCodeRecognition**는 1D/2D 바코드 인식을 위한 도구를 포함합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 디코딩 매개변수. AustraliaPost 심볼로지의 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec 인식 바코드의 특수 데이터를 저장합니다. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 인식된 바코드의 확장 매개변수를 저장합니다. |
| [BarCodeReader](./barcodereader/) | BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 바코드를 감지하기 위해 ReadBarCodes 작업을 수행할 수 있습니다. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | BarCodeReader에서 발생하는 일반 예외로, BarCodeException에서 상속됩니다. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 인식된 바코드의 영역 및 바코드 각도를 나타냅니다. |
| [BarCodeResult](./barcoderesult/) | 인식된 바코드 데이터를 [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/) 유형, 문자열 codetext, [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) 영역 및 기타 매개변수로 저장합니다. |
| [BarcodeSettings](./barcodesettings/) | 주요 BarCode 디코딩 매개변수. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [BaseDecodeType](./basedecodetype/) | MultiDecodeType 및 SingleDecodeType의 기본 클래스. |
| [BaseExtendedParameters](./baseextendedparameters/) | 인식된 바코드 저장을 위한 확장 매개변수의 기본 클래스. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 인식된 바코드의 Codabar 추가 정보를 저장합니다. |
| [Code128DataPortion](./code128dataportion/) | Code128 유형 바코드의 하위 유형 데이터를 포함합니다. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Code128 인식 바코드의 특수 데이터를 저장합니다. |
| [DataBarExtendedParameters](./databarextendedparameters/) | 인식된 바코드의 DataBar 추가 정보를 저장합니다. |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | DataMatrix 인식 바코드의 특수 데이터를 저장합니다. |
| [DecodeType](./decodetype/) | 읽을 바코드 유형을 지정합니다. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | DotCode 인식 바코드의 특수 데이터를 저장합니다. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 인식된 바코드의 **GS1 Composite Bar**에 대한 특수 데이터를 저장합니다 |
| [Iso15416Quality](./iso15416quality/) | 1D 바코드에 대한 ISO/IEC 15416 표준에 따라 계산된 바코드 품질 등급을 저장합니다. |
| [IsoSymbolQuality](./isosymbolquality/) | ISO/IEC 표준에 따라 바코드 심볼 품질 평가 결과를 저장합니다. |
| [LuminanceFrame](./luminanceframe/) | 8비트 그레이스케일 이미지 프레임을 나타냅니다. 각 픽셀은 밝기 값을 포함하는 1바이트로 표현됩니다. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 인식된 바코드의 MaxiCode 추가 정보를 저장합니다. |
| [MultiDecodeType](./multidecodetype/) | 복합 디코드 유형입니다. |
| [OneDExtendedParameters](./onedextendedparameters/) | 분리된 코드 텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다. |
| [QRExtendedParameters](./qrextendedparameters/) | 인식된 바코드의 QR Structured Append 정보를 저장합니다. |
| [Quadrangle](./quadrangle/) | 네 개의 포인트 집합을 저장하며, 이는 [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) 영역을 나타냅니다. |
| [QualitySettings](./qualitysettings/) | QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장된 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용하여 QualitySettings를 빠르게 설정할 수 있으며, 별도의 옵션을 수동으로 구성할 수도 있습니다. QualitySettings의 기본값은 NormalQuality입니다. |
| [RecognitionAbortedException](./recognitionabortedexception/) | BarCodeReader를 사용한 인식 중 시간 초과가 발생하여 발생하는 인식 중단 예외를 나타냅니다. |
| [SingleDecodeType](./singledecodetype/) | 단일 디코드 유형입니다. 인스턴스를 얻으려면 decode type을 참조하십시오. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | AustraliaPost 심볼에서 사용되는 고객 정보 필드 디코딩을 위한 공개 인터페이스입니다. 구현은 사용자가 제공해야 합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | 인식 신뢰 수준을 포함합니다. |
| [BarcodeQualityMode](./barcodequalitymode/) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요하여 인식 속도가 느려집니다. |
| [ChecksumValidation](./checksumvalidation/) | 1D 및 우편 바코드 인식 중 체크섬 검증을 활성화합니다. |
| [Code128SubType](./code128subtype/) | Code128 하위 집합 유형을 포함합니다. |
| [ComplexBackgroundMode](./complexbackgroundmode/) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [DeconvolutionMode](./deconvolutionmode/) | 이미지 퇴화 수준을 정의하는 디컨볼루션(이미지 복원) 모드입니다. 원래 디컨볼루션은 카메라로 이미지를 촬영할 때 흐림과 같은 자연 함수에 의해 퇴화(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 샤프하거나 수학적 형태학과 같은 잘 알려진 함수를 확인해야 합니다. |
| [InverseImageMode](./inverseimagemode/) | 색상 반전(휘도)된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [XDimensionMode](./xdimensionmode/) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드입니다. |


