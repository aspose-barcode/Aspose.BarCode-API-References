---
title: "CodetextParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Параметры Codetext.

Тип CodetextParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| two_d_display_text | Текст, который будет отображаться вместо текста кода в 2D штрих-кодах.<br/>            Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension.<br/>            Рекомендуется использовать FontMode.Auto, особенно в AutoSizeMode.Nearest или AutoSizeMode.Interpolation.<br/>            Значение по умолчанию: FontMode.Auto. |
| font | Укажите шрифт отображаемого текста кода.<br/>            Значение по умолчанию: Arial 5pt regular.<br/>            Игнорируется, если FontMode установлен в FontMode.Auto. |
| space | Расстояние между текстом кода и штрих-кодом в значении [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Значение по умолчанию: 2pt.<br/>            Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| выравнивание | Получает или задает выравнивание текста кода.<br/>            Значение по умолчанию: StringAlignment.Center. |
| цвет | Укажите отображаемый цвет CodeText.<br/>            Значение по умолчанию: Color.Black. |
| расположение | Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText.<br/>            Значение по умолчанию: CodeLocation.Below для 1D штрихкодов и CodeLocation.None для 2D штрихкодов. |
| no_wrap | Укажите переносы слов (разрывы строк) в тексте.<br/>            Значение по умолчанию: false. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

