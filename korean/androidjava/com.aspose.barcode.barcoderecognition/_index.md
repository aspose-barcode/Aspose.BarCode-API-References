---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode for Android via Java API Reference
description: 이 패키지는 1D/2D 바코드 인식을 위한 도구를 포함합니다.
type: docs
weight: 11
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/
---

이 패키지는 1D/2D 바코드 인식을 위한 도구를 포함합니다.


## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost 디코딩 매개변수입니다. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec 인식 바코드의 특수 데이터를 저장합니다 |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | 인식 신뢰도 수준을 포함합니다 |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | 인식된 바코드의 확장 매개변수를 저장합니다 |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이를 통해 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader에서 발생하는 일반 예외로, BarCodeException을 상속합니다. |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | 인식된 바코드의 영역 및 바코드 각도를 나타냅니다 |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | SingleDecodeType 유형, string codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다 |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | 주요 BarCode 디코딩 매개변수입니다. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | 바코드 감지기 설정입니다. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType 및 SingleDecodeType의 기본 클래스입니다. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | 인식된 바코드 저장을 위한 확장 매개변수의 기본 클래스입니다. |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | 인식된 바코드의 Codabar 추가 정보를 저장합니다 |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 유형 바코드의 서브타입 데이터를 포함합니다 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Code128 인식 바코드의 특수 데이터를 저장합니다 |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Code128 하위 집합의 유형을 포함합니다 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | 인식된 바코드의 DataBar 추가 정보를 저장합니다 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | DataMatrix 인식 바코드의 특수 데이터를 저장합니다 |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | 읽을 바코드 유형을 지정합니다. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | DotCode 인식 바코드의 특수 데이터를 저장합니다 |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | 인식된 바코드의  **GS1 Composite Bar**  특수 데이터를 저장합니다 |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | 인식된 바코드의 MaxiCode 추가 정보를 저장합니다 |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | 복합 디코드 유형입니다. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | 복합 디코드 유형입니다. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | 별도의 코드텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다 |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다 |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings는 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다 |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 인식된 바코드의 QR Structured Append 정보를 저장합니다 |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | 네 개의  Point  로 구성된  Quadrangle  영역을 저장합니다. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings는 인식 품질과 속도를 수동으로 구성하도록 허용합니다. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | BarCodeReader를 사용한 인식 중 시간 초과가 발생하여 발생하는 인식 중단 예외를 나타냅니다. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | 단일 디코드 유형입니다. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | AustraliaPost 심볼에서 사용되는 고객 정보 필드 디코딩을 위한 공개 인터페이스입니다. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost 바코드의 고객 정보를 위한 해석 유형(C\_TABLE 또는 N\_TABLE)을 정의합니다. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | 스케일된 이미지의 크기를 지정합니다 |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
