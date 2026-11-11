---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeGenerator 메서드. codetext를 바이트 시퀀스로 설정합니다"
type: docs
weight: 100
url: /ko/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

codetext를 바이트 시퀀스로 설정합니다.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| codeBytes | Byte[] | codetext의 바이트 |

### 또 보기

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

지정된 **encoding**을 사용하여 Unicode **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8은 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 이를 지원하는 경우, 함수가 자동으로 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)를 삽입합니다.

이 함수는 2D 바코드 전용(예: Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR 등)으로 사용하도록 설계되었습니다. 국가별 또는 특수 인코딩을 사용하여 유니코드 텍스트를 수동으로 인코딩할 수 있지만, 이 방법은 최신 애플리케이션에서는 구식으로 간주됩니다. 최신 사용 사례에서는 유니코드 데이터에 대해 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 인코딩을 권장합니다.

이 함수를 1D 바코드, GS1 호환 바코드(2D 포함) 또는 HIBC 바코드(2D 포함)와 함께 사용할 경우 해당 바코드 표준에서 지원되지 않으며 예측할 수 없는 결과가 발생할 수 있습니다.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| codeText | String | CodeText 문자열 |
| 인코딩 | 인코딩 | 적용된 인코딩 |

## 예제

이 예제는 `SetCodeText`를 사용하여 다양한 인코딩으로 2D 바코드에 대한 유니코드 인코딩 텍스트를 설정하는 방법을 보여줍니다:

```csharp
[C#]
//UTF-8 BOM을 사용하여 QR 코드 텍스트 인코딩
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Shift-JIS(일본어 인코딩)를 사용하여 DataMatrix 텍스트 인코딩
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### 또 보기

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

지정된 **encoding**을 사용하여 Unicode **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8은 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 이를 지원하고 **insertBOM**이 `true`로 설정된 경우, 함수가 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)를 포함합니다.

이 함수는 2D 바코드 전용(예: Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR 등)으로 사용하도록 설계되었습니다. 국가별 또는 특수 인코딩을 사용하여 유니코드 텍스트를 수동으로 인코딩할 수 있지만, 이 방법은 최신 애플리케이션에서는 구식으로 간주됩니다. 최신 사용 사례에서는 유니코드 데이터에 대해 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 인코딩을 권장합니다.

이 함수를 1D 바코드, GS1 호환 바코드(2D 포함) 또는 HIBC 바코드(2D 포함)와 함께 사용할 경우 해당 바코드 표준에서 지원되지 않으며 예측할 수 없는 결과가 발생할 수 있습니다.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| codeText | String | CodeText 문자열 |
| 인코딩 | 인코딩 | 적용된 인코딩 |
| insertBOM | Boolean | 지정된 인코딩이 지원하는 경우 바이트 순서 표시(BOM)를 삽입할지 여부를 나타냅니다(예: UTF-8, UTF-16, UTF-32). `true`로 설정하면 BOM이 추가되고, `false`로 설정하면 인코딩이 일반적으로 BOM을 사용하더라도 BOM이 생략됩니다. |

## 예제

이 예제는 2D 바코드에 대해 BOM을 포함하거나 포함하지 않고 `SetCodeText`를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//UTF-8 BOM을 사용하여 코드 텍스트 인코딩
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//UTF-8 BOM 없이 코드 텍스트 인코딩
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### 또 보기

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


