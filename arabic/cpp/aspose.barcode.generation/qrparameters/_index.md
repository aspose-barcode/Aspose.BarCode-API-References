---
title: "فئة Aspose::BarCode::Generation::QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::QrParameters. معلمات QR في C++."
type: docs
weight: 4400
url: /ar/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


معلمات QR.

```cpp
class QrParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [get_ECIEncoding](./get_eciencoding/)() const | معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | نوع ترميز QR للرمز [BarCode](../../aspose.barcode/). الوضع الافتراضي: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | مستوى تصحيح الأخطاء Reed‑Solomon للباركود QR وMicroQR وRectMicroQR. من منخفض إلى عالي: LevelL, LevelM, LevelQ, LevelH. راجع QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | معلمات الإلحاق المهيكل لـ QR. وضع الإلحاق المهيكل غير مدعوم من قبل باركودات MicroQR وRectMicroQR. |
| [get_Version](./get_version/)() const | إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | نوع ترميز QR للرمز [BarCode](../../aspose.barcode/). الوضع الافتراضي: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | مستوى تصحيح الأخطاء Reed‑Solomon للباركود QR وMicroQR وRectMicroQR. من منخفض إلى عالي: LevelL, LevelM, LevelQ, LevelH. راجع QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | معلمات الإلحاق المهيكل لـ QR. وضع الإلحاق المهيكل غير مدعوم من قبل باركودات MicroQR وRectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا [QrParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
