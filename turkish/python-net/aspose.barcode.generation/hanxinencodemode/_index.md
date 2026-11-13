---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Referansı"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code kodlama modu. ASCII / Çince karakterler için Auto veya Unicode karakterler için Unicode kullanılması önerilir.

## Members
| Üye adı | Açıklama |
| :- | :- |
| AUTO | Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. <br/>            Unicode karakterler, HanXin barkod spesifikasyonuna göre GB18030 kodlamasıyla kodlanır. |
| BINARY | Binary modda, CodeText en yüksek veri sıkıştırmasıyla kodlanır. <br/>            Bir Unicode karakter bulunursa, bir istisna fırlatılır. |
| ECI | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla bir ECI tanımlayıcısı eklenerek yeniden kodlanır.<br/>            Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır.<br/>            Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |
| UNICODE | Unicode modu, Han Xin Kodunda herhangi bir metin verisini UTF8 kodlaması/karakter kümesine referansla temsil etmenin bir yolunu tasarlar. |
| URI | URI modu, Han Xin Kodunda temsil edilen verinin Uniform Resource Identifier (URI) olduğunu gösterir<br/>            RFC 3986 referansı. |
| EXTENDED | Genişletilmiş mod, iç modların kombinasyonlarına izin verir: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Kod metni, önekler ve çift ters eğik çizgilerle manuel olarak oluşturulabilir, örn.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" veya HanXinExtCodetextBuilder kullanılarak.<br/>            Kod metni bir ECI parçası içeriyorsa, ECI parçasından sonra sadece aşağıdaki modlar bu kod metninde bulunabilir:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

