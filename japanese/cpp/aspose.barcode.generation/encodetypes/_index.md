---
title: "Aspose::BarCode::Generation::EncodeTypes class"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::EncodeTypes クラス。C++ でエンコードするバーコードのタイプを指定します。"
type: docs
weight: 2300
url: /ja/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


エンコードするバーコードのタイプを指定します。

```cpp
class EncodeTypes
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | データが利用可能なすべてのシンボロジーでチェックされることを指定します。 |
| static [GetNames](./getnames/)() | エンコードタイプの名前の配列を取得します。 |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | データを **Australian Post Domestic eParcel Barcode** バーコード仕様でエンコードすることを指定します。 |
| static [AustraliaPost](./australiapost/) | Australia Post カスタマーの [BarCode](../../aspose.barcode/) を表します。 |
| static [Aztec](./aztec/) | データを **Aztec** バーコード仕様でエンコードすることを指定します。 |
| static [Codabar](./codabar/) | データを **CODABAR** バーコード仕様でエンコードすることを指定します |
| static [CodablockF](./codablockf/) | データを **Codablock-F** バーコード仕様でエンコードすることを指定します。 |
| static [Code11](./code11/) | データを **CODE 11** バーコード仕様でエンコードすることを指定します |
| static [Code128](./code128/) | データを **CODE 128** バーコード仕様でエンコードすることを指定します |
| static [Code16K](./code16k/) | Code 16K バーコードを表します。 |
| static [Code32](./code32/) | データを **Code32** バーコード仕様でエンコードすることを指定します |
| static [Code39](./code39/) | データを **Code 39** 基本文字セットバーコード仕様（ISO/IEC 16388）でエンコードすることを指定します |
| static [Code39FullASCII](./code39fullascii/) | データを **Code 39** フルASCII文字セットバーコード仕様（ISO/IEC 16388）でエンコードすることを指定します |
| static [Code93](./code93/) | データを **CODE 93** バーコード仕様でエンコードすることを指定します |
| static [DatabarExpanded](./databarexpanded/) | GS1 Databar 拡張バーコードを表します。 |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | GS1 Databar 拡張スタックバーコードを表します。 |
| static [DatabarLimited](./databarlimited/) | GS1 Databar 限定バーコードを表します。 |
| static [DatabarOmniDirectional](./databaromnidirectional/) | データを **GS1 Databar omni-directional** バーコード仕様でエンコードすることを指定します。 |
| static [DatabarStacked](./databarstacked/) | GS1 Databar スタックバーコードを表します。 |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | GS1 Databar スタック omni-directional バーコードを表します。 |
| static [DatabarTruncated](./databartruncated/) | データを **GS1 Databar truncated** バーコード仕様でエンコードすることを指定します。 |
| static [DataLogic2of5](./datalogic2of5/) | データを **DataLogic 2 of 5** バーコード仕様でエンコードすることを指定します |
| static [DataMatrix](./datamatrix/) | 2D バーコードシンボル DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Deutsch Post バーコードを表します。このシンボルは Identcode、CodeIdentcode、German Postal 2 of 5 Identcode、Deutsch Post AG Identcode、Deutsch Frachtpost Identcode、Deutsch Post AG（DHL）としても知られています |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Deutsch Post Leitcode バーコードを表します。これは German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG（DHL）としても知られています。 |
| static [DotCode](./dotcode/) | データを **DotCode** バーコード仕様でエンコードすることを指定します |
| static [DutchKIX](./dutchkix/) | データを **Dutch KIX** バーコード仕様でエンコードすることを指定します |
| static [EAN13](./ean13/) | データを **EAN-13** バーコード仕様でエンコードすることを指定します |
| static [EAN14](./ean14/) | データを **EAN14** バーコード仕様でエンコードすることを指定します |
| static [EAN8](./ean8/) | データを **EAN-8** バーコード仕様でエンコードすることを指定します |
| static [GS1Aztec](./gs1aztec/) | データは **GS1 Aztec** バーコード仕様でエンコードされることを指定します。コードテキストは AI 用に括弧を含む必要があります。 |
| static [GS1CodablockF](./gs1codablockf/) | データは **GS1 Codablock-F** バーコード仕様でエンコードされることを指定します。コードテキストは AI 用に括弧を含む必要があります。 |
| static [GS1Code128](./gs1code128/) | データは **GS1 Code 128** バーコード仕様でエンコードされることを指定します。コードテキストは AI 用に括弧を含む必要があります。 |
| static [GS1CompositeBar](./gs1compositebar/) | データは **GS1 Composite Bar** バーコード仕様でエンコードされることを指定します。コードテキストは AI 用に括弧を含む必要があります。1D コードテキストと 2D コードテキストは '/' 記号で区切る必要があります。 |
| static [GS1DataMatrix](./gs1datamatrix/) | GS1 文字列形式の 2D バーコードシンボル DataMatrix |
| static [GS1DotCode](./gs1dotcode/) | データは **GS1 DotCode** バーコード仕様でエンコードされることを指定します。コードテキストは AI 用に括弧を含む必要があります。 |
| static [GS1HanXin](./gs1hanxin/) | GS1 文字列形式の 2D バーコードシンボル HanXin |
| static [GS1MicroPdf417](./gs1micropdf417/) | データは **GS1MicroPdf417** バーコード仕様でエンコードされることを指定します。 |
| static [GS1QR](./gs1qr/) | GS1 文字列形式の 2D バーコードシンボル QR |
| static [HanXin](./hanxin/) | データは **Han Xin** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCAztecLIC](./hibcazteclic/) | データは **HIBC LIC Aztec** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCAztecPAS](./hibcaztecpas/) | データは **HIBC PAS Aztec** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCCode128LIC](./hibccode128lic/) | データは **HIBC LIC Code128** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCCode128PAS](./hibccode128pas/) | データは **HIBC PAS Code128** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCCode39LIC](./hibccode39lic/) | データは **HIBC LIC Code39** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCCode39PAS](./hibccode39pas/) | データは **HIBC PAS Code39** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | データは **HIBC LIC DataMatrix** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | データは **HIBC PAS DataMatrix** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCQRLIC](./hibcqrlic/) | データは **HIBC LIC QR** バーコード仕様でエンコードされることを指定します。 |
| static [HIBCQRPAS](./hibcqrpas/) | データは **HIBC PAS QR** バーコード仕様でエンコードされることを指定します。 |
| static [IATA2of5](./iata2of5/) | IATA 2 of 5 バーコードを表します。IATA（International Air Transport Association）は航空貨物の管理にこのバーコードを使用します。 |
| static [Interleaved2of5](./interleaved2of5/) | データは **INTERLEAVED 2 of 5** バーコード仕様でエンコードされることを指定します |
| static [ISBN](./isbn/) | データは **ISBN** バーコード仕様でエンコードされることを指定します |
| static [ISMN](./ismn/) | データは **ISMN** バーコード仕様でエンコードされることを指定します |
| static [ISSN](./issn/) | データは **ISSN** バーコード仕様でエンコードされることを指定します |
| static [ItalianPost25](./italianpost25/) | イタリア郵便 25 バーコードを表します。 |
| static [ITF14](./itf14/) | データを **ITF14** バーコード仕様でエンコードする必要があることを指定します。 |
| static [ITF6](./itf6/) | ITF-6 バーコードを表します。 |
| static [JapanPost](./japanpost/) | 日本郵便の [BarCode](../../aspose.barcode/) を表します。 |
| static [MacroPdf417](./macropdf417/) | データを **MacroPdf417** バーコード仕様でエンコードする必要があることを指定します。 |
| static [Mailmark](./mailmark/) | Royal Mail Mailmark バーコードを表します。 |
| static [Matrix2of5](./matrix2of5/) | Matrix 2 of 5 の [BarCode](../../aspose.barcode/) を表します。 |
| static [MaxiCode](./maxicode/) | データを **MaxiCode** バーコード仕様でエンコードする必要があることを指定します。 |
| static [MicroPdf417](./micropdf417/) | データを **MicroPdf417** バーコード仕様でエンコードする必要があることを指定します。 |
| static [MicroQR](./microqr/) | データを **MicroQR Code** バーコード仕様でエンコードする必要があることを指定します。 |
| static [MSI](./msi/) | データを **MSI Plessey** バーコード仕様でエンコードする必要があることを指定します。 |
| static [None](./none/) | エンコードタイプが未指定です。 |
| static [OneCode](./onecode/) | データを USPS **OneCode** バーコード仕様でエンコードする必要があることを指定します。 |
| static [OPC](./opc/) | OPC（Optical Product Code）バーコードを表します。別名は VCA Barcode、VCA OPC、Vision Council of America OPC Barcode です。 |
| static [PatchCode](./patchcode/) | Patch code バーコードを表します。 |
| static [Pdf417](./pdf417/) | データを **Pdf417** バーコード仕様でエンコードする必要があることを指定します。 |
| static [Pharmacode](./pharmacode/) | Pharmacode バーコードを表します。 |
| static [Planet](./planet/) | データを **Planet** バーコード仕様でエンコードする必要があることを指定します。 |
| static [Postnet](./postnet/) | データを **Postnet** バーコード仕様でエンコードする必要があることを指定します。 |
| static [PZN](./pzn/) | PZN バーコードを表します。このシンボルは Pharmacy central number、Pharmazentralnummer とも呼ばれます。PZN7 と PZN8 がサポートされています。PZN7 は 6 桁以下の数字（例: "123456"）から生成されます。PZN8 は 7 桁以上の数字（例: "1234567"）から生成されます。提供された最後のチェックサム桁は無視され、バーコードエンジンによって生成されます。 |
| static [QR](./qr/) | データを **QR Code** バーコード仕様でエンコードする必要があることを指定します。 |
| static [RectMicroQR](./rectmicroqr/) | データを **RectMicroQR (rMQR) Code** バーコード仕様でエンコードする必要があることを指定します。 |
| static [RM4SCC](./rm4scc/) | RM4SCC バーコードを表します。RM4SCC（Royal Mail 4-state Customer Code）は、英国の自動郵便仕分けプロセスで使用されます。 |
| static [SCC14](./scc14/) | データを **SCC14** バーコード仕様でエンコードする必要があることを指定します。 |
| static [SingaporePost](./singaporepost/) | データを **Singapore Post Barcode** バーコード仕様でエンコードする必要があることを指定します。 |
| static [SSCC18](./sscc18/) | データは **SSCC18** バーコード仕様でエンコードされることを指定します |
| static [Standard2of5](./standard2of5/) | データは **Standard 2 of 5** バーコード仕様でエンコードされることを指定します |
| static [SwissPostParcel](./swisspostparcel/) | データは **Swiss Post Parcel Barcode** バーコード仕様でエンコードされることを指定します。サポートされるタイプ: Domestic Mail、International Mail、Additional Services (new) |
| static [UPCA](./upca/) | データは **UPC-A** バーコード仕様でエンコードされることを指定します |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | データは **UPC coupon with GS1-128 Extended Code** バーコード仕様でエンコードされることを指定します。入力文字列の例: BarcodeGenerator.Codetext = \"514141100906(8102)03\"、ここで UPCA 部分は \"514141100906\"、GS1Code128 部分は (8102)03 です。 |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | データは **UPC coupon with GS1 DataBar addition** バーコード仕様でエンコードされることを指定します。入力文字列の例: BarcodeGenerator.Codetext = \"514141100906(8110)106141416543213500110000310123196000\"、ここで UPCA 部分は \"514141100906\"、Databar 部分は \"(8110)106141416543213500110000310123196000\" です。キャプションを変更するには、Parameters.CaptionAbove.Text = \"company prefix + offer code\" を使用します。 |
| static [UPCE](./upce/) | データは **UPC-E** バーコード仕様でエンコードされることを指定します |
| static [VIN](./vin/) | VIN（Vehicle Identification Number）バーコードを表します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
