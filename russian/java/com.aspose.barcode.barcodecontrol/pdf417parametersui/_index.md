---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "Обёртка UI для класса com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /ru/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

Обёртка UI для класса com.aspose.barcode.generation.Pdf417Parameters.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Количество столбцов. |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeMode()](#getEncodeMode--) | Тип символьного набора Pdf417 в режиме кодирования BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Возвращает тип символьного набора Pdf417 уровня коррекции ошибок BarCode в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |
| [getMacroCharacters()](#getMacroCharacters--) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Имя получателя штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Возвращает идентификатор файла штрихкода macro Pdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Имя файла штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Размер файла MacroPdf417 (необязательное поле). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Возвращает идентификатор сегмента штрихкода macro Pdf417, который начинается с 0 и до MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Возвращает количество сегментов штрихкода macro Pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Используется, чтобы сообщить кодировщику, следует ли добавить терминатор Macro PDF417 (кодовое слово 922) к сегменту. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Метка времени штрихкода MacroPdf417 (необязательное поле). |
| [getRows()](#getRows--) | Количество строк. |
| [getTruncate()](#getTruncate--) | Определяет, усечён ли тип символьного набора Pdf417 BarCode (для экономии места). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и 909, также может кодировать 910 и 911, которые просто указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [isLinked()](#isLinked--) | Определяет связанные режимы с GS1MicroPdf417, MicroPdf417 и Pdf417 штрихкодами. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d режимы UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и 909, также может кодировать 910 и 911, которые просто указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [setColumns(int value)](#setColumns-int-) | Количество столбцов. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Тип символьного набора Pdf417 в режиме кодирования BarCode. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Устанавливает тип символьного набора Pdf417 уровня коррекции ошибок BarCode в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |
| [setLinked(boolean value)](#setLinked-boolean-) | Определяет связанные режимы с GS1MicroPdf417, MicroPdf417 и Pdf417 штрихкодами. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d режимы UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Имя получателя штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Устанавливает идентификатор файла штрихкода macro Pdf417. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Имя файла штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Размер файла MacroPdf417 (необязательное поле). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Устанавливает идентификатор сегмента штрихкода macro Pdf417, который начинается с 0 и до MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Устанавливает количество сегментов макро‑штрихкода Pdf417. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Используется, чтобы сообщить кодировщику, следует ли добавить терминатор Macro PDF417 (кодовое слово 922) к сегменту. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Метка времени штрихкода MacroPdf417 (необязательное поле). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setRows(int value)](#setRows-int-) | Количество строк. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Определяет, усечён ли тип символьного набора Pdf417 BarCode (для экономии места). |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Отношение высоты к ширине модуля 2D BarCode.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Количество столбцов.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи сканеру штрихкода деталей о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Тип символогии Pdf417 для режима кодирования BarCode. Значение по умолчанию: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Возвращает тип символьного набора Pdf417 уровня коррекции ошибок BarCode в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Имя получателя макро‑штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Контрольная сумма макро‑штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT-16: x^16 + x^12 + x^5 + 1.

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Получает идентификатор файла макро‑штрихкода Pdf417. Используется для MacroPdf417.

**Returns:**
int — идентификатор файла макро‑штрихкода Pdf417.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Имя файла макро‑штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Возвращает идентификатор сегмента штрихкода macro Pdf417, который начинается с 0 и до MacroSegmentsCount - 1.

**Returns:**
int — идентификатор сегмента макро‑штрихкода Pdf417, начинающийся с 0, до MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Возвращает количество сегментов штрихкода macro Pdf417.

**Returns:**
int — количество сегментов макро‑штрихкода Pdf417.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Имя отправителя макро‑штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Используется для указания кодировщику, следует ли добавить терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только к Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Метка времени макро‑штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Количество строк.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Определяет, усечён ли тип символьного набора Pdf417 BarCode (для экономии места).

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и 909, также может кодировать 910 и 911, которые просто указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Определяет связанные режимы с GS1MicroPdf417, MicroPdf417 и Pdf417 штрихкодами. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d режимы UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Отношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и 909, также может кодировать 910 и 911, которые просто указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Количество столбцов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи сканеру штрихкода деталей о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Тип символогии Pdf417 для режима кодирования BarCode. Значение по умолчанию: Pdf417EncodeMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Устанавливает тип символьного набора Pdf417 уровня коррекции ошибок BarCode в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Тип символогии Pdf417 для уровня коррекции ошибок BarCode, варьирующий от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Определяет связанные режимы с GS1MicroPdf417, MicroPdf417 и Pdf417 штрихкодами. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d режимы UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Имя получателя макро‑штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Контрольная сумма макро‑штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT-16: x^16 + x^12 + x^5 + 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Устанавливает идентификатор файла макро‑штрихкода Pdf417. Используется для MacroPdf417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Идентификатор файла макро‑штрихкода Pdf417. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Имя файла макро‑штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Устанавливает идентификатор сегмента штрихкода macro Pdf417, который начинается с 0 и до MacroSegmentsCount - 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Идентификатор сегмента макро‑штрихкода Pdf417, начинающийся с 0, до MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Устанавливает количество сегментов макро‑штрихкода Pdf417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Количество сегментов макро‑штрихкода Pdf417. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Имя отправителя макро‑штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Используется для указания кодировщику, следует ли добавить терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только к Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Метка времени макро‑штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Количество строк.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Определяет, усечён ли тип символьного набора Pdf417 BarCode (для экономии места).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String — строка, представляющая этот [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

