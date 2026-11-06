---
title: "Aspose::BarCode::LicenseCore فئة"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::LicenseCore فئة. فئة تقوم بقراءة وتطبيق الترخيص في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


فئة تقرأ وتنفذ الترخيص

```cpp
class LicenseCore : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | يقوم بترميز البيانات إلى توقيع |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | يحاول العثور على اسم الملف في مجلد التجميع |
| [LicenseCore](./licensecore/)() | يُنشئ مثلاً جديداً للفئة [LicenseCore](./) فئة. |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | تُعيد الطريقة ضبط حالة الترخيص للاستخدام الداخلي والاختبارات |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | يبحث عن الترخيص، يحمل ويحاول تطبيقه. يتم تعيين نتيجة التطبيق إلى errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | يحاول تطبيق الترخيص. يتم تعيين نتيجة التطبيق إلى errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## انظر أيضًا

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
