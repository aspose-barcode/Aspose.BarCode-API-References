---
title: "विधि"
linktitle: "Decode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। Decode Customer Information Field from AustraliaPost symbology. विभिन्न डेटा व्याख्या के लिए NTable और CTable एन्कोडिंग से उपयोग किया जा सकता है। डेटा को C++ में 0, 1, 2 या 3 के बार मानों की पंक्ति के रूप में प्रदान किया जाता है।"
type: docs
weight: 100
url: /hi/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


ऑस्ट्रेलिया पोस्ट प्रतीक से कस्टमर इन्फॉर्मेशन फील्ड को डिकोड करें। इसे NTable और CTable एन्कोडिंग से विभिन्न डेटा व्याख्या के लिए उपयोग किया जा सकता है। डेटा को बार मानों की पंक्ति के रूप में प्रदान किया जाता है: 0, 1, 2 या 3।

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| customerInformationField | System::String | यह Customer Information Field कच्चे बार मानों की पंक्ति के रूप में एन्कोड किया गया: 0, 1, 2 या 3 |

### ReturnValue

डिकोड किया गया Customer Information Field स्ट्रिंग
## टिप्पणियाँ



यह उदाहरण दिखाता है कि कैसे डेटा को [AustraliaPostCustomerInformationDecoder](../) इंटरफ़ेस के साथ डिकोड किया जाए
```cpp
[C#]
string[] N_Table = { "00", "01", "02", "10", "11", "12", "20", "21", "22", "30" };
public string Decode(string customerInformationField)
{
    StringBuilder bd = new StringBuilder();
    for (int i = 0; customerInformationField.Length > i; i += 2)
    {
        if (customerInformationField.Length >= i + 2)
        {
            string tmp = customerInformationField.Substring(i, 2);
            for (int j = 0; N_Table.Length > j; j++)
            {
                if (N_Table[j].Equals(tmp))
                {
                    bd.Append(j);
                    break;
                }
            }
        }
    }
     return bd.ToString();
}
```

## और देखें

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
