---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeResult 메서드. 인코딩을 사용하여 코드 �스트를 가져옵니다."
type: docs
weight: 130
url: /ko/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

인코딩된 코드 텍스트를 가져옵니다.

```csharp
public string GetCodeText(Encoding encoding)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인코딩 | 인코딩 | 코드 텍스트에 대한 인코딩입니다. |

### 반환 값

인식된 코드 �스트를 포함하는 문자열.

## 예제

이 예제는 `GetCodeText` 사용 방법을 보여줍니다:

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### 또 보기

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


