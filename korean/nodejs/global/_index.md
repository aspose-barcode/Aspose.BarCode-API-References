---
title: "Global"
linktitle: "Global"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Global 네임스페이스는 Aspose.BarCode for Node.js via Java 전반에 걸쳐 사용되는 핵심 열거형 및 유틸리티 클래스를 그룹화합니다."
type: docs
weight: 20
url: /ko/nodejs/global/
---
Global 네임스페이스는 인코딩 모드, 심볼 크기, 신뢰 수준 및 이미지 형식과 같은 바코드 속성을 정의하는 기본 열거형 및 도우미 타입 컬렉션을 제공합니다. 이러한 정의는 Aspose.BarCode API 전반에 걸쳐 바코드 생성 및 인식을 구성하고 해석하는 데 참조됩니다.

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [AddressType](./addresstype/) | 주소 유형 |
| [AutoSizeMode](./autosizemode/) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값은 AutoSizeMode.NONE입니다. |
| [AztecEncodeMode](./aztecencodemode/) | Aztec 바코드의 인코딩 모드. |
| [AztecSymbolMode](./aztecsymbolmode/) | Aztec 심볼 모드를 지정합니다. |
| [BarCodeConfidence](./barcodeconfidence/) | 인식 신뢰 수준을 포함합니다. |
| [BarCodeImageFormat](./barcodeimageformat/) | 이미지의 파일 형식을 지정합니다. |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes classification |
| [BarcodeQualityMode](./barcodequalitymode/) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소 r |
| [BorderDashStyle](./borderdashstyle/) | 점선 테두리 스타일을 지정합니다. |
| [ChecksumValidation](./checksumvalidation/) | 1D 바코드 인식 중 체크섬 검증을 활성화합니다. 기본값은 필수인 심볼에 대해 Yes로 처리됩니다. |
| [CodabarChecksumMode](./codabarchecksummode/) | Codabar에 대한 체크섬 알고리즘을 지정합니다. |
| [CodabarSymbol](./codabarsymbol/) | Codabar 바코드 사양의 시작 또는 종료 심볼을 지정합니다. |
| [Code128EncodeMode](./code128encodemode/) | Code128 바코드의 인코딩 모드. `Code 128` 사양. 이 코드는 다양한 방식으로 code 128을 생성하는 방법을 보여줍니다. |
| [Code128SubType](./code128subtype/) | Code128 하위 집합 유형을 포함합니다. |
| [CodeLocation](./codelocation/) | 코드텍스트 위치 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. 이 샘플은 Co 사용 방법을 보여줍니다. |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | AustralianPost 바코드에 대한 고객 정보의 해석 유형(C_TABLE 또는 N_TABLE)을 정의합니다. |
| [DataMatrixEccType](./datamatrixecctype/) | 인코딩할 ECC 유형을 지정합니다. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix 인코더의 인코딩 모드이며 기본값은 Auto입니다. 이 샘플은 확장 모드에서 코드 텍스트를 수행하는 방법을 보여줍니다. //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | 인코딩할 ECC 유형을 지정합니다. |
| [DecodeType](./decodetype/) | 읽을 바코드 유형을 지정합니다. |
| [DeconvolutionMode](./deconvolutionmode/) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 함수입니다. |
| [DotCodeEncodeMode](./dotcodeencodemode/) | DotCode 바코드의 인코딩 모드입니다. |
| [ECIEncodings](./eciencodings/) | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [EnableChecksum](./enablechecksum/) | 1D 바코드 생성 시 체크섬을 활성화합니다. 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 기본값이 Yes로 처리됩니다. |
| [EncodeTypes](./encodetypes/) | 인코딩할 바코드 유형을 지정합니다. |
| [FontMode](./fontmode/) | 글꼴 크기 모드입니다. |
| [FontStyle](./fontstyle/) | FontStyle 분류 |
| [GraphicsUnit](./graphicsunit/) | 주어진 데이터의 측정 단위를 지정합니다. |
| [HIBCLICDateFormat](./hibclicdateformat/) | HIBC LIC에 대한 다양한 날짜 형식 유형을 지정합니다. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | HIBC PAS 데이터 위치 유형입니다. |
| [HIBCPASDataType](./hibcpasdatatype/) | HIBC PAS 레코드의 데이터 유형입니다. |
| [HanXinEncodeMode](./hanxinencodemode/) | Han Xin Code 인코딩 모드입니다. ASCII/중국어 문자와 함께 Auto를 사용하거나 유니코드 문자를 위해 Unicode를 사용하는 것이 권장됩니다. |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순으로: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Han Xin Code 버전입니다. Version01(23×23 모듈)부터 Version84(189×189 모듈)까지이며, 모듈 수가 2씩 증가합니다. |
| [ITF14BorderType](./itf14bordertype/) | ITF14 바코드의 테두리 유형 |
| [InverseImageMode](./inverseimagemode/) | 색상 반전(휘도)된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. 이 샘플은 |
| [MacroCharacter](./macrocharacter/) | Macro 문자 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. 05 Macro 문자은 전송됩니다 |
| [Mailmark2DType](./mailmark2dtype/) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | MaxiCode 바코드의 인코딩 모드입니다. |
| [MaxiCodeMode](./maxicodemode/) | MaxiCode 바코드의 인코딩 모드입니다. |
| [MicroQRVersion](./microqrversion/) | MicroQR Code 버전입니다. M1부터 M4까지. |
| [PatchFormat](./patchformat/) | PatchCode 형식. 단일 PatchCode를 생성하려면 PatchOnly를 선택하십시오. 페이지 형식을 사용하여 PatchCodes가 포함된 Patch 페이지를 생성합니다. |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 바코드의 압축 모드 |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 바코드 인코딩 모드 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 바코드의 오류 정정 수준, 레벨 0부터 레벨 9까지, 레벨 0은 오류 정정이 없음을 의미하고, 레벨 9는 최상의 정정을 의미합니다. |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | 인코더에 매크로 PDF417 종결자(codeword 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PD에만 적용됩니다. |
| [QREncodeMode](./qrencodemode/) | QR 바코드의 인코딩 모드. ECI 인코딩 사용 예: generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | QR / MicroQR 선택 모드. 표준 QR 심볼에는 FORCE_QR를 선택하고, MicroQR에는 AUTO를 선택합니다. FORCE_MICRO_QR는 강력한 경우에 사용됩니다. |
| [QRErrorLevel](./qrerrorlevel/) | Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | QR 코드 버전. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 청구서 표준 버전 |
| [QrExtCompactionMode](./qrextcompactionmode/) | QrExtCodetextBuilder에 의해 추가된 코드텍스트에 대한 QR 압축 모드를 지정합니다. |
| [RectMicroQRVersion](./rectmicroqrversion/) | RectMicroQR 코드 버전. R7x43 버전부터 R17x139 버전까지. |
| [SvgColorMode](./svgcolormode/) | svg 파일에서 색상을 채우는 가능한 모드, RGB가 기본이며 SVG 1.1에서 지원됩니다. RGBA, HSL, HSLA도 SVG에서 허용됩니다. |
| [TextAlignment](./textalignment/) | 텍스트 정렬. |
