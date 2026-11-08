---
title: "com.aspose.barcode.barcoderecognition"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "تحتوي هذه الحزمة على أدوات للتعرف على باركود 1D/2D."
type: docs
weight: 12
url: /ar/java/com.aspose.barcode.barcoderecognition/
---

تحتوي هذه الحزمة على أدوات للتعرف على باركود 1D/2D.


## الفئات

| الفئة | الوصف |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | معلمات فك ترميز AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | يخزن بيانات خاصة لباركود Aztec المعترف به |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | يخزن معلمات موسعة للباركود المعترف به |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | استثناء عام يُرمى من قبل BarCodeReader، موروث من BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | يمثل منطقة الباركود المعترف به وزاوية الباركود |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | يخزن بيانات الباركود المعترف به مثل النوع SingleDecodeType، السلسلة string codetext، المنطقة BarCodeRegionParameters، ومعلمات أخرى |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | معلمات فك ترميز BarCode الرئيسية. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | إعدادات كاشف الباركود. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | الفئة الأساسية لـ MultiDecodeType و SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | الفئة الأساسية للمعلمات الموسعة لتخزين الباركود المعترف به |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | يخزن معلومات إضافية لرمز Codabar المعترف به |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | يحتوي على بيانات النوع الفرعي لرمز الباركود من نوع Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | يخزن بيانات خاصة لرمز Code128 المعترف به |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | يخزن معلومات إضافية لرمز DataBar المعترف به BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | يخزن بيانات خاصة لرمز DataMatrix المعترف به |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | حدد نوع الباركود للقراءة. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | يخزن بيانات خاصة لرمز DotCode المعترف به |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | يخزن بيانات خاصة لرمز **GS1 Composite Bar** المعترف به |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | يخزن معلومات إضافية لرمز MaxiCode المعترف به |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | نوع فك الترميز المركب. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | يخزن بيانات خاصة لرمز 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | يخزن معلومات بيانات تعريفية لرمز MacroPdf417 المعترف به |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | تسمح ProcessorSettings بالتعرف على الباركودات مع تحسين الأداء عبر تعدد الخيوط |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | يخزن معلومات إلحاق منظم QR لرمز الباركود المعترف به |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | يخزن مجموعة من أربع نقاط تمثل منطقة رباعية. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع فك الترميز الفردي. |

## الواجهات

| واجهة | الوصف |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | واجهة عامة لفك ترميز حقل معلومات العميل التي تُستخدم في ترميز AustraliaPost. |

## التعدادات

| تعداد | الوصف |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | يحتوي على مستوى ثقة التعرف |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | يحتوي على أنواع مجموعة فرعية من Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | يحدد نوع التفسير (C\_TABLE أو N\_TABLE) لمعلومات العميل لباركود AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
