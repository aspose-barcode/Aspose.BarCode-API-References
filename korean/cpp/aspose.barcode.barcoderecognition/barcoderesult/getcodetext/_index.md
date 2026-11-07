---
title: "메서드"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 인코딩이 적용된 코드 텍스트를 가져옵니다."
type: docs
weight: 1000
url: /ko/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


인코딩된 코드 텍스트를 가져옵니다.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인코딩 | System::SharedPtr\<System::Text::Encoding\> | 코드 텍스트에 대한 인코딩. |

### ReturnValue

인식된 코드 텍스트를 포함하는 문자열.
## 비고



이 예제는 **GetCodeText** 사용 방법을 보여줍니다:


```cpp
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

## 또 보기

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
