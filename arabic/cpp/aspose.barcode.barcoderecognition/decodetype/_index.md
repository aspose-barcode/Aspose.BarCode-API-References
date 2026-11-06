---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType فئة"
linktitle: "DecodeType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspise::BarCode::BarCodeRecognition::DecodeType فئة. حدد نوع الباركود للقراءة في C++."
type: docs
weight: 1600
url: /ar/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


حدد نوع الباركود للقراءة.

```cpp
class DecodeType
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | يحصل على مصفوفة تمثل AllSupportedTypes |
| static [GetNames](./getnames/)() | يسترجع مصفوفة بأسماء أنواع فك الترميز. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | يحدد ما إذا كان [BaseDecodeType](../basedecodetype/) المحدد يحتوي على أي رموز شريطية 1D |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | يحدد ما إذا كان [BaseDecodeType](../basedecodetype/) المحدد يحتوي على أي رموز شريطية 2D |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | يحدد ما إذا كان [BaseDecodeType](../basedecodetype/) المحدد يحتوي على أي رموز شريطية بريدية |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | يحوِّل تمثيل النص لـ [SingleDecodeType](../singledecodetype/) إلى مثيلها. تشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل نجحت أم فشلت. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | حدد مجموعات الفحص حسب barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | يحوِّل تمثيل النص لـ [SingleDecodeType](../singledecodetype/) إلى مثيلها. تشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل نجحت أم فشلت. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | يحوّل التمثيل النصي لـ [MultiDecodeType](../multidecodetype/) إلى كائنه. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
## الحقول

| حقل | الوصف |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | يحدد أن البيانات ستُفحص بجميع الرموز المتاحة |
| static [AustralianPosteParcel](./australianposteparcel/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Australia Post** |
| static [Aztec](./aztec/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Aztec** |
| static [Codabar](./codabar/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CODABAR** |
| static [CodablockF](./codablockf/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CodablockF** |
| static [Code11](./code11/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CODE 11** |
| static [Code128](./code128/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CODE 128** |
| static [Code16K](./code16k/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **SCode16K** |
| static [Code32](./code32/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Code32** |
| static [Code39](./code39/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Code 39** لمجموعة الأحرف الأساسية: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **Code 39** لمجموعة الأحرف ASCII الكاملة: ISO/IEC 16388 |
| static [Code93](./code93/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | يحدد أن البيانات يجب فك ترميزها باستخدام مواصفة الباركود **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **DataLogic 2 of 5** مواصفة الباركود |
| static [DataMatrix](./datamatrix/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** نظام ترميز الباركود |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **DeutschePost Ident code** مواصفة الباركود |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **DeutschePost Leit code** مواصفة الباركود |
| static [DotCode](./dotcode/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **DotCode** مواصفة الباركود |
| static [DutchKIX](./dutchkix/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **DotCode** مواصفة الباركود |
| static [EAN13](./ean13/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **EAN-13** مواصفة الباركود |
| static [EAN14](./ean14/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **EAN14** مواصفة الباركود |
| static [EAN8](./ean8/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **EAN-8** مواصفة الباركود |
| static [GS1Aztec](./gs1aztec/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 Aztec** مواصفة الباركود |
| static [GS1Code128](./gs1code128/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 CODE 128** مواصفة الباركود |
| static [GS1CompositeBar](./gs1compositebar/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 Composite Bar** مواصفة الباركود |
| static [GS1DataMatrix](./gs1datamatrix/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1DataMatrix** نظام ترميز الباركود |
| static [GS1DotCode](./gs1dotcode/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 DotCode** مواصفة الباركود |
| static [GS1HanXin](./gs1hanxin/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 Han Xin Code** مواصفة الباركود |
| static [GS1MicroPdf417](./gs1micropdf417/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **MicroPdf417** مواصفة الباركود |
| static [GS1QR](./gs1qr/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** مواصفة الباركود |
| static [HanXin](./hanxin/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **Han Xin Code** مواصفة الباركود |
| static [HIBCAztecLIC](./hibcazteclic/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC LIC Aztec** مواصفة الباركود |
| static [HIBCAztecPAS](./hibcaztecpas/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC PAS Aztec** مواصفة الباركود |
| static [HIBCCode128LIC](./hibccode128lic/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC LIC Code128** مواصفة الباركود |
| static [HIBCCode128PAS](./hibccode128pas/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC PAS Code128** مواصفة الباركود |
| static [HIBCCode39LIC](./hibccode39lic/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC LIC Code39** مواصفة الباركود |
| static [HIBCCode39PAS](./hibccode39pas/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC PAS Code39** مواصفة الباركود |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** مواصفة الباركود |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** مواصفة الباركود |
| static [HIBCQRLIC](./hibcqrlic/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **IATA 2 of 5**. تستخدم IATA (الاتحاد الدولي للنقل الجوي) هذا الباركود لإدارة الشحن الجوي. |
| static [Interleaved2of5](./interleaved2of5/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **ISBN** |
| static [ISMN](./ismn/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **ISMN** |
| static [ISSN](./issn/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **ISSN** |
| static [ItalianPost25](./italianpost25/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **Italian Post 25** |
| static [ITF14](./itf14/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **ITF14** |
| static [ITF6](./itf6/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **ITF6** |
| static [JapanPost](./japanpost/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **Japan Post** |
| static [MacroPdf417](./macropdf417/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **MacroPdf417** |
| static [Mailmark](./mailmark/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **MaxiCode** |
| static [MicrE13B](./micre13b/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | يحدد أن البيانات يجب أن تُفك شفرتها باستخدام **MicroPdf417** مواصفة الباركود |
| static [MicroQR](./microqr/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | يحدد أنه سيتم فحص البيانات باستخدام أكثر الرموز شيوعًا |
| static [MSI](./msi/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **MSI Plessey** |
| static [None](./none/) | نوع فك التشفير غير محدد. |
| static [OneCode](./onecode/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود USPS **OneCode** |
| static [OPC](./opc/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **OPC** |
| static [PatchCode](./patchcode/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام مواصفة الباركود **Patch code**. تُستخدم رموز الباركود للمسح الآلي |
| static [Pdf417](./pdf417/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام رموز الباركود **Pdf417** |
| static [Pharmacode](./pharmacode/) | يحدد أن البيانات يجب أن تُفك تشفيرها باستخدام باركود **Pharmacode**. تُعرف هذه الرموز أيضًا باسم Pharmaceutical Binary Code |
| static [Planet](./planet/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Planet** |
| static [PostalTypes](./postaltypes/) | يحدد أن البيانات ستُفحص بجميع رموز الباركود **1.5D Postal**، مثل **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Postnet** |
| static [PZN](./pzn/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **PZN**. يُعرف هذا الترميز أيضًا باسم Pharma Zentral Nummer. يتم دعم PZN7 و PZN8. |
| static [QR](./qr/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **RM4SCC**. يُستخدم RM4SCC (Royal Mail 4-state Customer Code) لعملية فرز البريد الآلي في المملكة المتحدة. |
| static [SCC14](./scc14/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **SCC14** |
| static [SSCC18](./sscc18/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **SSCC18** |
| static [Standard2of5](./standard2of5/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Standard 2 of 5** |
| static [Supplement](./supplement/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | يحدد أن البيانات ستُفحص بجميع رموز الباركود **1D** |
| static [Types2D](./types2d/) | يحدد أن البيانات ستُفحص بجميع رموز الباركود **2D** |
| static [UPCA](./upca/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-A** |
| static [UPCE](./upce/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-E** |
| static [VIN](./vin/) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **VIN** (Vehicle Identification Number) |
## ملاحظات


يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
