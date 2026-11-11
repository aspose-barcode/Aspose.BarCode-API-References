---
title: "Pdf417Parameters.IsLinked"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Pdf417Parameters 속성. GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와의 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906 907 912 913 914 915를 인코딩하고, 연결된 UCC/EAN128 모드를 제공합니다. MicroPdf417 및 Pdf417 심볼은 918 연결 플래그를 인코딩하여 EAN.UCC가 아닌 연관된 선형 구성 요소에 연결합니다."
type: docs
weight: 70
url: /ko/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결된 모드를 정의합니다. GS1MicroPdf417 기호는 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417 및 Pdf417 기호는 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다.

```csharp
public bool IsLinked { get; set; }
```

## 예제

이 샘플은 GS1MicroPdf417에서 "Linked" UCC/EAN-128 모드를 인코딩하고 MicroPdf417 및 Pdf417 바코드에서 연결 플래그(918)를 인코딩하는 방법을 보여줍니다.

```csharp
[C#]
//GS1 연결 모드 912를 날짜 필드 AI 11(생산일) 및 AI 10(로트 번호)와 함께 인코딩합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 912를 날짜 필드 AI 13(포장일) 및 AI 21(시리얼 번호)와 함께 인코딩합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 912를 날짜 필드 AI 15(판매기한) 및 AI 10(로트 번호)와 함께 인코딩합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 912를 날짜 필드 AI 17(만료 날짜) 및 AI 21(시리얼 번호)와 함께 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 914를 AI 10(LOT 번호)와 함께 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 915를 AI 21(시리얼 번호)와 함께 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 연결 모드 906, 907을 모든 AI와 함께 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//MicroPdf417 NON EAN.UCC 연결 모드 918을 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Pdf417 NON EAN.UCC 연결 모드 918을 인코딩합니다
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### 또 보기

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


