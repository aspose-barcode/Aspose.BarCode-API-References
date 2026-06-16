---
title: BarcodeGenerator
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: बैकएंड बारकोड छवियों के निर्माण के लिए BarcodeGenerator।
type: docs
weight: 13
url: /hi/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

बैकएंड बारकोड छवियों के निर्माण के लिए BarcodeGenerator।

समर्थित सिम्बोलॉजीज़: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator का एक उदाहरण बनाता है। |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator का एक उदाहरण बनाता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [dispose()](#dispose--) | उपयोग में मौजूद किसी भी संसाधन को साफ़ करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | BarCode गुणों को निर्दिष्ट xml-स्ट्रीम में निर्यात करता है |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | BarCode गुणों को निर्दिष्ट xml-फ़ाइल में निर्यात करता है |
| [generateBarCodeImage()](#generateBarCodeImage--) | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। |
| [getBarcodeType()](#getBarcodeType--) | बारकोड सिम्बोलॉजी प्रकार। |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | एन्कोड करने के लिए पाठ। |
| [getParameters()](#getParameters--) | उत्पादन पैरामीटर। |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | निर्दिष्ट xml-स्ट्रीम से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है। |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | निर्दिष्ट xml-फ़ाइल से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | BarCodeImage को विशिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजें। |
| [save(String filename)](#save-java.lang.String-) | बारकोड छवि को विशिष्ट फ़ाइल में सहेजें। |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | बारकोड छवि को विशिष्ट फ़ॉर्मेट में विशिष्ट फ़ाइल में सहेजें। |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | बारकोड सिम्बोलॉजी प्रकार। |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करें। |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | एन्कोड करने के लिए पाठ। |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) |  |
| [setCodeText(String codeText, Charset encoding, boolean insertBOM)](#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


BarcodeGenerator का एक उदाहरण बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | बारकोड सिम्बोलॉजी प्रकार। EncodeTypes क्लास का उपयोग करके सिम्बोलॉजी सेट करें। |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator का एक उदाहरण बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | बारकोड सिम्बोलॉजी प्रकार। EncodeTypes क्लास का उपयोग करके सिम्बोलॉजी सेट करें। |
| codeText | java.lang.String | एन्कोड करने के लिए पाठ। |

### dispose() {#dispose--}
```
public void dispose()
```


उपयोग में मौजूद किसी भी संसाधन को साफ़ करें।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


BarCode गुणों को निर्दिष्ट xml-स्ट्रीम में निर्यात करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xml | java.io.OutputStream | यह xml-stream |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं। सफलता के मामले में **True** लौटाता है; अन्यथा **False**
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


BarCode गुणों को निर्दिष्ट xml-फ़ाइल में निर्यात करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlFile | java.lang.String | फ़ाइल का नाम |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं।

सफलता की स्थिति में **True** लौटाता है; अन्यथा **False**।
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें।

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          OutputStream os = new FileOutputStream(outputFile);
>          Bitmap generatedBitmap = generator.generateBarCodeImage();
>          generatedBitmap.compress(Bitmap.CompressFormat.PNG, 100, os);
>          os.flush();
>          os.close();
> ```

**Returns:**
android.graphics.Bitmap - बारकोड छवि। देखें Bitmap।
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड सिम्बोलॉजी प्रकार।

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


एन्कोड करने के लिए पाठ।

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


उत्पादन पैरामीटर।

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


निर्दिष्ट xml-स्ट्रीम से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xml | java.io.InputStream | यह xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


निर्दिष्ट xml-फ़ाइल से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xmlFile | java.lang.String | फ़ाइल का नाम |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


BarCodeImage को विशिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


बारकोड छवि को विशिष्ट फ़ाइल में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


बारकोड छवि को विशिष्ट फ़ॉर्मेट में विशिष्ट फ़ाइल में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | आउटपुट छवि के फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


बारकोड सिम्बोलॉजी प्रकार।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| codeBytes | byte[] | कोडटेक्स्ट के बाइट्स |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


एन्कोड करने के लिए पाठ।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


निर्दिष्ट **encoding** का उपयोग करके यूनिकोड **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करती है, तो फ़ंक्शन स्वचालित रूप से एक  [byte order mark (BOM)][byte order mark _BOM] सम्मिलित करता है।

यह फ़ंक्शन केवल 2D बारकोड (जैसे, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके यूनिकोड टेक्स्ट को मैन्युअल रूप से एन्कोड करने की अनुमति देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, यूनिकोड डेटा के लिए  [ECI][] एन्कोडिंग की सिफारिश की जाती है।

इस फ़ंक्शन का उपयोग 1D बारकोड, GS1‑अनुपालन बारकोड (जिसमें 2D शामिल है), या HIBC बारकोड (जिसमें 2D शामिल है) के साथ करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम उत्पन्न हो सकते हैं।

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` setting Unicode-encoded text for 2D barcodes using different encodings:
>   
>   //Encode QR Code text using UTF-8 with BOM
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8;
>   gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode DataMatrix text using Shift-JIS (Japanese encoding)
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| codeText | java.lang.String | CodeText स्ट्रिंग |
| एन्कोडिंग | java.nio.charset.Charset | लागू एन्कोडिंग |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


निर्दिष्ट **encoding** का उपयोग करके यूनिकोड **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करती है और **insertBOM** को true पर सेट किया गया है, तो फ़ंक्शन एक  [byte order mark (BOM)][byte order mark _BOM] शामिल करता है।

यह फ़ंक्शन केवल 2D बारकोड (जैसे, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके यूनिकोड टेक्स्ट को मैन्युअल रूप से एन्कोड करने की अनुमति देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, यूनिकोड डेटा के लिए  [ECI][] एन्कोडिंग की सिफारिश की जाती है।

इस फ़ंक्शन का उपयोग 1D बारकोड, GS1‑अनुपालन बारकोड (जिसमें 2D शामिल है), या HIBC बारकोड (जिसमें 2D शामिल है) के साथ करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम उत्पन्न हो सकते हैं।

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` with or without a BOM for 2D barcodes.
>   
>  	//Encode codetext using UTF-8 with BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, true);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode codetext using UTF-8 without BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, false);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| codeText | java.lang.String | CodeText स्ट्रिंग |
| एन्कोडिंग | java.nio.charset.Charset | लागू एन्कोडिंग |
| insertBOM | boolean | निर्दिष्ट एन्कोडिंग के समर्थन में होने पर बाइट ऑर्डर मार्क (BOM) सम्मिलित करने का संकेत देता है (जैसे, UTF-8, UTF-16, UTF-32)। यदि true पर सेट किया जाता है, तो BOM जोड़ा जाता है; यदि false पर सेट किया जाता है, तो BOM को छोड़ा जाता है भले ही एन्कोडिंग सामान्यतः इसका उपयोग करती हो। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

