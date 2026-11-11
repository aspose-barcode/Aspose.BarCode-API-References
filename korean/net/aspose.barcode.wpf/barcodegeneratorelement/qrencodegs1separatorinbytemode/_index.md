---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeGeneratorElement 속성. QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다"
type: docs
weight: 1290
url: /ko/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

GS1 특수 문자를 QR 및 RectMicroQR 바코드에 대해 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다.

false인 경우, QR 사양에 따라 알파벳-숫자 모드에서 GS1 구분자를 '%'로 인코딩할 수 있습니다.

true인 경우, GS1 그룹 구분자는 0x1D 문자로 바이트 모드에서 인코딩되며, '%' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '%' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### 또 보기

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


