---
title: "فئة Aspose::BarCode::License"
linktitle: "رخصة"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::License. توفر طرقًا لترخيص المكوّن في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode/license/
---
## License class


يوفر طرقًا لترخيص المكوّن.

```cpp
class License : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [License](./license/)() | يُهيئ نسخة جديدة من هذه الفئة. |
| [SetLicense](./setlicense/)(System::String) | يرخص المكتبة. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | يرخص المكتبة. |
## ملاحظات


في هذا المثال، سيتم محاولة العثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## انظر أيضًا

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
