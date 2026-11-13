---
title: "MailmarkCodetext"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

4 durumlu Royal Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf.

MailmarkCodetext türü aşağıdaki üyeleri gösterir:
## Constructors
| Ad | Açıklama |
| :- | :- |
| MailmarkCodetext() | MailmarkCodetext sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| format | "0" – Null veya Test<br/>            "1" – Mektup<br/>            "2" – Büyük Mektup |
| version_id | Şu anda "1" – Mailmark barkodu için (0 ve 2'den 9'a ve A'dan Z'ye kadar gelecek kullanım için ayrılmıştır) |
| klass | "0" - Null veya Test<br/>            "1" - 1C (Perakende)<br/>            "2" - 2C (Perakende)<br/>            "3" - 3C (Perakende)<br/>            "4" - Premium (RetailPublishing Mail) (potansiyel gelecek kullanım için)<br/>            "5" - Deferred (Perakende)<br/>            "6" - Air (Perakende) (potansiyel gelecek kullanım için)<br/>            "7" - Surface (Perakende) (potansiyel gelecek kullanım için)<br/>            "8" - Premium (Network Access)<br/>            "9" - Standard (Network Access) |
| supply_chain_id | Maksimum değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| item_id | Maksimum değer 99999999'dur. |
| destination_post_code_and_dps | PC ve DP, PAF formatına uymalıdır.<br/>            Uluslararası "XY11     " (5 boşluk olduğunu unutmayın) gösteren dokuz karakterlik dize veya bir desen<br/>            yerel sıralama kodunu gösteren karakterler.<br/>            Yerel bir sıralama kodu, dış posta kodu, iç posta kodu ve Teslimat Noktası Soneki'nden oluşur. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_constructed_codetext() | Mailmark verilerinden kod metni oluştur. |
| init_from_string(constructed_codetext) | Oluşturulmuş kod metninden Mailmark verilerini başlatır. |
| get_barcode_type() | Barkod tipini alır. |

### Ayrıca Bakınız

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

