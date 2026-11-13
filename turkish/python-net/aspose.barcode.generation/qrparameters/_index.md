---
title: "QrParameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR parametreleri.

QrParameters türü aşağıdaki üyeleri gösterir:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| eci_encoding | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları iletmek için kullanılır.<br/>            Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir.<br/>            MicroQR tarafından desteklenmez. |
| encode_mode | BarCode'un kodlama modunun QR semboloji türü.<br/>            Varsayılan değer: QREncodeMode.Auto. |
| error_level | QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi.<br/>             Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. Bkz. QRErrorLevel. |
| version | QR Kodunun sürümü. Version1'den Version40'a kadar.<br/>            Varsayılan değer QRVersion.Auto. |
| micro_qr_version | MicroQR Kodunun sürümü. M1'den M4'e kadar.<br/>            Varsayılan değer MicroQRVersion.Auto. |
| rect_micro_qr_version | RectMicroQR Kodunun sürümü. R7x59'dan R17x139'a kadar.<br/>            Varsayılan değer RectMicroQRVersion.Auto. |
| aspect_ratio | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| structured_append | QR yapılandırılmış ekleme parametreleri.<br/>            Yapılandırılmış ekleme modu MicroQR ve RectMicroQR barkodları tarafından desteklenmez. |
| encode_gs1_separator_in_byte_mode |  |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

