---
title: "विधि"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. वह फ़्लैग जो AustraliaPost डिकोडर को CTable विधि के रूप में डिकोडिंग के दौरान कस्टमर इन्फॉर्मेशन फ़ील्ड में अंतिम फ़िलिंग पैटर्न को अनदेखा करने के लिए मजबूर करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई गैप नहीं होते और \"333\" अनुक्रम के फ़िलिंग पैटर्न को C++ में अक्षर \"z\" के रूप में डिकोड किया जाता है।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


फ़्लैग जो AustraliaPost डिकोडर को डिकोडिंग के दौरान कस्टमर इन्फॉर्मेशन फ़ील्ड में अंतिम भराव पैटर्न को CTable विधि के रूप में अनदेखा करने के लिए बाध्य करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई अंतर नहीं होता और भराव पैटर्न की श्रृंखला "333" को अक्षर "z" के रूप में डिकोड किया जाता है।

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## टिप्पणियाँ


AustraliaPost डिकोडर को CTable विधि डिकोडिंग के दौरान अंतिम फ़िलिंग पैटर्न को अनदेखा करने के लिए मजबूर करने वाला फ़्लैग।

यह नमूना दिखाता है कि CTable इंटरप्रेटिंग टाइप के साथ और फ़िलिंग पैटर्न को अनदेखा करके Australia Post बारकोड को कैसे जेनरेट और पहचानें।
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## और देखें

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
