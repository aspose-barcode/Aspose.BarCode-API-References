---
title: "Aspose::BarCode::LicenseCore क्लास"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::LicenseCore क्लास। क्लास C++ में लाइसेंस को पढ़ता और लागू करता है।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


लाइसेंस को पढ़ने और लागू करने वाली क्लास

```cpp
class LicenseCore : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | डेटा को हस्ताक्षर में एन्कोड करता है |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | असेंबली फ़ोल्डर में फ़ाइलनाम खोजने का प्रयास करता है |
| [LicenseCore](./licensecore/)() | नए [LicenseCore](./) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | विधि आंतरिक उपयोग और परीक्षण के लिए लाइसेंस स्थिति को रीसेट करती है |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | लाइसेंस खोजता है, लोड करता है और लागू करने का प्रयास करता है। कार्यान्वयन का परिणाम errorCode में सेट किया जाता है |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | लाइसेंस को लागू करने का प्रयास करता है। कार्यान्वयन का परिणाम errorCode में सेट किया जाता है |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## और देखें

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
