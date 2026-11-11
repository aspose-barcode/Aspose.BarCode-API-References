---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BaseGenerationParameters 속성. 바코드 이미지 회전 각도(도 단위) 예: RotationAngle 0 또는 RotationAngle 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아닌 경우 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값 0"
type: docs
weight: 110
url: /ko/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0.

```csharp
public float RotationAngle { get; set; }
```

## 예제

이 샘플은 BarCode 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### 또 보기

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


