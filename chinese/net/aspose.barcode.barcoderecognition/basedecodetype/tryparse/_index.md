---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BaseDecodeType 方法。将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败"
type: docs
weight: 40
url: /zh/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | 字符串 | 包含 SingleDecodeType 的字符串，格式如 "EAN8"、"EAN13" 或 "CodaBar"... 用于转换。 |
| 结果 | SingleDecodeType& | 当转换成功完成时返回实际的 SingleDecodeType；否则返回不确定类型：DecodeType.None。 |

### 返回值

**true** if parsingType was converted successfully; otherwise, **false**.

### 另见

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | 字符串 | 包含 MultiDecodeType 表示的字符串，用于转换。 |
| 结果 | MultiDecodeType& | 当转换成功完成时返回实际的 MultiDecodeType；否则返回不确定类型：new MultiDecodeType(DecodeType.None)。 |

### 返回值

**true** if parsingType was converted successfully; otherwise, **false**.

### 另见

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

将 BaseDecodeType 的字符串表示转换为其实例，并确定具体类型。返回值指示转换是成功还是失败。

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | 字符串 | 包含 MultiDecodeType 表示的字符串，用于转换。 |
| 结果 | BaseDecodeType& | 当转换成功完成时返回实际的 MultiDecodeType；否则返回不确定类型：DecodeType.None。 |

### 返回值

**true** if parsingType was converted successfully; otherwise, **false**.

### 另见

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


