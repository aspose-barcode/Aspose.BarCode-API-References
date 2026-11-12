---
title: "عام"
linktitle: "عام"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "تجمع مساحة الاسم Global التعدادات الأساسية والفئات المساعدة المستخدمة عبر Aspose.BarCode لـ Node.js عبر Java."
type: docs
weight: 20
url: /ar/nodejs/global/
---
يوفر النطاق العام مجموعة من التعدادات الأساسية وأنواع المساعدة التي تُعرّف خصائص الباركود مثل أوضاع الترميز، أحجام الرموز، مستويات الثقة، وتنسيقات الصور. يتم الإشارة إلى هذه التعريفات في جميع أنحاء Aspose.BarCode API لتكوين وتفسير إنشاء الباركود والتعرف عليه.

## التعدادات

| تعداد | الوصف |
| --- | --- |
| [AddressType](./addresstype/) | نوع العنوان |
| [AutoSizeMode](./autosizemode/) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية هي AutoSizeMode.NONE. |
| [AztecEncodeMode](./aztecencodemode/) | وضع الترميز لباركودات Aztec. |
| [AztecSymbolMode](./aztecsymbolmode/) | يحدد وضع رمز Aztec. |
| [BarCodeConfidence](./barcodeconfidence/) | يحتوي على مستوى ثقة التعرف |
| [BarCodeImageFormat](./barcodeimageformat/) | يحدد تنسيق ملف الصورة. |
| [BarcodeClassifications](./barcodeclassifications/) | تصنيف BarcodeClassifications EncodeTypes |
| [BarcodeQualityMode](./barcodequalitymode/) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل r |
| [BorderDashStyle](./borderdashstyle/) | يحدد نمط خطوط الحدود المتقطعة. |
| [ChecksumValidation](./checksumvalidation/) | تمكين التحقق من المجموع الاختباري أثناء التعرف على باركودات 1D. يُعامل الافتراضي على أنه نعم للأنماط التي يجب أن تستمر |
| [CodabarChecksumMode](./codabarchecksummode/) | يحدد خوارزمية المجموع الاختباري لـ Codabar |
| [CodabarSymbol](./codabarsymbol/) | يحدد رمز البداية أو النهاية لمواصفات باركود Codabar. |
| [Code128EncodeMode](./code128encodemode/) | وضع الترميز لباركودات Code128. مواصفة `Code 128`. يوضح هذا الكود كيفية إنشاء Code 128 بطرق مختلفة |
| [Code128SubType](./code128subtype/) | يحتوي على أنواع من مجموعة Code128 الفرعية |
| [CodeLocation](./codelocation/) | موقع نص الرمز |
| [ComplexBackgroundMode](./complexbackgroundmode/) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. هذا المثال يوضح كيفية استخدام Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | يحدد نوع التفسير (C_TABLE أو N_TABLE) لمعلومات العميل لباركود AustralianPost BarCode. |
| [DataMatrixEccType](./datamatrixecctype/) | حدد نوع ECC للترميز. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | وضع الترميز لمشفّر DataMatrix، الافتراضي Auto. هذا المثال يوضح كيفية إنشاء نص الشيفرة في الوضع الموسع. //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | حدد نوع ECC للترميز. |
| [DecodeType](./decodetype/) | حدد نوع الباركود للقراءة. |
| [DeconvolutionMode](./deconvolutionmode/) | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة |
| [DotCodeEncodeMode](./dotcodeencodemode/) | وضع الترميز لباركودات DotCode. |
| [ECIEncodings](./eciencodings/) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [EnableChecksum](./enablechecksum/) | تمكين التحقق من المجموع الاختباري أثناء الإنشاء لباركودات 1D. يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على مجموع اختباري |
| [EncodeTypes](./encodetypes/) | يحدد نوع الباركود للترميز. |
| [FontMode](./fontmode/) | وضع حجم الخط. |
| [FontStyle](./fontstyle/) | تصنيف FontStyle |
| [GraphicsUnit](./graphicsunit/) | يحدد وحدة القياس للبيانات المعطاة. |
| [HIBCLICDateFormat](./hibclicdateformat/) | يحدد الأنواع المختلفة لتنسيقات التاريخ لـ HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | أنواع مواقع بيانات HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | أنواع بيانات سجل HIBC PAS. |
| [HanXinEncodeMode](./hanxinencodemode/) | وضع الترميز لـ Han Xin Code. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode لأحرف Unicode |
| [HanXinErrorLevel](./hanxinerrorlevel/) | مستوى تصحيح الأخطاء Reed-Solomon. من منخفض إلى عالي: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | إصدار Han Xin Code. من Version01 - 23 × 23 وحدة إلى Version84 - 189 × 189 وحدة، مع زيادة بخطوات 2 وحدة |
| [ITF14BorderType](./itf14bordertype/) | نوع حد باركود ITF14 |
| [InverseImageMode](./inverseimagemode/) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (السطوع). هذا المثال |
| [MacroCharacter](./macrocharacter/) | قيم الأحرف الماكرو 05 و06 تُستخدم للحصول على ترميز أكثر تكثيفًا في الأوضاع الخاصة. الحرف الماكرو 05 يُحول |
| [Mailmark2DType](./mailmark2dtype/) | نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | وضع الترميز لباركودات MaxiCode. |
| [MaxiCodeMode](./maxicodemode/) | وضع الترميز لباركودات MaxiCode. |
| [MicroQRVersion](./microqrversion/) | إصدار MicroQR Code. من M1 إلى M4. |
| [PatchFormat](./patchformat/) | تنسيق PatchCode. اختر PatchOnly لتوليد PatchCode واحد. استخدم تنسيق الصفحة لتوليد صفحة Patch مع PatchCodes |
| [Pdf417CompactionMode](./pdf417compactionmode/) | وضع ضغط شيفرة الباركود Pdf417 |
| [Pdf417EncodeMode](./pdf417encodemode/) | وضع ترميز شيفرة الباركود Pdf417 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | مستوى تصحيح الأخطاء لشيفرة الباركود pdf417، من المستوى 0 إلى المستوى 9، المستوى 0 يعني لا تصحيح أخطاء، المستوى 9 يعني الأفضل |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PD |
| [QREncodeMode](./qrencodemode/) | وضع الترميز لباركودات QR. مثال على كيفية استخدام ترميز ECI generator = new BarcodeGenerator(EncodeTypes.QR, "12345TE |
| [QREncodeType](./qrencodetype/) | وضع اختيار QR / MicroQR. اختر FORCE_QR للرموز QR القياسية، AUTO لـ MicroQR. يُستخدم FORCE_MICRO_QR للقوة العالية |
| [QRErrorLevel](./qrerrorlevel/) | مستوى تصحيح الأخطاء Reed-Solomon. من منخفض إلى عالي: LEVEL_L، LEVEL_M، LEVEL_Q، LEVEL_H. |
| [QRVersion](./qrversion/) | إصدار QR Code. من Version1 إلى Version40 لرمز QR ومن M1 إلى M4 لMicroQr. |
| [QrBillStandardVersion](./qrbillstandardversion/) | إصدار معيار الفاتورة SwissQR |
| [QrExtCompactionMode](./qrextcompactionmode/) | يحدد وضع ضغط QR للنص المضاف بواسطة QrExtCodetextBuilder. |
| [RectMicroQRVersion](./rectmicroqrversion/) | إصدار RectMicroQR Code. من الإصدار R7x43 إلى الإصدار R17x139. |
| [SvgColorMode](./svgcolormode/) | الوضعيات الممكنة لتعبئة اللون في ملف svg، RGB هو الافتراضي ومدعوم من SVG 1.1. RGBA، HSL، HSLA مسموح بها في SVG. |
| [TextAlignment](./textalignment/) | محاذاة النص. |
