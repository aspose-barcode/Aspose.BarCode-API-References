---
title: DecodeType
second_title: Aspose.BarCode لمرجع .NET API
description: حدد نوع الباركود المراد قراءته.
type: docs
weight: 190
url: /ar/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

حدد نوع الباركود المراد قراءته.

```csharp
public static class DecodeType
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | يحصل على مصفوفة تمثل AllSupportedTypes |

## طُرق

| اسم | وصف |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | استرداد مصفوفة من أسماء أنواع فك التشفير. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | تحديد ما إذا كان محددًا[`BaseDecodeType`](../basedecodetype) يحتوي على أي رموز باركود 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | تحديد ما إذا كان محددًا[`BaseDecodeType`](../basedecodetype) يحتوي على أي رمز شريطي ثنائي الأبعاد |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | تحديد ما إذا كان محددًا[`BaseDecodeType`](../basedecodetype) يحتوي على أي رمز شريطي بريدي |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | تحويل تمثيل السلسلة من SingleDecodeType إلى مثيلها . تشير القيمة المرجعة إلى ما إذا كان التحويل قد نجح أو فشل. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | تحديد مجموعات المسح بواسطة الباركود الأنواع |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | تحويل تمثيل سلسلة MultyDecodeType إلى مثيله . تشير القيمة المرجعة إلى ما إذا كان التحويل قد نجح أو فشل. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | تحويل تمثيل السلسلة من SingleDecodeType إلى مثيلها . تشير القيمة المرجعة إلى ما إذا كان التحويل قد نجح أو فشل. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | يحدد أن البيانات سيتم فحصها باستخدام جميع الرموز المتاحة |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | تحديد أنه يجب فك تشفير البيانات باستخدام **البريد الأسترالي المحلي eParcel الباركود** مواصفات الباركود |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | تحديد أنه يجب فك تشفير البيانات باستخدام **أستراليا بوست** مواصفات الباركود |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | تحديد أنه يجب فك تشفير البيانات باستخدام **ازتيك** مواصفات الباركود |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | تحديد أنه يجب فك تشفير البيانات باستخدام **كودابار** مواصفات الباركود |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | تحديد أنه يجب فك تشفير البيانات باستخدام **كودابلوك** مواصفات الباركود |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | تحديد أنه يجب فك تشفير البيانات باستخدام **الكود 11** مواصفات الباركود |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | تحديد أنه يجب فك تشفير البيانات باستخدام **الكود 128** مواصفات الباركود |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | تحديد أنه يجب فك تشفير البيانات باستخدام **سكود** مواصفات الباركود |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | تحديد أنه يجب فك تشفير البيانات باستخدام **كود 32** مواصفات فارغة |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | تحديد أنه يجب فك تشفير البيانات باستخدام **تمديد الكود 39** مواصفات الباركود |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | تحديد أنه يجب فك تشفير البيانات باستخدام **الكود القياسي 39** مواصفات الباركود |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | تحديد أنه يجب فك تشفير البيانات باستخدام **تمديد الكود 93** مواصفات الباركود |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | تحديد أنه يجب فك تشفير البيانات باستخدام **الكود القياسي 93** مواصفات الباركود |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | تحديد أنه يجب فك تشفير البيانات باستخدام **CompactPdf417** مواصفات الباركود (PDF417Truncated) |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | تحديد أنه يجب فك تشفير البيانات باستخدام **تم توسيع GS1 Databar** مواصفات الباركود |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | تحديد أنه يجب فك تشفير البيانات باستخدام **موسعة GS1 Databar مكدسة** مواصفات الباركود |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 Databar المحدودة** مواصفات الباركود |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 Databar متعدد الاتجاهات** مواصفات الباركود |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 Databar مكدسة** مواصفات الباركود |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 Databar مكدس متعدد الاتجاهات** مواصفات الباركود |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 Databar مقطوع** مواصفات الباركود |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | تحديد أنه يجب فك تشفير البيانات باستخدام **DataLogic 2 من 5** مواصفات فارغة |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | تحديد أنه يجب فك تشفير البيانات باستخدام **مصفوفة البيانات** ترميز الباركود |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | تحديد أنه يجب فك تشفير البيانات باستخدام **كود التعريف DeutschePost** مواصفات الباركود |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | تحديد أنه يجب فك تشفير البيانات باستخدام **كود DeutschePost Leit** مواصفات الباركود |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | تحديد أنه يجب فك تشفير البيانات باستخدام **DotCode** مواصفات فارغة |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | تحديد أنه يجب فك تشفير البيانات باستخدام **DotCode** مواصفات فارغة |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | تحديد أنه يجب فك تشفير البيانات باستخدام **EAN-13** مواصفات الباركود |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | تحديد أنه يجب فك تشفير البيانات باستخدام **EAN14** مواصفات الباركود |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | تحديد أنه يجب فك تشفير البيانات باستخدام **EAN-8** مواصفات الباركود |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 كود 128** مواصفات الباركود |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1DataMatrix** ترميز الباركود |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | تحديد أنه يجب فك تشفير البيانات باستخدام **GS1 ر** مواصفات الباركود |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | تحديد أنه يجب فك تشفير البيانات باستخدام **إياتا 2 من 5** مواصفات الباركود. يستخدم الاتحاد الدولي للنقل الجوي (IATA) هذا الرمز الشريطي لإدارة الشحن الجوي. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | تحديد أنه يجب فك تشفير البيانات باستخدام **INTERLEAVED 2 من 5** مواصفات الباركود |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | تحديد أنه يجب فك تشفير البيانات باستخدام **رقم ISBN** مواصفات الباركود |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | تحديد أنه يجب فك تشفير البيانات باستخدام **ISMN** مواصفات الباركود |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | تحديد أنه يجب فك تشفير البيانات باستخدام **ISSN** مواصفات الباركود |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | تحديد أنه يجب فك تشفير البيانات باستخدام **البريد الإيطالي 25** مواصفات الباركود |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | تحديد أنه يجب فك تشفير البيانات باستخدام **ITF14** مواصفات الباركود |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | تحديد أنه يجب فك تشفير البيانات باستخدام **ITF6** مواصفات الباركود |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | تحديد أنه يجب فك تشفير البيانات باستخدام **MacroPdf417** مواصفات الباركود |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | تحديد أنه يجب فك تشفير البيانات باستخدام **Royal Mail Mailmark** مواصفات الباركود. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | تحديد أنه يجب فك تشفير البيانات باستخدام **مصفوفة 2 من 5** مواصفات الباركود |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | تحديد أنه يجب فك تشفير البيانات باستخدام **MaxiCode** مواصفات الباركود |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | تحديد أنه يجب فك تشفير البيانات باستخدام **MICR E-13B** مواصفات فارغة |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | تحديد أنه يجب فك تشفير البيانات باستخدام **ميكرو بي دي اف 417** مواصفات الباركود |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | تحديد أنه يجب فك تشفير البيانات باستخدام **كود MicroQR** مواصفات الباركود |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | يحدد أن البيانات سيتم فحصها باستخدام الرموز الأكثر استخدامًا |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | تحديد أنه يجب فك تشفير البيانات باستخدام **إم إس آي بليسي** مواصفات الباركود |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | نوع فك الشفرة غير محدد. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | يحدد أنه يجب فك تشفير البيانات باستخدام USPS **ون كود** مواصفات الباركود |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | تحديد أنه يجب فك تشفير البيانات باستخدام **OPC** مواصفات الباركود |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | تحديد أنه يجب فك تشفير البيانات باستخدام **كود التصحيح** مواصفات الباركود. يتم استخدام رموز الباركود للمسح الآلي |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | تحديد أنه يجب فك تشفير البيانات باستخدام **Pdf417** ترميز الباركود |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | تحديد أنه يجب فك تشفير البيانات باستخدام **فارماكود** الرمز الشريطي. يُعرف هذا الترميز أيضًا باسم الرمز الثنائي الصيدلاني |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | تحديد أنه يجب فك تشفير البيانات باستخدام **كوكب** مواصفات الباركود |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | تحديد تلك البيانات التي سيتم فحصها مع جميع **1.5 د البريدي** رموز الباركود ، مثل **Planet ، Postnet ، AustraliaPost ، OneCode ، RM4SCC ، DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | تحديد أنه يجب فك تشفير البيانات باستخدام **Postnet** مواصفات الباركود |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | تحديد أنه يجب فك تشفير البيانات باستخدام **PZN**مواصفات الباركود. يُعرف هذا الترميز أيضًا باسم Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | تحديد أنه يجب فك تشفير البيانات باستخدام **رمز الاستجابة السريعة** مواصفات الباركود |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | تحديد أنه يجب فك تشفير البيانات باستخدام **RM4SCC** مواصفات الباركود. يستخدم RM4SCC (رمز عميل Royal Mail 4-state) لعملية فرز البريد الآلي في المملكة المتحدة. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | تحديد أنه يجب فك تشفير البيانات باستخدام **SCC14** مواصفات الباركود |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | تحديد أنه يجب فك تشفير البيانات باستخدام **SSCC18** مواصفات الباركود |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | تحديد أنه يجب فك تشفير البيانات باستخدام **المعيار 2 من 5** مواصفات الباركود |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | تحديد أنه يجب فك تشفير البيانات باستخدام **الملحق (EAN2 ، EAN5)** مواصفات الباركود |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | تحديد أنه يجب فك تشفير البيانات باستخدام **الرمز الشريطي للبريد السويسري** مواصفات الباركود |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | تحديد تلك البيانات التي سيتم فحصها مع جميع **1 د** رموز الباركود |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | تحديد تلك البيانات التي سيتم فحصها مع جميع **2 د** رموز الباركود |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | تحديد أنه يجب فك تشفير البيانات باستخدام **اتحاد الوطنيين الكونغوليين- A** مواصفات الباركود |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | تحديد أنه يجب فك تشفير البيانات باستخدام **UPC-E** مواصفات الباركود |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | تحديد أنه يجب فك تشفير البيانات باستخدام **فين** (رقم تعريف السيارة) مواصفات الباركود |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
