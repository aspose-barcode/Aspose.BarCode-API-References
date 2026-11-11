---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "GS1Codetext メソッド。AIvalueAIvalue 形式の括弧付き GS1 要素文字列の解析を試み、構造化された検証エラーを返します。値内のリテラル  は  と記述する必要があり、他のエスケープシーケンスはサポートされず、  はエスケープする必要がありません。"
type: docs
weight: 140
url: /ja/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

括弧で囲まれた GS1 要素文字列 (AI)value(AI)value の形式を解析しようとし、構造化された検証エラーを返します。値の中のリテラルな '(' は \\( と記述する必要があります。他のエスケープシーケンスはサポートされておらず、')' はエスケープする必要はありません。

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | 文字列 | 解析する括弧付き GS1 要素文字列。 |
| 結果 | GS1Codetext& | このメソッドが true を返す場合、解析された GS1 コードテキストが含まれます。そうでない場合は null です。 |
| validationResult | GS1ValidationResult& | 検証結果を含みます、または *value* が null のときは null です。 |

### 戻り値

解析が成功した場合は true、そうでない場合は false です。

### 関連項目

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


