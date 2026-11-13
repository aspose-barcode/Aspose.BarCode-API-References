---
title: "QrParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

Параметры QR.

Тип QrParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| eci_encoding | Идентификаторы расширенной интерпретации канала. Он используется для передачи сканеру штрихкода деталей<br/>            о используемых ссылках для кодирования данных в символе.<br/>            Текущая реализация включает все известные кодировки наборов символов.<br/>            Не поддерживается MicroQR. |
| encode_mode | Тип символьной схемы QR для режима кодирования BarCode.<br/>            Значение по умолчанию: QREncodeMode.Auto. |
| error_level | Уровень коррекции ошибок Рид-Соломона для штрихкодов QR, MicroQR и RectMicroQR.<br/>             От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QERrrorLevel. |
| version | Версия QR‑кода. От Version1 до Version40.<br/>            Значение по умолчанию: QRVersion.Auto. |
| micro_qr_version | Версия MicroQR‑кода. От версии M1 до версии M4.<br/>            Значение по умолчанию: MicroQRVersion.Auto. |
| rect_micro_qr_version | Версия RectMicroQR‑кода. От версии R7x59 до версии R17x139.<br/>            Значение по умолчанию: RectMicroQRVersion.Auto. |
| aspect_ratio | Соотношение высоты к ширине модуля 2D BarCode. |
| structured_append | Параметры структурированного дополнения QR.<br/>            Режим структурированного дополнения не поддерживается штрихкодами MicroQR и RectMicroQR. |
| encode_gs1_separator_in_byte_mode |  |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

