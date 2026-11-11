---
title: "클래스 QrParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.QrParameters 클래스. QR 매개변수"
type: docs
weight: 1650
url: /ko/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR 매개변수.

```csharp
public class QrParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | 2D 바코드 모듈의 높이/너비 비율. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | GS1 특수 문자를 QR 및 RectMicroQR 바코드에 대해 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | BarCode의 인코딩 모드에 대한 QR 심볼 유형. 기본값: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | QR, MicroQR 및 RectMicroQR 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | MicroQR 코드의 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | RectMicroQR 코드의 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR 구조적 추가 매개변수. 구조적 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | QR 코드 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | 이 `QrParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


