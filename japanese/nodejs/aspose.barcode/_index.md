---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "aspose.barcode 名前空間は、Node.js via Java でさまざまなバーコードタイプを作成、カスタマイズ、デコードするためのクラスと列挙体を提供します。"
type: docs
weight: 10
url: /ja/nodejs/aspose.barcode/
---
これらの型を使用して、住所フォーマット、地域仕様、Aztec およびその他のシンボル向けの高度なパラメータなど、バーコード生成設定を構成します。名前空間には、拡張コードテキストの構築や特殊な郵便規格の処理を支援するヘルパーが含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [Address](./address/) | 債権者または債務者の住所。街路、番地、郵便番号、町名（構造化住所タイプ）を設定できます o |
| [AlternativeScheme](./alternativescheme/) | 代替支払スキームの指示 |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost デコードパラメータ。AustraliaPost シンボルの認識データに影響を与えるパラメータを含みます |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost バーコードパラメータ。 |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ。TwoDDisplayText プロパティを使用します。 |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec 認識バーコードの特殊データを格納します。このサンプルは Aztec の生データを取得する方法を示します。let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec パラメータ。 |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 認識されたバーコードの拡張パラメータを格納します |
| [BarCodeReader](./barcodereader/) | BarCodeReader は、1 つまたは複数のバーコードを含む可能性のある画像をカプセル化し、ReadBarCodes 操作を実行できます |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 認識されたバーコードの領域と角度を表します |
| [BarCodeResult](./barcoderesult/) | SingleDecodeType 型、`string` codetext、BarCodeRegionParameters region などの認識バーコードデータを格納します p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | バックエンドのバーコード画像生成用 BarcodeGenerator。サポートされるシンボル: 1D: Codabar、Code11、Code128、Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | バーコード生成パラメータ。 |
| [BarcodeSettings](./barcodesettings/) | 主な BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータが含まれます。 |
| [BaseGenerationParameters](./basegenerationparameters/) | バーコード画像生成パラメータ。 |
| [BorderParameters](./borderparameters/) | バーコード画像の境界パラメータ |
| [CMYKColor](./cmykcolor/) | CMYK カラー用のクラスです。null インスタンスは CMYK が使用されていないことを意味し、デフォルトの RGB カラーが使用されます。 |
| [CaptionParameters](./captionparameters/) | キャプションパラメータ。 |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 認識されたバーコードの Codabar 追加情報を格納します |
| [CodabarParameters](./codabarparameters/) | Codabar パラメータ。 |
| [CodablockParameters](./codablockparameters/) | Codablock パラメータ。 |
| [Code128DataPortion](./code128dataportion/) | Code128 タイプのバーコードのサブタイプデータを含みます |
| [Code128ExtendedParameters](./code128extendedparameters/) | 認識された Code128 バーコードの特別なデータを格納します。認識されたバーコードの領域とバーコードの角度を表します |
| [Code128Parameters](./code128parameters/) | Code128 パラメータ。 |
| [Code16KParameters](./code16kparameters/) | Code16K パラメータ。 |
| [CodetextParameters](./codetextparameters/) | Codetext パラメータ。 |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | バックエンドの複合バーコード（例: SwissQR）画像生成のための ComplexBarcodeGenerator。 |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader は codetext を指定された複合バーコードタイプにデコードします。 |
| [CouponParameters](./couponparameters/) | クーポンパラメータ。UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon に使用されます。 |
| [DataBarExtendedParameters](./databarextendedparameters/) | 認識されたバーコードの DataBar 追加情報を格納します |
| [DataBarParameters](./databarparameters/) | Databar パラメータ。 |
| [DataElement](./dataelement/) | 文書で使用される管轄特有のデータフィールドを表します。例: ElementID = "ZVA"、Value = "01"。 |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Extended codetext ジェネレータは 2D DataMatrix バーコード用で、DataMatrixEncodeMode の ExtendedCodetext モードに使用されます //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 認識された DataMatrix バーコードの特別なデータを格納します。このサンプルは DataMatrix の生データ値を取得する方法を示します。let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix パラメータ。 |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Extended codetext ジェネレータは 2D DotCode バーコード用で、DotCodeEncodeMode の ExtendedCodetext モードに使用されます |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | 認識された DotCode バーコードの特別なデータを格納します。このサンプルは DotCode の生データ値を取得する方法を示します |
| [DotCodeParameters](./dotcodeparameters/) | DotCode パラメータ。 |
| [ExtCodetextBuilder](./extcodetextbuilder/) | 拡張コードテキストモードの自動コードテキスト生成のためのヘルパークラス |
| [FontUnit](./fontunit/) | テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは Unit 値プロパティで指定します。 |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | `GS1 Composite Bar ` 認識されたバーコードの特別なデータを保存します |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite バー パラメータ。 |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラスで、一次データと二次データを保存します。このサンプル |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードする基底クラス。このサンプルは生の HIBC LI をデコードする方法を示します |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | 一次データを保存する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。このサンプルは方法を示します |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | 二次データを保存する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [HIBCPASCodetext](./hibcpascodetext/) | HIBC PAS コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [HIBCPASRecord](./hibcpasrecord/) | HIBC PAS レコードを保存するクラス。 |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Han Xin コードの拡張モード（HanXinEncodeMode）用の拡張コードテキストジェネレータ //拡張コードテキストモード //コードを作成 |
| [HanXinParameters](./hanxinparameters/) | Han Xin パラメータ。 |
| [HslaColor](./hslacolor/) | HSLA カラー（色相、彩度、明度、アルファ）を表すクラス |
| [IComplexCodetext](./icomplexcodetext/) | ComplexBarcodeGenerator と共に使用される複合コードテキスト用インターフェイス。 |
| [ITFParameters](./itfparameters/) | ITF パラメータ。 |
| [ImageParameters](./imageparameters/) | 画像パラメータ。 |
| [License](./license/) | コンポーネントをライセンスするためのメソッドを提供します。 |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [MailmarkCodetext](./mailmarkcodetext/) | 4 状態 Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [MandatoryFields](./mandatoryfields/) | カードの必須要素（フィールド） |
| [MaxiCodeCodetext](./maxicodecodetext/) | MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードする基底クラス。このサンプルは生の MaxiCod をデコードする方法を示します |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | モード 2 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | モード 3 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするクラス。このサンプルはエンコードと |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | MaxiCodeEncodeMode の拡張コードテキストモード用の MaxiCode バーコード拡張コードテキストジェネレータ。TwoDDisplayText を使用 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 認識されたバーコードの MaxiCode 追加情報を保存します |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode パラメータ。 |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。 |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。 |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | MaxiCode バーコードの標準第2メッセージをエンコードおよびデコードするクラスです。 |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | MaxiCode バーコードの標準第2メッセージをエンコードおよびデコードするクラスです。 |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | モード 2、3 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードする基底クラスです。 |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | MaxiCode バーコードの構造化第2メッセージをエンコードおよびデコードするクラスです。 |
| [OneDExtendedParameters](./onedextendedparameters/) | 認識された 1D バーコードの別個のコードテキストやチェックサムなどの特殊データを保存します。 |
| [OptionalFields](./optionalfields/) | カードのオプション要素（フィールド） |
| [Padding](./padding/) | パディング パラメータ。 |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode パラメータ。 |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 認識されたバーコードの MacroPdf417 メタデータ情報を保存します。 |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417、GS1MicroPdf417 のパラメータを含みます。MacroPDF417 には 2 つのフィールドが必要です。 |
| [PdfParameters](./pdfparameters/) | PDF パラメータ ラッパー。対応する getter/setter メソッドを提供する基礎となる `mwObject` インスタンスを期待します。 |
| [PostalParameters](./postalparameters/) | 郵便パラメータ。Postnet、Planet に使用されます。 |
| [PrimaryData](./primarydata/) | HIBC LIC の一次データを保存するクラスです。 |
| [QRExtendedParameters](./qrextendedparameters/) | 認識されたバーコードの QR Structured Append 情報を保存します。 |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | 2D QR バーコード用の ExtendedCodetext モード (QREncodeMode) の拡張コードテキストジェネレータ。B の Display2DText プロパティを使用します。 |
| [QrParameters](./qrparameters/) | QR パラメータ。 |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR Structured Append パラメータ。 |
| [Quadrangle](./quadrangle/) | 四つのポイントのセットで、Quadrangle 領域を表すものを保存します。 |
| [QualitySettings](./qualitysettings/) | QualitySettings は認識品質と速度を手動で構成できるようにします。QualitySettings をすぐに設定するには、em を使用します。 |
| [RecognitionAbortedException](./recognitionabortedexception/) | BarCodeReader での認識中にタイムアウトが超過した際にスローされる認識中止例外を表します。 |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | HIBC LIC の二次および追加データを保存するクラスです。 |
| [SubfileProperties](./subfileproperties/) | USA DL サブファイルのプロパティ、オフセット、長さは自動的に設定されます。 |
| [SupplementParameters](./supplementparameters/) | サプリメント パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN に使用されます。 |
| [SvgParameters](./svgparameters/) | SVG パラメータ。 |
| [SwissQRBill](./swissqrbill/) | SwissQR 請求書データ |
| [SwissQRCodetext](./swissqrcodetext/) | SwissQR コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [USADriveIdCodetext](./usadriveidcodetext/) | USA 運転免許証 PDF417 コードに埋め込まれたテキストをエンコードおよびデコードするクラス。 |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | USA DL の管轄固有フィールド用クラス |
| [Unit](./unit/) | サイズ値をさまざまな単位（ピクセル、インチなど）で指定します。 |
