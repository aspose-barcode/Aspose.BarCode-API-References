---
title: "विधि"
linktitle: "set_ChecksumValidation"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::BarCodeRecognition::BarcodeSettings क्लास की set_ChecksumValidation मेथड का उपयोग कैसे करें।"
type: docs
weight: 200
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_checksumvalidation/
---
## BarcodeSettings::set_ChecksumValidation method




```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_ChecksumValidation(Aspose::BarCode::BarCodeRecognition::ChecksumValidation value)
```

## टिप्पणियाँ


1D और पोस्टल बारकोड के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें।

डिफ़ॉल्ट को उन प्रतीकात्मकताओं के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ No माना जाता है।

चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

चेकसम हमेशा उपयोग किया जाता है: शेष प्रतीकात्मकताएँ

यह उदाहरण ChecksumValidation के पहचान गुणवत्ता और परिणामों पर प्रभाव को दर्शाता है
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //चेकसम अक्षम
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //चेकसम सक्षम
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```


1D और पोस्टल बारकोड के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें।
## और देखें

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
