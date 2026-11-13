---
title: "QrParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR パラメータ。

QrParameters 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| eci_encoding | 拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用される参照に関する詳細をバーコードリーダーに伝えるために使用されます。<br/>            現在の実装は、すべてのよく知られた文字セットエンコーディングを含みます。<br/>            MicroQR ではサポートされていません。 |
| encode_mode | バーコードのエンコードモードの QR シンボロジータイプです。<br/>            デフォルト値: QREncodeMode.Auto. |
| error_level | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。<br/>             低から高: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。 |
| version | QR コードのバージョンです。Version1 から Version40 まで。<br/>            デフォルト値は QRVersion.Auto です。 |
| micro_qr_version | MicroQR コードのバージョンです。M1 から M4 まで。<br/>            デフォルト値は MicroQRVersion.Auto です。 |
| rect_micro_qr_version | RectMicroQR コードのバージョンです。R7x59 から R17x139 まで。<br/>            デフォルト値は RectMicroQRVersion.Auto です。 |
| aspect_ratio | 2D バーコードモジュールの高さ/幅比率。 |
| structured_append | QR の構造化追加パラメータです。<br/>            構造化追加モードは MicroQR および RectMicroQR バーコードではサポートされていません。 |
| encode_gs1_separator_in_byte_mode |  |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

