---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "DataMatrix पैरामीटर।"
type: docs
weight: 32
url: /hi/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix पैरामीटर।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग प्राप्त करता है। |
| [getEccType()](#getEccType--) | Datamatrix ECC प्रकार प्राप्त करता है। |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix बारकोड का एन्कोड मोड। |
| [getMacroCharacters()](#getMacroCharacters--) | विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix बारकोड के संरचित जोड़ मोड के लिए बारकोड ID। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। |
| [getVersion()](#getVersion--) | Datamatrix प्रतीक का आकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग सेट करता है। |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC प्रकार सेट करता है। |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix बारकोड का एन्कोड मोड। |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix बारकोड के संरचित जोड़ मोड के लिए बारकोड ID। |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix प्रतीक का आकार सेट करता है। |
| [toString()](#toString--) | इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग प्राप्त करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Returns:**
int - ECI एन्कोडिंग।
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200।

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल DataMatrixEccType.Ecc200 या DataMatrixEccType.EccAuto के साथ उपयोग किया जा सकता है। EncodeTypes.GS1DataMatrix के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड आईडी। डिफ़ॉल्ट मान: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। डिफ़ॉल्ट मान: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Datamatrix प्रतीक का आकार प्राप्त करता है। डिफ़ॉल्ट मान: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false

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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग सेट करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | ECI एन्कोडिंग। |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | एक Datamatrix ECC प्रकार। |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल DataMatrixEccType.Ecc200 या DataMatrixEccType.EccAuto के साथ उपयोग किया जा सकता है। EncodeTypes.GS1DataMatrix के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacters.None.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड आईडी। डिफ़ॉल्ट मान: 0

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। डिफ़ॉल्ट मान: 0

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix प्रतीक का आकार सेट करता है। डिफ़ॉल्ट मान: Version.Auto.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | एक Datamatrix प्रतीक आकार। |

### toString() {#toString--}
```
public String toString()
```


इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) को दर्शाती है।
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

