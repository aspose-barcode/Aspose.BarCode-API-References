---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeSettings 속성. 인식을 위해 명시적으로 지정된 바코드 유형만 반환합니다. 활성화된 경우 다른 호환 또는 동등한 유형의 인식된 바코드가 필터링됩니다. 기본값은 false입니다."
type: docs
weight: 50
url: /ko/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형의 인식된 바코드가 필터링됩니다. 기본값은 false입니다.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

인식에 명시적으로 지정된 바코드 유형만 반환합니다. 기본값은 false입니다.

## 예제

이 샘플은 인식 결과를 요청된 바코드 유형으로만 제한하는 방법을 보여줍니다.

```csharp
[C#]
//EAN13 바코드를 생성합니다.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//UPCA 바코드만 인식합니다 (소스가 EAN13이므로 결과가 없습니다).
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//호환 유형을 인식합니다: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13은 UPCA와 동등하게 반환됩니다).
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### 또 보기

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


