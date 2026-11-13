---
title: "GS1ValidationErrorCode"
second_title: "Python 用 Aspose.Sildes（.NET API リファレンス）"
description: 
type: docs
url: /ja/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

GS1 要素文字列、Digital Link URI、または値の検証エラーを識別します。

## Members
| メンバー名 | 説明 |
| :- | :- |
| EMPTY_ELEMENT_STRING | 提供されたGS1要素文字列が空です。 |
| MISSING_OPENING_PARENTHESIS | Application Identifierの開始に必要な開き括弧がありません。 |
| MISSING_CLOSING_PARENTHESIS | Application Identifierに閉じ括弧がありません。 |
| INVALID_APPLICATION_IDENTIFIER | Application Identifierは2〜4桁のASCII数字を含んでいません。 |
| UNKNOWN_APPLICATION_IDENTIFIER | 提供されたApplication Identifierは、サポートされているGS1構文辞書で定義されていません。 |
| MISSING_VALUE | Application Identifierが値なしで存在しています。 |
| INVALID_ESCAPE_SEQUENCE | 値にサポートされていないエスケープシーケンスが含まれています。サポートされているのは \( のみです。 |
| VALUE_TOO_SHORT | 値が、そのApplication Identifierに定義された最小長さより短いです。 |
| VALUE_TOO_LONG | 値が、そのApplication Identifierに定義された最大長さを超えています。 |
| INVALID_CHARACTER | 値に、そのコンポーネントで許可された文字セット外の文字が含まれています。 |
| INVALID_CHECKSUM | 数値または英字のチェックサムが無効です。 |
| INVALID_DATE | 日付コンポーネントが、そのApplication Identifierで定義された規則に基づく有効な日付ではありません。 |
| INVALID_TIME | 時間コンポーネントが許容範囲外であるか、無効な構造です。 |
| INVALID_CODE_LIST_VALUE | コンポーネントの値が許可された閉じたコードリストに存在しません。 |
| INVALID_COMPONENT_LENGTH | コンポーネントがそのコンポーネント固有の長さ構造を満たしていません。 |
| TRUNCATED_COMPONENT | 固定長コンポーネントが、すべての必須文字が揃う前に終了しています。 |
| UNEXPECTED_DATA | アプリケーション識別子用に定義されたすべてのコンポーネントが消費された後にデータが残っています。 |
| INVALID_VALUE | コンポーネントが、より具体的な検証エラーコードが存在しないコンテンツルールに違反しています。 |
| GCP_PREFIX_TOO_SHORT | コンポーネントが、最小4桁の構造的GS1カンパニープレフィックスを含むには短すぎます。 |
| INVALID_GCP_PREFIX | 構造的GS1カンパニープレフィックスに、ASCII数字以外の文字が含まれています。 |
| INVALID_DIGITAL_LINK_URI | 提供された値は、正しく形成された絶対GS1デジタルリンクURIではありません。 |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | GS1デジタルリンクURIが、HTTPまたはHTTPS以外のスキームを使用しています。 |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | GS1デジタルリンクURIのパスに、サポートされているプライマリキーが含まれていません。 |
| INVALID_DIGITAL_LINK_PATH | GS1デジタルリンクURIのパスが、有効なAIと値のペアで構成されていません。 |
| INVALID_DIGITAL_LINK_QUALIFIER | パスのアプリケーション識別子は、その位置で許可された修飾子ではありません。 |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | GS1 デジタルリンクのクエリパラメータが不正です。 |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Application Identifier は GS1 デジタルリンクのデータ属性として許可されていません。 |
| INVALID_PERCENT_ENCODING | GS1 デジタルリンクの URI コンポーネントに不正なパーセントエンコーディングが含まれています。 |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | GS1 デジタルリンクの主キーとして複数の要素が選択される可能性があります。 |
| UNSUPPORTED_ELEMENT_COMBINATION | 指定された GS1 要素の組み合わせは、選択されたシンボルまたはエンコーディングモードでサポートされていません。 |

### 関連項目

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

