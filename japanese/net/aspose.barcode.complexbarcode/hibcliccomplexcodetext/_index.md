---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode for.NETAPIリファレンス
description: HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするための基本クラス
type: docs
weight: 380
url: /ja/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするための基本クラス。

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | バーコード タイプを取得または設定します。 HIBC LIC コードテキストは、HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、および HIBCQRLIC エンコード タイプを使用してエンコードできます。 デフォルト値: HIBCCode39LIC. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | バーコードの種類を取得します。 |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | を構築します codetext |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | 構築されたコードテキストからインスタンスを初期化します. |

### 例

このサンプルは、未加工の HIBC LIC コードテキストを HIBCLICComplexCodetext インスタンスにデコードする方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### 関連項目

* interface [IComplexCodetext](../icomplexcodetext/)
* 名前空間 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->