---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417 パラメータ。PDF417、MacroPDF417、MicroPDF417、GS1MicroPdf417 のパラメータを含みます。<br/>            MacroPDF417 には 2 つのフィールドが必要です：Pdf417MacroFileID と Pdf417MacroSegmentID。その他のフィールドはオプションです。<br/>            Structured Append モード（MacroPDF417 モードと同じ）での MicroPDF417 には 2 つのフィールドが必要です：Pdf417MacroFileID と Pdf417MacroSegmentID。その他のフィールドはオプションです。

Pdf417Parameters 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| encode_mode | Pdf417 エンコードモードを識別します。 <br/>            デフォルト値: Auto。 |
| error_level | BarCode のエラー訂正レベルの Pdf417 シンボロジータイプを取得または設定します。<br/>            level0 から level8 までの範囲で、level0 はエラー訂正情報がなく、level8 は最良のエラー訂正で、画像が大きくなります。 |
| truncate | BarCode の Pdf417 シンボロジータイプがトランケート（スペース削減）されているかどうか。 <br/>            CompactPDF417 とも呼ばれます。このモードでは右側の行インジケータと右側のストップパターンが削除されます。 |
| 列 | 列数。 |
| 行 | 行数。 |
| aspect_ratio | 2D バーコードモジュールの高さ/幅比率。 |
| macro_pdf_417_file_id | MacroPdf417 バーコードのファイル ID（必須フィールド）。<br/>            MicroPDF417 バーコードのファイル ID（Structured Append モードの必須フィールド） |
| macro_pdf_417_segment_id | MacroPdf417 バーコードのセグメント ID（必須フィールド）、0 から MacroSegmentsCount - 1 まで。<br/>            MicroPDF417 バーコードのセグメント ID（Structured Append モードの必須フィールド） |
| macro_pdf_417_segments_count | MacroPdf417 バーコードのセグメント数（オプションフィールド）。<br/>            MicroPDF417 バーコードのセグメント数（Structured Append モードのオプションフィールド） |
| macro_pdf_417_file_name | MacroPdf417 バーコードのファイル名（オプションフィールド）。<br/>            MicroPDF417 バーコードのファイル名（Structured Append モードのオプションフィールド） |
| macro_pdf_417_time_stamp | MacroPdf417 バーコードのタイムスタンプ（オプションフィールド）。<br/>            MicroPDF417 バーコードのタイムスタンプ（Structured Append モードのオプションフィールド） |
| macro_pdf_417_sender | MacroPdf417 バーコードの送信者名（オプションフィールド）。<br/>            MicroPDF417 バーコードの送信者名（Structured Append モードのオプションフィールド） |
| macro_pdf_417_addressee | MacroPdf417 バーコードの受取人名（オプションフィールド）。<br/>            MicroPDF417 バーコードの受取人名（Structured Append モードのオプションフィールド） |
| macro_pdf_417_file_size | MacroPdf417 ファイルサイズ（オプション フィールド）。<br/>            MicroPDF417 ファイルサイズ（構造化追加モード用のオプション フィールド）<br/>            ファイルサイズ フィールドは、ソース ファイル全体のバイト数を示します。 |
| macro_pdf_417_checksum | MacroPdf417 バーコードチェックサム（オプション フィールド）。<br/>            MicroPDF417 バーコードチェックサム（構造化追加モード用のオプション フィールド）<br/>            チェックサム フィールドは、CCITT-16 多項式（x^16 + x^12 + x^5 + 1）を使用した 16 ビット（2 バイト）CRC チェックサムの値を保持します。 |
| eci_encoding | 拡張チャネル解釈識別子。バーコードリーダーにシンボル内のデータエンコードに使用される参照の詳細を伝えるために使用されます。<br/>            Macro PDF417 テキスト フィールドには適用されません。<br/>            現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。 |
| macro_pdf_417eci_encoding | 拡張チャネル解釈識別子。Macro PDF417 テキスト フィールドに適用されます。 |
| macro_pdf_417_terminator | エンコーダにセグメントへ Macro PDF417 ターミネータ（コードワード 922）を追加するかどうかを指示するために使用します。<br/>            Macro PDF417 にのみ適用されます。 |
| is_reader_initialization | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。<br/>             |
| macro_characters | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを実現するために使用されます。<br/>            MicroPdf417 のみで使用でき、916 および 917 の MicroPdf417 モードをエンコードします。<br/>            デフォルト値: MacroCharacters.None。 |
| is_linked | GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。<br/>            GS1MicroPdf417 シンボルでは、906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。<br/>            MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連リニア コンポーネントへの 918 リンケージ フラグをエンコードします。 |
| is_code_128_emulation | MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。<br/>            2 番目の位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 をエンコードできます。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

