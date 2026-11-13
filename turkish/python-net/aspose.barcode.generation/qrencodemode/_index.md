---
title: "QREncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Referansı"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

QR barkodları için kodlama modu.

## Members
| Üye adı | Açıklama |
| :- | :- |
| AUTO | Otomatik modda, CodeText en yüksek veri sıkıştırmasıyla kodlanır. <br/>            Unicode karakterleri mümkünse kanji modunda kodlanır, aksi takdirde ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır.<br/>            Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| EXTENDED |  |
| BINARY | Binary modda, CodeText en yüksek veri sıkıştırmasıyla kodlanır. <br/>            Bir Unicode karakter bulunursa, bir istisna fırlatılır. |
| ECI | ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır.<br/>            Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır.<br/>            Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın.<br/>            Bu mod MicroQR barkodları tarafından desteklenmez. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

