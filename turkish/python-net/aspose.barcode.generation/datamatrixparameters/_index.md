---
title: "DataMatrixParameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix parametreleri.

DataMatrixParameters türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| ecc_type | Datamatrix ECC tipini alır veya ayarlar.<br/>            Varsayılan değer: DataMatrixEccType.Ecc200. |
| version | Datamatrix sembol boyutunu alır veya ayarlar.<br/>            Varsayılan değer: Version.Auto. |
| encode_mode | Datamatrix barkodunun kodlama modu.<br/>            Varsayılan değer: EncodeMode.Auto. |
| structured_append_barcode_id | Datamatrix barkodunun Structured Append modu için Barkod ID'si.<br/>            Varsayılan değer: 0 |
| structured_append_barcodes_count | Datamatrix barkodunun Structured Append modu için barkod sayısı.<br/>            Varsayılan değer: 0 |
| structured_append_file_id | Datamatrix barkodunun Structured Append modu için Dosya ID'si.<br/>            Varsayılan değer: 0 |
| is_reader_programming | Sembolde bulunan veriyi okuyucu başlatması için programlama olarak yorumlaması talimatını vermek için kullanılır.<br/>            Varsayılan değer: false |
| macro_characters | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır.<br/>            Yalnızca DataMatrixEccType.Ecc200 veya DataMatrixEccType.EccAuto ile kullanılabilir.<br/>            EncodeTypes.GS1DataMatrix ile kullanılamaz<br/>            Varsayılan değer: MacroCharacters.None. |
| aspect_ratio | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| eci_encoding | ECI kodlamasını alır veya ayarlar. EncodeMode Auto olduğunda kullanılır.<br/>            Varsayılan değer: ISO-8859-1 |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

