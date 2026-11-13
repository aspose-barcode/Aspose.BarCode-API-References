---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Referansı"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

DataMatrix kodlayıcısının kodlama modu, varsayılan olarak Otomatik

## Members
| Üye adı | Açıklama |
| :- | :- |
| AUTO | Auto modda, CodeText en yüksek veri sıkıştırmasıyla kodlanır. <br/>            Unicode karakterler, belirtilen ECIEncoding kodlamasıyla bir ECI tanımlayıcısı eklenerek yeniden kodlanır.<br/>            Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| ASCII | Her bayt için bir alfanümerik veya iki sayısal karakter kodlar. |
| C40 | C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar. |
| TEXT | Text kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar. |
| EDIFACT | EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez. |
| ANSIX12 | ANSI X12 kodlamasını kullanır. |
| EXTENDED |  |
| BASE256 | 8 bit değerleri kodlar. |
| BINARY | Binary modda, CodeText en yüksek veri sıkıştırmasıyla kodlanır. <br/>            Bir Unicode karakter bulunursa, bir istisna fırlatılır. |
| ECI | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla bir ECI tanımlayıcısı eklenerek yeniden kodlanır.<br/>            Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır.<br/>            Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

