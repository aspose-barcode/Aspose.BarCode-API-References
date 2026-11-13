---
title: "DataMatrixEncodeMode"
second_title: "Python 用 Aspose.Sildes（.NET API リファレンス）"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

DataMatrix エンコーダのエンコードモード、デフォルトは Auto

## Members
| メンバー名 | 説明 |
| :- | :- |
| AUTO | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字は、指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。<br/>選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| ASCII | 1 バイトあたり、1 つの英数字または 2 つの数字文字をエンコードします。 |
| C40 | C40 エンコーディングを使用します。大文字の英数字、 小文字、および特殊文字をエンコードします。 |
| TEXT | Text エンコーディングを使用します。小文字の英数字、大文字、および特殊文字をエンコードします。 |
| EDIFACT | EDIFACT エンコーディングを使用します。1 文字あたり 6 ビットを使用し、数字、大文字の文字、 多くの句読点をエンコードしますが、小文字はサポートされていません。 |
| ANSIX12 | ANSI X12 エンコーディングを使用します。 |
| EXTENDED |  |
| BASE256 | 8 ビットの値をエンコードします。 |
| BINARY | Binary モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | ECI モードでは、メッセージ全体が指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。<br/>選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。<br/>なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

