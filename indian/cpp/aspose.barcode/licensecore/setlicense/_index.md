---
title: "विधि"
linktitle: "SetLicense"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। लाइसेंस खोजता है, लोड करता है और लागू करने का प्रयास करता है। कार्यान्वयन का परिणाम C++ में errorCode में सेट किया जाता है।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


लाइसेंस खोजता है, लोड करता है और लागू करने का प्रयास करता है। कार्यान्वयन का परिणाम errorCode में सेट किया जाता है

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseName | System::String | यह पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | सर्च पाथ खोजने के लिए कॉलिंग असेंबली |
| errorCode | System::SharedPtr\\<Common::Generic::Types::Tup\\<LicenseErrors, System::DateTime, System::DateTime\\>> | त्रुटि कोड जो लाइसेंसिंग स्थिति और संभावित त्रुटि संदेश के लिए अतिरिक्त जानकारी संग्रहीत करता है। |

## और देखें

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


लाइसेंस को लागू करने का प्रयास करता है। कार्यान्वयन का परिणाम errorCode में सेट किया जाता है

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | संग्रहीत लाइसेंस वाला स्ट्रीम |
| errorCode | System::SharedPtr\\<Common::Generic::Types::Tup\\<LicenseErrors, System::DateTime, System::DateTime\\>> | त्रुटि कोड जो लाइसेंसिंग स्थिति और संभावित त्रुटि संदेश के लिए अतिरिक्त जानकारी संग्रहीत करता है। |

## और देखें

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
