---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Параметры генерации изображения штрихкода.

Тип BaseGenerationParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| use_anti_alias | Получает или задает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
| back_color | Фоновый цвет изображения штрихкода.<br/>            Значение по умолчанию: Color.White.<br/>            См. [Color](/barcode/python-net/aspose.drawing/color/). |
| разрешение | Получает или задает разрешение изображения BarCode.<br/>            Одно значение для обеих измерений.<br/>            Значение по умолчанию: 96 dpi. |
| rotation_angle | Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота.<br/>            Если RotationAngle НЕ равен 90, 180, 270 или 0, это может увеличить сложность считывания изображения сканером.<br/>            Значение по умолчанию: 0. |
| caption_above | Подпись над изображением BarCode. См. [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Подпись под изображением BarCode. См. [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Параметры изображения. См. [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Указывает различные типы режимов автоматического масштабирования.<br/>            Значение по умолчанию: AutoSizeMode.None. |
| image_height | Высота изображения BarCode, когда свойство [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| image_width | Ширина изображения BarCode, когда свойство [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation. |
| barcode | Получает [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) содержащий все свойства штрихкода. |
| border | Получает [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) содержащий все свойства конфигурации границы штрихкода. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

