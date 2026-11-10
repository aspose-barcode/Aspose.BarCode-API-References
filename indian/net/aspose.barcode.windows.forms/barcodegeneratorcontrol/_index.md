---
title: "क्लास BarCodeGeneratorControl"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl क्लास। BarCode विंडोज कंट्रोल को अपने टूलबॉक्स पैनल में जाएँ और Aspose.BarCode.dll जोड़ें और आप BarcodeGeneratorControl को दिखाई देते हुए देखेंगे। बस इसे ड्रैग करके अपने विंडोज फ़ॉर्म में ड्रॉप करें। see  see"
type: docs
weight: 1800
url: /hi/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, अपने टूलबॉक्स पैनल पर जाएँ और Aspose.BarCode.dll जोड़ें, और आप देखेंगे कि BarcodeGeneratorControl दिखाई देता है। बस इसे ड्रैग करके अपने Windows फ़ॉर्म में ड्रॉप करें। देखें  देखें

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | बारकोड के स्वचालित री-साइज़ होने के मोड को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान है AutoSizeMode.None। |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | बारकोड छवि की पृष्ठभूमि रंग। |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode इमेज की ऊँचाई जब [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया जाता है। |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Barcode पैडिंग पैरामीटर्स [`Padding`](../../aspose.barcode.generation/padding/) को प्राप्त करता है या सेट करता है। |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | BarCode का एन्कोड प्रकार (सिम्बोलॉजी)। वर्तमान सिम्बोलॉजी प्राप्त करने के लिए [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) का उपयोग करें। |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode इमेज की चौड़ाई जब [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया जाता है। |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | बार्स का रंग। |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D बारकोड की बार की ऊँचाई। यदि [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया है तो इसे नज़रअंदाज़ किया जाता है। |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Border पैरामीटर्स [`BorderParameters`](../../aspose.barcode.generation/borderparameters/) को प्राप्त करता है या सेट करता है। |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | BarCode इमेज के ऊपर कैप्शन। देखें [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | BarCode इमेज के नीचे कैप्शन। देखें [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Code128 और GS1Code128 बारकोड के लिए मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ। |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | एन्कोड करने के लिए डेटा, विभिन्न प्रकार के BarCode में अलग-अलग CodeText लंबाई प्रतिबंध हो सकते हैं। |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | CodeText पैरामीटर्स [`CodetextParametersUI`](../codetextparametersui/) को प्राप्त करता है या सेट करता है। |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | BarCode का एन्कोड प्रकार (सिम्बोलॉजी)। वर्तमान सिम्बोलॉजी प्राप्त करने के लिए [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) का उपयोग करें। |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। केवल 1D बारकोड के लिए। |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें। |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | BarCode इमेज का रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi। |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode छवि घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | विशिष्ट पैरामीटर |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | केवल 1D बारकोड के लिए। यदि codetext गलत है और मान true पर सेट किया गया है - अपवाद फेंका जाएगा। अन्यथा codetext को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी यदि codetext गलत है। अपवाद कभी नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 सिम्बोलॉजी यदि codetext गलत है। |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | छवि को रेंडर करने के लिए एंटी-एलियासिंग मोड का उपयोग किया जाता है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | वाइड बार से नॅरो बार का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार नॅरो बार से 3 गुना चौड़े होते हैं। उपयोग किया जाता है: ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimension BarCode बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड छवि की चौड़ाई बढ़ेगी। इसे अनदेखा किया जाएगा यदि [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया हो। |

### और देखें

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


