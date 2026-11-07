---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. C++ における GS1 要素文字列、Digital Link URI、または値の検証エラーを識別します。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


GS1 要素文字列、Digital Link URI、または値の検証エラーを識別します。

```cpp
enum class GS1ValidationErrorCode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| EmptyElementString | 0 | 提供された GS1 要素文字列は空です。 |
| MissingOpeningParenthesis | 1 | Application Identifier の開始に必要な開き括弧がありません。 |
| MissingClosingParenthesis | 2 | Application Identifier に閉じ括弧がありません。 |
| InvalidApplicationIdentifier | 3 | Application Identifier に 2〜4 桁の ASCII 数字が含まれていません。 |
| UnknownApplicationIdentifier | 4 | 提供された Application Identifier は、サポートされている GS1 Syntax Dictionary で定義されていません。 |
| MissingValue | 5 | Application Identifier が値なしで存在しています。 |
| InvalidEscapeSequence | 6 | 値にサポートされていないエスケープシーケンスが含まれています。サポートされているのは ( のみです。 |
| ValueTooShort | 7 | 値が、その Application Identifier に定義された最小長さより短くなっています。 |
| ValueTooLong | 8 | 値が、そのアプリケーション識別子で定義された最大長さを超えています。 |
| InvalidCharacter | 9 | 値に、コンポーネントで許可された文字セット外の文字が含まれています。 |
| InvalidChecksum | 10 | 数値または英字のチェックサムが無効です。 |
| InvalidDate | 11 | 日付コンポーネントは、アプリケーション識別子で定義された規則に基づく有意な日付ではありません。 |
| InvalidTime | 12 | 時間コンポーネントが許可範囲外であるか、構造が無効です。 |
| InvalidCodeListValue | 13 | コンポーネントの値が、許可されたクローズドコードリストに存在しません。 |
| InvalidComponentLength | 14 | コンポーネントが、そのコンポーネント固有の長さ構造を満たしていません。 |
| TruncatedComponent | 15 | 固定長コンポーネントが、すべての必須文字が揃う前に終了しています。 |
| UnexpectedData | 16 | アプリケーション識別子用に定義されたすべてのコンポーネントが処理された後にデータが残っています。 |
| 無効な値 | 17 | コンポーネントが、より具体的な検証エラーコードがないコンテンツルールに違反しています。 |
| GcpPrefixTooShort | 18 | コンポーネントが短すぎて、最低4桁の構造的GS1カンパニープレフィックスを含めることができません。 |
| InvalidGcpPrefix | 19 | 構造的GS1カンパニープレフィックスに、ASCII数字以外の文字が含まれています。 |
| InvalidDigitalLinkUri | 20 | 提供された値は、正しく形成された絶対GS1デジタルリンクURIではありません。 |
| UnsupportedDigitalLinkScheme | 21 | GS1デジタルリンクURIが、HTTPまたはHTTPS以外のスキームを使用しています。 |
| MissingDigitalLinkPrimaryKey | 22 | GS1デジタルリンクURIのパスに、サポートされているプライマリキーが含まれていません。 |
| InvalidDigitalLinkPath | 23 | GS1デジタルリンクURIのパスが、有効なAIと値のペアで構成されていません。 |
| InvalidDigitalLinkQualifier | 24 | パスのアプリケーション識別子は、その位置では許可された修飾子ではありません。 |
| InvalidDigitalLinkQueryParameter | 25 | GS1 デジタルリンクのクエリ パラメータが不正です。 |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Application Identifier は GS1 デジタルリンクのデータ属性として許可されていません。 |
| InvalidPercentEncoding | 27 | GS1 デジタルリンクの URI コンポーネントに不正なパーセントエンコーディングが含まれています。 |
| MultipleDigitalLinkPrimaryKeys | 28 | GS1 デジタルリンクの主キーとして複数の要素が選択可能です。 |
| UnsupportedElementCombination | 29 | 指定された GS1 要素の組み合わせは、選択されたシンボルまたはエンコーディングモードでサポートされていません。 |

## 関連項目

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
