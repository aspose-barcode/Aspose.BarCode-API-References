---
title: "विधि"
linktitle: "TryParse"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। अनकम्प्रेस्ड GS1 डिजिटल लिंक URI को पार्स करने का प्रयास करता है और C++ में संरचित वैधता त्रुटियां लौटाता है।"
type: docs
weight: 2000
url: /hi/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


एक असंपीड़ित GS1 डिजिटल लिंक URI को पार्स करने का प्रयास करता है और संरचित मान्यकरण त्रुटियों को लौटाता है।

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::String | पार्स करने के लिए GS1 डिजिटल लिंक URI। |
| result | System::SharedPtr\<GS1DigitalLink\>\& | जब यह मेथड true लौटाता है, तो इसमें पार्स किया गया GS1 डिजिटल लिंक होता है; अन्यथा null। |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | वैधता परिणाम को शामिल करता है, या जब *value* null हो तो null। |

### ReturnValue

पार्सिंग सफल होने पर true; अन्यथा false।

## और देखें

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
