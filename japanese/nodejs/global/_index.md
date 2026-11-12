---
title: "グローバル"
linktitle: "グローバル"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Global 名前空間は、Aspose.BarCode for Node.js via Java 全体で使用されるコア列挙体とユーティリティクラスをまとめています。"
type: docs
weight: 20
url: /ja/nodejs/global/
---
Global 名前空間は、エンコーディングモード、シンボルサイズ、信頼レベル、画像フォーマットなどのバーコードプロパティを定義する基本的な列挙体とヘルパー型のコレクションを提供します。これらの定義は Aspose.BarCode API 全体で参照され、バーコードの生成と認識を構成および解釈します。

## 列挙体

| 列挙 | 説明 |
| --- | --- |
| [AddressType](./addresstype/) | 住所タイプ |
| [AutoSizeMode](./autosizemode/) | 自動サイズモードのさまざまなタイプを指定します。デフォルト値は AutoSizeMode.NONE です。 |
| [AztecEncodeMode](./aztecencodemode/) | Aztec バーコードのエンコーディングモード。 |
| [AztecSymbolMode](./aztecsymbolmode/) | Aztec シンボルモードを指定します。 |
| [BarCodeConfidence](./barcodeconfidence/) | 認識信頼レベルを含みます |
| [BarCodeImageFormat](./barcodeimageformat/) | 画像のファイル形式を指定します。 |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes の分類 |
| [BarcodeQualityMode](./barcodequalitymode/) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素 r |
| [BorderDashStyle](./borderdashstyle/) | 破線の境界線スタイルを指定します。 |
| [ChecksumValidation](./checksumvalidation/) | 1D バーコードの認識時にチェックサム検証を有効にします。デフォルトは、チェックサムが必須のシンボロジーでは Yes とみなされます。 |
| [CodabarChecksumMode](./codabarchecksummode/) | Codabar のチェックサムアルゴリズムを指定します。 |
| [CodabarSymbol](./codabarsymbol/) | Codabar バーコード仕様の開始または停止シンボルを指定します。 |
| [Code128EncodeMode](./code128encodemode/) | Code128 バーコードのエンコーディングモード。`Code  128` 仕様。このコードは、さまざまな方法で Code 128 を生成する方法を示します。 |
| [Code128SubType](./code128subtype/) | Code128 のサブセットタイプを含みます |
| [CodeLocation](./codelocation/) | Codetext の位置 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモードです。このサンプルは Co の使用方法を示しています |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | AustralianPost BarCode の顧客情報の解釈タイプ（C_TABLE または N_TABLE）を定義します。 |
| [DataMatrixEccType](./datamatrixecctype/) | エンコードする ECC のタイプを指定します。 |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix エンコーダのエンコーディングモードで、デフォルトは Auto です。このサンプルは拡張モードでコードテキストを行う方法を示しています。 //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | エンコードする ECC のタイプを指定します。 |
| [DecodeType](./decodetype/) | 読み取るバーコードのタイプを指定します。 |
| [DeconvolutionMode](./deconvolutionmode/) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。もともとデコンボリューションは機能です。 |
| [DotCodeEncodeMode](./dotcodeencodemode/) | DotCode バーコードのエンコーディングモードです。 |
| [ECIEncodings](./eciencodings/) | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [EnableChecksum](./enablechecksum/) | 1D バーコードの生成時にチェックサムを有効にします。チェックサムが必須のシンボロジーでは、デフォルトは Yes とみなされます。 |
| [EncodeTypes](./encodetypes/) | エンコードするバーコードのタイプを指定します。 |
| [FontMode](./fontmode/) | フォントサイズモードです。 |
| [FontStyle](./fontstyle/) | フォントスタイルの分類 |
| [GraphicsUnit](./graphicsunit/) | 指定されたデータの測定単位を指定します。 |
| [HIBCLICDateFormat](./hibclicdateformat/) | HIBC LIC の日付形式の種類を指定します。 |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | HIBC PAS データの配置タイプです。 |
| [HIBCPASDataType](./hibcpasdatatype/) | HIBC PAS レコードのデータタイプです。 |
| [HanXinEncodeMode](./hanxinencodemode/) | 漢信コードのエンコーディングモードです。ASCII / 中国語文字または Unicode 文字には Auto の使用が推奨されます。 |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Reed-Solomon 誤り訂正のレベルです。低から高へ: L1、L2、L3、L4。 |
| [HanXinVersion](./hanxinversion/) | 漢信コードのバージョンです。Version01（23 x 23 モジュール）から Version84（189 x 189 モジュール）まで、2 モジュールずつ増加します。 |
| [ITF14BorderType](./itf14bordertype/) | ITF14 バーコードのボーダータイプです。 |
| [InverseImageMode](./inverseimagemode/) | 反転色（輝度）の画像上のバーコードの追加認識を有効または無効にするモードです。このサンプルは |
| [MacroCharacter](./macrocharacter/) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。05 マクロ文字は |
| [Mailmark2DType](./mailmark2dtype/) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | MaxiCode バーコードのエンコーディングモードです。 |
| [MaxiCodeMode](./maxicodemode/) | MaxiCode バーコードのエンコーディングモードです。 |
| [MicroQRVersion](./microqrversion/) | MicroQR Code のバージョンです。M1 から M4 まで。 |
| [PatchFormat](./patchformat/) | PatchCode の形式です。単一の PatchCode を生成するには PatchOnly を選択してください。PatchCodes を含む Patch ページを生成するには page 形式を使用します。 |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 バーコードの圧縮モード |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 バーコードのエンコードモード |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 バーコードの誤り訂正レベル。レベル0からレベル9まであり、レベル0は誤り訂正なし、レベル9は最高です。 |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | エンコーダにセグメントへ Macro PDF417 Terminator（コードワード 922）を追加するかどうかを指示するために使用します。Macro PD にのみ適用されます。 |
| [QREncodeMode](./qrencodemode/) | QR バーコードのエンコーディングモード。ECI エンコーディングの使用例: generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | QR / MicroQR セレクターモード。標準 QR シンボルには FORCE_QR を選択し、MicroQR には AUTO を選択します。FORCE_MICRO_QR は強力な場合に使用されます。 |
| [QRErrorLevel](./qrerrorlevel/) | Reed-Solomon 誤り訂正のレベル。低から高へ: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H。 |
| [QRVersion](./qrversion/) | QR コードのバージョン。QR コードは Version1 から Version40、MicroQr は M1 から M4 までです。 |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 請求書標準バージョン |
| [QrExtCompactionMode](./qrextcompactionmode/) | QrExtCodetextBuilder によって追加されたコードテキストの QR 圧縮モードを指定します。 |
| [RectMicroQRVersion](./rectmicroqrversion/) | RectMicroQR コードのバージョン。バージョン R7x43 から R17x139 までです。 |
| [SvgColorMode](./svgcolormode/) | svg ファイルの塗りつぶし色の可能なモード。RGB がデフォルトで SVG 1.1 に対応しています。RGBA、HSL、HSLA も SVG で使用可能です。 |
| [TextAlignment](./textalignment/) | テキストの配置。 |
