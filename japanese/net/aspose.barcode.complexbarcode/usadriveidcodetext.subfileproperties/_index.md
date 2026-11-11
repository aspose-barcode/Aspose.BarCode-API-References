---
title: "クラス USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties クラス。USA DL サブファイルプロパティのオフセットと長さは自動的に設定されます"
type: docs
weight: 840
url: /ja/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL サブファイルプロパティ、オフセットと長さは自動的に設定されます。

```csharp
public class SubfileProperties
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。サブファイルの長さを計算する際には、セグメントターミネータを含める必要があります。セグメントターミネータ = 1。各サブファイルは2文字の Subfile Type で開始し、これら2文字も長さに含める必要があります。 |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4 桁の数値は、ファイルの先頭（ヘッド）から特定のサブファイルに関連するデータが位置するまでのバイト数を指定します。ファイルの最初のバイトはオフセット 0 にあります。 |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2 バイトのサブファイルタイプ（例: "DL"） |

### 関連項目

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


