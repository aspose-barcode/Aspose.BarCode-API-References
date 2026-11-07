---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings class"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings class. QualitySettings आपको पहचान की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxQuality के साथ जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। C++ में QualitySettings का डिफ़ॉल्ट मान NormalQuality है।"
type: docs
weight: 3100
url: /hi/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। यह मोड गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए उपयोग किया जा सकता है। |
| [get_BarcodeQuality](./get_barcodequality/)() const | वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्वों को पहचानने के लिए अधिक कठिन विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है। |
| [get_ComplexBackground](./get_complexbackground/)() const | वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [get_Deconvolution](./get_deconvolution/)() const | Deconvolution (इमेज रिस्टोरेशन) मोड जो छवि क्षय के स्तर को परिभाषित करता है। मूल रूप से डिकॉन्भोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे शार्प या गणितीय मोर्फ़ोलॉजी की जाँच करनी पड़ती है। |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं। |
| static [get_HighQuality](./get_highquality/)() | HighQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। यह अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है। |
| [get_InverseImage](./get_inverseimage/)() const | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड्स को पहचानने के लिए विकसित किया गया है, यहाँ तक कि गलत बारकोड्स को भी। |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में। |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality पहचान गुणवत्ता प्रीसेट। अधिकांश बारकोड्स के लिए उपयुक्त। |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) सेट करता है: मैट्रिक्स सेल या बार। |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। यह मोड गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए उपयोग किया जा सकता है। |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्वों को पहचानने के लिए अधिक कठिन विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है। |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Deconvolution (इमेज रिस्टोरेशन) मोड जो छवि क्षय के स्तर को परिभाषित करता है। मूल रूप से डिकॉन्भोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे शार्प या गणितीय मोर्फ़ोलॉजी की जाँच करनी पड़ती है। |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में। |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) सेट करता है: मैट्रिक्स सेल या बार। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे [QualitySettings](./) को [BarCodeReader](../barcodereader/) के साथ उपयोग किया जाए।
```cpp
[C#]
//HighPerformance पहचान मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality पहचान मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//छोटे आकार के बारकोड्स के लिए HighPerformance पहचान मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//कम गुणवत्ता वाले बारकोड्स के लिए HighPerformance पहचान मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
