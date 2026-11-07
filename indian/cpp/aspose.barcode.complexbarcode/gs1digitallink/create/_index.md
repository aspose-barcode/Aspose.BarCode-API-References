---
title: "विधि"
linktitle: "बनाएँ"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में GS1 codetext से सभी एलिमेंट्स को कॉपी करके और उपलब्ध एकमात्र प्राइमरी की को चुनकर GS1 Digital Link बनाता है।"
type: docs
weight: 2100
url: /hi/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


GS1 codetext से सभी तत्वों को कॉपी करके और केवल उपलब्ध प्राथमिक कुंजी का चयन करके एक GS1 Digital Link बनाता है।

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uriStem | System::String | प्राइमरी की से पहले का एब्सोल्यूट HTTP या HTTPS URI प्रीफ़िक्स। |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext जिसके एलिमेंट्स कॉपी किए जाते हैं। |

### ReturnValue

कॉपी किए गए तत्वों को शामिल करने वाला एक GS1 डिजिटल लिंक।

## और देखें

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


GS1 codetext से सभी तत्वों को कॉपी करके और निर्दिष्ट प्राथमिक कुंजी का उपयोग करके एक GS1 Digital Link बनाता है।

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uriStem | System::String | प्राइमरी की से पहले का एब्सोल्यूट HTTP या HTTPS URI प्रीफ़िक्स। |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext जिसके एलिमेंट्स कॉपी किए जाते हैं। |
| primaryApplicationIdentifier | System::String | प्राथमिक कुंजी AI। |

### ReturnValue

कॉपी किए गए तत्वों को शामिल करने वाला एक GS1 डिजिटल लिंक।

## और देखें

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
