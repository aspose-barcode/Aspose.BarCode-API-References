---
title: Pdf417Parameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры PDF417.
type: docs
weight: 60
url: /ru/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме Structured Append (тот же, что режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.

Эти примеры показывают, как кодировать режимы UCC/EAN-128 без ссылки в GS1MicroPdf417

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Соотношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Количество столбцов. |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeMode()](#getEncodeMode--) | Определяет режим кодирования Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Получает тип символьной системы Pdf417 уровня коррекции ошибок BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению. |
| [getMacroCharacters()](#getMacroCharacters--) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Имя получателя штрих‑кода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Имя файла штрих‑кода MacroPdf417 (необязательное поле). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Размер файла MacroPdf417 (необязательное поле). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Используется, чтобы указать кодировщику, добавлять ли макро PDF417 Terminator (кодовое слово 922) в сегмент. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Метка времени штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Тип символьного набора Pdf417 для режима уплотнения штрих‑кода. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Определяет режим кодирования Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Получает тип символьной системы Pdf417 уровня коррекции ошибок BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | Имя получателя штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | Имя файла штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | Размер файла MacroPdf417 (необязательное поле). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Используется, чтобы указать кодировщику, добавлять ли макро PDF417 Terminator (кодовое слово 922) в сегмент. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | Метка времени штрих‑кода MacroPdf417 (необязательное поле). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для уменьшения места). |
| [getRows()](#getRows--) | Количество строк. |
| [getTruncate()](#getTruncate--) | Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для уменьшения места). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [isLinked()](#isLinked--) | Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Соотношение высоты к ширине модуля 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [setColumns(int value)](#setColumns-int-) | Количество столбцов. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Определяет режим кодирования Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Устанавливает тип символьного набора Pdf417 для уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |
| [setLinked(boolean value)](#setLinked-boolean-) | Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Имя получателя штрих‑кода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Имя файла штрих‑кода MacroPdf417 (необязательное поле). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Размер файла MacroPdf417 (необязательное поле). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Используется, чтобы указать кодировщику, добавлять ли макро PDF417 Terminator (кодовое слово 922) в сегмент. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Метка времени штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Тип символьного набора Pdf417 для режима уплотнения штрих‑кода. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Определяет режим кодирования Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Устанавливает тип символьного набора Pdf417 для уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | Имя получателя штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | Имя файла штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | Размер файла MacroPdf417 (необязательное поле). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Используется, чтобы указать кодировщику, добавлять ли макро PDF417 Terminator (кодовое слово 922) в сегмент. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | Метка времени штрих‑кода MacroPdf417 (необязательное поле). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для уменьшения места). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setRows(int value)](#setRows-int-) | Количество строк. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для уменьшения места). |
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


Соотношение высоты к ширине модуля 2D BarCode.

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


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки набора символов.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Получает тип символьной системы Pdf417 уровня коррекции ошибок BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с MicroPdf417 и кодировать режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

Эти примеры показывают, как кодировать макросимволы в MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Имя получателя штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

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


Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Имя файла штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

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


Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Используется, чтобы сообщить кодировщику, следует ли добавить Macro PDF417 Terminator (кодовое слово 922) в сегмент. Применяется только для Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Метка времени штрих‑кода MacroPdf417 (необязательное поле). Метка времени штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append)

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Тип символьного набора Pdf417 для режима уплотнения штрих‑кода. Значение по умолчанию: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки набора символов.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Получает тип символьной системы Pdf417 уровня коррекции ошибок BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


Имя получателя штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


Имя файла штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Используется, чтобы сообщить кодировщику, следует ли добавить Macro PDF417 Terminator (кодовое слово 922) в сегмент. Применяется только для Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


Метка времени штрих‑кода MacroPdf417 (необязательное поле). Метка времени штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются индикатор правой строки и правый стоп‑шаблон.

**Returns:**
boolean
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


Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются индикатор правой строки и правый стоп‑шаблон.

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


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без него. Таким образом MicroPdf417 может быть декодирован как штрих‑код Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

Эти примеры показывают, как кодировать режимы "Linked" UCC/EAN-128 в GS1MicroPdf417 и флаг связи (Linkage Flag) (918) в штрих‑кодах MicroPdf417 и Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

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


Соотношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без него. Таким образом MicroPdf417 может быть декодирован как штрих‑код Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

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


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки набора символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Устанавливает тип символьного набора Pdf417 для уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Уровень коррекции ошибок типа символьного набора Pdf417 штрих‑кода, варьирующий от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

Эти примеры показывают, как кодировать режимы "Linked" UCC/EAN-128 в GS1MicroPdf417 и флаг связи (Linkage Flag) (918) в штрих‑кодах MicroPdf417 и Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с MicroPdf417 и кодировать режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

Эти примеры показывают, как кодировать макросимволы в MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Имя получателя штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

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


Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Имя файла штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

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


Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Используется, чтобы сообщить кодировщику, следует ли добавить Macro PDF417 Terminator (кодовое слово 922) в сегмент. Применяется только для Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Метка времени штрих‑кода MacroPdf417 (необязательное поле). Метка времени штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Тип символьного набора Pdf417 для режима уплотнения штрих‑кода. Значение по умолчанию: Pdf417CompactionMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки набора символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Устанавливает тип символьного набора Pdf417 для уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Уровень коррекции ошибок типа символьного набора Pdf417 штрих‑кода, варьирующий от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


Имя получателя штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


Имя файла штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и заканчивается значением MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


Количество сегментов штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


Имя отправителя штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Используется, чтобы сообщить кодировщику, следует ли добавить Macro PDF417 Terminator (кодовое слово 922) в сегмент. Применяется только для Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


Метка времени штрих‑кода MacroPdf417 (необязательное поле). Метка времени штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются индикатор правой строки и правый стоп‑шаблон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Указывает, усечён ли тип символьного набора Pdf417 штрих‑кода (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются индикатор правой строки и правый стоп‑шаблон.

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
java.lang.String — строка, представляющая этот объект [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

