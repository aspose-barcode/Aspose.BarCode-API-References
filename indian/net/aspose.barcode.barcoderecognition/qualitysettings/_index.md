---
title: "क्लास QualitySettings"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings क्लास। QualitySettings आपको मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट HighPerformance, NormalQuality, HighQuality, MaxQuality के साथ जल्दी से QualitySettings सेट कर सकते हैं या आप अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।"
type: docs
weight: 370
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings आपको मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स के साथ जल्दी से QualitySettings सेट कर सकते हैं: HighPerformance, NormalQuality, HighQuality, MaxQuality या आप अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

```csharp
public sealed class QualitySettings
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance मान्यता गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं। |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है। |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को भी पहचानने के लिए विकसित किया गया है। |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality मान्यता गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त है। |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। इस मोड का उपयोग गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए किया जा सकता है। |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | एक मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक जटिल विधियों की आवश्यकता होती है जो मान्यता को धीमा कर देती हैं। |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त मान्यता को सक्षम या अक्षम करने वाला मोड। |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Deconvolution (इमेज रिस्टोरेशन) मोड जो इमेज क्षय के स्तर को परिभाषित करता है। मूल रूप से डिकनवोल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) इमेज को पुनर्स्थापित कर सकता है। चूंकि हम उस इमेज फ़ंक्शन का पता नहीं लगा सकते जो इमेज को भ्रष्ट करता है, हमें शार्प या गणितीय मोर्फ़ोलॉजी जैसी सबसे ज्ञात फ़ंक्शनों की जाँच करनी पड़ती है। |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | उल्टे रंग (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त मान्यता को सक्षम या अक्षम करने वाला मोड। |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | UseMinimalXDimension के साथ उपयोग किया जाने वाला XDimension का न्यूनतम आकार पिक्सेल में। |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | मान्यता मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) सेट करता है: मैट्रिक्स सेल या बार। |

## उदाहरण

यह नमूना दिखाता है कि QualitySettings को BarCodeReader के साथ कैसे उपयोग किया जाए

```csharp
[C#]
//HighPerformance मान्यता मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality मान्यता मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//छोटे आकार के बारकोड के लिए HighPerformance मान्यता मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//कम गुणवत्ता वाले बारकोड के लिए HighPerformance मान्यता मोड सेट करें
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


