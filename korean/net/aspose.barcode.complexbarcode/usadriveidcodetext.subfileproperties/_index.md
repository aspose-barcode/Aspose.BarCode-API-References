---
title: "클래스 USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties 클래스. USA DL 서브파일 속성의 오프셋과 길이는 자동으로 설정됩니다."
type: docs
weight: 840
url: /ko/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL 서브파일 속성, 오프셋 및 길이는 자동으로 설정됩니다.

```csharp
public class SubfileProperties
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 이 바이트는 서브파일의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종료자는 서브파일 길이를 계산할 때 포함되어야 합니다. 세그먼트 종료자 = 1. 각 서브파일은 두 문자로 된 Subfile Type으로 시작해야 하며, 이 두 문자도 길이에 포함되어야 합니다. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4자리 숫자 값은 파일의 시작(헤드)부터 특정 서브파일과 관련된 데이터가 위치하는 바이트 수를 지정합니다. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 예: "DL"와 같은 2바이트 서브파일 유형 |

### 또 보기

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


