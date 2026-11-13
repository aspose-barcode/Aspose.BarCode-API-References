---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix पैरामीटर।

DataMatrixParameters प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| ecc_type | Datamatrix ECC प्रकार को प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट मान: DataMatrixEccType.Ecc200. |
| version | Datamatrix प्रतीक आकार को प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट मान: Version.Auto. |
| encode_mode | Datamatrix बारकोड का एन्कोड मोड।<br/>            डिफ़ॉल्ट मान: EncodeMode.Auto. |
| structured_append_barcode_id | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID।<br/>            डिफ़ॉल्ट मान: 0 |
| structured_append_barcodes_count | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या।<br/>            डिफ़ॉल्ट मान: 0 |
| structured_append_file_id | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल ID।<br/>            डिफ़ॉल्ट मान: 0 |
| is_reader_programming | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।<br/>            डिफ़ॉल्ट मान: false |
| macro_characters | विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए Macro Characters 05 और 06 मानों का उपयोग किया जाता है।<br/>            केवल DataMatrixEccType.Ecc200 या DataMatrixEccType.EccAuto के साथ उपयोग किया जा सकता है।<br/>            EncodeTypes.GS1DataMatrix के साथ उपयोग नहीं किया जा सकता है।<br/>            डिफ़ॉल्ट मान: MacroCharacters.None. |
| aspect_ratio | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| eci_encoding | ECI एन्कोडिंग को प्राप्त करता है या सेट करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है।<br/>            डिफ़ॉल्ट मान: ISO-8859-1 |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

