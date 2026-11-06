---
title: "Pdf417Parameters"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Параметры PDF417."
type: docs
weight: 58
url: /ru/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме Structured Append (тот же, что режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.

Эти примеры показывают, как кодировать нелинкованные режимы UCC/EAN-128 в GS1MicroPdf417

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Соотношение высоты к ширине модуля 2D‑штрихкода. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Количество столбцов. |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeMode()](#getEncodeMode--) | Определяет режим кодирования Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Получает тип символьного набора Pdf417 уровня коррекции ошибок штрихкода BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению. |
| [getMacroCharacters()](#getMacroCharacters--) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Имя получателя штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Имя файла штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Размер файла MacroPdf417 (необязательное поле). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Количество сегментов штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Используется, чтобы указать кодировщику, добавлять ли терминатор Macro PDF417 (кодовое слово 922) к сегменту. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Временная метка штрихкода MacroPdf417 (необязательное поле). |
| [getRows()](#getRows--) | Количество строк. |
| [getTruncate()](#getTruncate--) | Указывает, сокращён ли тип символьного набора Pdf417 штрихкода BarCode (для экономии места). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [isLinked()](#isLinked--) | Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 режимы. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Соотношение высоты к ширине модуля 2D‑штрихкода. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [setColumns(int value)](#setColumns-int-) | Количество столбцов. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Определяет режим кодирования Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Устанавливает тип символьного набора Pdf417 уровня коррекции ошибок штрихкода BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению. |
| [setLinked(boolean value)](#setLinked-boolean-) | Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 режимы. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Имя получателя штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Имя файла штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Размер файла MacroPdf417 (необязательное поле). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Количество сегментов штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Используется, чтобы указать кодировщику, добавлять ли терминатор Macro PDF417 (кодовое слово 922) к сегменту. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Временная метка штрихкода MacroPdf417 (необязательное поле). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setRows(int value)](#setRows-int-) | Количество строк. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Указывает, сокращён ли тип символьного набора Pdf417 штрихкода BarCode (для экономии места). |
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


Соотношение высоты к ширине модуля 2D‑штрихкода.

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


Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрихкода деталей о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

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


Получает тип символьного набора Pdf417 уровня коррекции ошибок штрихкода BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

Эти примеры показывают, как кодировать макросимволы в MicroPdf417

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2 байта) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Идентификаторы расширенной интерпретации каналов. Применяется к текстовым полям Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

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


Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрихкода MicroPDF417 (обязательное поле для режима Structured Append)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Используется, чтобы указать кодировщику, следует ли добавить терминальный кодовый символ Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

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


Является ли тип символьного набора Pdf417 штрихкода усечённым (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются правый индикатор строки и правый стоп‑шаблон.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без неё. Таким образом MicroPdf417 может быть декодирован как штрихкод Code 128.

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 режимы. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

Эти примеры показывают, как кодировать "Linked" UCC/EAN‑128 режимы в GS1MicroPdf417 и флаг связи (Linkage Flag) (918) в штрихкодах MicroPdf417 и Pdf417.

```

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


Соотношение высоты к ширине модуля 2D‑штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128.

Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без неё. Таким образом MicroPdf417 может быть декодирован как штрихкод Code 128.

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


Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрихкода деталей о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

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


Устанавливает тип символьного набора Pdf417 уровня коррекции ошибок штрихкода BarCode, варьирующийся от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию ошибок, что приводит к более крупному изображению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Тип символьного набора Pdf417 штрихкода имеет уровень коррекции ошибок от level0 до level8, где level0 означает отсутствие информации о коррекции ошибок, а level8 — лучшую коррекцию, что приводит к более крупному изображению. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьном наборе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 режимы. При символьных наборах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

Эти примеры показывают, как кодировать "Linked" UCC/EAN‑128 режимы в GS1MicroPdf417 и флаг связи (Linkage Flag) (918) в штрихкодах MicroPdf417 и Pdf417.

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None.

Эти примеры показывают, как кодировать макросимволы в MicroPdf417

```

```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2 байта) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Идентификаторы расширенной интерпретации каналов. Применяется к текстовым полям Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

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


Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрихкода MicroPDF417 (обязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Используется, чтобы указать кодировщику, следует ли добавить терминальный кодовый символ Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

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


Является ли тип символьного набора Pdf417 штрихкода усечённым (для экономии места). Также известен как CompactPDF417. В этом режиме удаляются правый индикатор строки и правый стоп‑шаблон.

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

