---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "توفر مساحة الاسم aspose.barcode فئات وتعدادات لإنشاء وتخصيص وفك تشفير مجموعة واسعة من أنواع الباركود في Node.js عبر Java."
type: docs
weight: 10
url: /ar/nodejs/aspose.barcode/
---
استخدم هذه الأنواع لتكوين إعدادات إنشاء الباركود مثل تنسيق العنوان، المواصفات الإقليمية، والمعلمات المتقدمة لـ Aztec وغيرها من الرموز. تشمل مساحة الاسم مساعدات لبناء نصوص رموز موسعة ومعالجة معايير البريد المتخصصة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [Address](./address/) | عنوان الدائن أو المدين. يمكنك إما تحديد الشارع، رقم المنزل، الرمز البريدي والمدينة (نوع عنوان منظم) o |
| [AlternativeScheme](./alternativescheme/) | تعليمات نظام الدفع البديل |
| [AustraliaPostSettings](./australiapostsettings/) | معلمات فك تشفير AustraliaPost. تحتوي على معلمات تؤثر على البيانات التي تم التعرف عليها من رموز AustraliaPost symbolog |
| [AustralianPostParameters](./australianpostparameters/) | معلمات الباركود AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | مولد نص الكود الموسع لباركود Aztec لوضع ExtendedCodetext من AztecEncodeMode استخدم الخاصية TwoDDisplayText |
| [AztecExtendedParameters](./aztecextendedparameters/) | يخزن البيانات الخاصة لباركود Aztec الذي تم التعرف عليه. يوضح هذا المثال كيفية الحصول على القيم الخام لAztec let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | معلمات Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | يخزن المعلمات الموسعة للباركود الذي تم التعرف عليه |
| [BarCodeReader](./barcodereader/) | يقوم BarCodeReader بتغليف صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes operatio |
| [BarCodeRegionParameters](./barcoderegionparameters/) | يمثل منطقة الباركود الذي تم التعرف عليه وزاوية الباركود |
| [BarCodeResult](./barcoderesult/) | يخزن بيانات الباركود الذي تم التعرف عليه مثل النوع SingleDecodeType، نص الكود `string`، المنطقة BarCodeRegionParameters وغيرها p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator لإنشاء صور الباركود الخلفية. الرموز المدعومة: 1D: Codabar، Code11، Code128، Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | معلمات إنشاء الباركود. |
| [BarcodeSettings](./barcodesettings/) | معلمات فك ترميز الباركود الرئيسية. تحتوي على معلمات تؤثر على البيانات المعترف بها. |
| [BaseGenerationParameters](./basegenerationparameters/) | معلمات إنشاء صورة الباركود. |
| [BorderParameters](./borderparameters/) | معلمات حدود صورة الباركود |
| [CMYKColor](./cmykcolor/) | فئة للون CMYK. يعني وجود نسخة فارغة أن CMYK غير مستخدم، ويتم استخدام لون RGB الافتراضي. |
| [CaptionParameters](./captionparameters/) | معلمات التسمية. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | يخزن معلومات إضافية عن Codabar للباركود المعترف به |
| [CodabarParameters](./codabarparameters/) | معلمات Codabar. |
| [CodablockParameters](./codablockparameters/) | معلمات Codablock. |
| [Code128DataPortion](./code128dataportion/) | يحتوي على بيانات النوع الفرعي لباركود من نوع Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | يخزن بيانات خاصة لباركود Code128 المعترف به، يمثل منطقة الباركود المعترف به وزاوية الباركود |
| [Code128Parameters](./code128parameters/) | معلمات Code128. |
| [Code16KParameters](./code16kparameters/) | معلمات Code16K. |
| [CodetextParameters](./codetextparameters/) | معلمات Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator لتوليد صور الباركود المعقد في الخلفية (مثل SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader يفك تشفير النص المشفر إلى نوع الباركود المعقد المحدد. |
| [CouponParameters](./couponparameters/) | معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon و UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | يخزن معلومات إضافية عن DataBar للباركود المعترف به |
| [DataBarParameters](./databarparameters/) | معلمات Databar. |
| [DataElement](./dataelement/) | يمثل حقل بيانات خاص بالسلطة القضائية يُستخدم في المستندات، على سبيل المثال ElementID = "ZVA" مع Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | مولد النص المشفر الموسع لباركود DataMatrix ثنائي الأبعاد لوضعية ExtendedCodetext في DataMatrixEncodeMode //كود موسع |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | يخزن بيانات خاصة لباركود DataMatrix المعترف به. هذا المثال يوضح كيفية الحصول على القيم الخام لـ DataMatrix، دع المولد = |
| [DataMatrixParameters](./datamatrixparameters/) | معلمات DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | مولد النص المشفر الموسع لباركود DotCode ثنائي الأبعاد لوضعية ExtendedCodetext في DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | يخزن بيانات خاصة لباركود DotCode المعترف به. هذا المثال يوضح كيفية الحصول على القيم الخام لـ DotCode |
| [DotCodeParameters](./dotcodeparameters/) | معلمات DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | فئة المساعدة لتوليد النص الرمزي تلقائيًا لوضع Extended Codetext Mode |
| [FontUnit](./fontunit/) | يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط حيث يكون الحجم في خاصية قيمة الوحدة. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | يخزن بيانات خاصة لـ `GS1 Composite Bar ` الباركود المعترف به |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | معلمات شريط GS1 Composite. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية. هذا مثال |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز HIBC LIC. يوضح هذا المثال كيفية فك تشفير HIBC LI الخام |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية. يوضح هذا المثال كيفية |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الثانوية. |
| [HIBCPASCodetext](./hibcpascodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | فئة لتخزين سجل HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | مولد النص الرمزي الموسع لرمز Han Xin لوضع الموسع في HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | معلمات Han Xin. |
| [HslaColor](./hslacolor/) | فئة لتمثيل لون HSLA (الدرجة، التشبع، الإضاءة، الشفافية) |
| [IComplexCodetext](./icomplexcodetext/) | واجهة للنص الرمزي المعقد المستخدم مع ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | معلمات ITF. |
| [ImageParameters](./imageparameters/) | معلمات الصورة. |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز 4-state Royal Mailmark. |
| [MandatoryFields](./mandatoryfields/) | العناصر الإلزامية (الحقول) للبطاقة |
| [MaxiCodeCodetext](./maxicodecodetext/) | الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode. يوضح هذا المثال كيفية فك تشفير MaxiCod الخام |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 3. يوضح هذا المثال كيفية الترميز و |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | مولد النص الرمزي الموسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode استخدم TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | يخزن معلومات إضافية عن MaxiCode للباركود المعترف به |
| [MaxiCodeParameters](./maxicodeparameters/) | معلمات MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | فئة لتشفير وفك تشفير نص MaxiCode للأنماط 4، 5 و6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | فئة لتشفير وفك تشفير نص MaxiCode للأنماط 4، 5 و6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | فئة لتشفير وفك تشفير الرسالة الثانية القياسية لباركود MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | فئة لتشفير وفك تشفير الرسالة الثانية القياسية لباركود MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | الفئة الأساسية لتشفير وفك تشفير النص المدمج في رمز MaxiCode للأنماط 2 و3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | فئة لتشفير وفك تشفير الرسالة الثانية المهيكلة لباركود MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | يخزن بيانات خاصة للباركود أحادي الأبعاد المعترف به مثل نص منفصل ومجموع التحقق. |
| [OptionalFields](./optionalfields/) | العناصر (الحقول) الاختيارية للبطاقة. |
| [Padding](./padding/) | معلمات الحشو. |
| [PatchCodeParameters](./patchcodeparameters/) | معلمات PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | يخزن معلومات بيانات تعريفية لـ MacroPdf417 للباركود المعترف به. |
| [Pdf417Parameters](./pdf417parameters/) | معلمات PDF417. يحتوي على معلمات PDF417 وMacroPDF417 وMicroPDF417 وGS1MicroPdf417. يتطلب MacroPDF417 ملفين. |
| [PdfParameters](./pdfparameters/) | غلاف معلمات PDF. يتوقع وجود كائن أساسي `mwObject` يوفر طرق getter/setter المقابلة. |
| [PostalParameters](./postalparameters/) | معلمات البريد. تُستخدم لـ Postnet وPlanet. |
| [PrimaryData](./primarydata/) | فئة لتخزين البيانات الأولية لـ HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | يخزن معلومات الإلحاق المهيكل QR للباركود المعترف به. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | مولد نص موسع لباركود QR ثنائي الأبعاد لوضع ExtendedCodetext في QREncodeMode. استخدم خاصية Display2DText من B |
| [QrParameters](./qrparameters/) | معلمات QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | معلمات الإلحاق المهيكل QR. |
| [Quadrangle](./quadrangle/) | يخزن مجموعة من أربع نقاط تمثل منطقة رباعية. |
| [QualitySettings](./qualitysettings/) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة عن طريق em |
| [RecognitionAbortedException](./recognitionabortedexception/) | يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | خصائص ملف فرعي USA DL، الإزاحة والطول تُضبط تلقائيًا. |
| [SupplementParameters](./supplementparameters/) | معلمات المكمل. تُستخدم لـ Interleaved2of5 وStandard2of5 وEAN13 وEAN8 وUPCA وUPCE وISBN وISSN وISMN. |
| [SvgParameters](./svgparameters/) | معلمات SVG. |
| [SwissQRBill](./swissqrbill/) | بيانات الفاتورة SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | فئة لتشفير وفك تشفير النص المضمن في رمز PDF417 لرخصة القيادة الأمريكية. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | فئة للحقول الخاصة بالاختصاص القضائي لرخصة القيادة الأمريكية. |
| [Unit](./unit/) | يحدد قيمة الحجم بوحدات مختلفة (بكسل، بوصات، إلخ). |
