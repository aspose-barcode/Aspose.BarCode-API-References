---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::CodetextParameters class. Параметры текста кода в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Параметры Codetext.

```cpp
class CodetextParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Получает выравнивание текста кода. Значение по умолчанию: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Укажите цвет отображаемого текста кода. Значение по умолчанию: Color.Black. |
| [get_Font](./get_font/)() const | Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет вычислен автоматически на основе значения xDimension. Рекомендуется использовать [FontMode.Auto](../aztecencodemode/), особенно в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). Значение по умолчанию: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Укажите расположение отображаемого CodeText, установите [CodeLocation.None](../codelocation/) для скрытия CodeText. Значение по умолчанию: [CodeLocation.Below](../codelocation/) для 1D штрихкодов и [CodeLocation.None](../codelocation/) для 2D штрихкодов. |
| [get_NoWrap](./get_nowrap/)() const | Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false. |
| [get_Space](./get_space/)() const | Расстояние между CodeText и [BarCode](../../aspose.barcode/) в значении [Unit ](../unit/). Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Текст, который будет отображаться вместо codetext в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |
| [set_Alignment](./set_alignment/)(TextAlignment) | Устанавливает выравнивание текста кода. Значение по умолчанию: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Укажите цвет отображаемого текста кода. Значение по умолчанию: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет вычислен автоматически на основе значения xDimension. Рекомендуется использовать [FontMode.Auto](../aztecencodemode/), особенно в [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). Значение по умолчанию: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Укажите расположение отображаемого CodeText, установите [CodeLocation.None](../codelocation/) для скрытия CodeText. Значение по умолчанию: [CodeLocation.Below](../codelocation/) для 1D штрихкодов и [CodeLocation.None](../codelocation/) для 2D штрихкодов. |
| [set_NoWrap](./set_nowrap/)(bool) | Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Расстояние между CodeText и [BarCode](../../aspose.barcode/) в значении [Unit ](../unit/). Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Текст, который будет отображаться вместо codetext в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [CodetextParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
