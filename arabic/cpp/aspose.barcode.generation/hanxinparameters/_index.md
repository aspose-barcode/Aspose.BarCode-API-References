---
title: "فئة Aspose::BarCode::Generation::HanXinParameters"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::HanXinParameters. معلمات Han Xin في C++."
type: docs
weight: 2900
url: /ar/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


معلمات Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. يحتوي التنفيذ الحالي على جميع ترميزات مجموعة الأحرف المعروفة. |
| [get_EncodeMode](./get_encodemode/)() const | وضع ترميز HanXin. القيمة الافتراضية: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | مستوى تصحيح الأخطاء Reed-Solomon لباركود Han Xin. من منخفض إلى عالي: L1، L2، L3، L4. انظر ErrorLevel. |
| [get_Version](./get_version/)() const | إصدار رمز HanXin. من Version01 إلى Version84 لرمز Han Xin. القيمة الافتراضية هي [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. يحتوي التنفيذ الحالي على جميع ترميزات مجموعة الأحرف المعروفة. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | وضع ترميز HanXin. القيمة الافتراضية: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | مستوى تصحيح الأخطاء Reed-Solomon لباركود Han Xin. من منخفض إلى عالي: L1، L2، L3، L4. انظر ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | إصدار رمز HanXin. من Version01 إلى Version84 لرمز Han Xin. القيمة الافتراضية هي [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا [HanXinParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
