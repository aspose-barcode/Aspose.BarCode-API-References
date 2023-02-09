---
title: TryParse
second_title: Aspose.BarCode for.NETAPIリファレンス
description: SingleDecodeType の文字列表現をそのインスタンスに変換します 戻り値は変換が成功したか失敗したかを示します
type: docs
weight: 920
url: /ja/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

SingleDecodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| parsingType | String | 変換する "Index:-1; Name:None" の形式の文字列。 |
| result | SingleDecodeType& | 変換が正常に完了すると、実際の SingleDecodeType が返されます。 |

### 戻り値

**真実** s が正常に変換された場合。さもないと、 **間違い**.

### 関連項目

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* 組み立て [Aspose.BarCode](../../../)

---

## TryParse(string, out MultyDecodeType) {#tryparse}

MultyDecodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。

```csharp
public static bool TryParse(string parsingType, out MultyDecodeType result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| parsingType | String | 変換する "AllSupportedTypes" または "EAN8,EAN13,CodaBar" の形式の文字列。 |
| result | MultyDecodeType& | 変換が正常に完了すると、実際の MultyDecodeType が返されます。 |

### 戻り値

**真実** s が正常に変換された場合。さもないと、 **間違い**.

### 関連項目

* class [MultyDecodeType](../../multydecodetype/)
* class [DecodeType](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* 組み立て [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->