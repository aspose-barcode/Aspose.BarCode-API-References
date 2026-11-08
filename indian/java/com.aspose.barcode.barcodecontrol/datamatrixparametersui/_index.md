---
title: "DataMatrixParametersUI"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "UI रैपर for com.aspose.barcode.generation.DataMatrixParameters क्लास."
type: docs
weight: 14
url: /hi/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

UI रैपर for com.aspose.barcode.generation.DataMatrixParameters क्लास.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग प्राप्त करता है। |
| [getEccType()](#getEccType--) | Datamatrix ECC प्रकार प्राप्त करता है। |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix बारकोड का एन्कोड मोड। |
| [getMacroCharacters()](#getMacroCharacters--) | पहले स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200)। |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Structured Append मोड के लिए बारकोड ID। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Structured Append मोड के लिए बारकोड की संख्या। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Structured Append मोड के लिए फ़ाइल ID। |
| [getVersion()](#getVersion--) | DataMatrix प्रतीक का आकार। |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग सेट करता है। |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC प्रकार सेट करता है। |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix बारकोड का एन्कोड मोड। |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | पहले स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200)। |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Structured Append मोड के लिए बारकोड ID। |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Structured Append मोड के लिए बारकोड की संख्या। |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Structured Append मोड के लिए फ़ाइल ID। |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | DataMatrix प्रतीक का आकार। |
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


ECI एन्कोडिंग प्राप्त करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है।

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


पहले स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200)।

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Structured Append मोड के लिए बारकोड ID।

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Structured Append मोड के लिए बारकोड की संख्या।

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Structured Append मोड के लिए फ़ाइल ID।

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


DataMatrix प्रतीक का आकार।

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग सेट करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है।

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


पहले स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Structured Append मोड के लिए बारकोड ID।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Structured Append मोड के लिए बारकोड की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Structured Append मोड के लिए फ़ाइल ID।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


DataMatrix प्रतीक का आकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

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

