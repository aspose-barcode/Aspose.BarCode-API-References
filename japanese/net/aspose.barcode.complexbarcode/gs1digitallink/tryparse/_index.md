---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "GS1DigitalLink メソッド。圧縮されていない GS1 Digital Link URI の解析を試み、構造化された検証エラーを返します。"
type: docs
weight: 190
url: /ja/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

圧縮されていない GS1 Digital Link URI の解析を試み、構造化された検証エラーを返します。

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | 文字列 | 解析対象の GS1 Digital Link URI。 |
| 結果 | GS1DigitalLink& | このメソッドが true を返す場合、解析された GS1 Digital Link を含みます。そうでない場合は null です。 |
| validationResult | GS1ValidationResult& | 検証結果を含みます、または *value* が null のときは null です。 |

### 戻り値

解析が成功した場合は true、そうでない場合は false です。

### 関連項目

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


