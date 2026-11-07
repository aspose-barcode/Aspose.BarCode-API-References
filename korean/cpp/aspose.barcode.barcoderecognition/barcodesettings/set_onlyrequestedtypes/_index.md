---
title: "메서드"
linktitle: "set_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. 인식에 명시적으로 지정된 바코드 유형만 반환합니다. 활성화된 경우, 다른 호환 또는 동등한 유형의 인식된 바코드는 필터링됩니다. 기본값은 C++에서 false입니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_onlyrequestedtypes/
---
## BarcodeSettings::set_OnlyRequestedTypes method


인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형의 인식된 바코드는 필터링됩니다. 기본값은 false입니다.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_OnlyRequestedTypes(bool value)
```

## 비고


이 샘플은 인식 결과를 요청된 바코드 유형으로만 제한하는 방법을 보여줍니다
```cpp
[C#]
//EAN13 바코드 생성
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//UPCA 바코드만 인식 (결과 없음, 소스가 EAN13이기 때문)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//호환 유형 인식: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13은 UPCA와 동등하게 반환됩니다)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


인식에 명시적으로 지정된 바코드 유형만 반환합니다. 기본값은 false입니다.
## 또 보기

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
