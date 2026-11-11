---
title: "列挙体 GS1ValidationErrorCode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode 列挙体。GS1 要素文字列、Digital Link URI、または値の検証エラーを識別します"
type: docs
weight: 430
url: /ja/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

GS1 要素文字列、Digital Link URI、または値の検証エラーを識別します。

```csharp
public enum GS1ValidationErrorCode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| EmptyElementString | `0` | 提供された GS1 要素文字列が空です。 |
| MissingOpeningParenthesis | `1` | Application Identifier の開始を示す開き括弧が欠落しています。 |
| MissingClosingParenthesis | `2` | Application Identifier に閉じ括弧がありません。 |
| InvalidApplicationIdentifier | `3` | Application Identifier が 2〜4 桁の ASCII 数字を含んでいません。 |
| UnknownApplicationIdentifier | `4` | 提供された Application Identifier は、サポートされている GS1 構文辞書で定義されていません。 |
| MissingValue | `5` | Application Identifier が値なしで存在しています。 |
| InvalidEscapeSequence | `6` | 値にサポートされていないエスケープシーケンスが含まれています。サポートされているのは \( のみです。 |
| ValueTooShort | `7` | 値が、その Application Identifier に定義された最小長さより短いです。 |
| ValueTooLong | `8` | 値が、その Application Identifier に定義された最大長さを超えています。 |
| InvalidCharacter | `9` | 値に、そのコンポーネントで許可されている文字セット外の文字が含まれています。 |
| InvalidChecksum | `10` | 数値または英字のチェックサムが無効です。 |
| InvalidDate | `11` | 日付コンポーネントが、その Application Identifier 用に定義された規則において有意な日付ではありません。 |
| InvalidTime | `12` | 時間コンポーネントが許可範囲外であるか、構造が無効です。 |
| InvalidCodeListValue | `13` | コンポーネント値が、許可されたクローズドコードリストに存在しません。 |
| InvalidComponentLength | `14` | コンポーネントが、そのコンポーネント固有の長さ構造を満たしていません。 |
| TruncatedComponent | `15` | 固定長コンポーネントが、すべての必須文字が揃う前に終了しています。 |
| UnexpectedData | `16` | Application Identifier 用に定義されたすべてのコンポーネントが消費された後にデータが残っています。 |
| InvalidValue | `17` | コンポーネントが、より具体的な検証エラーコードが存在しないコンテンツ規則に違反しています。 |
| GcpPrefixTooShort | `18` | コンポーネントが短すぎて、最低4桁の構造的GS1カンパニープレフィックスを含むことができません。 |
| InvalidGcpPrefix | `19` | 構造的GS1カンパニープレフィックスにASCII数字以外の文字が含まれています。 |
| InvalidDigitalLinkUri | `20` | 提供された値は、正しく形成された絶対GS1デジタルリンクURIではありません。 |
| UnsupportedDigitalLinkScheme | `21` | GS1デジタルリンクURIがHTTPまたはHTTPS以外のスキームを使用しています。 |
| MissingDigitalLinkPrimaryKey | `22` | GS1デジタルリンクURIのパスにサポートされているプライマリキーが含まれていません。 |
| InvalidDigitalLinkPath | `23` | GS1デジタルリンクURIのパスが有効なAIと値のペアで構成されていません。 |
| InvalidDigitalLinkQualifier | `24` | パスのアプリケーション識別子は、その位置で許可された修飾子ではありません。 |
| InvalidDigitalLinkQueryParameter | `25` | GS1デジタルリンクのクエリパラメータが不正な形式です。 |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | アプリケーション識別子はGS1デジタルリンクのデータ属性として許可されていません。 |
| InvalidPercentEncoding | `27` | GS1デジタルリンクURIのコンポーネントに不正なパーセントエンコーディングが含まれています。 |
| MultipleDigitalLinkPrimaryKeys | `28` | GS1デジタルリンクのプライマリキーとして複数の要素が選択可能です。 |
| UnsupportedElementCombination | `29` | 提供されたGS1要素の組み合わせは、選択されたシンボルまたはエンコーディングモードでサポートされていません。 |

### 関連項目

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


