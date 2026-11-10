---
title: "الفئة AztecExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder الفئة. مولد النص الموسع للباركودات Aztec لوضع ExtendedCodetext في AztecEncodeMode"
type: docs
weight: 950
url: /ar/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

مولد النص الموسع للباركودات Aztec لوضع ExtendedCodetext في AztecEncodeMode

استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص الظاهر لإزالة الأحرف الإدارية.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | يضيف نص الشيفرة مع معرف القناة الموسعة. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | يمسح عناصر النص الشيفري الموسعة. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | ينشئ نص شيفرة موسع من قائمة النص الشيفري الموسعة. |

## أمثلة

يعرض هذا المثال كيفية استخدام AztecExtCodetextBuilder في الوضع الموسع.

```csharp
[C#]
//إنشاء نص شيفرة.
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


