---
title: "BarcodeParameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Barkod oluşturma parametreleri.

BarcodeParameters türü aşağıdaki üyeleri ortaya çıkarır:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| x_dimension | x-dimension, BarCode çubukları veya boşlukları biriminin en küçük genişliğidir.<br/>            Bunu artırmak, tüm barkod görüntüsü genişliğini artırır.<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır. |
| bar_height | 1D barkodların çubuk yüksekliği, [Unit](/barcode/python-net/aspose.barcode.generation/unit/) değerinde.<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır. |
| bar_color | Çubukların rengi.<br/>            Varsayılan değer: Color.Black. |
| padding | Barkod kenar boşlukları.<br/>            Varsayılan değer: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol basamağını göster. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Yalnızca 1D barkodlar için.<br/>            Kod metni hatalıysa ve değer true olarak ayarlanmışsa - istisna fırlatılır. Aksi takdirde kod metni barkodun spesifikasyonuna uyması için düzeltilir.<br/>            İstisna her zaman şu durumlarda fırlatılır: Databar sembolojisi, kod metni hatalıysa.<br/>            İstisna hiçbir zaman fırlatılmaz: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi, kod metni hatalıysa. |
| wide_narrow_ratio | Geniş çubukların dar çubuklara oranı.<br/>            Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir.<br/>            ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII için kullanılır. |
| code_text_parameters | Kodmetni parametreleri. |
| filled_bars | Çubukların doldurulup doldurulmadığını gösteren bir değeri alır veya ayarlar.<br/>            Yalnızca 1D barkodlar için.<br/>            Varsayılan değer: true. |
| bar_width_reduction | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini alır veya ayarlar.<br/>            Varsayılan değer: 0 |
| postal | Posta parametreleri. Postnet ve Planet için kullanılır. |
| patch_code | PatchCode parametreleri. |
| australya_posta | AustralianPost barkod parametreleri. |
| veri_bar | Databar parametreleri. |
| gs1_kompozit_bar | GS1 Kompozit Bar parametreleri. |
| kodablok | Codablock parametreleri. |
| veri_matris | DataMatrix parametreleri. |
| kod_16k | Code16K parametreleri. |
| nokta_kod | DotCode parametreleri. |
| itf | ITF parametreleri. |
| pdf417 | PDF417 parametreleri. |
| qr | QR, MicroQR ve RectMicroQR parametreleri. |
| ek | Ek parametreler. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN için kullanılır. |
| maxi_kod | MaxiCode parametreleri. |
| aztek | Aztec parametreleri. |
| kod128 | Code128 parametreleri. |
| kodabar | Codabar parametreleri. |
| kupon | Kupon parametreleri. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon için kullanılır. |
| han_xin | HanXin parametreleri. |
| gs1 | GS1 parametreleri. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

