---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "बैकएंड बारकोड इमेज जनरेशन के लिए BarcodeGenerator."
type: docs
weight: 13
url: /hi/java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

बैकएंड बारकोड इमेज जनरेशन के लिए BarcodeGenerator.

समर्थित सिम्बोलॉजीज़: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator का एक उदाहरण बनाता है। |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator का एक उदाहरण बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [dispose()](#dispose--) | उपयोग में ली जा रही किसी भी संसाधन को साफ़ करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | निर्दिष्ट xml-स्ट्रीम में BarCode गुण निर्यात करता है |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है |
| [generateBarCodeImage()](#generateBarCodeImage--) | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। |
| [getBarcodeType()](#getBarcodeType--) | बारकोड सिम्बोलॉजी प्रकार। |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | एन्कोड करने के लिए पाठ। |
| [getParameters()](#getParameters--) | जनरेशन पैरामीटर। |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | निर्दिष्ट xml-stream से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है। |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | निर्दिष्ट xml-file से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | बारकोड छवि को विशिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजें। |
| [save(String filename)](#save-java.lang.String-) | बारकोड छवि को विशिष्ट फ़ाइल में सहेजें। |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | बारकोड छवि को विशिष्ट फ़ाइल में विशिष्ट फ़ॉर्मेट में सहेजें। |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | बारकोड सिम्बोलॉजी प्रकार। |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | codetext को बाइट्स की श्रृंखला के रूप में सेट करें। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | बारकोड सिम्बोलॉजी प्रकार। सिम्बोलॉजी सेट करने के लिए EncodeTypes क्लास का उपयोग करें। |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator का एक उदाहरण बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | बारकोड सिम्बोलॉजी प्रकार। सिम्बोलॉजी सेट करने के लिए EncodeTypes क्लास का उपयोग करें। |
| codeText | java.lang.String | एन्कोड करने के लिए पाठ। |

### dispose() {#dispose--}
```
public void dispose()
```


उपयोग में ली जा रही किसी भी संसाधन को साफ़ करें।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


निर्दिष्ट xml-स्ट्रीम में BarCode गुण निर्यात करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xml | java.io.OutputStream | यह xml-stream |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं। सफलता की स्थिति में **True** लौटाता है; अन्यथा **False**।
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlFile | java.lang.String | फ़ाइल का नाम |

**Returns:**
boolean - क्या निर्यात सफलतापूर्वक पूरा हुआ या नहीं।

सफलता की स्थिति में  **True**  लौटाता है;  **False**  अन्यथा।
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें।

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          BufferedImage image = generator.generateBarCodeImage();
>          ImageIO.write(image, "png",outputFile);
> ```

**Returns:**
java.awt.image.BufferedImage - बारकोड छवि। देखें Bitmap।
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


जनरेशन पैरामीटर।

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


निर्दिष्ट xml-stream से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xml | java.io.InputStream | यह xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


निर्दिष्ट xml-file से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


बारकोड छवि को विशिष्ट फ़ॉर्मेट में स्ट्रीम पर सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | आउटपुट OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | आउटपुट छवि के फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


बारकोड छवि को विशिष्ट फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


बारकोड छवि को विशिष्ट फ़ाइल में विशिष्ट फ़ॉर्मेट में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | आउटपुट छवि के फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


बारकोड सिम्बोलॉजी प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


codetext को बाइट्स की श्रृंखला के रूप में सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeBytes | byte[] | codetext के बाइट्स |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


एन्कोड करने के लिए पाठ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Unicode **codeText** को निर्दिष्ट **encoding** का उपयोग करके बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसका समर्थन करती है, तो फ़ंक्शन स्वचालित रूप से एक [byte order mark (BOM)][byte order mark _BOM] सम्मिलित करता है।

यह फ़ंक्शन केवल 2D बारकोड (जैसे, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके Unicode पाठ को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, Unicode डेटा के लिए [ECI][] एन्कोडिंग की सिफारिश की जाती है।

इस फ़ंक्शन को 1D बारकोड, GS1-अनुपालन बारकोड (जिसमें 2D शामिल है), या HIBC बारकोड (जिसमें 2D शामिल है) के साथ उपयोग करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और अप्रत्याशित परिणाम दे सकता है।

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
>  	Charset charset = Charset.forName("Shift_JIS");
>  	gen.setCodeText("\u8eca\u7a2e\u540d", charset);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(charset));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | java.lang.String | CodeText स्ट्रिंग |
| encoding | java.nio.charset.Charset | लागू किया गया एन्कोडिंग |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Unicode **codeText** को निर्दिष्ट **encoding** का उपयोग करके बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसका समर्थन करती है और **insertBOM** को true पर सेट किया गया है, तो फ़ंक्शन एक [byte order mark (BOM)][byte order mark _BOM] शामिल करता है।

यह फ़ंक्शन केवल 2D बारकोड (जैसे, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके Unicode पाठ को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, Unicode डेटा के लिए [ECI][] एन्कोडिंग की सिफारिश की जाती है।

इस फ़ंक्शन को 1D बारकोड, GS1-अनुपालन बारकोड (जिसमें 2D शामिल है), या HIBC बारकोड (जिसमें 2D शामिल है) के साथ उपयोग करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और अप्रत्याशित परिणाम दे सकता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | java.lang.String | CodeText स्ट्रिंग |
| encoding | java.nio.charset.Charset | लागू किया गया एन्कोडिंग |
| insertBOM | boolean | जब निर्दिष्ट एन्कोडिंग इसका समर्थन करती है (जैसे, UTF-8, UTF-16, UTF-32) तो बाइट ऑर्डर मार्क (BOM) सम्मिलित करने का संकेत देता है। यदि true पर सेट किया गया है, तो BOM जोड़ा जाता है; यदि false पर सेट है, तो एन्कोडिंग सामान्यतः BOM का उपयोग करती हो भी, इसे छोड़ा जाता है। |

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
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

