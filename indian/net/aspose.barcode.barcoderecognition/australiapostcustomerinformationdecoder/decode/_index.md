---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "AustraliaPostCustomerInformationDecoder मेथड। AustraliaPost सिम्बोलॉजी से Customer Information Field को डिकोड करता है। इसे NTable और CTable एन्कोडिंग से विभिन्न डेटा व्याख्या के लिए उपयोग किया जा सकता है। डेटा को 0 1 2 या 3 बार मानों की पंक्ति के रूप में प्रदान किया जाता है।"
type: docs
weight: 10
url: /hi/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

AustraliaPost प्रतीक विज्ञान से ग्राहक सूचना फ़ील्ड को डिकोड करें। इसे NTable और CTable एन्कोडिंग से विभिन्न डेटा व्याख्या के लिए उपयोग किया जा सकता है। डेटा को बार मानों की पंक्ति के रूप में प्रदान किया जाता है: 0, 1, 2 या 3।

```csharp
public string Decode(string customerInformationField)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| customerInformationField | स्ट्रिंग | Customer Information Field को कच्चे बार मानों की पंक्ति के रूप में एन्कोड किया गया है: 0, 1, 2 या 3 |

### वापसी मान

डिकोड किया गया Customer Information Field स्ट्रिंग

## उदाहरण

यह उदाहरण दिखाता है कि कैसे AustraliaPostCustomerInformationDecoder इंटरफ़ेस के साथ डेटा को डिकोड किया जाए

```csharp
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

### और देखें

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


