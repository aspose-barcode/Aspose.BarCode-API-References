---
title: DecodeType
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: पढ़ने के लए बरकड क प्रकर नर्दष्ट करें
type: docs
weight: 190
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
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | एक सरणी प्राप्त करता है जो AllSupportedTypes का प्रतिनिधित्व करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | डिकोड प्रकारों के नामों की एक सरणी प्राप्त करता है। |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट किया गया है या नहीं[`BaseDecodeType`](../basedecodetype/) कोई 1D बारकोड सहजीवन शामिल है |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट किया गया है या नहीं[`BaseDecodeType`](../basedecodetype/) कोई 2D बारकोड सहजीवन शामिल है |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | निर्धारित करता है कि निर्दिष्ट किया गया है या नहीं[`BaseDecodeType`](../basedecodetype/) कोई डाक बारकोड सहजीवन शामिल है |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType के स्ट्रिंग प्रस्तुतिकरण को उसके उदाहरण में कनवर्ट करता है. वापसी मान इंगित करता है कि रूपांतरण सफल हुआ या विफल. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | बारकोडटाइप्स द्वारा स्कैन सेट निर्दिष्ट करें |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | एक मल्टीडिकोडटाइप के स्ट्रिंग प्रतिनिधित्व को इसके उदाहरण में परिवर्तित करता है। वापसी मान इंगित करता है कि रूपांतरण सफल हुआ या विफल हुआ। |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType के स्ट्रिंग प्रस्तुतिकरण को उसके उदाहरण में कनवर्ट करता है. वापसी मान इंगित करता है कि रूपांतरण सफल हुआ या विफल. |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | निर्दिष्ट करता है कि सभी उपलब्ध सिम्बोलोजी के साथ डेटा की जाँच की जाएगी |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ऑस्ट्रेलियन पोस्ट डोमेस्टिक ई-पार्सल बारकोड** बारकोड विनिर्देश |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ऑस्ट्रेलिया पोस्ट** बारकोड विनिर्देश |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एज़्टेक** बारकोड विनिर्देश |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोडाबार** बारकोड विनिर्देश |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोडब्लॉक एफ** बारकोड विनिर्देश |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोड 11** बारकोड विनिर्देश |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोड 128** बारकोड विनिर्देश |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोड 16 के** बारकोड विनिर्देश |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कोड32** रिक्त विनिर्देश |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **विस्तारित कोड 39** बारकोड विनिर्देश |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **मानक कोड 39** बारकोड विनिर्देश |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **विस्तारित कोड 93** बारकोड विनिर्देश |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **मानक कोड 93** बारकोड विनिर्देश |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **कॉम्पैक्ट पीडीएफ 417** (Pdf417काट-छाँट) बारकोड विनिर्देश |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 डाटाबार का विस्तार हुआ** बारकोड विनिर्देश |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 डेटाबार विस्तारित स्टैक्ड** बारकोड विनिर्देश |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 डाटाबार लिमिटेड** बारकोड विनिर्देश |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **GS1 डाटाबार सर्वदिशात्मक** बारकोड विनिर्देश |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 डाटाबार स्टैक्ड** बारकोड विनिर्देश |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 डाटाबार स्टैक्ड सर्वदिशात्मक** बारकोड विनिर्देश |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **GS1 डाटाबार छोटा किया गया** बारकोड विनिर्देश |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **डेटालॉजिक 5 में से 2** रिक्त विनिर्देश |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **डेटा मैट्रिक्स** बारकोड सहजीवन |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **DeutschePost पहचान कोड** बारकोड विनिर्देश |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **DeutschePost Leit कोड** बारकोड विनिर्देश |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **डॉटकोड** रिक्त विनिर्देश |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **डॉटकोड** रिक्त विनिर्देश |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ईएएन-13** बारकोड विनिर्देश |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ईएएन14** बारकोड विनिर्देश |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ईएएन-8** बारकोड विनिर्देश |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 कोड 128** बारकोड विनिर्देश |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1डाटामैट्रिक्स** बारकोड सहजीवन |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **GS1 डॉटकोड** रिक्त विनिर्देश |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **जीएस1 क्यूआर** बारकोड विनिर्देश |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी एलआईसी एज़्टेक** रिक्त विनिर्देश |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी पीएएस एज़्टेक** रिक्त विनिर्देश |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी एलआईसी कोड 128** रिक्त विनिर्देश |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी पीएएस कोड128** रिक्त विनिर्देश |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी एलआईसी कोड39** रिक्त विनिर्देश |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी पीएएस कोड39** रिक्त विनिर्देश |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी एलआईसी डेटामैट्रिक्स** रिक्त विनिर्देश |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी पीएएस डेटामैट्रिक्स** रिक्त विनिर्देश |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी एलआईसी क्यूआर** रिक्त विनिर्देश |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एचआईबीसी पास क्यूआर** रिक्त विनिर्देश |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईएटीए 2 का 5**बारकोड विनिर्देश। IATA (इंटरनेशनल एयर ट्रांसपोर्ट एसोसिएशन) एयर कार्गो के प्रबंधन के लिए इस बारकोड का उपयोग करता है। |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **इंटरलीव्ड 2 ऑफ 5** बारकोड विनिर्देश |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईएसबीएन** बारकोड विनिर्देश |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईएसएमएन** बारकोड विनिर्देश |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईएसएसएन** बारकोड विनिर्देश |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **इतालवी पोस्ट 25** बारकोड विनिर्देश |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईटीएफ 14** बारकोड विनिर्देश |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **आईटीएफ6** बारकोड विनिर्देश |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **मैक्रोपीडीएफ417** बारकोड विनिर्देश |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **रॉयल मेल मेलमार्क** बारकोड विशिष्टता. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **5 का मैट्रिक्स 2** बारकोड विनिर्देश |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **मैक्सीकोड** बारकोड विनिर्देश |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एमआईसीआर ई-13बी** रिक्त विनिर्देश |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **माइक्रोपीडीएफ417** बारकोड विनिर्देश |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **माइक्रोक्यूआर कोड** बारकोड विनिर्देश |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | निर्दिष्ट करता है कि डेटा को सबसे अधिक उपयोग किए जाने वाले प्रतीकों के साथ जांचा जाएगा |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एमएसआई प्लेसी** बारकोड विनिर्देश |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | अनिर्दिष्ट डिकोड प्रकार। |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | निर्दिष्ट करता है कि डेटा को यूएसपीएस के साथ डिकोड किया जाना चाहिए **वनकोड** बारकोड विनिर्देश |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ओपीसी** बारकोड विनिर्देश |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **पैच कोड** बारकोड विनिर्देश। स्वचालित स्कैनिंग के लिए बारकोड सहजीवन का उपयोग किया जाता है |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **पीडीएफ417** बारकोड सहजीवन |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **फार्माकोड** बारकोड। इस सहजीवन को फार्मास्युटिकल बाइनरी कोड के रूप में भी जाना जाता है |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **ग्रह** बारकोड विनिर्देश |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | निर्दिष्ट करता है कि डेटा सभी के साथ चेक किया जाएगा **1.5डी डाक** बारकोड सहजीवन, जैसे **प्लैनेट, पोस्टनेट, ऑस्ट्रेलियापोस्ट, वनकोड, RM4SCC, डचकिक्स** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **पोस्टनेट** बारकोड विनिर्देश |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **पीजेडएन** बारकोड विनिर्देश। इस सहजीवन को Pharma Zentral Nummer के नाम से भी जाना जाता है |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **क्यू आर संहिता** बारकोड विनिर्देश |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **RM4SCC** बारकोड विनिर्देश। RM4SCC (रॉयल मेल 4-राज्य ग्राहक कोड) का उपयोग यूके में स्वचालित मेल सॉर्ट प्रक्रिया के लिए किया जाता है। |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एससीसी14** बारकोड विनिर्देश |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **एसएससीसी18** बारकोड विनिर्देश |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **मानक 2 का 5** बारकोड विनिर्देश |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **पूरक (EAN2, EAN5)** बारकोड विनिर्देश |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **स्विस पोस्ट पार्सल बारकोड** बारकोड विनिर्देश |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | निर्दिष्ट करता है कि डेटा सभी के साथ चेक किया जाएगा **-1 डी** बारकोड प्रतीकों |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | निर्दिष्ट करता है कि डेटा सभी के साथ चेक किया जाएगा **2डी** बारकोड प्रतीकों |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **यूपीसी-ए** बारकोड विनिर्देश |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **यूपीसी-ई** बारकोड विनिर्देश |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | निर्दिष्ट करता है कि डेटा को डीकोड किया जाना चाहिए **विन** (वाहन पहचान संख्या) बारकोड विनिर्देश |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
