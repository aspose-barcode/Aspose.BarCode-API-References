---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::CodetextParameters sınıfı. C++'da kod metni parametreleri."
type: docs
weight: 1500
url: /tr/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Kod metni parametreleri.

```cpp
class CodetextParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Kod metninin hizalamasını alır. Varsayılan değer: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Görüntülenen CodeText'in rengini belirtin. Varsayılan değer: Color.Black. |
| [get_Font](./get_font/)() const | Görüntülenen CodeText'in yazı tipini belirtin. Varsayılan değer: Arial 5pt regular. FontMode [FontMode.Auto](../aztecencodemode/) olarak ayarlanmışsa yok sayılır. |
| [get_FontMode](./get_fontmode/)() const | FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. Özellikle [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) içinde [FontMode.Auto](../aztecencodemode/) kullanmanız önerilir. Varsayılan değer: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için [CodeLocation.None](../codelocation/) olarak ayarlayın. Varsayılan değer: 1D barkodlar için [CodeLocation.Below](../codelocation/) ve 2D barkodlar için [CodeLocation.None](../codelocation/). |
| [get_NoWrap](./get_nowrap/)() const | Metin içinde kelime kaydırmalarını (satır sonlarını) belirtin. Varsayılan değer: false. |
| [get_Space](./get_space/)() const | KodMetni ile [BarCode](../../aspose.barcode/) arasındaki boşluk, [Unit ](../unit/) biriminde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | 2D barkodlarda kodmetni yerine görüntülenecek metin. Şunlar için kullanılır: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Kod metninin hizalamasını ayarlar. Varsayılan değer: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Görüntülenen CodeText'in rengini belirtin. Varsayılan değer: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. Özellikle [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) içinde [FontMode.Auto](../aztecencodemode/) kullanmanız önerilir. Varsayılan değer: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için [CodeLocation.None](../codelocation/) olarak ayarlayın. Varsayılan değer: 1D barkodlar için [CodeLocation.Below](../codelocation/) ve 2D barkodlar için [CodeLocation.None](../codelocation/). |
| [set_NoWrap](./set_nowrap/)(bool) | Metin içinde kelime kaydırmalarını (satır sonlarını) belirtin. Varsayılan değer: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | KodMetni ile [BarCode](../../aspose.barcode/) arasındaki boşluk, [Unit ](../unit/) biriminde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | 2D barkodlarda kodmetni yerine görüntülenecek metin. Şunlar için kullanılır: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Bu [CodetextParameters](./) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
