---
title: "클래스 AztecParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.AztecParameters 클래스. Aztec 매개변수"
type: docs
weight: 960
url: /ko/net/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class

Aztec 매개변수.

```csharp
public class AztecParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/aztecparameters/aspectratio/) { get; set; } | 2D 바코드 모듈의 높이/너비 비율. |
| [ECIEncoding](../../aspose.barcode.generation/aztecparameters/eciencoding/) { get; set; } | ECI 인코딩을 가져오거나 설정합니다. AztecEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/aztecparameters/encodemode/) { get; set; } | Aztec 인코드 모드를 가져오거나 설정합니다. 기본값: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/aztecparameters/errorlevel/) { get; set; } | Aztec 유형 바코드의 오류 정정 수준. 값은 5에서 95 사이여야 합니다. |
| [IsReaderInitialization](../../aspose.barcode.generation/aztecparameters/isreaderinitialization/) { get; set; } | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [LayersCount](../../aspose.barcode.generation/aztecparameters/layerscount/) { get; set; } | Aztec 심볼의 레이어 수를 가져오거나 설정합니다. Compact 모드에서는 레이어 수가 1에서 3 사이여야 하고, Full Range 모드에서는 1에서 32 사이여야 합니다. 기본값: 0 (자동). |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodeid/) { get; set; } | Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. 바코드 ID는 1에서 바코드 수까지의 범위에 있어야 합니다. 기본값: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodescount/) { get; set; } | Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/aztecparameters/structuredappendfileid/) { get; set; } | Aztec 바코드의 Structured Append 모드에 대한 파일 ID (선택 필드). 파일 ID에는 공백이 포함될 수 없습니다. 기본값: 빈 문자열 |
| [SymbolMode](../../aspose.barcode.generation/aztecparameters/symbolmode/) { get; set; } | Aztec Symbol 모드를 가져오거나 설정합니다. 기본값: AztecSymbolMode.Auto. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/aztecparameters/tostring/)() | 이 `AztecParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


