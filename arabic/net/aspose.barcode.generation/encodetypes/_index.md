---
title: EncodeTypes
second_title: Aspose.BarCode لمرجع .NET API
description: يحدد نوع الرمز الشريطي المراد ترميزه.
type: docs
weight: 720
url: /ar/net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

يحدد نوع الرمز الشريطي المراد ترميزه.

```csharp
public static class EncodeTypes
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes) { get; } | يحدد أن البيانات سيتم فحصها مع جميع الرموز المتاحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames)() | استرداد مصفوفة من أسماء أنواع الترميز. |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse)(string, out BaseEncodeType) | تحويل تمثيل سلسلة BaseEncodeType إلى مثيله . تشير القيمة المرجعة إلى ما إذا كان التحويل قد نجح أو فشل. |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse)(string, out BaseEncodeType) | تحويل تمثيل سلسلة BaseEncodeType إلى مثيله . تشير القيمة المرجعة إلى ما إذا كان التحويل قد نجح أو فشل. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel) | تحديد أنه يجب تشفير البيانات باستخدام **البريد الأسترالي المحلي eParcel الباركود** مواصفات الباركود |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost) | يمثل Australia Post Customer BarCode |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec) | تحديد أنه يجب تشفير البيانات باستخدام **ازتيك** مواصفات الباركود |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar) | تحديد أنه يجب تشفير البيانات باستخدام **كودابار** مواصفات الباركود |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf) | تحديد أنه يجب تشفير البيانات باستخدام **كودابلوك- F** مواصفات الباركود. |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11) | تحديد أنه يجب تشفير البيانات باستخدام **الكود 11** مواصفات الباركود |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128) | تحديد أنه يجب تشفير البيانات باستخدام **الكود 128** مواصفات الباركود |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k) | يمثل كود 16K باركود . |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32) | تحديد أنه يجب تشفير البيانات باستخدام **كود 32** مواصفات الباركود |
| static readonly [Code39Extended](../../aspose.barcode.generation/encodetypes/code39extended) | تحديد أنه يجب تشفير البيانات باستخدام **تمديد الكود 39** مواصفات الباركود |
| static readonly [Code39Standard](../../aspose.barcode.generation/encodetypes/code39standard) | تحديد أنه يجب تشفير البيانات باستخدام **الكود القياسي 39** مواصفات الباركود |
| static readonly [Code93Extended](../../aspose.barcode.generation/encodetypes/code93extended) | تحديد أنه يجب تشفير البيانات باستخدام **تمديد الكود 93** مواصفات الباركود |
| static readonly [Code93Standard](../../aspose.barcode.generation/encodetypes/code93standard) | تحديد أنه يجب تشفير البيانات باستخدام **الكود القياسي 93** مواصفات الباركود |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded) | يمثل الرمز الشريطي الموسع GS1 Databar. |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked) | يمثل GS1 Databar الرمز الشريطي المكدس الموسع. |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited) | يمثل رمز الباركود المحدود GS1 Databar. |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional) | تحديد أنه يجب تشفير البيانات باستخدام **GS1 Databar متعدد الاتجاهات** مواصفات الباركود. |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked) | يمثل الرمز الشريطي المكدس GS1 Databar. |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional) | يمثل GS1 Databar باركود متعدد الاتجاهات مكدس. |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated) | تحديد أنه يجب تشفير البيانات باستخدام **GS1 Databar مقطوع** مواصفات الباركود. |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5) | تحديد أنه يجب تشفير البيانات باستخدام **DataLogic 2 من 5** مواصفات الباركود |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix) | 2D رموز الباركود DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode) | يمثل الرمز الشريطي للبريد الألماني ، يُعرف هذا الرمز أيضًا باسم رمز التعريف ، رمز التعريف ، الرمز البريدي الألماني 2 من 5 رمز التعريف ، رمز التعريف الألماني للبريد ، رمز التعريف الألماني Frachtpost ، Deutsch Post AG (DHL) |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode) | يمثل الرمز الشريطي لـ Deutsch Post Leitcode ، المعروف أيضًا باسم البريد الألماني 2 من 5 Leitcode ، CodeLeitcode ، Leitcode ، Deutsch Post AG (DHL) . |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode) | تحديد أنه يجب تشفير البيانات باستخدام **DotCode** مواصفات الباركود |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix) | تحديد أنه يجب تشفير البيانات باستخدام **هولندي كيكس** مواصفات الباركود |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13) | تحديد أنه يجب تشفير البيانات باستخدام **EAN-13** مواصفات الباركود |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14) | تحديد أنه يجب تشفير البيانات باستخدام **EAN14** مواصفات الباركود |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8) | تحديد أنه يجب تشفير البيانات باستخدام **EAN-8** مواصفات الباركود |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf) | تحديد أنه يجب تشفير البيانات باستخدام **GS1 كودابلوك- F** مواصفات الباركود. يجب أن يحتوي نص الترميز على أقواس لـ AI. |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128) | تحديد أنه يجب تشفير البيانات باستخدام **GS1 كود 128** مواصفات الباركود. يجب أن يحتوي نص الترميز على أقواس لـ AI. |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar) | تحديد أنه يجب تشفير البيانات باستخدام **شريط مركب GS1** مواصفات الباركود. يجب أن يحتوي نص الشفرة على أقواس للذكاء الاصطناعي. يجب فصل نص الترميز أحادي الأبعاد ونص الترميز ثنائي الأبعاد بالرمز '/' |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix) | مصفوفة ترميز الباركود ثنائية الأبعاد بتنسيق سلسلة GS1 |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr) | رمز الباركود ثنائي الأبعاد QR بتنسيق سلسلة GS1 |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5) | يمثل IATA 2 من 5 باركود. IATA (International Air Transport Assosiation) تستخدم هذا الرمز الشريطي لإدارة الشحن الجوي. |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5) | تحديد أنه يجب تشفير البيانات باستخدام **INTERLEAVED 2 من 5** مواصفات الباركود |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn) | تحديد أنه يجب تشفير البيانات باستخدام **رقم ISBN** مواصفات الباركود |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn) | تحديد أنه يجب تشفير البيانات باستخدام **ISMN** مواصفات الباركود |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn) | تحديد أنه يجب تشفير البيانات باستخدام **ISSN** مواصفات الباركود |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25) | يمثل الرمز الشريطي للبريد الإيطالي 25. |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14) | تحديد أنه يجب تشفير البيانات باستخدام **ITF14** مواصفات الباركود |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6) | يمثل ITF-6 الباركود. |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417) | تحديد أنه يجب تشفير البيانات باستخدام **MacroPdf417** مواصفات الباركود |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark) | يمثل الرمز الشريطي لعلامة البريد الإلكتروني الملكية. |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5) | يمثل المصفوفة 2 من 5 BarCode |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode) | تحديد أنه يجب تشفير البيانات باستخدام **MaxiCode** مواصفات الباركود |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417) | تحديد أنه يجب تشفير البيانات باستخدام **ميكرو بي دي اف 417** مواصفات الباركود |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi) | تحديد أنه يجب تشفير البيانات باستخدام **إم إس آي بليسي** مواصفات الباركود |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none) | نوع ترميز غير محدد. |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode) | تحديد أنه يجب تشفير البيانات باستخدام USPS **ون كود** مواصفات الباركود |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc) | يمثل الرمز الشريطي OPC (رمز المنتج البصري) ، المعروف أيضًا باسم VCA Barcode VCA OPC ، Vision Council of America OPC Barcode. |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode) | يمثل رمز التصحيح الباركود |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417) | تحديد أنه يجب تشفير البيانات باستخدام **Pdf417** مواصفات الباركود |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode) | يمثل الباركود الصيدلاني. |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet) | تحديد أنه يجب تشفير البيانات باستخدام **كوكب** مواصفات الباركود |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet) | تحديد أنه يجب تشفير البيانات باستخدام **Postnet** مواصفات الباركود |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn) | يمثل الرمز الشريطي PZN. تُعرف هذه الرموز أيضًا بالرقم المركزي للصيدلة ، Pharmazentralnummer |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr) | تحديد أنه يجب تشفير البيانات باستخدام **رمز الاستجابة السريعة** مواصفات الباركود |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc) | يمثل الرمز الشريطي RM4SCC. يستخدم RM4SCC (رمز عميل Royal Mail 4-state) لعملية فرز البريد الآلي في المملكة المتحدة. |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14) | تحديد أنه يجب تشفير البيانات باستخدام **SCC14** مواصفات الباركود |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost) | تحديد أنه يجب تشفير البيانات باستخدام **سنغافورة بوست الباركود** مواصفات الباركود |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18) | تحديد أنه يجب تشفير البيانات باستخدام **SSCC18** مواصفات الباركود |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5) | تحديد أنه يجب تشفير البيانات باستخدام **المعيار 2 من 5** مواصفات الباركود |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel) | تحديد أنه يجب تشفير البيانات باستخدام **الرمز الشريطي للبريد السويسري**مواصفات الباركود. الأنواع المدعومة: البريد المحلي ، البريد الدولي ، الخدمات الإضافية (جديد) |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca) | تحديد أنه يجب تشفير البيانات باستخدام **اتحاد الوطنيين الكونغوليين- A** مواصفات الباركود |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon) | تحديد أنه يجب تشفير البيانات باستخدام **كوبون UPC مع رمز موسع GS1-128** مواصفات الباركود. مثال على سلسلة الإدخال: BarcodeGenerator.Codetext = "514141100906 (8102) 03" ، حيث يكون جزء UPCA "514141100906" ، جزء GS1Code128 هو (8102) 03. |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon) | تحديد أنه يجب تشفير البيانات باستخدام **كوبون UPC مع إضافة GS1 DataBar**مواصفات الباركود. مثال على سلسلة الإدخال: BarcodeGenerator.Codetext = "514141100906 (8110) 106141416543213500110000310123196000" ، حيث يكون جزء UPCA هو "514141100906" ، جزء Databar هو "(81105410) 106000 Parameters.CaptionAbove.Text = "بادئة الشركة + كود العرض" ؛ |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce) | تحديد أنه يجب تشفير البيانات باستخدام **UPC-E** مواصفات الباركود |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin) | يمثل VIN (رقم تعريف السيارة) الرمز الشريطي. |

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
