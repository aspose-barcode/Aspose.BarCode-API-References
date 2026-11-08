---
title: "Aspose::BarCode::Generation::BarcodeParameters sınıfı"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::BarcodeParameters sınıfı. C++'da barkod oluşturma parametreleri."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Barkod oluşturma parametreleri.

```cpp
class BarcodeParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost barkod parametreleri. |
| [get_Aztec](./get_aztec/)() const | Aztec parametreleri. |
| [get_BarColor](./get_barcolor/)() const | Çubukların rengi. Varsayılan değer: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | 1D barkod çubuklarının yüksekliği [Unit](../unit/) biriminde. [BaseGenerationParameters::AutoSizeMode](../) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlanmışsa göz ardı edilir. |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini alır veya ayarlar. Varsayılan değer: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı rakamını göster. |
| [get_Codabar](./get_codabar/)() const | Codabar parametreleri. |
| [get_Codablock](./get_codablock/)() const | Codablock parametreleri. |
| [get_Code128](./get_code128/)() const | Code128 parametreleri. |
| [get_Code16K](./get_code16k/)() const | Code16K parametreleri. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Kod metni parametreleri. |
| [get_Coupon](./get_coupon/)() const | Kupon parametreleri. UpcaGs1DatabarCoupon ve UpcaGs1Code128Coupon için kullanılır. |
| [get_DataBar](./get_databar/)() const | Databar parametreleri. |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix parametreleri. |
| [get_DotCode](./get_dotcode/)() const | DotCode parametreleri. |
| [get_FilledBars](./get_filledbars/)() const | Çubukların doldurulup doldurulmadığını gösteren bir değer alır. Yalnızca 1D barkodlar için. Varsayılan değer: true. |
| [get_GS1](./get_gs1/)() const | GS1 parametreleri. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 Composite Bar parametreleri. |
| [get_HanXin](./get_hanxin/)() const | HanXin parametreleri. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF parametreleri. |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode parametreleri. |
| [get_Padding](./get_padding/)() const | Barkod doldurma boşlukları. Varsayılan değer: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | PatchCode parametreleri. |
| [get_Pdf417](./get_pdf417/)() const | PDF417 parametreleri. |
| [get_Postal](./get_postal/)() const | Posta parametreleri. Postnet ve Planet için kullanılır. |
| [get_QR](./get_qr/)() const | QR, MicroQR ve RectMicroQR parametreleri. |
| [get_Supplement](./get_supplement/)() const | Ek parametreler. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN için kullanılır. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Yalnızca 1D barkodlar için. codetext yanlış ise ve değer true olarak ayarlanmışsa - bir istisna fırlatılacak. Aksi takdirde codetext barkodun spesifikasyonuna uygun şekilde düzeltilecektir. İstisna her zaman şu durumlarda fırlatılacak: Databar sembolojisi için codetext yanlış ise. İstisna her zaman fırlatılmayacak durumlar: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi için codetext yanlış ise. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Geniş çubukların dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. Şunlar için kullanılır: ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [get_XDimension](./get_xdimension/)() const | x-dimension, [BarCode](../../aspose.barcode/) çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artıracaktır. [BaseGenerationParameters::AutoSizeMode](../) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlanmışsa yok sayılır. |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Çubukların rengi. Varsayılan değer: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | 1D barkod çubuklarının yüksekliği [Unit](../unit/) biriminde. [BaseGenerationParameters::AutoSizeMode](../) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlanmışsa göz ardı edilir. |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini alır veya ayarlar. Varsayılan değer: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı rakamını göster. |
| [set_FilledBars](./set_filledbars/)(bool) | Çubukların doldurulup doldurulmadığını gösteren bir değer ayarlar. Yalnızca 1D barkodlar için. Varsayılan değer: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 Composite Bar parametreleri. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Yalnızca 1D barkodlar için. codetext yanlış ise ve değer true olarak ayarlanmışsa - bir istisna fırlatılacak. Aksi takdirde codetext barkodun spesifikasyonuna uygun şekilde düzeltilecektir. İstisna her zaman şu durumlarda fırlatılacak: Databar sembolojisi için codetext yanlış ise. İstisna her zaman fırlatılmayacak durumlar: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi için codetext yanlış ise. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Geniş çubukların dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. Şunlar için kullanılır: ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension, [BarCode](../../aspose.barcode/) çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artıracaktır. [BaseGenerationParameters::AutoSizeMode](../) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlanmışsa yok sayılır. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
