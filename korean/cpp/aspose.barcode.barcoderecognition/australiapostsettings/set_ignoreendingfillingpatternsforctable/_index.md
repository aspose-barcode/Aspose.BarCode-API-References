---
title: "메서드"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. CTable 방식으로 디코딩할 때 Customer Information Field에서 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 시퀀스 \"333\"은 C++에서 문자 \"z\"로 디코딩됩니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


디코딩 중에 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 "333" 시퀀스는 문자 "z"로 디코딩됩니다.

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## 비고


CTable 방식 디코딩 중에 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그

이 샘플은 CTable 해석 유형을 사용하고 채우기 패턴을 무시하면서 Australia Post 바코드를 생성하고 인식하는 방법을 보여줍니다.
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

## 또 보기

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
