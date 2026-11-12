---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "DataMatrix पैरामीटर।"
type: docs
weight: 360
url: /hi/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix पैरामीटर।

```js
new DataMatrixParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [getColumns()](#getcolumns) | स्तंभों की गिनती। |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | ECI एन्कोडिंग प्राप्त करता है। जब DataMatrixEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 मैक्रो अक्षर 11.3 पहला स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200) मैक्रो Cha |
| [getRows()](#getrows) | पंक्तियों की गिनती। |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोडों की गिनती। डिफ़ॉल्ट मान: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0 |
| [getVersion()](#getversion) | Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setAspectRatio()](#setaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [setColumns()](#setcolumns) | स्तंभों की गिनती। |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | ECI एन्कोडिंग सेट करता है। जब DataMatrixEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 मैक्रो अक्षर 11.3 पहला स्थान में मैक्रो अक्षरों के लिए प्रोटोकॉल (केवल ECC 200) मैक्रो Cha |
| [setReaderProgramming()](#setreaderprogramming) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setRows()](#setrows) | पंक्तियों की गिनती। |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोडों की गिनती। डिफ़ॉल्ट मान: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0 |
| [setVersion(value)](#setversion) | Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: Version.Auto. |
| [toString()](#tostring) | इस DataMatrixParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### getAspectRatio() {#getaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### getColumns() {#getcolumns}

स्तंभों की गिनती।

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

ECI एन्कोडिंग प्राप्त करता है। जब DataMatrixEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

### getEncodeMode() {#getencodemode}

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 मैक्रो कैरेक्टर 11.3 पहले स्थिति में मैक्रो कैरेक्टर के लिए प्रोटोकॉल (केवल ECC 200) मैक्रो कैरेक्टर 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल DataMatrixEccType.ECC_200 या DataMatrixEccType.ECC_AUTO के साथ उपयोग किया जा सकता है। EncodeTypes.GS_1_DATA_MATRIX के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacter.NONE।

### getRows() {#getrows}

पंक्तियों की गिनती।

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Datamatrix बारकोड के Structured Append मोड के लिए बारकोडों की गिनती। डिफ़ॉल्ट मान: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0

### getVersion() {#getversion}

Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false

### setAspectRatio() {#setaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### setColumns() {#setcolumns}

स्तंभों की गिनती।

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200.

| पैरामीटर | विवरण |
| --- | --- |
| मान | एक Datamatrix ECC प्रकार। |

### setECIEncoding() {#seteciencoding}

ECI एन्कोडिंग सेट करता है। जब DataMatrixEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

### setEncodeMode() {#setencodemode}

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 मैक्रो कैरेक्टर 11.3 पहले स्थिति में मैक्रो कैरेक्टर के लिए प्रोटोकॉल (केवल ECC 200) मैक्रो कैरेक्टर 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल DataMatrixEccType.ECC_200 या DataMatrixEccType.ECC_AUTO के साथ उपयोग किया जा सकता है। EncodeTypes.GS_1_DATA_MATRIX के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: MacroCharacter.NONE।

### setReaderProgramming() {#setreaderprogramming}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false

### setRows() {#setrows}

पंक्तियों की गिनती।

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Datamatrix बारकोड के Structured Append मोड के लिए बारकोडों की गिनती। डिफ़ॉल्ट मान: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID। डिफ़ॉल्ट मान: 0

### setVersion(value) {#setversion}

Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: Version.Auto.

| पैरामीटर | विवरण |
| --- | --- |
| मान | एक Datamatrix प्रतीक आकार। |

### toString() {#tostring}

इस DataMatrixParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** presentation of this DataMatrixParameters.
