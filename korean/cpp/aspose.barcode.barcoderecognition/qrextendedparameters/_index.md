---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters 클래스"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters 클래스. 인식된 바코드의 QR 구조 추가 정보를 C++에 저장합니다."
type: docs
weight: 2900
url: /ko/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


인식된 바코드의 [QR](../../aspose.barcode.barcoderecognition.qr/) 구조 추가 정보를 저장합니다

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | 인식된 바코드의 리드-솔로몬 오류 정정 수준. 낮은 수준부터 높은 수준: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [get_MicroQRVersion](./get_microqrversion/)() const | 인식된 MicroQR 코드의 버전. M1부터 M4까지. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | 인식된 RectMicroQR 코드의 버전. R7x43부터 R17x139까지. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 구조 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 구조 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) 구조 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. |
| [get_Version](./get_version/)() const | 인식된 [QR](../../aspose.barcode.barcoderecognition.qr/) 코드의 버전. Version1부터 Version40까지. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [QRExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 [QR](../../aspose.barcode.barcoderecognition.qr/) 구조 추가 데이터를 가져오는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
