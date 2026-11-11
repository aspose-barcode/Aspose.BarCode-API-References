---
title: "BarcodeSettings.DetectEncoding"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeSettings 속성. 엔진이 유니코드 코드셋에 대한 코드텍스트 인코딩을 감지하도록 강제하는 플래그입니다. 기본값은 true입니다."
type: docs
weight: 40
url: /ko/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

Unicode 코드셋에 대한 코드텍스트 인코딩을 감지하도록 엔진을 강제하는 플래그입니다. 기본값은 true입니다.

```csharp
public bool DetectEncoding { get; set; }
```

### Property Value

엔진이 유니코드 코드셋에 대한 코드텍스트 인코딩을 감지하도록 강제하는 플래그

## 예제

이 샘플은 DetectEncoding이 활성화된 경우 텍스트 인코딩을 실시간으로 감지하는 방법을 보여줍니다.

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //유니코드 코드셋에 대한 인코딩 감지가 활성화되었습니다.
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //인코딩 감지가 비활성화되었습니다.
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 또 보기

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


