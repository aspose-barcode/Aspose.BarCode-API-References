---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Pdf417Parameters 속성. MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치에 FNC1을 인코딩할 수 있는 모드 908 및 909와, 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타내는 910 및 911도 인코딩할 수 있습니다."
type: docs
weight: 60
url: /ko/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128로 해석될 수 있음을 나타냅니다.

```csharp
public bool IsCode128Emulation { get; set; }
```

## 예제

이 샘플은 두 번째 위치에 FNC1을 포함하거나 포함하지 않은 Code 128 에뮬레이션 모드를 인코딩하는 방법을 보여줍니다. 이렇게 하면 MicroPdf417를 Code 128 바코드로 디코딩할 수 있습니다.

```csharp
[C#]
//MicroPdf417를 Code 128 에뮬레이션 모드에서 두 번째 위치에 FNC1을 사용하고 애플리케이션 인디케이터 "a"와 함께 인코딩합니다, 모드 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417를 Code 128 에뮬레이션 모드에서 두 번째 위치에 FNC1을 사용하고 애플리케이션 인디케이터 "99"와 함께 인코딩합니다, 모드 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417를 Code 128 에뮬레이션 모드로 인코딩합니다, 모드 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### 또 보기

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


