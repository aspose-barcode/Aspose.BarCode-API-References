---
title: "طريقة"
linktitle: "SetLicense"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. تبحث عن الترخيص، تقوم بتحميله وتحاول تنفيذه. يتم تعيين نتيجة التنفيذ إلى errorCode في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


يبحث عن الترخيص، يحمل ويحاول تطبيقه. يتم تعيين نتيجة التطبيق إلى errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | System::String | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمن. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | التجميع المستدعي للعثور على مسار البحث |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | رمز الخطأ الذي يخزن حالة الترخيص ومعلومات إضافية لرسالة الخطأ المحتملة |

## انظر أيضًا

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


يحاول تطبيق الترخيص. يتم تعيين نتيجة التطبيق إلى errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | دفق يحتوي على الترخيص المخزن |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | رمز الخطأ الذي يخزن حالة الترخيص ومعلومات إضافية لرسالة الخطأ المحتملة |

## انظر أيضًا

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
