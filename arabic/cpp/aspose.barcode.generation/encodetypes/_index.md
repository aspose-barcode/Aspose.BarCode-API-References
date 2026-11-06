---
title: "فئة Aspose::BarCode::Generation::EncodeTypes"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::EncodeTypes. تحدد نوع الباركود الذي سيتم ترميزه في C++."
type: docs
weight: 2300
url: /ar/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


يحدد نوع الباركود المراد ترميزه.

```cpp
class EncodeTypes
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | يحدد أن البيانات سيتم فحصها باستخدام جميع الرموز المتاحة. |
| static [GetNames](./getnames/)() | يسترجع مصفوفة بأسماء أنواع الترميز. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | يقوم بتحويل التمثيل النصي لـ [BaseEncodeType](../baseencodetype/) إلى كائنه. تشير قيمة الإرجاع إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | يقوم بتحويل التمثيل النصي لـ [BaseEncodeType](../baseencodetype/) إلى كائنه. تشير قيمة الإرجاع إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
## الحقول

| حقل | الوصف |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | يحدد أن البيانات يجب أن تُرمّز وفقًا لمواصفة الباركود **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | يمثل باركود عميل أستراليا بوست [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | يحدد أن البيانات يجب أن تُرمّز وفقًا لمواصفة الباركود **Aztec** |
| static [Codabar](./codabar/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **CODABAR** |
| static [CodablockF](./codablockf/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Codablock-F**. |
| static [Code11](./code11/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **CODE 11** |
| static [Code128](./code128/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **CODE 128** |
| static [Code16K](./code16k/) | يمثل باركود Code 16K. |
| static [Code32](./code32/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Code32** |
| static [Code39](./code39/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Code 39** لمجموعة الأحرف الأساسية: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Code 39** لمجموعة الأحرف ASCII الكاملة: ISO/IEC 16388 |
| static [Code93](./code93/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **CODE 93** |
| static [DatabarExpanded](./databarexpanded/) | يمثل باركود GS1 Databar الموسع. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | يمثل باركود GS1 Databar الموسع المكدس. |
| static [DatabarLimited](./databarlimited/) | يمثل باركود GS1 Databar المحدود. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **GS1 Databar omni-directional**. |
| static [DatabarStacked](./databarstacked/) | يمثل باركود GS1 Databar المكدس. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | يمثل باركود GS1 Databar المكدس متعدد الاتجاهات. |
| static [DatabarTruncated](./databartruncated/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **GS1 Databar truncated**. |
| static [DataLogic2of5](./datalogic2of5/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | رموز الباركود ثنائية الأبعاد DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | يمثل باركود Deutsch Post، وتعرف هذه الرموز أيضًا باسم Identcode,CodeIdentcode,German Postal 2 of 5 Identcode,Deutsch Post AG Identcode,Deutsch Frachtpost Identcode,Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | يمثل باركود Deutsch Post Leitcode، المعروف أيضًا باسم German Postal 2 of 5 Leitcode,CodeLeitcode,Leitcode,Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **DotCode** |
| static [DutchKIX](./dutchkix/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Dutch KIX** |
| static [EAN13](./ean13/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **EAN-13** |
| static [EAN14](./ean14/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **EAN14** |
| static [EAN8](./ean8/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1 Aztec**. يجب أن يحتوي نص الرمز على أقواس للمعرف AI. |
| static [GS1CodablockF](./gs1codablockf/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1 Codablock-F**. يجب أن يحتوي نص الرمز على أقواس للمعرف AI. |
| static [GS1Code128](./gs1code128/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1 Code 128**. يجب أن يحتوي نص الرمز على أقواس للمعرف AI. |
| static [GS1CompositeBar](./gs1compositebar/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1 Composite Bar**. يجب أن يحتوي نص الرمز على أقواس للمعرف AI. يجب أن يُفصل نص الرمز أحادي الأبعاد (1D) ونص الرمز ثنائي الأبعاد (2D) بالرمز '/'. |
| static [GS1DataMatrix](./gs1datamatrix/) | ترميز الباركود ثنائي الأبعاد DataMatrix مع تنسيق سلسلة GS1 |
| static [GS1DotCode](./gs1dotcode/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1 DotCode**. يجب أن يحتوي نص الرمز على أقواس للمعرف AI. |
| static [GS1HanXin](./gs1hanxin/) | ترميز الباركود ثنائي الأبعاد HanXin مع تنسيق سلسلة GS1 |
| static [GS1MicroPdf417](./gs1micropdf417/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **GS1MicroPdf417**. |
| static [GS1QR](./gs1qr/) | ترميز الباركود ثنائي الأبعاد QR مع تنسيق سلسلة GS1 |
| static [HanXin](./hanxin/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **Han Xin**. |
| static [HIBCAztecLIC](./hibcazteclic/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC LIC Aztec**. |
| static [HIBCAztecPAS](./hibcaztecpas/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC PAS Aztec**. |
| static [HIBCCode128LIC](./hibccode128lic/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC LIC Code128**. |
| static [HIBCCode128PAS](./hibccode128pas/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC PAS Code128**. |
| static [HIBCCode39LIC](./hibccode39lic/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC LIC Code39**. |
| static [HIBCCode39PAS](./hibccode39pas/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC PAS Code39**. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC LIC DataMatrix**. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC PAS DataMatrix**. |
| static [HIBCQRLIC](./hibcqrlic/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC LIC QR**. |
| static [HIBCQRPAS](./hibcqrpas/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **HIBC PAS QR**. |
| static [IATA2of5](./iata2of5/) | يمثل باركود IATA 2 من 5. تستخدم IATA (الاتحاد الدولي للنقل الجوي) هذا الباركود لإدارة الشحن الجوي. |
| static [Interleaved2of5](./interleaved2of5/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **INTERLEAVED 2 of 5**. |
| static [ISBN](./isbn/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **ISBN**. |
| static [ISMN](./ismn/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **ISMN**. |
| static [ISSN](./issn/) | يحدد أن البيانات يجب أن تُشفَّر وفق مواصفات الباركود **ISSN**. |
| static [ItalianPost25](./italianpost25/) | يمثل باركود إيطالي بوست 25. |
| static [ITF14](./itf14/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **ITF14** |
| static [ITF6](./itf6/) | يمثل باركود ITF-6. |
| static [JapanPost](./japanpost/) | يمثل بريد اليابان [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **MacroPdf417** |
| static [Mailmark](./mailmark/) | يمثل باركود رويال ميل Mailmark. |
| static [Matrix2of5](./matrix2of5/) | يمثل Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **MaxiCode** |
| static [MicroPdf417](./micropdf417/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **MicroPdf417** |
| static [MicroQR](./microqr/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **MicroQR Code** |
| static [MSI](./msi/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **MSI Plessey** |
| static [None](./none/) | نوع الترميز غير محدد. |
| static [OneCode](./onecode/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود USPS **OneCode** |
| static [OPC](./opc/) | يمثل باركود OPC(Optical Product Code)، المعروف أيضًا باسم VCA Barcode VCA OPC، Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | يمثل باركود Patch code |
| static [Pdf417](./pdf417/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Pdf417** |
| static [Pharmacode](./pharmacode/) | يمثل باركود Pharmacode. |
| static [Planet](./planet/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Planet** |
| static [Postnet](./postnet/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Postnet** |
| static [PZN](./pzn/) | يمثل باركود PZN. هذه الرمزية معروفة أيضًا باسم Pharmacy central number، Pharmazentralnummer. يتم دعم PZN7 و PZN8. يتم إنشاء PZN7 من 6 أرقام أو أقل، مثل "123456". يتم إنشاء PZN8 من 7 أرقام أو أكثر، مثل "1234567". يتم تجاهل رقم التحقق الأخير المقدم ويتم إنشاؤه بواسطة محرك الباركود. |
| static [QR](./qr/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **QR Code** |
| static [RectMicroQR](./rectmicroqr/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | يمثل باركود RM4SCC. RM4SCC (Royal Mail 4-state Customer Code) يُستخدم لعملية فرز البريد الآلية في المملكة المتحدة. |
| static [SCC14](./scc14/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **SCC14** |
| static [SingaporePost](./singaporepost/) | يحدد أن البيانات يجب ترميزها باستخدام مواصفة الباركود **Singapore Post Barcode** |
| static [SSCC18](./sscc18/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **SSCC18** |
| static [Standard2of5](./standard2of5/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **Standard 2 of 5** |
| static [SwissPostParcel](./swisspostparcel/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **Swiss Post Parcel Barcode**. الأنواع المدعومة: البريد المحلي، البريد الدولي، الخدمات الإضافية (جديد) |
| static [UPCA](./upca/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **UPC-A** |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **UPC coupon with GS1-128 Extended Code**. مثال على سلسلة الإدخال: BarcodeGenerator.Codetext = "514141100906(8102)03"، حيث الجزء UPCA هو "514141100906"، والجزء GS1Code128 هو (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **UPC coupon with GS1 DataBar addition**. مثال على سلسلة الإدخال: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000"، حيث الجزء UPCA هو "514141100906"، والجزء Databar هو "(8110)106141416543213500110000310123196000". لتغيير التسمية، استخدم Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | يحدد أن البيانات يجب أن تُشفّر وفق مواصفة الباركود **UPC-E** |
| static [VIN](./vin/) | يمثل باركود VIN (رقم تعريف المركبة). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
