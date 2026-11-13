---
title: "CodetextParameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

معلمات Codetext.

يعرض نوع CodetextParameters الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| two_d_display_text | النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد.<br/>            يُستخدم لـ: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension.<br/>            يُنصح باستخدام FontMode.Auto خاصةً في AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.<br/>            القيمة الافتراضية: FontMode.Auto. |
| font | حدد خط CodeText المعروض.<br/>            القيمة الافتراضية: Arial 5pt عادي.<br/>            يتم تجاهله إذا تم تعيين FontMode إلى FontMode.Auto. |
| space | المسافة بين CodeText والباركود بوحدة [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            القيمة الافتراضية: 2pt.<br/>            يتم تجاهلها لـ EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon. |
| المحاذاة | يحصل أو يضبط محاذاة نص الشيفرة.<br/>            القيمة الافتراضية: StringAlignment.Center. |
| اللون | حدد لون عرض نص الشيفرة.<br/>            القيمة الافتراضية: Color.Black. |
| الموقع | حدد موقع عرض نص الشيفرة، اضبطه إلى CodeLocation.None لإخفاء نص الشيفرة.<br/>            القيمة الافتراضية: CodeLocation.Below للباركودات أحادية الأبعاد و CodeLocation.None للباركودات ثنائية الأبعاد. |
| no_wrap | حدد التفاف الكلمات (فواصل الأسطر) داخل النص.<br/>            القيمة الافتراضية: false. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

