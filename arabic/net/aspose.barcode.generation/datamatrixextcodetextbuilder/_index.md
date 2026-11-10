---
title: "الفئة DataMatrixExtCodetextBuilder."
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder. مولد نص شيفرة موسع لباركودات DataMatrix ثنائية الأبعاد لوضع ExtendedCodetext في EncodeMode."
type: docs
weight: 1210
url: /ar/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

مولد نص شيفرة موسع لباركودات DataMatrix ثنائية الأبعاد لوضع ExtendedCodetext في EncodeMode.

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | يضيف نص شيفرة مع وضع الترميز المحدد إلى عناصر النص الشيفري الموسعة. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | يضيف نص الشيفرة مع معرف القناة الموسعة. |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | يضيف نص شيفرة مع معرف القناة الموسعة مع وضع الترميز المحدد. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | يمسح عناصر النص الشيفري الموسعة. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | ينشئ نص شيفرة موسع من قائمة النص الشيفري الموسعة. |

## أمثلة

```csharp
[C#]
//وضع النص الشيفري الموسع.

//إنشاء نص شيفرة.
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


