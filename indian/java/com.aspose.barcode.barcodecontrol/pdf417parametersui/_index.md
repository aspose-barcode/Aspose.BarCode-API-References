---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "UI रैपर for com.aspose.barcode.generation.Pdf417Parameters क्लास."
type: docs
weight: 16
url: /hi/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

UI रैपर for com.aspose.barcode.generation.Pdf417Parameters क्लास.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | कॉलम की संख्या। |
| [getECIEncoding()](#getECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getEncodeMode()](#getEncodeMode--) | BarCode के एन्कोड मोड का Pdf417 सिम्बोलॉजी प्रकार। |
| [getErrorLevel()](#getErrorLevel--) | BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है, जो level0 से level8 तक होता है, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है। |
| [getMacroCharacters()](#getMacroCharacters--) | विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Macro Pdf417 बारकोड का फ़ाइल ID प्राप्त करता है। |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Macro Pdf417 बारकोड का सेगमेंट ID प्राप्त करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Macro Pdf417 बारकोड सेगमेंट की संख्या प्राप्त करता है। |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि क्या सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है। |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। |
| [getRows()](#getRows--) | पंक्तियों की संख्या। |
| [getTruncate()](#getTruncate--) | क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त है (स्थान कम करने के लिए)। |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड को एन्कोड करता है। दूसरा स्थान मोड 908 और 909 में FNC1 एन्कोड कर सकता है, साथ ही 910 और 911 एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है। |
| [isLinked()](#isLinked--) | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 मोड एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग एन्कोड करती हैं जो किसी जुड़े रैखिक घटक को दर्शाता है, जो EAN.UCC नहीं है। |
| [isReaderInitialization()](#isReaderInitialization--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड को एन्कोड करता है। दूसरा स्थान मोड 908 और 909 में FNC1 एन्कोड कर सकता है, साथ ही 910 और 911 एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है। |
| [setColumns(int value)](#setColumns-int-) | कॉलम की संख्या। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | BarCode के एन्कोड मोड का Pdf417 सिम्बोलॉजी प्रकार। |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार सेट करता है, जो level0 से level8 तक होता है, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है। |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 मोड एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग एन्कोड करती हैं जो किसी जुड़े रैखिक घटक को दर्शाता है, जो EAN.UCC नहीं है। |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Macro Pdf417 बारकोड का फ़ाइल ID सेट करता है। |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Macro Pdf417 बारकोड का सेगमेंट ID सेट करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | मैक्रो Pdf417 बारकोड सेगमेंट की गिनती सेट करता है। |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि क्या सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है। |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setRows(int value)](#setRows-int-) | पंक्तियों की संख्या। |
| [setTruncate(boolean value)](#setTruncate-boolean-) | क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त है (स्थान कम करने के लिए)। |
| [toString()](#toString--) | इस [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


कॉलम की संख्या।

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं होता। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है।

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


बारकोड के एन्कोड मोड का Pdf417 सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: Pdf417EncodeMode.Auto।

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है, जो level0 से level8 तक होता है, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है।

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


मैक्रो कैरेक्टर्स 05 और 06 मानों का उपयोग विशेष मोड्स में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड्स को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None।

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)।

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान रखता है। x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स पर लागू होता है।

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


मैक्रो Pdf417 बारकोड की फ़ाइल आईडी प्राप्त करता है। MacroPdf417 के लिए उपयोग किया जाता है।

**Returns:**
int - मैक्रो Pdf417 बारकोड की फ़ाइल आईडी।
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)।

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड संपूर्ण स्रोत फ़ाइल के बाइट्स में आकार रखता है।

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Macro Pdf417 बारकोड का सेगमेंट ID प्राप्त करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है।

**Returns:**
int - मैक्रो Pdf417 बारकोड का सेगमेंट आईडी, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है।
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Macro Pdf417 बारकोड सेगमेंट की संख्या प्राप्त करता है।

**Returns:**
int - मैक्रो Pdf417 बारकोड सेगमेंट की गिनती।
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)।

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल मैक्रो PDF417 के लिए लागू होता है।

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)।

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


पंक्तियों की संख्या।

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त है (स्थान कम करने के लिए)।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड को एन्कोड करता है। दूसरा स्थान मोड 908 और 909 में FNC1 एन्कोड कर सकता है, साथ ही 910 और 911 एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है।

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 मोड एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग एन्कोड करती हैं जो किसी जुड़े रैखिक घटक को दर्शाता है, जो EAN.UCC नहीं है।

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड को एन्कोड करता है। दूसरा स्थान मोड 908 और 909 में FNC1 एन्कोड कर सकता है, साथ ही 910 और 911 एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


कॉलम की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं होता। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


बारकोड के एन्कोड मोड का Pdf417 सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: Pdf417EncodeMode.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार सेट करता है, जो level0 से level8 तक होता है, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | बारकोड के एरर करेक्शन लेवल का Pdf417 सिम्बोलॉजी प्रकार, जो level0 से level8 तक होता है, level0 का अर्थ कोई एरर करेक्शन जानकारी नहीं, level8 का अर्थ सर्वोत्तम एरर करेक्शन जो बड़ी छवि देता है। |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 मोड एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग एन्कोड करती हैं जो किसी जुड़े रैखिक घटक को दर्शाता है, जो EAN.UCC नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


मैक्रो कैरेक्टर्स 05 और 06 मानों का उपयोग विशेष मोड्स में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड्स को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान रखता है। x^16 + x^12 + x^5 + 1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स पर लागू होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


मैक्रो Pdf417 बारकोड की फ़ाइल आईडी सेट करता है। MacroPdf417 के लिए उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | मैक्रो Pdf417 बारकोड की फ़ाइल आईडी। |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड संपूर्ण स्रोत फ़ाइल के बाइट्स में आकार रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Macro Pdf417 बारकोड का सेगमेंट ID सेट करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | मैक्रो Pdf417 बारकोड का सेगमेंट आईडी, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


मैक्रो Pdf417 बारकोड सेगमेंट की गिनती सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | मैक्रो Pdf417 बारकोड सेगमेंट की गिनती। |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल मैक्रो PDF417 के लिए लागू होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


पंक्तियों की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त है (स्थान कम करने के लिए)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```


इस [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) को दर्शाती है।
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

