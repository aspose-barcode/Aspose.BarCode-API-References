---
title: "BarcodeParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Параметры генерации штрихкода.

Тип BarcodeParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| x_dimension | x-dimension — это наименьшая ширина единицы штрихов или пробелов BarCode.<br/>            Увеличение этого параметра увеличит общую ширину изображения штрих‑кода.<br/>            Игнорируется, если свойство [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| bar_height | Высота штрихов 1D‑штрих‑кодов в значении [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Игнорируется, если свойство [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| bar_color | Цвет штрихов.<br/>            Значение по умолчанию: Color.Black. |
| padding | Отступы штрих‑кода.<br/>            Значение по умолчанию: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Всегда отображать контрольную цифру в читаемом человеком тексте для штрих‑кодов Code128 и GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Только для 1D‑штрих‑кодов.<br/>            Если текст кода неверен и значение установлено в true — будет выброшено исключение. В противном случае текст кода будет скорректирован в соответствии со спецификацией штрих‑кода.<br/>            Исключение всегда будет выброшено для: символьной системы Databar, если текст кода неверен.<br/>            Исключение никогда не будет выброшено для: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, символьной системы Code128, если текст кода неверен. |
| wide_narrow_ratio | Отношение широких штрихов к узким.<br/>            Значение по умолчанию: 3, то есть широкие штрихи в 3 раза шире узких.<br/>            Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| code_text_parameters | Параметры Codetext. |
| filled_bars | Получает или задает значение, указывающее, заполнены ли штрихи.<br/>            Только для 1D‑штрих‑кодов.<br/>            Значение по умолчанию: true. |
| bar_width_reduction | Получает или задает значение уменьшения ширины штрихов, используемое для компенсации растекания чернил при печати.<br/>            Значение по умолчанию: 0 |
| postal | Почтовые параметры. Используется для Postnet, Planet. |
| patch_code | Параметры PatchCode. |
| australian_post | Параметры штрихкода AustralianPost. |
| data_bar | Параметры Databar. |
| gs1_composite_bar | Параметры GS1 Composite Bar. |
| codablock | Параметры Codablock. |
| data_matrix | Параметры DataMatrix. |
| code_16k | Параметры Code16K. |
| dot_code | Параметры DotCode. |
| itf | Параметры ITF. |
| pdf417 | Параметры PDF417. |
| qr | Параметры QR, MicroQR и RectMicroQR. |
| supplement | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Параметры MaxiCode. |
| aztec | Параметры Aztec. |
| code128 | Параметры Code128. |
| codabar | Параметры Codabar. |
| coupon | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | Параметры HanXin. |
| gs1 | Параметры GS1. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

