---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

バーコード生成パラメータ。

BarcodeParameters 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| x_dimension | x-dimension はバーコードのバーまたはスペースの単位の最小幅です。<br/>            これを増やすと全体のバーコード画像の幅が広がります。<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。 |
| bar_height | 1D バーコードのバーの高さを [Unit](/barcode/python-net/aspose.barcode.generation/unit/) の値で指定します。<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。 |
| bar_color | バーの色。<br/>            デフォルト値: Color.Black. |
| padding | バーコードの余白。<br/>            デフォルト値: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Code128 および GS1Code128 バーコードの人が読めるテキストにチェックサム桁を常に表示します。 |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | 1D バーコード専用です。<br/>            codetext が正しくなく、値が true に設定されている場合は例外がスローされます。そうでない場合、codetext はバーコードの仕様に合わせて修正されます。<br/>            例外は常にスローされます: codetext が正しくない場合の Databar シンボル。<br/>            例外は常にスローされません: codetext が正しくない場合の AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボル。 |
| wide_narrow_ratio | 太いバーと細いバーの比率。<br/>            デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。<br/>            使用対象: ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII |
| code_text_parameters | Codetext パラメータ。 |
| filled_bars | バーが塗りつぶされているかどうかを示す値を取得または設定します。<br/>            1D バーコード専用です。<br/>            デフォルト値: true. |
| bar_width_reduction | 印刷時のインク拡散を補正するために使用されるバー幅削減値を取得または設定します。<br/>            デフォルト値: 0 |
| postal | 郵便パラメータ。Postnet と Planet 用です。 |
| patch_code | PatchCode パラメータ。 |
| australian_post | AustralianPostバーコードパラメータです。 |
| data_bar | Databar パラメータ。 |
| gs1_composite_bar | GS1 Composite Bar パラメータ。 |
| codablock | Codablock パラメータ。 |
| data_matrix | DataMatrix パラメータ。 |
| code_16k | Code16K パラメータ。 |
| dot_code | DotCode パラメータ。 |
| itf | ITF パラメータ。 |
| pdf417 | PDF417 パラメータ。 |
| qr | QR、MicroQR および RectMicroQR パラメータ。 |
| supplement | 補足パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN 用です。 |
| maxi_code | MaxiCode パラメータ。 |
| aztec | Aztec パラメータ。 |
| code128 | Code128 パラメータ。 |
| codabar | Codabar パラメータ。 |
| coupon | クーポンパラメータ。UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon に使用されます。 |
| han_xin | HanXin パラメータ。 |
| gs1 | GS1 パラメータ。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

