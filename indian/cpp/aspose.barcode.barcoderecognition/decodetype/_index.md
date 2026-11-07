---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType class"
linktitle: "DecodeType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType class. C++ में पढ़ने के लिए बारकोड का प्रकार निर्दिष्ट करता है।"
type: docs
weight: 1600
url: /hi/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


पढ़ने के लिए बारकोड का प्रकार निर्दिष्ट करें।

```cpp
class DecodeType
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | AllSupportedTypes को दर्शाने वाला एक एरे प्राप्त करता है |
| static [GetNames](./getnames/)() | डिकोड प्रकारों के नामों का एरे पुनः प्राप्त करता है। |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | निर्धारित करता है कि निर्दिष्ट [BaseDecodeType](../basedecodetype/) में कोई 1D बारकोड सिम्बोलॉजी है या नहीं |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | निर्धारित करता है कि निर्दिष्ट [BaseDecodeType](../basedecodetype/) में कोई 2D बारकोड सिम्बोलॉजी है या नहीं |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | निर्धारित करता है कि निर्दिष्ट [BaseDecodeType](../basedecodetype/) में कोई पोस्टल बारकोड सिम्बोलॉजी है या नहीं |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में बदलता है। एक लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | बारकोड प्रकारों द्वारा स्कैन सेट निर्दिष्ट करें |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में बदलता है। एक लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | निर्दिष्ट करता है कि डेटा सभी उपलब्ध सिम्बोलॉजीज़ के साथ जाँच किया जाएगा |
| static [AustralianPosteParcel](./australianposteparcel/) | निर्दिष्ट करता है कि डेटा को **Australian Post Domestic eParcel Barcode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [AustraliaPost](./australiapost/) | निर्दिष्ट करता है कि डेटा को **Australia Post** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Aztec](./aztec/) | निर्दिष्ट करता है कि डेटा को **Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Codabar](./codabar/) | निर्दिष्ट करता है कि डेटा को **CODABAR** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [CodablockF](./codablockf/) | निर्दिष्ट करता है कि डेटा को **CodablockF** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Code11](./code11/) | निर्दिष्ट करता है कि डेटा को **CODE 11** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Code128](./code128/) | निर्दिष्ट करता है कि डेटा को **CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Code16K](./code16k/) | निर्दिष्ट करता है कि डेटा को **SCode16K** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Code32](./code32/) | निर्दिष्ट करता है कि डेटा को **Code32** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [Code39](./code39/) | निर्दिष्ट करता है कि डेटा को **Code 39** बेसिक कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | निर्दिष्ट करता है कि डेटा को **Code 39** पूर्ण ASCII कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| static [Code93](./code93/) | निर्दिष्ट करता है कि डेटा को **CODE 93** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [CompactPdf417](./compactpdf417/) | निर्दिष्ट करता है कि डेटा को **CompactPdf417** (Pdf417Truncated) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarExpanded](./databarexpanded/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar expanded** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar expanded stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarLimited](./databarlimited/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar limited** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarOmniDirectional](./databaromnidirectional/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarStacked](./databarstacked/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar stacked omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DatabarTruncated](./databartruncated/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar truncated** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static [DataLogic2of5](./datalogic2of5/) | निर्दिष्ट करता है कि डेटा को **DataLogic 2 of 5** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [DataMatrix](./datamatrix/) | निर्दिष्ट करता है कि डेटा को **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** बारकोड सिम्बॉलॉजी के साथ डिकोड किया जाना चाहिए |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | निर्दिष्ट करता है कि डेटा को **DeutschePost Ident code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | निर्दिष्ट करता है कि डेटा को **DeutschePost Leit code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [DotCode](./dotcode/) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [DutchKIX](./dutchkix/) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [EAN13](./ean13/) | निर्दिष्ट करता है कि डेटा को **EAN-13** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [EAN14](./ean14/) | निर्दिष्ट करता है कि डेटा को **EAN14** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [EAN8](./ean8/) | निर्दिष्ट करता है कि डेटा को **EAN-8** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1Aztec](./gs1aztec/) | निर्दिष्ट करता है कि डेटा को **GS1 Aztec** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1Code128](./gs1code128/) | निर्दिष्ट करता है कि डेटा को **GS1 CODE 128** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1CompositeBar](./gs1compositebar/) | निर्दिष्ट करता है कि डेटा को **GS1 Composite Bar** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1DataMatrix](./gs1datamatrix/) | निर्दिष्ट करता है कि डेटा को **GS1DataMatrix** बारकोड सिम्बॉलॉजी के साथ डिकोड किया जाना चाहिए |
| static [GS1DotCode](./gs1dotcode/) | निर्दिष्ट करता है कि डेटा को **GS1 DotCode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1HanXin](./gs1hanxin/) | निर्दिष्ट करता है कि डेटा को **GS1 Han Xin Code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1MicroPdf417](./gs1micropdf417/) | निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [GS1QR](./gs1qr/) | निर्दिष्ट करता है कि डेटा को **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HanXin](./hanxin/) | निर्दिष्ट करता है कि डेटा को **Han Xin Code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCAztecLIC](./hibcazteclic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Aztec** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCAztecPAS](./hibcaztecpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Aztec** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCCode128LIC](./hibccode128lic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Code128** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCCode128PAS](./hibccode128pas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Code128** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCCode39LIC](./hibccode39lic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Code39** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCCode39PAS](./hibccode39pas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Code39** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCQRLIC](./hibcqrlic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [HIBCQRPAS](./hibcqrpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [IATA2of5](./iata2of5/) | निर्दिष्ट करता है कि डेटा को **IATA 2 of 5** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए। IATA (International Air Transport Association) इस बारकोड का उपयोग हवाई माल के प्रबंधन के लिए करता है। |
| static [Interleaved2of5](./interleaved2of5/) | निर्दिष्ट करता है कि डेटा को **INTERLEAVED 2 of 5** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ISBN](./isbn/) | निर्दिष्ट करता है कि डेटा को **ISBN** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ISMN](./ismn/) | निर्दिष्ट करता है कि डेटा को **ISMN** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ISSN](./issn/) | निर्दिष्ट करता है कि डेटा को **ISSN** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ItalianPost25](./italianpost25/) | निर्दिष्ट करता है कि डेटा को **Italian Post 25** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ITF14](./itf14/) | निर्दिष्ट करता है कि डेटा को **ITF14** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [ITF6](./itf6/) | निर्दिष्ट करता है कि डेटा को **ITF6** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [JapanPost](./japanpost/) | निर्दिष्ट करता है कि डेटा को **Japan Post** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MacroPdf417](./macropdf417/) | निर्दिष्ट करता है कि डेटा को **MacroPdf417** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [Mailmark](./mailmark/) | निर्दिष्ट करता है कि डेटा को **Royal Mail Mailmark** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए। |
| static [Matrix2of5](./matrix2of5/) | निर्दिष्ट करता है कि डेटा को **Matrix 2 of 5** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MaxiCode](./maxicode/) | निर्दिष्ट करता है कि डेटा को **MaxiCode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MicrE13B](./micre13b/) | निर्दिष्ट करता है कि डेटा को **MICR E-13B** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MicroPdf417](./micropdf417/) | निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MicroQR](./microqr/) | निर्दिष्ट करता है कि डेटा को **MicroQR Code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [MostCommonTypes](./mostcommontypes/) | निर्दिष्ट करता है कि डेटा को सबसे अधिक उपयोग की जाने वाली प्रतीकात्मकताओं के साथ जाँच किया जाएगा |
| static [MSI](./msi/) | निर्दिष्ट करता है कि डेटा को **MSI Plessey** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [None](./none/) | अस्पष्ट डिकोड प्रकार। |
| static [OneCode](./onecode/) | निर्दिष्ट करता है कि डेटा को USPS **OneCode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [OPC](./opc/) | निर्दिष्ट करता है कि डेटा को **OPC** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [PatchCode](./patchcode/) | निर्दिष्ट करता है कि डेटा को **Patch code** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए। बारकोड प्रतीकात्मकता स्वचालित स्कैनिंग के लिए उपयोग की जाती है |
| static [Pdf417](./pdf417/) | निर्दिष्ट करता है कि डेटा को **Pdf417** बारकोड प्रतीकात्मकता के साथ डिकोड किया जाना चाहिए |
| static [Pharmacode](./pharmacode/) | निर्दिष्ट करता है कि डेटा को **Pharmacode** बारकोड के साथ डिकोड किया जाना चाहिए। यह प्रतीकात्मकता फ़ार्मास्यूटिकल बाइनरी कोड के रूप में भी जानी जाती है |
| static [Planet](./planet/) | निर्दिष्ट करता है कि डेटा को **Planet** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [PostalTypes](./postaltypes/) | निर्दिष्ट करता है कि डेटा को सभी **1.5D Postal** बारकोड प्रतीकों के साथ जाँच किया जाएगा, जैसे **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | निर्दिष्ट करता है कि डेटा को **Postnet** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [PZN](./pzn/) | निर्दिष्ट करता है कि डेटा को **PZN** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए। यह प्रतीक Pharma Zentral Nummer के नाम से भी जाना जाता है। PZN7 और PZN8 समर्थित हैं। |
| static [QR](./qr/) | निर्दिष्ट करता है कि डेटा को **[QR](../../aspose.barcode.barcoderecognition.qr/) कोड** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [RectMicroQR](./rectmicroqr/) | निर्दिष्ट करता है कि डेटा को **RectMicroQR (rMQR) कोड** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [RM4SCC](./rm4scc/) | निर्दिष्ट करता है कि डेटा को **RM4SCC** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए। RM4SCC (Royal Mail 4-state Customer Code) यूके में स्वचालित मेल सॉर्ट प्रक्रिया के लिए उपयोग किया जाता है। |
| static [SCC14](./scc14/) | निर्दिष्ट करता है कि डेटा को **SCC14** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [SSCC18](./sscc18/) | निर्दिष्ट करता है कि डेटा को **SSCC18** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [Standard2of5](./standard2of5/) | निर्दिष्ट करता है कि डेटा को **Standard 2 of 5** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [Supplement](./supplement/) | निर्दिष्ट करता है कि डेटा को **Supplement(EAN2, EAN5)** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [SwissPostParcel](./swisspostparcel/) | निर्दिष्ट करता है कि डेटा को **Swiss Post Parcel Barcode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [Types1D](./types1d/) | निर्दिष्ट करता है कि डेटा को सभी **1D** बारकोड प्रतीकों के साथ जाँच किया जाएगा |
| static [Types2D](./types2d/) | निर्दिष्ट करता है कि डेटा को सभी **2D** बारकोड प्रतीकों के साथ जाँच किया जाएगा |
| static [UPCA](./upca/) | निर्दिष्ट करता है कि डेटा को **UPC-A** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [UPCE](./upce/) | निर्दिष्ट करता है कि डेटा को **UPC-E** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static [VIN](./vin/) | निर्दिष्ट करता है कि डेटा को **VIN** (Vehicle Identification Number) बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
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

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
