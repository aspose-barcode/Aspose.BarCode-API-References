---
title: BarcodeParameters
second_title: Справочник по API Aspose.BarCode для .NET
description: Параметры генерации штрих-кода.
type: docs
weight: 500
url: /ru/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Параметры генерации штрих-кода.

```csharp
public class BarcodeParameters
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | Параметры штрих-кода AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Ацтекские параметры. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Цвет полос. Значение по умолчанию:Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Высота баров 1D штрихкодов в[`Unit`](../unit)значение. Игнорируется, если для свойстваAutoSizeModeустановлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Получить или установить значение сокращения полос, которое используется для компенсации растекания краски при печати. Значение по умолчанию:0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Всегда отображать цифру контрольной суммы в удобочитаемом тексте для штрих-кодов Code128 и GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Параметры Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Параметры блока кода. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Параметры Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Параметры кодового текста. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Параметры панели данных. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | Параметры DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | Параметры DotCode. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Указывает, объясняет ли символ "\" как escape-символ в свойстве CodeText. Используется только для Pdf417, DataMatrix, Code128 Если EnableEscape имеет значение true, "\" будет объяснен как специальный escape-символ. В противном случае "\" действует как обычный символ.  Aspose.BarCode поддерживает ввод десятичного кода ASCII и мнемоники для символов управляющего кода ASCII. Например, \013 и \\CR означают CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Получает или задает значение, указывающее, заполнены ли бары. Только для одномерных штрих-кодов. Значение по умолчанию:true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | Параметры композитного стержня GS1. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Включить контрольную сумму при генерации одномерных штрих-кодов. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | Параметры ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | Параметры MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Отступы штрих-кода. Значение по умолчанию:5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | Параметры PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | Параметры PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Почтовые параметры. Используется для Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | Параметры QR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Только для одномерных штрих-кодов. Если кодовый текст неверный и установлено значение true - будет выброшено исключение. В противном случае кодовый текст будет исправлен в соответствии со спецификацией штрих-кода. Исключение всегда будет вызываться для:Символики панели данных, если кодовый текст неверен. Исключение всегда не будет выдаваться для:AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128, если кодовый текст неверен. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Соотношение широких и узких полос. Значение по умолчанию:3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | x-размер — это наименьшая ширина блока штрихов или пробелов штрих-кода. Увеличение этого параметра приведет к увеличению ширины всего изображения штрих-кода. Игнорируется, если для свойстваAutoSizeModeустановлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |

### Смотрите также

* пространство имен [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
