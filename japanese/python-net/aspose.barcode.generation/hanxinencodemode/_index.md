---
title: "HanXinEncodeMode"
second_title: "Python 用 Aspose.Sildes（.NET API リファレンス）"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code のエンコーディングモードです。ASCII / 中国語文字とともに Auto を使用するか、Unicode 文字には Unicode を使用することを推奨します。

## Members
| メンバー名 | 説明 |
| :- | :- |
| AUTO | Auto モードでは、CodeText が最大限にデータを圧縮してエンコードされます。 <br/>            Unicode 文字は HanXin バーコード仕様に従い GB18030 エンコーディングでエンコードされます。 |
| BINARY | Binary モードでは、CodeText が最大限のデータ圧縮でエンコードされます。<br/>Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | ECI モードでは、メッセージ全体が指定された ECIEncoding エンコーディングで再エンコードされ、ECI 識別子が挿入されます。<br/>選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。<br/>なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |
| UNICODE | Unicode モードは、Han Xin コードで UTF8 エンコーディング/文字セットを参照して任意のテキストデータを表現する方法を提供します。 |
| URI | URI モードは、Han Xin コードで表現されるデータが Uniform Resource Identifier (URI) であることを示します<br/>            （RFC 3986 を参照）。 |
| EXTENDED | Extended モードは、内部モードの組み合わせを許可します: Auto、Binary、Text、Numeric、URI、Unicode、ECI、Common Chinese Region One、<br/>            Common Chinese Region Two、GB18030 Two Byte、GB18030 Four Byte。<br/>            コードテキストはプレフィックスと二重バックスラッシュを使用して手動で構築できます。例: @"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c" または HanXinExtCodetextBuilder を使用します。<br/>            コードテキストに ECI フラグメントが含まれる場合、ECI フラグメント以降のコードテキストで使用できるモードは次のものに限定されます:<br/>            Auto、Binary、Text、Numeric、URI、ECI. |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

