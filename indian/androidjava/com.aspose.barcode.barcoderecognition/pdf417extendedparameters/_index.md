---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Stores a MacroPdf417 metadata information of recognized barcode
type: docs
weight: 40
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Stores a MacroPdf417 metadata information of recognized barcode

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Pdf417ExtendedParameters मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 प्राप्तकर्ता नाम (वैकल्पिक)। |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 चेकसम (वैकल्पिक)। |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | बारकोड का फ़ाइल आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 फ़ाइल नाम (वैकल्पिक)। |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 फ़ाइल आकार (वैकल्पिक)। |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | बारकोड का सेगमेंट आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Macro PDF417 बारकोड सेगमेंट्स की संख्या प्राप्त करता है। |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 प्रेषक नाम (वैकल्पिक)। |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | यह दर्शाता है कि सेगमेंट Macro PDF417 फ़ाइल का अंतिम सेगमेंट है या नहीं। |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 टाइम स्टैंप (वैकल्पिक)। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isCode128Emulation()](#isCode128Emulation--) | फ़्लैग जो दर्शाता है कि MicroPdf417 बारकोड 908, 909, 910 या 911 कोड 128 अनुकरण कोडवर्ड्स के साथ एन्कोड किया गया है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [isLinked()](#isLinked--) | फ़्लैग जो दर्शाता है कि बारकोड को 1D बारकोड से लिंक किया जाना चाहिए। |
| [isReaderInitialization()](#isReaderInitialization--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस Pdf417ExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Pdf417ExtendedParameters मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 प्राप्तकर्ता नाम (वैकल्पिक)।

**Returns:**
java.lang.String - प्राप्तकर्ता नाम।
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 चेकसम (वैकल्पिक)।

**Returns:**
int - चेकसम।
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


बारकोड का फ़ाइल आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध।

मान: MacroPdf417 के लिए फ़ाइल आईडी

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 फ़ाइल नाम (वैकल्पिक)।

**Returns:**
java.lang.String - फ़ाइल नाम।
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 फ़ाइल आकार (वैकल्पिक)।

**Returns:**
int - फ़ाइल आकार।
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


बारकोड का सेगमेंट आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध।

मान: बारकोड का सेगमेंट आईडी।

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Macro PDF417 बारकोड सेगमेंट्स की संख्या प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: सेगमेंट्स की संख्या।

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 प्रेषक नाम (वैकल्पिक)।

**Returns:**
java.lang.String - प्रेषक नाम
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


यह दर्शाता है कि सेगमेंट Macro PDF417 फ़ाइल का अंतिम सेगमेंट है या नहीं।

**Returns:**
boolean - टर्मिनेटर।
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 टाइम स्टैंप (वैकल्पिक)।

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


फ़्लैग जो दर्शाता है कि MicroPdf417 बारकोड 908, 909, 910 या 911 कोड 128 अनुकरण कोडवर्ड्स के साथ एन्कोड किया गया है।

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं

मान: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो **true** लौटाता है; अन्यथा, **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


फ़्लैग जो दर्शाता है कि बारकोड को 1D बारकोड से लिंक किया जाना चाहिए।

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

Value: Reader initialization flag

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


इस Pdf417ExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

