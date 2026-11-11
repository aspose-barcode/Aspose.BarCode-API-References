---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeGenerator 메서드. 현재 설정으로 바코드 이미지를 생성합니다"
type: docs
weight: 80
url: /ko/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

현재 설정으로 바코드 이미지를 생성합니다.

```csharp
public Bitmap GenerateBarCodeImage()
```

### 반환 값

바코드 이미지. Bitmap을 참조하십시오.

## 예제

이 샘플은 바코드 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### 또 보기

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


