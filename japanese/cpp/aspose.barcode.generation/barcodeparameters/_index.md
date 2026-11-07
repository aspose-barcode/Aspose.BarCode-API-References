---
title: "Aspose::BarCode::Generation::BarcodeParameters クラス"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::BarcodeParameters クラス。C++ のバーコード生成パラメータです。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


バーコード生成パラメーター。

```cpp
class BarcodeParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost バーコードパラメーター。 |
| [get_Aztec](./get_aztec/)() const | Aztec パラメーター。 |
| [get_BarColor](./get_barcolor/)() const | バーの色。デフォルト値: Color.Black。 |
| [get_BarHeight](./get_barheight/)() const | 1D バーコードのバーの高さを [Unit](../unit/) の値で指定します。 [BaseGenerationParameters::AutoSizeMode](../) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合は無視されます。 |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | バーの減少値を取得または設定します。この値は印刷時のインク拡散を補正するために使用されます。デフォルト値: 0。 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Code128 と GS1Code128 バーコードの人が読めるテキストに常にチェックサム桁を表示します。 |
| [get_Codabar](./get_codabar/)() const | Codabar パラメータ。 |
| [get_Codablock](./get_codablock/)() const | Codablock パラメータ。 |
| [get_Code128](./get_code128/)() const | Code128 パラメータ。 |
| [get_Code16K](./get_code16k/)() const | Code16K パラメータ。 |
| [get_CodeTextParameters](./get_codetextparameters/)() const | コードテキスト パラメータ。 |
| [get_Coupon](./get_coupon/)() const | クーポンパラメータ。UpcaGs1DatabarCoupon と UpcaGs1Code128Coupon に使用されます。 |
| [get_DataBar](./get_databar/)() const | Databar パラメータ。 |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix パラメータ。 |
| [get_DotCode](./get_dotcode/)() const | DotCode パラメータ。 |
| [get_FilledBars](./get_filledbars/)() const | バーが塗りつぶされているかどうかを示す値を取得します。1D バーコード専用です。デフォルト値: true。 |
| [get_GS1](./get_gs1/)() const | GS1 パラメータ。 |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 コンポジットバーのパラメータ。 |
| [get_HanXin](./get_hanxin/)() const | HanXin のパラメータ。 |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF パラメータ。 |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode パラメータ。 |
| [get_Padding](./get_padding/)() const | バーコードのパディング。デフォルト値: 5pt 5pt 5pt 5pt。 |
| [get_PatchCode](./get_patchcode/)() const | PatchCode パラメータ。 |
| [get_Pdf417](./get_pdf417/)() const | PDF417 のパラメータ。 |
| [get_Postal](./get_postal/)() const | 郵便パラメータ。Postnet、Planet 用。 |
| [get_QR](./get_qr/)() const | QR、MicroQR、RectMicroQR のパラメータ。 |
| [get_Supplement](./get_supplement/)() const | 補足パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN 用。 |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | 1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。それ以外の場合、codetext はバーコードの仕様に合わせて修正されます。例外は常にスローされます: Databar シンボロジーで codetext が正しくない場合。例外がスローされないのは常に次の場合です: AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジーで codetext が正しくない場合。 |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | 太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII で使用されます。 |
| [get_XDimension](./get_xdimension/)() const | x-ディメンションは [BarCode](../../aspose.barcode/) のバーまたはスペースの単位の最小幅です。これを増やすとバーコード画像全体の幅が広がります。[BaseGenerationParameters::AutoSizeMode](../) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合は無視されます。 |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | バーの色。デフォルト値: Color.Black。 |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | 1D バーコードのバーの高さを [Unit](../unit/) の値で指定します。 [BaseGenerationParameters::AutoSizeMode](../) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合は無視されます。 |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | バーの減少値を取得または設定します。この値は印刷時のインク拡散を補正するために使用されます。デフォルト値: 0。 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Code128 と GS1Code128 バーコードの人が読めるテキストに常にチェックサム桁を表示します。 |
| [set_FilledBars](./set_filledbars/)(bool) | バーが塗りつぶされているかどうかを示す値を設定します。1D バーコード専用です。デフォルト値: true。 |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 コンポジットバーのパラメータ。 |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | 1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。それ以外の場合、codetext はバーコードの仕様に合わせて修正されます。例外は常にスローされます: Databar シンボロジーで codetext が正しくない場合。例外がスローされないのは常に次の場合です: AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジーで codetext が正しくない場合。 |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | 太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII で使用されます。 |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-ディメンションは [BarCode](../../aspose.barcode/) のバーまたはスペースの単位の最小幅です。これを増やすとバーコード画像全体の幅が広がります。[BaseGenerationParameters::AutoSizeMode](../) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合は無視されます。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
