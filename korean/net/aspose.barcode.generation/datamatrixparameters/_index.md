---
title: "클래스 DataMatrixParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.DataMatrixParameters 클래스. DataMatrix 매개변수"
type: docs
weight: 1220
url: /ko/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

DataMatrix 매개변수.

```csharp
public class DataMatrixParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | 2D 바코드 모듈의 높이/너비 비율. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Datamatrix ECC 유형을 가져오거나 설정합니다. 기본값: DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | ECI 인코딩을 가져오거나 설정합니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | 특수 모드에서 보다 압축된 인코딩을 얻기 위해 매크로 문자 05 및 06 값을 사용합니다. DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다. EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다. 기본값: MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. 기본값: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. 기본값: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Datamatrix 심볼 크기를 가져오거나 설정합니다. 기본값: Version.Auto. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | `DataMatrixParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


