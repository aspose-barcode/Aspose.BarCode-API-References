---
title: "क्लास BarcodeParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.BarcodeParameters क्लास। बारकोड जेनरेशन पैरामीटर"
type: docs
weight: 1010
url: /hi/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

बारकोड जनरेशन पैरामीटर।

```csharp
public class BarcodeParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | ऑस्ट्रेलियनपोस्ट बारकोड पैरामीटर। |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec पैरामीटर। |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | बार्स का रंग। डिफ़ॉल्ट मान: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | 1D बारकोड्स की बार्स की ऊँचाई [`Unit`](../unit/) मान में। यदि [`AutoSizeMode`](../basegenerationparameters/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया है तो इसे नजरअंदाज किया जाता है। |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | बार्स की कमी मान प्राप्त करता है या सेट करता है, जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। डिफ़ॉल्ट मान: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Code128 और GS1Code128 बारकोड के लिए मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ। |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar पैरामीटर। |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock पैरामीटर। |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128 पैरामीटर। |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K पैरामीटर। |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | कोडटेक्स्ट पैरामीटर। |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है। |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar पैरामीटर। |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix पैरामीटर। |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode पैरामीटर। |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। केवल 1D बारकोड्स के लिए। डिफ़ॉल्ट मान: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1 पैरामीटर। |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 कॉम्पोज़िट बार पैरामीटर। |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin पैरामीटर। |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | 1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें। |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF पैरामीटर। |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode पैरामीटर। |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode पैरामीटर। |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 पैरामीटर। |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postal पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है। |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR, MicroQR और RectMicroQR पैरामीटर। |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Supplement पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है। |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | केवल 1D बारकोड्स के लिए। यदि codetext गलत है और मान true पर सेट किया गया है - अपवाद फेंका जाएगा। अन्यथा codetext को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी के लिए यदि codetext गलत है। अपवाद हमेशा नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी के लिए यदि codetext गलत है। |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | वाइड बार से नॅरो बार का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार नॅरो बार से 3 गुना चौड़े होते हैं। उपयोग किया जाता है: ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड छवि की चौड़ाई बढ़ेगी। यदि [`AutoSizeMode`](../basegenerationparameters/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया है तो इसे नजरअंदाज किया जाता है। |

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


