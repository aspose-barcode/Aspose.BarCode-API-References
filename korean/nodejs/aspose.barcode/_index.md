---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "aspose.barcode 네임스페이스는 Node.js via Java에서 다양한 바코드 유형을 생성, 사용자 정의 및 디코딩하기 위한 클래스와 열거형을 제공합니다."
type: docs
weight: 10
url: /ko/nodejs/aspose.barcode/
---
이 유형을 사용하여 주소 형식, 지역 사양 및 Aztec 등 기타 심볼로지를 위한 고급 매개변수와 같은 바코드 생성 설정을 구성합니다. 해당 네임스페이스에는 확장 코드 텍스트를 구축하고 특수 우편 표준을 처리하기 위한 도우미가 포함되어 있습니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Address](./address/) | 채권자 또는 채무자의 주소입니다. 거리, 건물 번호, 우편 번호 및 도시(구조화된 주소 유형)를 설정할 수 있습니다 o |
| [AlternativeScheme](./alternativescheme/) | 대체 결제 방식 지침 |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 디코딩 매개변수. AustraliaPost 심볼로지에서 인식된 데이터에 영향을 주는 매개변수를 포함합니다 |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost 바코드 매개변수. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | AztecEncodeMode의 ExtendedCodetext 모드를 위한 Aztec 바코드 확장 코드텍스트 생성기. TwoDDisplayText 속성을 사용합니다. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec 인식 바코드의 특수 데이터를 저장합니다. 이 샘플은 Aztec 원시 값을 가져오는 방법을 보여줍니다. let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec 매개변수. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 인식된 바코드의 확장 매개변수를 저장합니다 |
| [BarCodeReader](./barcodereader/) | BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이후 ReadBarCodes 작업을 수행할 수 있습니다 |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 인식된 바코드의 영역 및 바코드 각도를 나타냅니다 |
| [BarCodeResult](./barcoderesult/) | SingleDecodeType 유형, `string` codetext, BarCodeRegionParameters 영역 및 기타 p와 같은 인식된 바코드 데이터를 저장합니다 |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | 백엔드 바코드 이미지 생성을 위한 BarcodeGenerator. 지원되는 심볼로지: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | 바코드 생성 매개변수. |
| [BarcodeSettings](./barcodesettings/) | 주요 바코드 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [BaseGenerationParameters](./basegenerationparameters/) | 바코드 이미지 생성 매개변수. |
| [BorderParameters](./borderparameters/) | 바코드 이미지 테두리 매개변수 |
| [CMYKColor](./cmykcolor/) | CMYK 색상에 대한 클래스입니다. null 인스턴스는 CMYK가 사용되지 않으며 기본 RGB 색상이 사용됨을 의미합니다. |
| [CaptionParameters](./captionparameters/) | 캡션 매개변수. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 인식된 바코드의 Codabar 추가 정보를 저장합니다 |
| [CodabarParameters](./codabarparameters/) | Codabar 매개변수. |
| [CodablockParameters](./codablockparameters/) | Codablock 매개변수. |
| [Code128DataPortion](./code128dataportion/) | Code128 유형 바코드의 서브타입 데이터를 포함합니다 |
| [Code128ExtendedParameters](./code128extendedparameters/) | 인식된 Code128 바코드의 특수 데이터를 저장합니다. 인식된 바코드의 영역 및 바코드 각도를 나타냅니다 |
| [Code128Parameters](./code128parameters/) | Code128 매개변수. |
| [Code16KParameters](./code16kparameters/) | Code16K 매개변수. |
| [CodetextParameters](./codetextparameters/) | 코드텍스트 매개변수. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | 백엔드 복합 바코드(예: SwissQR) 이미지 생성을 위한 ComplexBarcodeGenerator. |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader가 코드텍스트를 지정된 복합 바코드 유형으로 디코딩합니다. |
| [CouponParameters](./couponparameters/) | 쿠폰 매개변수. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon에 사용됩니다. |
| [DataBarExtendedParameters](./databarextendedparameters/) | 인식된 바코드의 DataBar 추가 정보를 저장합니다 |
| [DataBarParameters](./databarparameters/) | Databar 매개변수. |
| [DataElement](./dataelement/) | 문서에서 사용되는 관할 구역별 데이터 필드를 나타냅니다. 예: ElementID = "ZVA"이고 Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | DataMatrixEncodeMode의 ExtendedCodetext 모드를 위한 2D DataMatrix 바코드용 확장 코드텍스트 생성기 //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 인식된 DataMatrix 바코드의 특수 데이터를 저장합니다. 이 샘플은 DataMatrix 원시 값을 가져오는 방법을 보여줍니다. let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix 매개변수. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | DotCodeEncodeMode의 ExtendedCodetext 모드를 위한 2D DotCode 바코드용 확장 코드텍스트 생성기 |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | 인식된 DotCode 바코드의 특수 데이터를 저장합니다. 이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다 |
| [DotCodeParameters](./dotcodeparameters/) | DotCode 매개변수. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Extended Codetext Mode의 자동 코드텍스트 생성을 위한 도우미 클래스 |
| [FontUnit](./fontunit/) | 텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴, 크기 및 스타일 속성이 포함되고 크기는 Unit 값 속성에 있습니다. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | `GS1 Composite Bar` 인식된 바코드의 특수 데이터를 저장합니다 |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite 바 매개변수. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스이며, 기본 및 보조 데이터를 저장합니다. 이 샘플 |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 기본 클래스입니다. 이 샘플은 원시 HIBC LI를 디코딩하는 방법을 보여줍니다 |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | 기본 데이터를 저장하는 HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. 이 샘플은 방법을 보여줍니다 |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | 보조 데이터를 저장하는 HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. |
| [HIBCPASCodetext](./hibcpascodetext/) | HIBC PAS 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. |
| [HIBCPASRecord](./hibcpasrecord/) | HIBC PAS 레코드를 저장하는 클래스입니다. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | HanXinEncodeMode의 확장 모드용 Han Xin 코드에 대한 확장 코드텍스트 생성기 //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Han Xin 매개변수. |
| [HslaColor](./hslacolor/) | HSLA 색상(색조, 채도, 밝기, 알파)를 나타내는 클래스 |
| [IComplexCodetext](./icomplexcodetext/) | ComplexBarcodeGenerator와 함께 사용되는 복합 코드텍스트용 인터페이스 |
| [ITFParameters](./itfparameters/) | ITF 매개변수. |
| [ImageParameters](./imageparameters/) | 이미지 매개변수. |
| [License](./license/) | 구성 요소에 대한 라이선스를 부여하는 메서드를 제공합니다. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. |
| [MailmarkCodetext](./mailmarkcodetext/) | 4-state Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. |
| [MandatoryFields](./mandatoryfields/) | 카드의 필수 요소(필드) |
| [MaxiCodeCodetext](./maxicodecodetext/) | MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 기본 클래스입니다. 이 샘플은 원시 MaxiCod를 디코딩하는 방법을 보여줍니다 |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | 모드 2용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | 모드 3용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다. 이 샘플은 인코딩 및 |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | MaxiCodeEncodeMode의 ExtendedCodetext 모드용 MaxiCode 바코드에 대한 확장 코드텍스트 생성기. TwoDDisplayText 사용 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 인식된 바코드의 MaxiCode 추가 정보를 저장합니다 |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode 매개변수. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | 모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | 모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | MaxiCode 바코드의 표준 두 번째 메시지를 인코딩 및 디코딩하기 위한 클래스. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | MaxiCode 바코드의 표준 두 번째 메시지를 인코딩 및 디코딩하기 위한 클래스. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | 모드 2 및 3에 대한 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | MaxiCode 바코드의 구조화된 두 번째 메시지를 인코딩 및 디코딩하기 위한 클래스. |
| [OneDExtendedParameters](./onedextendedparameters/) | 별도의 코드텍스트 및 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다 |
| [OptionalFields](./optionalfields/) | 카드의 선택적 요소(필드) |
| [Padding](./padding/) | 패딩 매개변수. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode 매개변수. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다 |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 fie가 필요합니다 |
| [PdfParameters](./pdfparameters/) | PDF 매개변수 래퍼. 해당 getter/setter 메서드를 제공하는 기본 `mwObject` 인스턴스를 기대합니다 |
| [PostalParameters](./postalparameters/) | 우편 매개변수. Postnet 및 Planet에 사용됩니다. |
| [PrimaryData](./primarydata/) | HIBC LIC 기본 데이터를 저장하기 위한 클래스. |
| [QRExtendedParameters](./qrextendedparameters/) | 인식된 바코드의 QR Structured Append 정보를 저장합니다 |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | ExtendedCodetext 모드의 QREncodeMode에 대한 2D QR 바코드용 확장 코드텍스트 생성기. B의 Display2DText 속성을 사용합니다 |
| [QrParameters](./qrparameters/) | QR 매개변수. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR Structured Append 매개변수. |
| [Quadrangle](./quadrangle/) | 사각형 영역을 나타내는 네 개의 포인트 집합을 저장합니다 |
| [QualitySettings](./qualitysettings/) | QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. QualitySettings를 빠르게 설정하려면 em을 사용하세요 |
| [RecognitionAbortedException](./recognitionabortedexception/) | BarCodeReader를 사용한 인식 중 시간 초과가 발생하여 발생하는 인식 중단 예외를 나타냅니다. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스. |
| [SubfileProperties](./subfileproperties/) | USA DL 서브파일 속성, 오프셋 및 길이가 자동으로 설정됩니다. |
| [SupplementParameters](./supplementparameters/) | 보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다. |
| [SvgParameters](./svgparameters/) | SVG 매개변수. |
| [SwissQRBill](./swissqrbill/) | SwissQR 청구서 데이터 |
| [SwissQRCodetext](./swissqrcodetext/) | SwissQR 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스. |
| [USADriveIdCodetext](./usadriveidcodetext/) | USA 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | USA DL에 대한 관할 구역별 필드용 클래스. |
| [Unit](./unit/) | 다양한 단위(Pixel, Inches 등)로 크기 값을 지정합니다. |
