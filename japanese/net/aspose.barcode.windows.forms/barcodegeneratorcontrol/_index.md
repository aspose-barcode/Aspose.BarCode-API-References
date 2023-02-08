---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode for.NETAPIリファレンス
description: BarCode Windows コントロールツールボックス パネルに移動しAspose.BarCode.dll を追加するとBarcodeGeneratorControl が表示されます Windows フォームにドラッグ アンド ドロップするだけです を参照してください 参照
type: docs
weight: 1320
url: /ja/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows コントロール、ツールボックス パネルに移動し、Aspose.BarCode.dll、 を追加すると、BarcodeGeneratorControl が表示されます。 Windows フォームにドラッグ アンド ドロップするだけです。 を参照してください。 参照

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | バーコードが自動的にサイズ変更されるモードを取得または設定します。 デフォルト値は AutoSizeMode.None. です。 |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | バーコード画像の背景色. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | 時のバーコード画像の高さ[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation. に設定されている |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | バーコード パディング パラメータを取得または設定します[`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | バーコードのエンコード タイプ (シンボル)。 使用[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/)現在のシンボルを取得します. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | 時のバーコード画像幅[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation. に設定されている |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | バーの色. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D バーコードのバーの高さ. 次の場合は無視されます[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation. に設定されている |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Border パラメータを取得または設定します[`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | キャプション バーコード画像の上。見る[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | キャプション バーコード画像の下。見る[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Code128 および GS1Code128 バーコードの人間が読めるテキストに常にチェックサム数字を表示します。 |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | エンコードされるデータ。バーコードの種類によって、CodeText の長さの制限が異なる場合があります。 |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | CodeText パラメーターを取得または設定します[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/). |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | CodeText プロパティで文字「\」をエスケープ文字として説明するかどうかを示します。 Pdf417、DataMatrix、Code128 のみに使用 EnableEscape が true の場合、「\」は特殊なエスケープ文字として説明されます。それ以外の場合、「\」は通常の文字として機能します. Aspose.BarCode は、10 進数の ASCII コードと ASCII コントロール コード文字のニーモニックの入力をサポートします。たとえば、\013 と \\CR は CR を表します。 |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | バーコードのエンコード タイプ (シンボル)。 使用[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/)現在のシンボルを取得します. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | バーが塗りつぶされているかどうかを示す値を取得または設定します. 1D バーコードのみ. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 1D バーコードの生成中にチェックサムを有効にします。 |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | バーコード イメージの解像度を取得または設定します。 両方の寸法に対して 1 つの値。 デフォルト値: 96 dpi。 |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | バーコード画像の回転角度。度単位で測定されます。たとえば、RotationAngle = 0 または RotationAngle = 360 は回転しないことを意味します。 RotationAngle が 90、180、270、または 0 に等しくない場合、スキャナーが画像を読み取るのが難しくなる可能性があります。 |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | 特定のパラメーター |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | 1D バーコードのみ。 codetext が正しくなく、値が true に設定されている場合 - 例外がスローされます。それ以外の場合、codetext はバーコードの仕様に一致するように修正されます。 次の場合は常に例外がスローされます: codetext が正しくない場合は Databar シンボル体系。 次の場合は例外は常にスローされません: . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | 幅の広いバーと幅の狭いバーの比率。 デフォルト値: 3。つまり、幅の広いバーは幅の狭いバーの 3 倍です。 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost に使用されます。 、OPC、Code32、DataLogic2of5、PatchCode、Code39Extended、Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X 寸法は、バーコード バーまたはスペースの単位の最小幅です。 これを大きくすると、バーコード イメージ全体の幅が大きくなります。 次の場合は無視されます。[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation. に設定されている |

### 関連項目

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* 名前空間 [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
