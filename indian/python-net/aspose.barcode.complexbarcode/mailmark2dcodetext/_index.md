---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

Mailmark2DCodetext प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| Mailmark2DCodetext() | Mailmark2DCodetext वर्ग की नई इंस्टेंस को प्रारंभ करता है |
## गुण
| नाम | विवरण |
| :- | :- |
| upu_country_id | UPU देश ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| information_type_id | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| version_id | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। |
| klass | आइटम की वर्ग की पहचान करता है। |
| supply_chain_id | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है।<br/>            अधिकतम मान: 9999999. |
| item_id | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है।<br/>            प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है<br/>            ताकि इसे कम से कम 90 दिनों तक अद्वितीय रूप से पहचाना जा सके।<br/>            अधिकतम मान: 99999999. |
| destination_post_code_and_dps | डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है<br/>            यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं।<br/>            एरिया (1 या 2 अक्षर) जिला (1 या 2 अक्षर)<br/>            सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर).<br/>            पोस्टकोड और DPS को वैध PAF® प्रारूप के अनुरूप होना चाहिए। |
| rts_flag | फ़्लैग जो दर्शाता है कि कौन स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| return_to_sender_post_code | Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं।<br/>            PC (बिना DPS) को PAF® प्रारूप के अनुरूप होना चाहिए। |
| customer_content | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| customer_content_encode_mode | Datamatrix बारकोड का एन्कोड मोड।<br/>            डिफ़ॉल्ट मान: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark प्रकार Data Matrix बारकोड का आकार परिभाषित करता है। |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| get_constructed_codetext() | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| init_from_string(constructed_codetext) | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |
| get_barcode_type() | बारकोड प्रकार प्राप्त करता है। |

### संबंधित देखें

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

