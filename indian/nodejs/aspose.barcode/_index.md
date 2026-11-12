---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "aspose.barcode नेमस्पेस Node.js via Java में विभिन्न प्रकार के बारकोड बनाने, अनुकूलित करने और डिकोड करने के लिए क्लासेज़ और एन्उम प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs/aspose.barcode/
---
इन प्रकारों का उपयोग बारकोड जनरेशन सेटिंग्स जैसे पता फ़ॉर्मेटिंग, क्षेत्रीय विशिष्टताएँ, और Aztec तथा अन्य सिम्बोलॉजीज़ के लिए उन्नत पैरामीटर कॉन्फ़िगर करने के लिए करें। नेमस्पेस विस्तारित कोड टेक्स्ट बनाने और विशेष पोस्टल मानकों को संभालने के लिए हेल्पर्स शामिल करता है।

## क्लासेज़

| क्लास | विवरण |
| --- | --- |
| [Address](./address/) | ऋणदाता या ऋणग्राहक का पता। आप सड़क, घर नंबर, पोस्टल कोड और शहर (संरचित पता प्रकार) सेट कर सकते हैं o |
| [AlternativeScheme](./alternativescheme/) | वैकल्पिक भुगतान योजना निर्देश |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो AustraliaPost सिम्बोलॉजी के पहचाने गए डेटा को प्रभावित करते हैं। |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost बारकोड पैरामीटर। |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Aztec बारकोड के लिए ExtendedCodetext मोड में ExtendedCodetext जेनरेटर, AztecEncodeMode के TwoDDisplayText प्रॉपर्टी का उपयोग करें। |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है। यह उदाहरण दिखाता है कि Aztec कच्चे मान कैसे प्राप्त करें let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec पैरामीटर। |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | पहचाने गए बारकोड के विस्तारित पैरामीटर संग्रहीत करता है |
| [BarCodeReader](./barcodereader/) | BarCodeReader एक छवि को संलग्न करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह ReadBarCodes ऑपरेशन कर सकता है। |
| [BarCodeRegionParameters](./barcoderegionparameters/) | पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है |
| [BarCodeResult](./barcoderesult/) | पहचाने गए बारकोड डेटा जैसे SingleDecodeType प्रकार, `string` कोडटेक्स्ट, BarCodeRegionParameters क्षेत्र और अन्य p संग्रहीत करता है |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | Backend बारकोड इमेज जनरेशन के लिए BarcodeGenerator। समर्थित सिम्बोलॉजीज़: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | बारकोड जनरेशन पैरामीटर। |
| [BarcodeSettings](./barcodesettings/) | मुख्य बारकोड डिकोडिंग पैरामीटर। उन पैरामीटरों को शामिल करता है जो पहचाने गए डेटा पर प्रभाव डालते हैं। |
| [BaseGenerationParameters](./basegenerationparameters/) | बारकोड इमेज जनरेशन पैरामीटर। |
| [BorderParameters](./borderparameters/) | बारकोड इमेज बॉर्डर पैरामीटर |
| [CMYKColor](./cmykcolor/) | CMYK रंग के लिए क्लास। एक नल इंस्टेंस का मतलब है कि CMYK उपयोग नहीं किया गया है, और डिफ़ॉल्ट RGB रंग उपयोग में है। |
| [CaptionParameters](./captionparameters/) | कैप्शन पैरामीटर। |
| [CodabarExtendedParameters](./codabarextendedparameters/) | पहचाने गए बारकोड की कोडाबार अतिरिक्त जानकारी संग्रहीत करता है |
| [CodabarParameters](./codabarparameters/) | कोडाबार पैरामीटर। |
| [CodablockParameters](./codablockparameters/) | कोडाब्लॉक पैरामीटर। |
| [Code128DataPortion](./code128dataportion/) | Code128 प्रकार के बारकोड के सबटाइप का डेटा शामिल करता है |
| [Code128ExtendedParameters](./code128extendedparameters/) | Code128 पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है जो पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है |
| [Code128Parameters](./code128parameters/) | Code128 पैरामीटर। |
| [Code16KParameters](./code16kparameters/) | Code16K पैरामीटर। |
| [CodetextParameters](./codetextparameters/) | कोडटेक्स्ट पैरामीटर। |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | बैकएंड कॉम्प्लेक्स बारकोड (जैसे SwissQR) इमेज जनरेशन के लिए ComplexBarcodeGenerator। |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट कॉम्प्लेक्स बारकोड प्रकार में डिकोड करता है। |
| [CouponParameters](./couponparameters/) | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है। |
| [DataBarExtendedParameters](./databarextendedparameters/) | पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है |
| [DataBarParameters](./databarparameters/) | डेटाबार पैरामीटर। |
| [DataElement](./dataelement/) | दस्तावेज़ों में उपयोग किए जाने वाले अधिकार-विशिष्ट डेटा फ़ील्ड का प्रतिनिधित्व करता है, उदाहरण के लिए ElementID = "ZVA" और Value = "01"। |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | ExtendedCodetext मोड के DataMatrixEncodeMode के लिए 2D DataMatrix बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DataMatrix कच्चे मान कैसे प्राप्त करें let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix पैरामीटर। |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | ExtendedCodetext मोड के DotCodeEncodeMode के लिए 2D DotCode बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | DotCode पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DotCode कच्चे मान कैसे प्राप्त करें |
| [DotCodeParameters](./dotcodeparameters/) | DotCode पैरामीटर। |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Extended Codetext Mode की स्वचालित कोडटेक्स्ट जनरेशन के लिए हेल्पर क्लास |
| [FontUnit](./fontunit/) | पाठ के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में होता है। |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | `GS1 Composite Bar ` पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite बार पैरामीटर। |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास जो प्राथमिक और द्वितीयक डेटा संग्रहीत करता है। यह samp |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास। यह सैंपल दिखाता है कि कैसे रॉ HIBC LI को डिकोड किया जाए |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास जो प्राथमिक डेटा संग्रहीत करता है। यह सैंपल दिखाता है कैसे |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास जो द्वितीयक डेटा संग्रहीत करता है। |
| [HIBCPASCodetext](./hibcpascodetext/) | HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [HIBCPASRecord](./hibcpasrecord/) | HIBC PAS रिकॉर्ड को संग्रहीत करने के लिए क्लास। |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Han Xin कोड के Extended Mode के लिए Extended codetext जेनरेटर HanXinEncodeMode //Extended codetext मोड //कोड बनाएं |
| [HanXinParameters](./hanxinparameters/) | Han Xin पैरामीटर। |
| [HslaColor](./hslacolor/) | HSLA रंग (ह्यू, सैचुरेशन, लाइटनेस, अल्फा) को दर्शाने के लिए क्लास। |
| [IComplexCodetext](./icomplexcodetext/) | ComplexBarcodeGenerator के साथ उपयोग किए जाने वाले कॉम्प्लेक्स कोडटेक्स्ट के लिए इंटरफ़ेस। |
| [ITFParameters](./itfparameters/) | ITF पैरामीटर। |
| [ImageParameters](./imageparameters/) | इमेज पैरामीटर। |
| [License](./license/) | कम्पोनेंट को लाइसेंस करने के लिए मेथड्स प्रदान करता है। |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [MailmarkCodetext](./mailmarkcodetext/) | 4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [MandatoryFields](./mandatoryfields/) | कार्ड के अनिवार्य तत्व (फ़ील्ड)। |
| [MaxiCodeCodetext](./maxicodecodetext/) | MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास। यह सैंपल दिखाता है कि कैसे रॉ MaxiCod को डिकोड किया जाए |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | मोड्स 2 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | मोड्स 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। यह सैंपल दिखाता है कैसे एन्कोड और |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | MaxiCode बारकोड के लिए ExtendedCodetext मोड में Extended codetext जेनरेटर MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | पहचाने गए बारकोड की MaxiCode अतिरिक्त जानकारी संग्रहीत करता है |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode पैरामीटर। |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास। |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास। |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | MaxiCode बारकोड के लिए मानक द्वितीय संदेश को एन्कोड और डिकोड करने वाली क्लास। |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | MaxiCode बारकोड के लिए मानक द्वितीय संदेश को एन्कोड और डिकोड करने वाली क्लास। |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | मोड 2 और 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने की बेस क्लास। |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | MaxiCode बारकोड के लिए संरचित द्वितीय संदेश को एन्कोड और डिकोड करने वाली क्लास। |
| [OneDExtendedParameters](./onedextendedparameters/) | पहचाने गए 1D बारकोड के विशेष डेटा जैसे अलग कोडटेक्स्ट और चेकसम को संग्रहीत करता है |
| [OptionalFields](./optionalfields/) | कार्ड के वैकल्पिक तत्व (फ़ील्ड)। |
| [Padding](./padding/) | पैडिंग पैरामीटर। |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode पैरामीटर। |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी संग्रहीत करता है |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 को दो फ़ाइलों की आवश्यकता होती है |
| [PdfParameters](./pdfparameters/) | PDF पैरामीटर रैपर। यह एक अंतर्निहित `mwObject` इंस्टेंस की अपेक्षा करता है जो संबंधित गेटर/सेटर मेथड्स प्रदान करता है |
| [PostalParameters](./postalparameters/) | डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है। |
| [PrimaryData](./primarydata/) | HIBC LIC प्राथमिक डेटा संग्रहीत करने वाली क्लास। |
| [QRExtendedParameters](./qrextendedparameters/) | पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | ExtendedCodetext मोड के QREncodeMode के लिए 2D QR बारकोड का विस्तारित कोडटेक्स्ट जेनरेटर। B की Display2DText प्रॉपर्टी का उपयोग करें |
| [QrParameters](./qrparameters/) | QR पैरामीटर। |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR Structured Append पैरामीटर। |
| [Quadrangle](./quadrangle/) | एक क्वाड्रैंगल क्षेत्र का प्रतिनिधित्व करने वाले चार पॉइंट्स का सेट संग्रहीत करता है |
| [QualitySettings](./qualitysettings/) | QualitySettings मैन्युअली पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप जल्दी से QualitySettings सेट अप कर सकते हैं। |
| [RecognitionAbortedException](./recognitionabortedexception/) | BarCodeReader के साथ पहचान के दौरान टाइमआउट अधिक होने पर फेंकी जाने वाली पहचान रद्द अपवाद को दर्शाता है। |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने वाली क्लास। |
| [SubfileProperties](./subfileproperties/) | USA DL सबफ़ाइल प्रॉपर्टीज़, ऑफ़सेट और लंबाई स्वचालित रूप से सेट की जाती हैं। |
| [SupplementParameters](./supplementparameters/) | सप्लीमेंट पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है। |
| [SvgParameters](./svgparameters/) | SVG पैरामीटर। |
| [SwissQRBill](./swissqrbill/) | SwissQR बिल डेटा |
| [SwissQRCodetext](./swissqrcodetext/) | SwissQR कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [USADriveIdCodetext](./usadriveidcodetext/) | USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास। |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | USA DL के लिए अधिकार क्षेत्र विशिष्ट फ़ील्ड्स की क्लास। |
| [Unit](./unit/) | विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान निर्दिष्ट करता है। |
