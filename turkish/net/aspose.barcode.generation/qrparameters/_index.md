---
title: "Sınıf QrParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.QrParameters sınıfı. QR parametreleri"
type: docs
weight: 1650
url: /tr/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR parametreleri.

```csharp
public class QrParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında ayrıntıları bildirmek için kullanılır. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir. MicroQR tarafından desteklenmez. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | BarCode'un kodlama modunun QR semboloji türü. Varsayılan değer: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel'a bakın. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | MicroQR Kodunun sürümü. M1 sürümünden M4 sürümüne kadar. Varsayılan değer: MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | RectMicroQR Kodunun sürümü. R7x59 sürümünden R17x139 sürümüne kadar. Varsayılan değer: RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR yapılandırılmış ekleme parametreleri. Yapılandırılmış ekleme modu MicroQR ve RectMicroQR barkodları tarafından desteklenmez. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | QR Kod sürümü. Version1'den Version40'a kadar. Varsayılan değer QRVersion.Auto'dur. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Bu `QrParameters` nesnesinin insan tarafından okunabilir dize temsilini döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


