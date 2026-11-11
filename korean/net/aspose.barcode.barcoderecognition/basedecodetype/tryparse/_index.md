---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BaseDecodeType 메서드. SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다."
type: docs
weight: 40
url: /ko/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | String | 변환할 "EAN8" 또는 "EAN13" 또는 "CodaBar"와 같은 형식의 SingleDecodeType을 포함하는 문자열입니다. |
| 결과 | SingleDecodeType& | 변환이 성공적으로 완료되면 실제 SingleDecodeType이 반환됩니다; 그렇지 않으면 불확정 유형인 DecodeType.None을 반환합니다. |

### 반환 값

**true** if parsingType was converted successfully; otherwise, **false**.

### 또 보기

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | String | 변환할 MultiDecodeType 표현을 포함하는 문자열 |
| 결과 | MultiDecodeType& | 변환이 성공적으로 완료되면 실제 MultiDecodeType이 반환됩니다; 그렇지 않으면 불확정 유형인 new MultiDecodeType(DecodeType.None)을 반환합니다. |

### 반환 값

**true** if parsingType was converted successfully; otherwise, **false**.

### 또 보기

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

BaseDecodeType의 문자열 표현을 해당 인스턴스로 변환하며, 구체적인 유형을 결정합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | String | 변환할 MultiDecodeType 표현을 포함하는 문자열 |
| 결과 | BaseDecodeType& | 변환이 성공적으로 완료되면 실제 MultiDecodeType이 반환됩니다; 그렇지 않으면 불확정 유형인 DecodeType.None을 반환합니다. |

### 반환 값

**true** if parsingType was converted successfully; otherwise, **false**.

### 또 보기

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


