---
title: "USADriveIdCodetext"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

ABD Sürücü Belgesi PDF417 koduna gömülü metni kodlamak ve çözmek için sınıf.

USADriveIdCodetext türü aşağıdaki üyeleri sunar:
## Constructors
| Ad | Açıklama |
| :- | :- |
| USADriveIdCodetext() | USADriveIdCodetext sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| issuer_identification_number | Bu sayı, <br/>            veren yargı bölgesini benzersiz şekilde tanımlar ve ISO<br/>            Yayım Yetkilisi(AAMVA) ile iletişime geçilerek elde edilebilir.  Tam 6 haneli IIN kodlanmalıdır. |
| aamva_version_number | AAMVA Sürüm Numarası 00-99 |
| jurisdiction_version_number | Yargı Bölgesi Sürüm Numarası 00-99 |
| number_of_entries | Alt dosyaların 00-99 numarası |
| subfile_designator | Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. <br/>            Önemli: sadece tip, ofset ve uzunluk otomatik olarak ayarlanacaktır. |
| mandatory_elements | Kartın zorunlu öğeleri (alanları) |
| optional_elements | Kartın isteğe bağlı öğeleri (alanları) |
| jurisdiction_specific_subfile | Yargı Bölgesi Özel Alanları |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_constructed_codetext() | USA DL verilerinden kod metnini oluştur |
| init_from_string(constructed_codetext) | Kod metninden USA DL nesnesini başlat |
| get_barcode_type() | USA DL'nin (Pdf417) barkod tipini döndürür |
| save_to_xml(stream) | XML'e kaydeder |

### Ayrıca Bakınız

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

