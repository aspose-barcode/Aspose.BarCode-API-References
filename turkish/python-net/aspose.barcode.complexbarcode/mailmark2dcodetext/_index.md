---
title: "Mailmark2DCodetext"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf.

Mailmark2DCodetext türü aşağıdaki üyeleri gösterir:
## Constructors
| Ad | Açıklama |
| :- | :- |
| Mailmark2DCodetext() | Mailmark2DCodetext sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| upu_country_id | UPU Country ID'yi belirler. Maksimum uzunluk: 4 karakter. |
| information_type_id | Royal Mail Mailmark barkod yükünü her ürün tipi için belirler. |
| version_id | Bilgi Tipi ID'sine göre ilgili barkod sürümünü belirler. |
| klass | Öğenin sınıfını belirler. |
| supply_chain_id | Posta gönderiminde yer alan benzersiz müşteri grubunu belirler.<br/>            Maksimum değer: 9999999. |
| item_id | Supply Chain ID içinde benzersiz öğeyi belirler.<br/>            Her Mailmark barkodunun bir ID taşıması gerekir<br/>            böylece en az 90 gün boyunca benzersiz olarak tanımlanabilir.<br/>            Maksimum değer: 99999999. |
| destination_post_code_and_dps | Teslimat adresinin posta kodunu DPS ile içerir<br/>            İç kara için Posta Kodu/DP aşağıdaki karakter sayısına sahiptir.<br/>            Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter)<br/>            Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter).<br/>            Posta kodu ve DPS geçerli bir PAF® formatına uymalıdır. |
| rts_flag | İstenen geri gönderim hizmetinin seviyesini gösteren bayrak. |
| return_to_sender_post_code | Geri gönderim posta kodunu içerir ancak DPS yoktur.<br/>            DPS'siz PC geçerli bir PAF® formatına uymalıdır. |
| customer_content | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| customer_content_encode_mode | Datamatrix barkodunun kodlama modu.<br/>            Varsayılan değer: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark Tipi, Data Matrix barkodunun boyutunu tanımlar. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_constructed_codetext() | Mailmark verilerinden kod metni oluştur. |
| init_from_string(constructed_codetext) | Oluşturulmuş kod metninden Mailmark verilerini başlatır. |
| get_barcode_type() | Barkod tipini alır. |

### Ayrıca Bakınız

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

