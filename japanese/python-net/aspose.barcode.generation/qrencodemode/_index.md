---
title: "QREncodeMode"
second_title: "Python 用 Aspose.Sildes（.NET API リファレンス）"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

QR バーコードのエンコーディングモード。

## Members
| メンバー名 | 説明 |
| :- | :- |
| AUTO | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。 <br/>            可能な場合は Unicode 文字は漢字モードでエンコードされ、そうでない場合は指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。<br/>            選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| EXTENDED |  |
| BINARY | Binary モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | ECI モードでは、メッセージ全体が指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。<br/>            選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。<br/>            一部の古い（2006 年以前の）スキャナーはこのモードをサポートしない可能性があることに注意してください。<br/>            このモードは MicroQR バーコードではサポートされていません。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

