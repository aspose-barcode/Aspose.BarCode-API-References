---
title: "열거형 Pdf417EncodeMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode 열거형. Pdf417 바코드 인코딩 모드"
type: docs
weight: 1540
url: /ko/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 바코드 인코드 모드

```csharp
public enum Pdf417EncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| Binary | `1` | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | `2` | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다. |
| Extended | `3` | 다중 ECI 모드를 지원하는 확장 모드. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


