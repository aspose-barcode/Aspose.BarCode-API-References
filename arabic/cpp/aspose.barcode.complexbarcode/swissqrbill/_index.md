---
title: "فئة Aspose::BarCode::ComplexBarcode::SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::SwissQRBill. بيانات SwissQR bill في C++."
type: docs
weight: 2700
url: /ar/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


بيانات الفاتورة SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | ينشئ ويضبط مرجع الدائن ISO11649 من سلسلة خام عن طريق إضافة البادئة "RF" إلى الـString وحساب المجموع الاختباري modulo 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | يحدد ما إذا كانت الفاتورة المحددة مساوية للفاتورة الحالية. |
| [get_Account](./get_account/)() const | يحصل على رقم حساب الدائن. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | يحصل أو يضبط أنظمة الدفع البديلة. |
| [get_Amount](./get_amount/)() const | يحصل على مبلغ الدفع. |
| [get_BillInformation](./get_billinformation/)() const | يحصل على معلومات الفاتورة المهيكلة الإضافية. |
| [get_Creditor](./get_creditor/)() const | يحصل على عنوان الدائن. |
| [get_Currency](./get_currency/)() const | يحصل على عملة الدفع. |
| [get_Debtor](./get_debtor/)() const | يحصل على عنوان المدين. |
| [get_Reference](./get_reference/)() const | يحصل على مرجع دفع الدائن. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | يحصل على الرسالة غير المهيكلة الإضافية. |
| [get_Version](./get_version/)() const | يحصل على نسخة معيار فاتورة SwissQR. |
| [GetHashCode](./gethashcode/)() const override | يحصل على قيمة التجزئة لهذا المثيل. |
| [set_Account](./set_account/)(System::String) | يضبط رقم حساب الدائن. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | يحصل أو يضبط أنظمة الدفع البديلة. |
| [set_Amount](./set_amount/)(System::Decimal) | يضبط مبلغ الدفع. |
| [set_BillInformation](./set_billinformation/)(System::String) | يضبط معلومات الفاتورة المهيكلة الإضافية. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | يضبط عنوان الدائن. |
| [set_Currency](./set_currency/)(System::String) | يضبط عملة الدفع. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | يضبط عنوان المدين. |
| [set_Reference](./set_reference/)(System::String) | يضبط مرجع دفع الدائن. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | يضبط الرسالة غير المهيكلة الإضافية. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | يضبط إصدار معيار الفاتورة SwissQR. |
## Typedefs

| تعريف نوع | الوصف |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | إصدار معيار الفاتورة SwissQR |
## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
