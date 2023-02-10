---
title: DecodeType
second_title: Aspose.BarCode for.NETAPIリファレンス
description: 読み取るバーコードの種類を指定します
type: docs
weight: 190
url: /ja/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

読み取るバーコードの種類を指定します。

```csharp
public static class DecodeType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | AllSupportedTypes を表す配列を取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | デコード タイプの名前の配列を取得します。 |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | 指定された[`BaseDecodeType`](../basedecodetype/) 1D バーコード symbology を含む |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | 指定された[`BaseDecodeType`](../basedecodetype/)2D バーコード symbology を含む |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | 指定された[`BaseDecodeType`](../basedecodetype/)任意の郵便バーコードを含む symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。 |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | バーコードタイプでスキャンセットを指定 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | MultyDecodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | 使用可能なすべてのシンボル体系でデータをチェックすることを指定します |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | でデータをデコードする必要があることを指定します **オーストラリア郵便の国内 eParcel バーコード**バーコード仕様 |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | でデータをデコードする必要があることを指定します **オーストラリアポスト**バーコード仕様 |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | でデータをデコードする必要があることを指定します **アステカ**バーコード仕様 |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | でデータをデコードする必要があることを指定します **コーダバー**バーコード仕様 |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | でデータをデコードする必要があることを指定します **CodablockF**バーコード仕様 |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | でデータをデコードする必要があることを指定します **コード 11**バーコード仕様 |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | でデータをデコードする必要があることを指定します **コード 128**バーコード仕様 |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | でデータをデコードする必要があることを指定します **SCode16K**バーコード仕様 |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | でデータをデコードする必要があることを指定します **Code32**ブランク仕様 |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | でデータをデコードする必要があることを指定します **拡張コード 39**バーコード仕様 |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | でデータをデコードする必要があることを指定します **標準コード 39**バーコード仕様 |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | でデータをデコードする必要があることを指定します **拡張コード 93**バーコード仕様 |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | でデータをデコードする必要があることを指定します **標準コード 93**バーコード仕様 |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | でデータをデコードする必要があることを指定します **コンパクトPDF417**(Pdf417Truncated) バーコード仕様 |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | でデータをデコードする必要があることを指定します **GS1 データバーの拡張**バーコード仕様 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | でデータをデコードする必要があることを指定します **GS1 Databar 拡張スタック**バーコード仕様 |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | でデータをデコードする必要があることを指定します **GS1 データバー限定**バーコード仕様 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | でデータをデコードする必要があることを指定します **GS1 Databar 無指向性**バーコード仕様 |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | でデータをデコードする必要があることを指定します **GS1 Databar 積み上げ**バーコード仕様 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | でデータをデコードする必要があることを指定します **GS1 Databar スタック全方向**バーコード仕様 |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | でデータをデコードする必要があることを指定します **GS1 データバーが切り捨てられました**バーコード仕様 |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | でデータをデコードする必要があることを指定します **DataLogic 2/5**ブランク仕様 |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | でデータをデコードする必要があることを指定します **データマトリックス**バーコード symbology |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | でデータをデコードする必要があることを指定します **DeutschePost ID コード**バーコード仕様 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | でデータをデコードする必要があることを指定します **ドイツポストのLeitコード**バーコード仕様 |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | でデータをデコードする必要があることを指定します **ドットコード**ブランク仕様 |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | でデータをデコードする必要があることを指定します **ドットコード**ブランク仕様 |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | でデータをデコードする必要があることを指定します **EAN-13**バーコード仕様 |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | でデータをデコードする必要があることを指定します **EAN14**バーコード仕様 |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | でデータをデコードする必要があることを指定します **EAN-8**バーコード仕様 |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | でデータをデコードする必要があることを指定します **GS1 コード 128**バーコード仕様 |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | でデータをデコードする必要があることを指定します **GS1データマトリックス**バーコード symbology |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | でデータをデコードする必要があることを指定します **GS1ドットコード**ブランク仕様 |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | でデータをデコードする必要があることを指定します **GS1 QR**バーコード仕様 |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | でデータをデコードする必要があることを指定します **HIBC LIC アステカ**ブランク仕様 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | でデータをデコードする必要があることを指定します **HIBC PAS アズテック**ブランク仕様 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | でデータをデコードする必要があることを指定します **HIBC LICコード128**ブランク仕様 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | でデータをデコードする必要があることを指定します **HIBC PAS Code128**ブランク仕様 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | でデータをデコードする必要があることを指定します **HIBC LIC Code39**ブランク仕様 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | でデータをデコードする必要があることを指定します **HIBC PAS Code39**ブランク仕様 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | でデータをデコードする必要があることを指定します **HIBC LIC データマトリックス**ブランク仕様 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | でデータをデコードする必要があることを指定します **HIBC PAS データマトリックス**ブランク仕様 |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | でデータをデコードする必要があることを指定します **HIBC LIC QR**ブランク仕様 |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | でデータをデコードする必要があることを指定します **HIBC PAS QR**ブランク仕様 |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | でデータをデコードする必要があることを指定します **IATA 2/5**バーコード仕様。 IATA（国際航空運送協会）はこのバーコードを航空貨物の管理に使用しています. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | でデータをデコードする必要があることを指定します **インターリーブ 2 の 5**バーコード仕様 |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | でデータをデコードする必要があることを指定します **ISBN**バーコード仕様 |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | でデータをデコードする必要があることを指定します **ISMN**バーコード仕様 |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | でデータをデコードする必要があることを指定します **ISSN**バーコード仕様 |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | でデータをデコードする必要があることを指定します **イタリアンポスト25**バーコード仕様 |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | でデータをデコードする必要があることを指定します **ITF14**バーコード仕様 |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | でデータをデコードする必要があることを指定します **ITF6**バーコード仕様 |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | でデータをデコードする必要があることを指定します **MacroPdf417**バーコード仕様 |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | でデータをデコードする必要があることを指定します **ロイヤルメールのメールマーク**バーコード仕様. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | でデータをデコードする必要があることを指定します **マトリックス 2/5**バーコード仕様 |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | でデータをデコードする必要があることを指定します **マキシコード**バーコード仕様 |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | でデータをデコードする必要があることを指定します **MICR E-13B**ブランク仕様 |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | でデータをデコードする必要があることを指定します **MicroPdf417**バーコード仕様 |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | でデータをデコードする必要があることを指定します **マイクロQRコード**バーコード仕様 |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | 最も一般的に使用されるシンボル体系でデータをチェックすることを指定します |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | でデータをデコードする必要があることを指定します **MSIプレッシー**バーコード仕様 |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | 未指定のデコード タイプ。 |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | データを USPS でデコードする必要があることを指定します **ワンコード**バーコード仕様 |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | でデータをデコードする必要があることを指定します **OPC**バーコード仕様 |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | でデータをデコードする必要があることを指定します **パッチコード**バーコード仕様。バーコード記号は自動スキャンに使用されます |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | でデータをデコードする必要があることを指定します **PDF417**バーコード symbology |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | でデータをデコードする必要があることを指定します **ファーマコード**バーコード。このシンボル体系は、Pharmaceutical Binary Code としても知られています。 |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | でデータをデコードする必要があることを指定します **星**バーコード仕様 |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | すべてのデータをチェックすることを指定します。 **1.5D郵便**バーコード記号など **Planet、Postnet、AustraliaPost、OneCode、RM4SCC、DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | でデータをデコードする必要があることを指定します **ポストネット**バーコード仕様 |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | でデータをデコードする必要があることを指定します **PZN**バーコード仕様。このシンボルは、Pharma Zentral Nummer としても知られています。 |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | でデータをデコードする必要があることを指定します **QRコード**バーコード仕様 |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | でデータをデコードする必要があることを指定します **RM4SCC**バーコード仕様。 RM4SCC (Royal Mail 4-state Customer Code) は、英国の自動郵便仕分けプロセスに使用されます. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | でデータをデコードする必要があることを指定します **SCC14**バーコード仕様 |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | でデータをデコードする必要があることを指定します **SSCC18**バーコード仕様 |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | でデータをデコードする必要があることを指定します **標準 2 の 5**バーコード仕様 |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | でデータをデコードする必要があることを指定します **補足(EAN2、EAN5)**バーコード仕様 |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | でデータをデコードする必要があることを指定します **スイス郵便小包バーコード**バーコード仕様 |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | すべてのデータをチェックすることを指定します。 **1D**バーコード記号 |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | すべてのデータをチェックすることを指定します。 **二次元**バーコード記号 |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | でデータをデコードする必要があることを指定します **UPC-A**バーコード仕様 |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | でデータをデコードする必要があることを指定します **UPC-E**バーコード仕様 |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | でデータをデコードする必要があることを指定します **ヴィン** （車両識別番号）バーコード仕様 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 関連項目

* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
