---
title: "الفئة DotCodeExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. مولد نص رمزي موسع لباركودات DotCode ثنائية الأبعاد لوضعية ExtendedCodetext في DotCodeEncodeMode"
type: docs
weight: 1250
url: /ar/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

مولد نص رمزي موسع لباركودات DotCode ثنائية الأبعاد لوضعية ExtendedCodetext في DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | يضيف نص الشيفرة مع معرف القناة الموسعة. |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | يضيف معرف تنسيق FNC1 إلى عناصر النص الرمزي الموسع |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | يضيف تهيئة القارئ FNC3 إلى عناصر النص الرمزي الموسع |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | يضيف فاصل الرمز FNC3 إلى عناصر نص الرمز الموسعة |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة. |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | يضيف وضع الإلحاق المنظم إلى عناصر نص الرمز الموسعة |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | يمسح عناصر النص الشيفري الموسعة. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | ينشئ نص شيفرة موسع من قائمة النص الشيفري الموسعة. |

## أمثلة

```csharp
[C#]
//وضع النص الشيفري الموسع.
//إنشاء نص شيفرة.
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


