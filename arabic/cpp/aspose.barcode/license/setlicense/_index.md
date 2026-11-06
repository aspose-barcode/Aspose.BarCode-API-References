---
title: "طريقة"
linktitle: "SetLicense"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. ترخيص المكتبة في C++."
type: docs
weight: 200
url: /ar/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


يرخص المكتبة.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | System::String | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمن. |
## ملاحظات


يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن **Aspose**.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مضمّن في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمّن في تجميع استدعاء العميل.

في هذا المثال، سيتم محاولة العثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## انظر أيضًا

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


يرخص المكتبة.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | System::SharedPtr\<System::IO::Stream\> | دفق يحتوي على الترخيص. |
## ملاحظات



استخدم هذه الطريقة لتحميل الترخيص من دفق.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## انظر أيضًا

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
