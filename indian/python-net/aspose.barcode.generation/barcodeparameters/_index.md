---
title: "BarcodeParameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

बारकोड जनरेशन पैरामीटर।

BarcodeParameters प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| x_dimension | x-dimension बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है।<br/>            इसे बढ़ाने से पूरी बारकोड छवि की चौड़ाई बढ़ेगी।<br/>            यदि [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया है तो इसे अनदेखा किया जाएगा। |
| bar_height | 1D बारकोड के बार की ऊँचाई [Unit](/barcode/python-net/aspose.barcode.generation/unit/) मान में।<br/>            यदि [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) प्रॉपर्टी को AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट किया गया है तो इसे अनदेखा किया जाएगा। |
| bar_color | बारों का रंग।<br/>            डिफ़ॉल्ट मान: Color.Black. |
| padding | बारकोड पैडिंग।<br/>            डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Code128 और GS1Code128 बारकोड के मानव-पठनीय टेक्स्ट में हमेशा चेकसम अंक प्रदर्शित करें। |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | केवल 1D बारकोड के लिए।<br/>            यदि कोडटेक्स्ट गलत है और मान true पर सेट है - अपवाद फेंका जाएगा। अन्यथा कोडटेक्स्ट को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा।<br/>            अपवाद हमेशा फेंका जाएगा: Databar सिंबोलॉजी के लिए यदि कोडटेक्स्ट गलत है।<br/>            अपवाद कभी नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिंबोलॉजी के लिए यदि कोडटेक्स्ट गलत है। |
| wide_narrow_ratio | वाइड बार और नॉर्‍ड बार का अनुपात।<br/>            डिफ़ॉल्ट मान: 3, अर्थात्, वाइड बार नॉर्‍ड बार से 3 गुना चौड़े होते हैं।<br/>            उपयोग किया जाता है: ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Codetext पैरामीटर। |
| filled_bars | बार भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है।<br/>            केवल 1D बारकोड के लिए।<br/>            डिफ़ॉल्ट मान: true. |
| bar_width_reduction | प्रिंटिंग के दौरान इंक फैलाव की भरपाई के लिए उपयोग किया जाने वाला बार चौड़ाई कमी मान प्राप्त या सेट करता है।<br/>            डिफ़ॉल्ट मान: 0 |
| postal | डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है। |
| patch_code | पैचकोड पैरामीटर। |
| australian_post | AustralianPost बारकोड पैरामीटर। |
| data_bar | Databar पैरामीटर। |
| gs1_composite_bar | GS1 Composite Bar पैरामीटर। |
| codablock | Codablock पैरामीटर। |
| data_matrix | DataMatrix पैरामीटर। |
| code_16k | Code16K पैरामीटर। |
| dot_code | DotCode पैरामीटर। |
| itf | ITF पैरामीटर। |
| pdf417 | PDF417 पैरामीटर। |
| qr | QR, MicroQR और RectMicroQR पैरामीटर। |
| पूरक | पूरक पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है। |
| maxi_code | मैक्सीकोड पैरामीटर। |
| aztec | Aztec पैरामीटर। |
| code128 | Code128 पैरामीटर। |
| codabar | Codabar पैरामीटर। |
| कूपन | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है। |
| han_xin | HanXin पैरामीटर। |
| gs1 | GS1 पैरामीटर। |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

