---
title: Pdf417ExtendedParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Сохраняет метаданные MacroPdf417 распознанного штрихкода
type: docs
weight: 40
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Сохраняет метаданные MacroPdf417 распознанного штрихкода

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному  Pdf417ExtendedParameters  значению. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Имя получателя Macro PDF417 (необязательно). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Контрольная сумма Macro PDF417 (необязательно). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Получает идентификатор файла штрихкода, доступно только с MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Имя файла Macro PDF417 (необязательно). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Размер файла Macro PDF417 (необязательно). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Получает идентификатор сегмента штрихкода, доступно только с MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Получает количество сегментов штрихкода macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Имя отправителя Macro PDF417 (необязательно). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Указывает, является ли сегмент последним сегментом файла Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Временная метка Macro PDF417 (необязательно). |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [isCode128Emulation()](#isCode128Emulation--) | Флаг, указывающий, что штрихкод MicroPdf417 закодирован кодовыми словами эмуляции Code 128 908, 909, 910 или 911. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все параметры только значения по умолчанию. |
| [isLinked()](#isLinked--) | Флаг, указывающий, что штрихкод должен быть связан с 1D штрихкодом. |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого  Pdf417ExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному  Pdf417ExtendedParameters  значению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Имя получателя Macro PDF417 (необязательно).

**Returns:**
java.lang.String - Имя получателя.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Контрольная сумма Macro PDF417 (необязательно).

**Returns:**
int - Контрольная сумма.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Получает идентификатор файла штрихкода, доступно только с MacroPdf417.

Значение: Идентификатор файла для MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Имя файла Macro PDF417 (необязательно).

**Returns:**
java.lang.String - Имя файла.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Размер файла Macro PDF417 (необязательно).

**Returns:**
int - Размер файла.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Получает идентификатор сегмента штрихкода, доступно только с MacroPdf417.

Значение: Идентификатор сегмента штрихкода.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Получает количество сегментов штрихкода macro pdf417. Значение по умолчанию — -1.

Значение: Количество сегментов.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Имя отправителя Macro PDF417 (необязательно).

**Returns:**
java.lang.String - Имя отправителя
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Указывает, является ли сегмент последним сегментом файла Macro PDF417.

**Returns:**
boolean - Завершитель.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Временная метка Macro PDF417 (необязательно).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Флаг, указывающий, что штрихкод MicroPdf417 закодирован кодовыми словами эмуляции Code 128 908, 909, 910 или 911.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все параметры только значения по умолчанию.

Значение: Возвращает  **true**  если все параметры имеют только значения по умолчанию; в противном случае  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Флаг, указывающий, что штрихкод должен быть связан с 1D штрихкодом.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого  Pdf417ExtendedParameters .

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

