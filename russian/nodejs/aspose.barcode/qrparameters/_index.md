---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры QR."
type: docs
weight: 830
url: /ru/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Параметры QR.

```js
new QrParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [getECIEncoding()](#geteciencoding) | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Получает или задает значение, указывающее, следует ли кодировать специальные символы GS1 в режиме байтов для QR и RectMicroQR штрихкода |
| [getEncodeMode()](#getencodemode) | Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Уровень коррекции ошибок Рида-Соломона для штрихкода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Версия MicroQR-кода. От версии M1 до версии M4. Значение по умолчанию: MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [getQrEncodeMode()](#getqrencodemode) | Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Режим выбора QR / MicroQR. Выберите ForceQR для стандартных символов QR, Auto для MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Уровень коррекции ошибок Рида-Соломона для штрихкода QR. От низкого к высокому: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. см. QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Версия QR-кода. От Version1 до Version40 для QR кода и от M1 до M4 для MicroQr. Значение по умолчанию: QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Версия RectMicroQR-кода. От версии R7x59 до версии R17x139. Значение по умолчанию: RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Параметры структурированного добавления QR. |
| [getVersion()](#getversion) | Версия QR-кода. От Version1 до Version40. Значение по умолчанию: QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [setECIEncoding()](#seteciencoding) | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Получает или задает значение, указывающее, следует ли кодировать специальные символы GS1 в режиме байтов для QR и RectMicroQR штрихкода |
| [setEncodeMode()](#setencodemode) | Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Уровень коррекции ошибок Рида-Соломона для штрихкода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Версия MicroQR-кода. От версии M1 до версии M4. Значение по умолчанию: MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Режим выбора QR / MicroQR. Выберите ForceQR для стандартных символов QR, Auto для MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Уровень коррекции ошибок Рида-Соломона для штрихкода QR. От низкого к высокому: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. см. QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Версия QR-кода. От Version1 до Version40 для QR кода и от M1 до M4 для MicroQr. Значение по умолчанию: QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Версия RectMicroQR-кода. От версии R7x59 до версии R17x139. Значение по умолчанию: RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Параметры структурированного добавления QR. |
| [setVersion()](#setversion) | Версия QR-кода. От Version1 до Version40. Значение по умолчанию: QRVersion.Auto. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого QrParameters. |

### getAspectRatio() {#getaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### getECIEncoding() {#geteciencoding}

Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Они используются для передачи считывателю штрихкода деталей о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки наборов символов. Не поддерживается MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Получает или задает значение, указывающее, следует ли кодировать специальные символы GS1 в режиме байтов для штрихкодов QR и RectMicroQR. Если false, разделители GS1 могут быть закодированы как '%' в алфавитно-цифровом режиме согласно спецификации QR. Если true, групповые разделители GS1 кодируются в режиме байтов как символ 0x1D, а символы '%' также кодируются в режиме байтов для сохранения их как данных. Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '%' как разделителей GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Уровень коррекции ошибок Рида-Соломона для штрихкода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Версия MicroQR-кода. От версии M1 до версии M4. Значение по умолчанию: MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации каналов (Extended Channel Interpretation Identifiers). Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация состоит из всех известных кодировок наборов символов.

### getQrEncodeMode() {#getqrencodemode}

Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Режим выбора QR / MicroQR. Выберите ForceQR для стандартных символов QR, Auto для MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Уровень коррекции ошибок Рида-Соломона для штрихкода QR. От низкого к высокому: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. см. QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Версия QR-кода. От Version1 до Version40 для QR-кода и от M1 до M4 для MicroQr. Значение по умолчанию: QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Версия RectMicroQR-кода. От версии R7x59 до версии R17x139. Значение по умолчанию: RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Параметры структурированного добавления QR.

### getVersion() {#getversion}

Версия QR-кода. От Version1 до Version40. Значение по умолчанию: QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### setECIEncoding() {#seteciencoding}

Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Они используются для передачи считывателю штрихкода деталей о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки наборов символов. Не поддерживается MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Получает или задает значение, указывающее, следует ли кодировать специальные символы GS1 в режиме байтов для штрихкодов QR и RectMicroQR. Если false, разделители GS1 могут быть закодированы как '%' в алфавитно-цифровом режиме согласно спецификации QR. Если true, групповые разделители GS1 кодируются в режиме байтов как символ 0x1D, а символы '%' также кодируются в режиме байтов для сохранения их как данных. Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '%' как разделителей GS1.

| Параметр | Описание |
| --- | --- |
| значение | значение, указывающее, следует ли кодировать специальные символы GS1 в режиме байтов для штрихкодов QR и RectMicroQR. |

### setEncodeMode() {#setencodemode}

Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Уровень коррекции ошибок Рида-Соломона для штрихкода QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Версия MicroQR-кода. От версии M1 до версии M4. Значение по умолчанию: MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации каналов (Extended Channel Interpretation Identifiers). Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация состоит из всех известных кодировок наборов символов.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Тип символьной системы QR в режиме кодирования BarCode. Значение по умолчанию: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Режим выбора QR / MicroQR. Выберите ForceQR для стандартных символов QR, Auto для MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Уровень коррекции ошибок Рида-Соломона для штрихкода QR. От низкого к высокому: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. см. QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Версия QR-кода. От Version1 до Version40 для QR-кода и от M1 до M4 для MicroQr. Значение по умолчанию: QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Версия RectMicroQR-кода. От версии R7x59 до версии R17x139. Значение по умолчанию: RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Параметры структурированного добавления QR.

### setVersion() {#setversion}

Версия QR-кода. От Version1 до Version40. Значение по умолчанию: QRVersion.Auto.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого QrParameters.

**Returns:** A string that represents this QrParameters.
