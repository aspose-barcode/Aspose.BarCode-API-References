---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for .NET API 참조"
description: "AustraliaPostSettings 속성. CTable 방식으로 디코딩할 때 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 시퀀스 333은 문자 z로 디코딩됩니다."
type: docs
weight: 30
url: /ko/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

디코딩 중 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 시퀀스 "333"은 문자 "z"로 디코딩됩니다.

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

CTable 방식 디코딩 중 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다.

## 예제

이 샘플은 CTable 해석 유형과 채우기 패턴 무시를 사용하여 Australia Post 바코드를 생성하고 인식하는 방법을 보여줍니다.

```csharp
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

### 또 보기

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


