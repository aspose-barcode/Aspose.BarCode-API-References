---
title: DataMatrixParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: DataMatrix पैरामीटर।
type: docs
weight: 34
url: /hi/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | स्तंभों की संख्या। |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Datamatrix ECC प्रकार प्राप्त करता है। |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Datamatrix बारकोड का एन्कोड मोड। |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Datamatrix प्रतीक आकार प्राप्त करता है। |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग प्राप्त करता है। |
| [getEccType()](#getEccType--) | Datamatrix ECC प्रकार प्राप्त करता है। |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix बारकोड का एन्कोड मोड। |
| [getMacroCharacters()](#getMacroCharacters--) | विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [getRows()](#getRows--) | पंक्तियों की संख्या। |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। |
| [getVersion()](#getVersion--) | Datamatrix प्रतीक आकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setColumns(int value)](#setColumns-int-) | स्तंभों की संख्या। |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC प्रकार सेट करता है। |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix बारकोड का एन्कोड मोड। |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix प्रतीक आकार सेट करता है। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग सेट करता है। |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC प्रकार सेट करता है। |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix बारकोड का एन्कोड मोड। |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setRows(int value)](#setRows-int-) | पंक्तियों की संख्या। |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix प्रतीक आकार सेट करता है। |
| [toString()](#toString--) | इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


स्तंभों की संख्या।

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200।

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: Version.Auto।

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग प्राप्त करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1।

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


विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए Macro Characters 05 और 06 मानों का उपयोग किया जाता है। केवल DataMatrixEccType.Ecc200 या DataMatrixEccType.EccAuto के साथ ही उपयोग किया जा सकता है। EncodeTypes.GS1DataMatrix के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacters.None।

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


पंक्तियों की संख्या।

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0।

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0।

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0।

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: Version.Auto।

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
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


पाठक को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को पाठक प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


स्तंभों की संख्या।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | एक Datamatrix ECC प्रकार। |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: Version.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | एक Datamatrix प्रतीक आकार। |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग सेट करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | ECI एन्कोडिंग। |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | एक Datamatrix ECC प्रकार। |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए Macro Characters 05 और 06 मानों का उपयोग किया जाता है। केवल DataMatrixEccType.Ecc200 या DataMatrixEccType.EccAuto के साथ ही उपयोग किया जा सकता है। EncodeTypes.GS1DataMatrix के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacters.None।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


पाठक को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को पाठक प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


पंक्तियों की संख्या।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: Version.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | एक Datamatrix प्रतीक आकार। |

### toString() {#toString--}
```
public String toString()
```


इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) का प्रतिनिधित्व करती है।
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

