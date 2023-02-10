---
title: QualitySettings
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: गुणवत्त सेटंग्स मन्यत गुणवत्त और गत क मैन्युअल रूप से कन्फ़गर करने क अनुमत देत हैं आप एम्बेडेड प्रसेट द्वर गुणवत्त सेटंग्स क जल्द से सेट कर सकते हैं उच्च प्रदर्शन समन्य गुणवत्त उच्च गुणवत्त मैक्सबरकड य आप अलगअलग वकल्पं क मैन्युअल रूप से कन्फ़गर कर सकते हैं गुणवत्त सेटंग्स क डफ़ल्ट मन समन्य गुणवत्त है
type: docs
weight: 270
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

गुणवत्ता सेटिंग्स मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देती हैं। आप एम्बेडेड प्रीसेट द्वारा गुणवत्ता सेटिंग्स को जल्दी से सेट कर सकते हैं: उच्च प्रदर्शन, सामान्य गुणवत्ता, उच्च गुणवत्ता, मैक्सबारकोड या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। गुणवत्ता सेटिंग्स का डिफ़ॉल्ट मान सामान्य गुणवत्ता है।

```csharp
public sealed class QualitySettings
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | उच्च प्रदर्शन पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | उच्च गुणवत्ता पहचान गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। विकर्ण और अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है। |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | हाई क्वालिटी डिटेक्शन रिकग्निशन क्वालिटी प्रीसेट। सामान्य गुणवत्ता के समान लेकिन उच्च गुणवत्ता के साथ[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | MaxBarCodes पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहां तक कि गलत बारकोड को पहचानने के लिए विकसित किया गया है। |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | MaxQualityDetection पहचान गुणवत्ता प्रीसेट। सामान्य गुणवत्ता के समान लेकिन उच्चतम गुणवत्ता के साथ[`DetectorSettings`](./detectorsettings/) . विकर्ण और क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है। |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | सामान्य गुणवत्ता पहचान गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | इंजन को अतिरिक्त स्कैन के रूप में रंगीन पृष्ठभूमि पर रंगीन बारकोड को पहचानने की अनुमति देता है। बेहद धीमा मोड. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | डेटामैट्रिक्स के लिए इंजन को धराशायी औद्योगिक डेटामैट्रिक्स बारकोड को पहचानने की अनुमति देता है। धीमा मोड जो केवल धराशायी बारकोड के लिए मदद करता है जो स्पॉट से मिलकर बनता है। |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | इंजन को घटी हुई छवि को अतिरिक्त स्कैन के रूप में पहचानने की अनुमति देता है। घटाने के लिए आकार आंतरिक इंजन एल्गोरिदम द्वारा चुना गया है। मोड बारकोड को पहचानने में मदद करता है जो शोर और धुंधला है लेकिन उच्च रिज़ॉल्यूशन के साथ कैप्चर किया गया है। |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | इंजन को पहचानने की गति बढ़ाने के लिए स्कैन के बीच अंतराल का उपयोग करने की अनुमति देता है। मोड कम ऊंचाई वाले बारकोड के साथ पहचान की समस्या पैदा कर सकता है. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | इंजन को गलत चेकसम या गलत मान वाले बारकोड को पहचानने की अनुमति देता है। मोड का उपयोग गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए किया जा सकता है। |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | इंजन को उलटे रंग की छवि को अतिरिक्त स्कैन के रूप में पहचानने की अनुमति देता है। काली पृष्ठभूमि पर बारकोड सफेद होने पर मोड का उपयोग किया जा सकता है. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | इंजन को अतिरिक्त स्कैन के रूप में मीडियन स्मूथिंग को सक्षम करने की अनुमति देता है। मोड शोर वाले बारकोड को पहचानने में मदद करता है। |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | इंजन को डाक बारकोड के लिए थोड़ी शोर वाली छवियों को पहचानने की अनुमति देता है। मोड थोड़ा क्षतिग्रस्त डाक बारकोड को पहचानने में मदद करता है। |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | इंजन को 1डी बारकोड के लिए उच्च गुणवत्ता वाले बारकोड को तुरंत पहचानने की अनुमति देता है जो लगभग पूरी छवि भरते हैं। मोड इंटरनेट से उत्पन्न बारकोड को तुरंत पहचानने में मदद करता है। |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | इंजन को 1डी बारकोड के लिए पैटर्न में सिंगल वाइप/ग्लूड बार के साथ बारकोड को पहचानने की अनुमति देता है। |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | इंजन को QR/MicroQR के लिए क्षतिग्रस्त माइक्रोक्यूआर बारकोड को पहचानने की अनुमति देता है। |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | इंजन को मुख्य स्कैन के रूप में बिना किसी पुनर्स्थापना के नियमित छवि को पहचानने की अनुमति देता है। छवि को इस रूप में पहचानने का तरीका. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | इंजन को बारकोड को सॉल्ट और पेपर नॉइज़ टाइप के साथ पहचानने की अनुमति देता है। मोड सफेद और काले डॉट्स के साथ छोटे शोर को दूर कर सकता है। |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | इंजन को अतिरिक्त स्कैन के रूप में छोटे सफेद धब्बों के बिना छवि को पहचानने की अनुमति देता है। मोड नॉइज़ इमेज के साथ-साथ मेडियन स्मूथिंग फ़िल्टरिंग को पहचानने में मदद करता है। |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | इंजन को अधिक पहचान वेरिएंट की जांच करके चेकसम के साथ 1D बारकोड को पहचानने की अनुमति देता है। डिफ़ॉल्ट मान: असत्य. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | बारकोड डिटेक्टर सेटिंग. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | 1डी बारकोड के लिए इंजन को किसी भी समय लेने वाले एल्गोरिदम का उपयोग किए बिना छवि के मध्य भाग को जल्दी से पहचानने और परिणाम वापस करने की अनुमति देता है। |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | मीडियन स्मूथिंग के लिए विंडो का आकार। विशिष्ट मान 3 या 4 हैं। डिफ़ॉल्ट मान 3 है। AllowMedianSmoothing सेट होना चाहिए। |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | इंजन को बड़ी छवियों पर छोटे बारकोड को पहचानने की अनुमति देता है। अगर नजरअंदाज कर दिया[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/) ट्रू पर सेट है। डिफ़ॉल्ट मान: असत्य. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | पुराने बारकोड डिटेक्टर पर स्विच करता है। |

### उदाहरण

यह नमूना दिखाता है कि BarCodeReader के साथ QualitySettings का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // उच्च प्रदर्शन मोड सेट करें
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // सामान्य गुणवत्ता मोड डिफ़ॉल्ट रूप से सेट किया गया है
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // कम गति पहचान के साथ उच्च गुणवत्ता मोड सेट करें 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // अधिकतम बारकोड मोड सेट करें, जो सभी संभावित बारकोड खोजने का प्रयास करता है, यहां तक कि गलत भी। सबसे धीमी पहचान मोड
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // उच्च प्रदर्शन मोड सेट करें
   reader.QualitySettings = QualitySettings.HighPerformance;
   // अलग विकल्प सेट करें
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // डिफ़ॉल्ट मोड सामान्य गुणवत्ता है
   // अलग विकल्प सेट करें
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'उच्च प्रदर्शन मोड सेट करें
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'सामान्य गुणवत्ता मोड डिफ़ॉल्ट रूप से सेट होता है
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'निम्न गति पहचान के साथ उच्च गुणवत्ता मोड सेट करें
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'अधिकतम बारकोड मोड सेट करें, जो सभी संभावित बारकोड खोजने का प्रयास करता है, यहां तक कि गलत भी। सबसे धीमी पहचान मोड
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'उच्च प्रदर्शन मोड सेट करें
   reader.QualitySettings = QualitySettings.HighPerformance
   'अलग विकल्प सेट करें
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'डिफ़ॉल्ट मोड सामान्य गुणवत्ता है
   'अलग विकल्प सेट करें
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
