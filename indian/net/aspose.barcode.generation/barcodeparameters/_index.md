---
title: BarcodeParameters
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: बरकड जनरेशन पैरमटर.
type: docs
weight: 710
url: /hi/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

बारकोड जनरेशन पैरामीटर.

```csharp
public class BarcodeParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | ऑस्ट्रेलियनपोस्ट बारकोड पैरामीटर। |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | एज़्टेक पैरामीटर। |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | बार्स का रंग. डिफ़ॉल्ट मान: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | में 1डी बारकोड बारकोड की ऊंचाई[`Unit`](../unit/) value. अगर नज़रअंदाज़ किया गयाAutoSizeMode गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | बार रिडक्शन वैल्यू प्राप्त करें या सेट करें जिसका उपयोग प्रिंटिंग के दौरान स्याही के फैलाव की भरपाई के लिए किया जाता है। डिफ़ॉल्ट मान: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | हमेशा कोड128 और जीएस1कोड128 बारकोड के लिए मानव पठनीय पाठ में चेकसम अंक प्रदर्शित करें। |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | कोडाबार पैरामीटर। |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | कोडब्लॉक पैरामीटर। |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | कोड 16K पैरामीटर। |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | कोड टेक्स्ट पैरामीटर. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. के लिए प्रयुक्त |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | डाटाबार पैरामीटर। |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | डेटामैट्रिक्स पैरामीटर। |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | डॉटकोड पैरामीटर. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape/) { get; set; } | इंगित करता है कि क्या वर्ण "\" को CodeText गुण में एस्केप वर्ण के रूप में समझाता है। Pdf417, DataMatrix, Code128 only के लिए उपयोग किया जाता है यदि EnableEscape सही है, तो "\" को एक विशेष एस्केप कैरेक्टर के रूप में समझाया जाएगा। अन्यथा, "\" सामान्य वर्णों के रूप में कार्य करता है। Aspose.BarCode ASCII नियंत्रण-कोड वर्णों के लिए दशमलव ascii कोड और स्मरक इनपुट करने का समर्थन करता है। उदाहरण के लिए, \013 और \\CR का मतलब CR है। |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि क्या बार भरे हुए हैं। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: सत्य। |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | जीएस1 समग्र बार पैरामीटर। |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | जनरेशन 1D बारकोड के दौरान चेकसम सक्षम करें। |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | आईटीएफ पैरामीटर। |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | मैक्सीकोड पैरामीटर. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | बारकोड पैडिंग. डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | पैचकोड पैरामीटर. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 पैरामीटर. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | डाक पैरामीटर। पोस्टनेट, प्लैनेट के लिए प्रयुक्त. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR पैरामीटर. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | पूरक पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. के लिए प्रयुक्त |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान सही पर सेट है - अपवाद फेंक दिया जाएगा। अन्यथा कोडटेक्स्ट को बारकोड के विनिर्देश से मिलान करने के लिए सही किया जाएगा। . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | चौड़े बार से संकीर्ण बार का अनुपात। डिफ़ॉल्ट मान: 3, यानी, चौड़े बार संकीर्ण बार की तुलना में 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost के लिए उपयोग किया जाता है , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-आयाम बारकोड बार या रिक्त स्थान की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरे बारकोड छवि की चौड़ाई बढ़ जाएगी। पर ध्यान न दिया जाएAutoSizeMode गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
