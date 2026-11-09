---
title: "AztecParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Параметры Aztec."
type: docs
weight: 12
url: /ru/java/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Параметры Aztec.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Получает режим кодирования Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [getLayersCount()](#getLayersCount--) | Получает количество слоёв символа Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Идентификатор штрихкода для режима Structured Append штрихкода Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Количество штрихкодов для режима Structured Append штрихкода Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). |
| [getSymbolMode()](#getSymbolMode--) | Получает режим символа Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Устанавливает режим кодирования Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Устанавливает количество слоёв символа Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Идентификатор штрихкода для режима Structured Append штрихкода Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Количество штрихкодов для режима Structured Append штрихкода Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Устанавливает режим символа Aztec. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Получает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1.

**Returns:**
int - кодировка ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Получает режим кодирования Aztec. Значение по умолчанию: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode — режим кодирования Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Получает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для компактного режима и от 1 до 32 для режима полного диапазона. Значение по умолчанию: 0 (авто).

**Returns:**
int — количество слоёв символа Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен быть в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Получает режим Aztec Symbol. Значение по умолчанию: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Устанавливает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Кодировка ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.barcode.generation.AztecEncodeMode | режим кодирования Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Устанавливает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для компактного режима и от 1 до 32 для режима полного диапазона. Значение по умолчанию: 0 (авто).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | количество слоёв символа Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен быть в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Устанавливает режим Aztec Symbol. Значение по умолчанию: AztecSymbolMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | режим Aztec Symbol. |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String — строка, представляющая этот [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

