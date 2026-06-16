---
title: com.aspose.barcode.barcoderecognition
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: تحتوي هذه الحزمة على أدوات للتعرف على باركود 1D/2D.
type: docs
weight: 11
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/
---

تحتوي هذه الحزمة على أدوات للتعرف على باركود 1D/2D.


## الفئات

| الفئة | الوصف |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | معلمات فك ترميز AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | يخزن البيانات الخاصة للباركود المعترف به من نوع Aztec |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | يحتوي على مستوى ثقة التعرف |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | يخزن المعلمات الموسعة للباركود المعترف به |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | استثناء عام يُرمى من قبل BarCodeReader، موروث من BarCodeException. |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | يمثل منطقة الباركود المعترف به وزاوية الباركود |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | يخزن بيانات الباركود المعترف به مثل النوع SingleDecodeType، النص string codetext، المنطقة BarCodeRegionParameters، ومعلمات أخرى |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | معلمات فك ترميز BarCode الرئيسية. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | إعدادات كاشف الباركود. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | الفئة الأساسية لـ MultiDecodeType و SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | الفئة الأساسية للمعلمات الموسعة لتخزين الباركود المعترف به |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | يخزن معلومات إضافية من نوع Codabar للباركود المعترف به |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | يحتوي على بيانات النوع الفرعي لباركود من نوع Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | يخزن بيانات خاصة للباركود Code128 المعترف به |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | يحتوي على أنواع من مجموعة Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | يخزن معلومات إضافية لباركود DataBar المعترف به BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | يخزن بيانات خاصة لباركود DataMatrix المعترف به |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | حدد نوع الباركود للقراءة. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | يخزن بيانات خاصة لباركود DotCode المعترف به |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | يخزن بيانات خاصة لباركود **GS1 Composite Bar** المعترف به |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | يخزن معلومات إضافية لباركود MaxiCode المعترف به |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | نوع فك الترميز المركب. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | نوع فك الترميز المركب. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | يخزن بيانات خاصة لباركود 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | يخزن معلومات بيانات تعريفية لباركود MacroPdf417 المعترف به |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | تسمح ProcessorSettings بالتعرف على الباركودات مع تحسين الأداء عبر تعدد الخيوط |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | يخزن معلومات QR Structured Append لباركود معترف به |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | يخزن مجموعة من أربع نقاط Point تمثل منطقة Quadrangle |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع فك الترميز الفردي. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## الواجهات

| واجهة | الوصف |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | واجهة عامة لتشفير حقل معلومات العميل (Customer Information Field) المستخدمة في ترميز AustraliaPost. |

## التعدادات

| تعداد | الوصف |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | يحدد نوع التفسير (C\_TABLE أو N\_TABLE) لمعلومات العميل لباركود AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | حدد حجم الصورة المُقاسة |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
