---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

4‑स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

MailmarkCodetext प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| MailmarkCodetext() | MailmarkCodetext क्लास की नई इंस्टेंस को प्रारंभ करता है |
## गुण
| नाम | विवरण |
| :- | :- |
| format | "0" – शून्य या परीक्षण<br/>            "1" – अक्षर<br/>            "2" – बड़ा अक्षर |
| version_id | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित) |
| klass | "0" - शून्य या परीक्षण<br/>            "1" - 1C (रिटेल)<br/>            "2" - 2C (रिटेल)<br/>            "3" - 3C (रिटेल)<br/>            "4" - प्रीमियम (RetailPublishing Mail) (भविष्य उपयोग के लिए संभावित)<br/>            "5" - स्थगित (रिटेल)<br/>            "6" - एयर (रिटेल) (भविष्य उपयोग के लिए संभावित)<br/>            "7" - सतह (रिटेल) (भविष्य उपयोग के लिए संभावित)<br/>            "8" - प्रीमियम (नेटवर्क एक्सेस)<br/>            "9" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| supply_chain_id | अधिकतम मान 99 बारकोड C के लिए और 999999 बारकोड L के लिए हैं। |
| item_id | अधिकतम मान 99999999 है। |
| destination_post_code_and_dps | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए.<br/>            नौ अक्षरों की स्ट्रिंग जो अंतर्राष्ट्रीय "XY11     " को दर्शाती है (ध्यान दें कि 5 trailing spaces हैं) या एक पैटर्न<br/>            अक्षरों का जो घरेलू सॉर्टिंग कोड को दर्शाता है.<br/>            एक घरेलू सॉर्टिंग कोड में एक outward पोस्टकोड, एक inward पोस्टकोड, और एक डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं. |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| get_constructed_codetext() | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| init_from_string(constructed_codetext) | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |
| get_barcode_type() | बारकोड प्रकार प्राप्त करता है। |

### संबंधित देखें

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

