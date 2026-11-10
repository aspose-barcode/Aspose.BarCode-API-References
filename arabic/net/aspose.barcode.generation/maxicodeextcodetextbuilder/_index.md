---
title: "فئة MaxiCodeExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "فئة Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder. مولد النص الموسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /ar/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

مولد النص الموسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode

استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص الظاهر لإزالة الأحرف الإدارية.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | يضيف نص الشيفرة مع معرف القناة الموسعة. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | يمسح عناصر النص الشيفري الموسعة. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | ينشئ نص شيفرة موسع من قائمة النص الشيفري الموسعة. |

## أمثلة

يعرض هذا المثال كيفية استخدام MaxiCodeExtCodetextBuilder في الوضع الموسع.

```csharp
[C#]
//إنشاء نص شيفرة.
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


