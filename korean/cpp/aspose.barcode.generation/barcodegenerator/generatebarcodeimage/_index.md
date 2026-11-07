---
title: "메서드"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. C++에서 현재 설정으로 바코드 이미지를 생성합니다."
type: docs
weight: 800
url: /ko/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


현재 설정으로 바코드 이미지를 생성합니다.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

바코드 이미지. [Bitmap](../)을 참조하십시오.
## 비고



이 샘플은 바코드 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## 또 보기

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
