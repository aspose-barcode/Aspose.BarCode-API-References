---
title: "Aspose::BarCode::Generation::BarcodeParameters class"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::BarcodeParameters class. C++ में बारकोड जनरेशन पैरामीटर।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


बारकोड निर्माण पैरामीटर।

```cpp
class BarcodeParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost बारकोड पैरामीटर। |
| [get_Aztec](./get_aztec/)() const | Aztec पैरामीटर। |
| [get_BarColor](./get_barcolor/)() const | बार्स का रंग। डिफ़ॉल्ट मान: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | 1D बारकोड की बार्स की ऊँचाई [Unit](../unit/) मान में। यदि [BaseGenerationParameters::AutoSizeMode](../) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया गया है तो इसे नजरअंदाज किया जाता है। |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | बार्स की कमी मान प्राप्त करें या सेट करें, जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। डिफ़ॉल्ट मान: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Code128 और GS1Code128 बारकोड के लिए मानव‑पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें। |
| [get_Codabar](./get_codabar/)() const | कोडबार पैरामीटर। |
| [get_Codablock](./get_codablock/)() const | कोडब्लॉक पैरामीटर। |
| [get_Code128](./get_code128/)() const | कोड128 पैरामीटर। |
| [get_Code16K](./get_code16k/)() const | कोड16K पैरामीटर। |
| [get_CodeTextParameters](./get_codetextparameters/)() const | कोडटेक्स्ट पैरामीटर। |
| [get_Coupon](./get_coupon/)() const | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है। |
| [get_DataBar](./get_databar/)() const | डेटाबार पैरामीटर। |
| [get_DataMatrix](./get_datamatrix/)() const | डेटा मैट्रिक्स पैरामीटर। |
| [get_DotCode](./get_dotcode/)() const | डॉटकोड पैरामीटर। |
| [get_FilledBars](./get_filledbars/)() const | बारों के भरे होने को दर्शाने वाला मान प्राप्त करता है। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true। |
| [get_GS1](./get_gs1/)() const | GS1 पैरामीटर। |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 कॉम्पोजिट बार पैरामीटर। |
| [get_HanXin](./get_hanxin/)() const | HanXin पैरामीटर। |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF पैरामीटर। |
| [get_MaxiCode](./get_maxicode/)() const | मैक्सीकोड पैरामीटर। |
| [get_Padding](./get_padding/)() const | बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt। |
| [get_PatchCode](./get_patchcode/)() const | पैचकोड पैरामीटर। |
| [get_Pdf417](./get_pdf417/)() const | PDF417 पैरामीटर। |
| [get_Postal](./get_postal/)() const | डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है। |
| [get_QR](./get_qr/)() const | QR, माइक्रोQR और RectMicroQR पैरामीटर। |
| [get_Supplement](./get_supplement/)() const | पूरक पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है। |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | केवल 1D बारकोड के लिए। यदि codetext गलत है और मान true सेट किया गया है - अपवाद फेंका जाएगा। अन्यथा codetext को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी के लिए यदि codetext गलत है। अपवाद हमेशा नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी के लिए यदि codetext गलत है। |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | वाइड बार से नॉर्‍ड बार का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात्, वाइड बार नॉर्‍ड बार से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है। |
| [get_XDimension](./get_xdimension/)() const | x-dimension यूनिट के [BarCode](../../aspose.barcode/) बार या स्पेस की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरे बारकोड छवि की चौड़ाई बढ़ेगी। यदि [BaseGenerationParameters::AutoSizeMode](../) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया गया है तो इसे अनदेखा किया जाएगा। |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | बार्स का रंग। डिफ़ॉल्ट मान: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | 1D बारकोड की बार्स की ऊँचाई [Unit](../unit/) मान में। यदि [BaseGenerationParameters::AutoSizeMode](../) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया गया है तो इसे नजरअंदाज किया जाता है। |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | बार्स की कमी मान प्राप्त करें या सेट करें, जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। डिफ़ॉल्ट मान: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Code128 और GS1Code128 बारकोड के लिए मानव‑पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें। |
| [set_FilledBars](./set_filledbars/)(bool) | बारों के भरे होने को दर्शाने वाला मान सेट करता है। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true। |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 कॉम्पोजिट बार पैरामीटर। |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | केवल 1D बारकोड के लिए। यदि codetext गलत है और मान true सेट किया गया है - अपवाद फेंका जाएगा। अन्यथा codetext को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी के लिए यदि codetext गलत है। अपवाद हमेशा नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी के लिए यदि codetext गलत है। |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | वाइड बार से नॉर्‍ड बार का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात्, वाइड बार नॉर्‍ड बार से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है। |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension यूनिट के [BarCode](../../aspose.barcode/) बार या स्पेस की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरे बारकोड छवि की चौड़ाई बढ़ेगी। यदि [BaseGenerationParameters::AutoSizeMode](../) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया गया है तो इसे अनदेखा किया जाएगा। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
