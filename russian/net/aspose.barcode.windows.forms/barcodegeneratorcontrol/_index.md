---
title: BarCodeGeneratorControl
second_title: Справочник по API Aspose.BarCode для .NET
description: BarCode Windows Control перейдите на панель инструментов и добавьте Aspose.BarCode.dll  и вы увидите что BarcodeGeneratorControl появляется. см.
type: docs
weight: 1050
url: /ru/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, перейдите на панель инструментов и добавьте Aspose.BarCode.dll, , и вы увидите, что BarcodeGeneratorControl появляется. см.

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Получает или задает режим автоматического изменения размера штрих-кода. Значение по умолчанию — AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Цвет фона изображения штрих-кода. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | Высота изображения штрих-кода при[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) установлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Получает или задает параметры заполнения штрих-кода[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Тип кодирования штрих-кода (символика). Использование[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) чтобы получить текущие символы. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Ширина изображения штрих-кода при[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) установлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Цвет полос. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Высота штрихов одномерных штрих-кодов. Игнорируется, если[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) установлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Получает или задает параметры границы[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Подпись над изображением штрих-кода. Видеть[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Подпись под изображением штрих-кода. Видеть[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Всегда отображать цифру контрольной суммы в удобочитаемом тексте для штрих-кодов Code128 и GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Данные для кодирования, разные типы штрих-кода могут иметь разные ограничения длины CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Получает или задает параметры CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Указывает, объясняет ли символ "\" как escape-символ в свойстве CodeText. Используется только для Pdf417, DataMatrix, Code128 Если EnableEscape имеет значение true, «\» будет объяснен как специальный управляющий символ. В противном случае "\" действует как обычный символ. Aspose.BarCode поддерживает ввод десятичного кода ASCII и мнемоники для символов управляющего кода ASCII. Например, \013 и \\CR означают CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Тип кодирования штрих-кода (символика). Использование[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) чтобы получить текущие символы. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Получает или задает значение, указывающее, заполнены ли столбцы. Только для одномерных штрих-кодов. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Включить контрольную сумму во время генерации штрих-кодов 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Получает или задает разрешение изображения штрих-кода. Одно значение для обоих размеров. Значение по умолчанию: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | Угол поворота изображения штрих-кода, измеряемый в градусах, например, RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота. Если RotationAngle НЕ равен 90, 180, 270 или 0, сканеру может быть сложнее считывать изображение. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Особые параметры |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Только для одномерных штрих-кодов. Если кодовый текст неверен и установлено значение true, будет выдано исключение. В противном случае кодовый текст будет исправлен в соответствии со спецификацией штрих-кода. Исключение всегда будет выдаваться для: Символики панели данных, если кодовый текст неверен. Исключение всегда не будет выдаваться для: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128, если кодовый текст неверен. . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Соотношение широких и узких столбцов. Значение по умолчанию: 3, то есть широкие столбцы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | Размер по оси X — это наименьшая ширина единицы штрихов или пробелов штрих-кода.[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) установлено значение AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |

### Смотрите также

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* пространство имен [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
