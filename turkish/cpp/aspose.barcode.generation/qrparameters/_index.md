---
title: "Aspose::BarCode::Generation::QrParameters class"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::QrParameters sınıfı. C++'da QR parametreleri."
type: docs
weight: 4400
url: /tr/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR parametreleri.

```cpp
class QrParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [get_ECIEncoding](./get_eciencoding/)() const | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir. MicroQR tarafından desteklenmez. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | [BarCode](../../aspose.barcode/) kodlama modunun QR semboloji türü. Varsayılan değer: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | QR, MicroQR ve RectMicroQR barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. Bkz. QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | MicroQR Kodunun sürümü. M1 sürümünden M4 sürümüne kadar. Varsayılan değer: [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | RectMicroQR Kodunun sürümü. R7x59 sürümünden R17x139 sürümüne kadar. Varsayılan değer: [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR yapılandırılmış ek parametreleri. Yapılandırılmış ek modu MicroQR ve RectMicroQR barkodları tarafından desteklenmez. |
| [get_Version](./get_version/)() const | QR Kodunun sürümü. Version1'den Version40'a kadar. Varsayılan değer: [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir. MicroQR tarafından desteklenmez. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | [BarCode](../../aspose.barcode/) kodlama modunun QR semboloji türü. Varsayılan değer: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | QR, MicroQR ve RectMicroQR barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. Bkz. QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | MicroQR Kodunun sürümü. M1 sürümünden M4 sürümüne kadar. Varsayılan değer: [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | RectMicroQR Kodunun sürümü. R7x59 sürümünden R17x139 sürümüne kadar. Varsayılan değer: [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR yapılandırılmış ek parametreleri. Yapılandırılmış ek modu MicroQR ve RectMicroQR barkodları tarafından desteklenmez. |
| [set_Version](./set_version/)(QRVersion) | QR Kodunun sürümü. Version1'den Version40'a kadar. Varsayılan değer: [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Bu [QrParameters](./) nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
