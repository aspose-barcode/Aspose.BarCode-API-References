---
title: "MaxiCodeEncodeMode"
second_title: "Python 用 Aspose.Sildes（.NET API リファレンス）"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

MaxiCode バーコードのエンコーディングモード。

## Members
| メンバー名 | 説明 |
| :- | :- |
| AUTO | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字は、指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。<br/>選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| EXTENDED |  |
| BINARY | Binary モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | ECI モードでは、メッセージ全体が指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。<br/>選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。<br/>なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

