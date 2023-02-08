---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: BarCode Windows Control अपने टूलबक्स पैनल पर जएं और Aspose.BarCode.dll जड़ें और आप BarcodeGeneratorControl प्रकट हते देखेंगे बस इसे खंचें और अपने वंडज़ फर्म पर छड़ दें देखें देखें
type: docs
weight: 1320
url: /hi/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, अपने टूलबॉक्स पैनल पर जाएं और Aspose.BarCode.dll, जोड़ें और आप BarcodeGeneratorControl प्रकट होते देखेंगे। बस इसे खींचें और अपने विंडोज़ फॉर्म पर छोड़ दें। देखें देखें

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | उस मोड को प्राप्त या सेट करता है जिसके द्वारा बारकोड स्वचालित रूप से आकार बदलता है। डिफ़ॉल्ट मान AutoSizeMode.कोई नहीं है। |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | बारकोड छवि का पृष्ठभूमि रंग. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | बारकोड छवि ऊंचाई जब[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | बारकोड पैडिंग पैरामीटर प्राप्त या सेट करता है[`Padding`](../../aspose.barcode.generation/padding/) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | बारकोड का एनकोड प्रकार (सिम्बोलॉजी) . उपयोग करें[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) वर्तमान सहजीवन प्राप्त करने के लिए. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | बारकोड छवि चौड़ाई जब[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | बार्स का रंग। |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1डी बारकोड बारकोड की ऊंचाई. अगर नज़रअंदाज़ किया जाता है[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | बॉर्डर पैरामीटर प्राप्त या सेट करता है[`BorderParameters`](../../aspose.barcode.generation/borderparameters/) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | कैप्शन बारकोड छवि के ऊपर। देखना[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | कैप्शन बारकोड इमेज के नीचे। देखना[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | हमेशा कोड128 और जीएस1कोड128 बारकोड के लिए मानव पठनीय पाठ में चेकसम अंक प्रदर्शित करें। |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | डेटा एन्कोड किया जाना है, विभिन्न प्रकार के बारकोड में अलग-अलग कोडटेक्स्ट लंबाई प्रतिबंध हो सकते हैं। |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | कोडटेक्स्ट पैरामीटर प्राप्त या सेट करता है[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | इंगित करता है कि क्या वर्ण "\" को CodeText गुण में एस्केप वर्ण के रूप में समझाता है। Pdf417, DataMatrix, Code128 only के लिए उपयोग किया जाता है यदि EnableEscape सही है, तो "\" को एक विशेष एस्केप कैरेक्टर के रूप में समझाया जाएगा। अन्यथा, "\" सामान्य वर्णों के रूप में कार्य करता है। Aspose.BarCode ASCII नियंत्रण-कोड वर्णों के लिए दशमलव ascii कोड और स्मरक इनपुट करने का समर्थन करता है। उदाहरण के लिए, \013 और \\CR का मतलब CR है। |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | बारकोड का एनकोड प्रकार (सिम्बोलॉजी) . उपयोग करें[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) वर्तमान सहजीवन प्राप्त करने के लिए. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि क्या बार भरे हुए हैं। केवल 1D बारकोड के लिए। |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | जनरेशन 1D बारकोड के दौरान चेकसम सक्षम करें। |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | बारकोड छवि का रिज़ॉल्यूशन प्राप्त या सेट करता है. दोनों आयामों के लिए एक मान. डिफ़ॉल्ट मान: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | बारकोड छवि रोटेशन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ है कोई रोटेशन नहीं। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि को पढ़ने में कठिनाई बढ़ा सकता है। |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | विशिष्ट पैरामीटर |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान सही पर सेट है - अपवाद फेंक दिया जाएगा। अन्यथा कोडटेक्स्ट को बारकोड के विनिर्देश से मिलान करने के लिए सही किया जाएगा। . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | चौड़े बार से संकीर्ण बार का अनुपात। डिफ़ॉल्ट मान: 3, यानी, चौड़े बार संकीर्ण बार की तुलना में 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost के लिए उपयोग किया जाता है , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-आयाम बारकोड बार या रिक्त स्थान की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरे बारकोड छवि की चौड़ाई बढ़ जाएगी। पर ध्यान न दिया जाए[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) गुण AutoSizeMode.Nearest या AutoSizeMode.Interpolation. पर सेट है |

### यह सभी देखें

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* नाम स्थान [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
