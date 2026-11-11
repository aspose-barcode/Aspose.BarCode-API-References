---
title: "열거형 EnableChecksum"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.EnableChecksum 열거형. 1D 바코드 생성 중 체크섬을 활성화합니다."
type: docs
weight: 1280
url: /ko/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

1D 바코드 생성 시 체크섬을 활성화합니다.

체크섬이 반드시 포함되어야 하는 심볼에 대해서는 기본값이 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다.

체크섬이 사용되지 않음: Codabar

체크섬을 사용할 수 있습니다: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

체크섬이 항상 사용됩니다: 나머지 심볼

```csharp
public enum EnableChecksum
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | `0` | 사양에서 체크섬이 요구되는 경우 - 체크섬이 첨부됩니다. |
| Yes | `1` | 가능하면 항상 체크섬을 사용하십시오. |
| No | `2` | 체크섬을 사용하지 마십시오. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


