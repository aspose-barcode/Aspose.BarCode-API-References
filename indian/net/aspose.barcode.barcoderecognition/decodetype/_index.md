---
title: "Class DecodeType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType class. पढ़ने के लिए बारकोड का प्रकार निर्दिष्ट करें"
type: docs
weight: 230
url: /hi/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

पढ़ने के लिए बारकोड का प्रकार निर्दिष्ट करें।

```csharp
public static class DecodeType
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | AllSupportedTypes को दर्शाने वाला एक एरे प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | डिकोड प्रकारों के नामों का एरे पुनः प्राप्त करता है। |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट [`BaseDecodeType`](../basedecodetype/) में कोई 1D बारकोड सिम्बोलॉजी है या नहीं |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट [`BaseDecodeType`](../basedecodetype/) में कोई 2D बारकोड सिम्बोलॉजी है या नहीं |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट [`BaseDecodeType`](../basedecodetype/) में कोई पोस्टल बारकोड सिम्बोलॉजी है या नहीं |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | barcodeTypes द्वारा स्कैन सेट निर्दिष्ट करें |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | निर्दिष्ट करता है कि डेटा सभी उपलब्ध सिम्बोलॉजीज़ के साथ जाँच किया जाएगा |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | निर्दिष्ट करता है कि डेटा को **Australian Post Domestic eParcel Barcode** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | निर्दिष्ट करता है कि डेटा को **Australia Post** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | निर्दिष्ट करता है कि डेटा को **Aztec** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | निर्दिष्ट करता है कि डेटा को **CODABAR** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | निर्दिष्ट करता है कि डेटा को **CodablockF** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | निर्दिष्ट करता है कि डेटा को **CODE 11** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | निर्दिष्ट करता है कि डेटा को **CODE 128** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | निर्दिष्ट करता है कि डेटा को **SCode16K** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | निर्दिष्ट करता है कि डेटा को **Code32** बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | निर्दिष्ट करता है कि डेटा को **Code 39** बुनियादी कैरसेट बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | निर्दिष्ट करता है कि डेटा को **Code 39** पूर्ण ASCII कैरसेट बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | निर्दिष्ट करता है कि डेटा को **CODE 93** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | निर्दिष्ट करता है कि डेटा को **CompactPdf417** (Pdf417Truncated) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar expanded** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar expanded stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar limited** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar stacked omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | निर्दिष्ट करता है कि डेटा को **GS1 Databar truncated** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | निर्दिष्ट करता है कि डेटा को **DataLogic 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | निर्दिष्ट करता है कि डेटा को **DataMatrix** बारकोड सिम्बोलॉजी के साथ डिकोड किया जाना चाहिए |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | निर्दिष्ट करता है कि डेटा को **DeutschePost Ident code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | निर्दिष्ट करता है कि डेटा को **DeutschePost Leit code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | निर्दिष्ट करता है कि डेटा को **EAN-13** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | निर्दिष्ट करता है कि डेटा को **EAN14** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | निर्दिष्ट करता है कि डेटा को **EAN-8** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | निर्दिष्ट करता है कि डेटा को **GS1 Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | निर्दिष्ट करता है कि डेटा को **GS1 CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | निर्दिष्ट करता है कि डेटा को **GS1 Composite Bar** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | निर्दिष्ट करता है कि डेटा को **GS1DataMatrix** बारकोड सिम्बोलॉजी के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | निर्दिष्ट करता है कि डेटा को **GS1 DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | निर्दिष्ट करता है कि डेटा को **GS1 Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | निर्दिष्ट करता है कि डेटा को **GS1 QR** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | निर्दिष्ट करता है कि डेटा को **Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Code128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Code128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC Code39** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS Code39** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC DataMatrix** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS DataMatrix** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | निर्दिष्ट करता है कि डेटा को **HIBC LIC QR** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | निर्दिष्ट करता है कि डेटा को **HIBC PAS QR** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | निर्दिष्ट करता है कि डेटा को **IATA 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। IATA (International Air Transport Association) इस बारकोड का उपयोग हवाई माल के प्रबंधन के लिए करता है। |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | निर्दिष्ट करता है कि डेटा को **INTERLEAVED 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | निर्दिष्ट करता है कि डेटा को **ISBN** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | निर्दिष्ट करता है कि डेटा को **ISMN** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | निर्दिष्ट करता है कि डेटा को **ISSN** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | निर्दिष्ट करता है कि डेटा को **Italian Post 25** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | निर्दिष्ट करता है कि डेटा को **ITF14** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | निर्दिष्ट करता है कि डेटा को **ITF6** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | निर्दिष्ट करता है कि डेटा को **Japan Post** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | निर्दिष्ट करता है कि डेटा को **MacroPdf417** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | निर्दिष्ट करता है कि डेटा को **Royal Mail Mailmark** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | निर्दिष्ट करता है कि डेटा को **Matrix 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | निर्दिष्ट करता है कि डेटा को **MaxiCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | निर्दिष्ट करता है कि डेटा को **MICR E-13B** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | निर्दिष्ट करता है कि डेटा को **MicroQR Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | निर्दिष्ट करता है कि डेटा को सबसे अधिक सामान्यतः उपयोग की जाने वाली सिम्बोलॉजीज़ के साथ जांचा जाएगा |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | निर्दिष्ट करता है कि डेटा को **MSI Plessey** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | अस्पष्ट डिकोड प्रकार। |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | निर्दिष्ट करता है कि डेटा को USPS **OneCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | निर्दिष्ट करता है कि डेटा को **OPC** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | निर्दिष्ट करता है कि डेटा को **Patch code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। बारकोड सिम्बोलॉजी स्वचालित स्कैनिंग के लिए उपयोग की जाती है |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | निर्दिष्ट करता है कि डेटा को **Pdf417** बारकोड सिम्बोलॉजी के साथ डिकोड किया जाना चाहिए |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | निर्दिष्ट करता है कि डेटा को **Pharmacode** बारकोड के साथ डिकोड किया जाना चाहिए। यह सिम्बोलॉजी फार्मास्यूटिकल बाइनरी कोड के नाम से भी जानी जाती है |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | निर्दिष्ट करता है कि डेटा को **Planet** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | निर्दिष्ट करता है कि डेटा को सभी **1.5D Postal** बारकोड सिम्बोलॉजीज़, जैसे **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** के साथ जांचा जाएगा |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | निर्दिष्ट करता है कि डेटा को **Postnet** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | निर्दिष्ट करता है कि डेटा को **PZN** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। यह सिम्बोलॉजी Pharma Zentral Nummer के नाम से भी जानी जाती है। PZN7 और PZN8 समर्थित हैं। |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | निर्दिष्ट करता है कि डेटा को **QR Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | निर्दिष्ट करता है कि डेटा को **RectMicroQR (rMQR) Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | निर्दिष्ट करता है कि डेटा को **RM4SCC** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। RM4SCC (Royal Mail 4-state Customer Code) यूके में स्वचालित मेल सॉर्ट प्रक्रिया के लिए उपयोग किया जाता है। |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | निर्दिष्ट करता है कि डेटा को **SCC14** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | निर्दिष्ट करता है कि डेटा को **SSCC18** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | निर्दिष्ट करता है कि डेटा को **Standard 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | निर्दिष्ट करता है कि डेटा को **Supplement(EAN2, EAN5)** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | निर्दिष्ट करता है कि डेटा को **Swiss Post Parcel Barcode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | निर्दिष्ट करता है कि डेटा को सभी **1D** बारकोड सिम्बोलॉजीज़ के साथ जांचा जाएगा |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | निर्दिष्ट करता है कि डेटा को सभी **2D** बारकोड सिम्बोलॉजीज़ के साथ जांचा जाएगा |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | निर्दिष्ट करता है कि डेटा को **UPC-A** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | निर्दिष्ट करता है कि डेटा को **UPC-E** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | निर्दिष्ट करता है कि डेटा को **VIN** (Vehicle Identification Number) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

```csharp
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

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


