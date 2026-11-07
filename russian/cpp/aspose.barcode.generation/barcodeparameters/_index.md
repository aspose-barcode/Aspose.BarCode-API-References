---
title: "Aspose::BarCode::Generation::BarcodeParameters класс"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::BarcodeParameters класс. Параметры генерации штрихкода в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Параметры генерации штрихкода.

```cpp
class BarcodeParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | Параметры штрихкода AustralianPost. |
| [get_Aztec](./get_aztec/)() const | Параметры Aztec. |
| [get_BarColor](./get_barcolor/)() const | Цвет полос. Значение по умолчанию: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Высота полос 1D штрихкодов в значении [Unit](../unit/). Игнорируется, если свойство [BaseGenerationParameters::AutoSizeMode](../) установлено в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Получает или задает значение уменьшения полос, используемое для компенсации растекания чернил при печати. Значение по умолчанию: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Всегда отображать цифру контрольной суммы в читаемом человеком тексте для штрихкодов Code128 и GS1Code128. |
| [get_Codabar](./get_codabar/)() const | Параметры Codabar. |
| [get_Codablock](./get_codablock/)() const | Параметры Codablock. |
| [get_Code128](./get_code128/)() const | Параметры Code128. |
| [get_Code16K](./get_code16k/)() const | Параметры Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Параметры Codetext. |
| [get_Coupon](./get_coupon/)() const | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Параметры Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Параметры DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Параметры DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Получает значение, указывающее, заполнены ли полосы. Только для 1D‑штрихкодов. Значение по умолчанию: true. |
| [get_GS1](./get_gs1/)() const | Параметры GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | Параметры GS1 Composite Bar. |
| [get_HanXin](./get_hanxin/)() const | Параметры HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Параметры ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Параметры MaxiCode. |
| [get_Padding](./get_padding/)() const | Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Параметры PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | Параметры PDF417. |
| [get_Postal](./get_postal/)() const | Почтовые параметры. Используется для Postnet, Planet. |
| [get_QR](./get_qr/)() const | Параметры QR, MicroQR и RectMicroQR. |
| [get_Supplement](./get_supplement/)() const | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Только для 1D‑штрихкодов. Если текст кода неверен и значение установлено в true — будет выброшено исключение. В противном случае текст кода будет скорректирован в соответствии со спецификацией штрихкода. Исключение всегда будет выброшено для: символьной системы Databar, если текст кода неверен. Исключение никогда не будет выброшено для: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, символьной системы Code128, если текст кода неверен. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Соотношение широких полос к узким полосам. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | x-dimension — это наименьшая ширина единицы [BarCode](../../aspose.barcode/) полос или пробелов. Увеличение этого параметра увеличит общую ширину изображения штрихкода. Игнорируется, если свойство [BaseGenerationParameters::AutoSizeMode](../) установлено в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Цвет полос. Значение по умолчанию: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Высота полос 1D штрихкодов в значении [Unit](../unit/). Игнорируется, если свойство [BaseGenerationParameters::AutoSizeMode](../) установлено в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Получает или задает значение уменьшения полос, используемое для компенсации растекания чернил при печати. Значение по умолчанию: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Всегда отображать цифру контрольной суммы в читаемом человеком тексте для штрихкодов Code128 и GS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | Устанавливает значение, указывающее, заполнены ли полосы. Только для 1D‑штрихкодов. Значение по умолчанию: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | Параметры GS1 Composite Bar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Только для 1D‑штрихкодов. Если текст кода неверен и значение установлено в true — будет выброшено исключение. В противном случае текст кода будет скорректирован в соответствии со спецификацией штрихкода. Исключение всегда будет выброшено для: символьной системы Databar, если текст кода неверен. Исключение никогда не будет выброшено для: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, символьной системы Code128, если текст кода неверен. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Соотношение широких полос к узким полосам. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension — это наименьшая ширина единицы [BarCode](../../aspose.barcode/) полос или пробелов. Увеличение этого параметра увеличит общую ширину изображения штрихкода. Игнорируется, если свойство [BaseGenerationParameters::AutoSizeMode](../) установлено в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
