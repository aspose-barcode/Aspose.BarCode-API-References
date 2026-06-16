---
title: AztecParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры Aztec.
type: docs
weight: 12
url: /ru/androidjava/com.aspose.barcode.generation/aztecparameters/
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
| [getAspectRatio()](#getAspectRatio--) | Соотношение высоты к ширине модуля 2D BarCode. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Получает режим кодирования Aztec. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Получает режим символа Aztec. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Получает режим кодирования Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [getLayersCount()](#getLayersCount--) | Получает количество слоёв символа Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). |
| [getSymbolMode()](#getSymbolMode--) | Получает режим символа Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Соотношение высоты к ширине модуля 2D BarCode. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Устанавливает режим кодирования Aztec. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Устанавливает режим символа Aztec. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Устанавливает режим кодирования Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Уровень коррекции ошибок для штрихкодов типа Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Устанавливает количество слоёв символа Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). |
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


Соотношение высоты к ширине модуля 2D BarCode.

**Returns:**
float
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Получает режим кодирования Aztec. Значение по умолчанию: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode — режим кодирования Aztec.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Уровень коррекции ошибок для штрих‑кодов типа Aztec. Значение должно быть от 5 до 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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
int — кодировка ECI.
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


Уровень коррекции ошибок для штрих‑кодов типа Aztec. Значение должно быть от 5 до 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Получает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для режима Compact и от 1 до 32 для режима Full Range. Значение по умолчанию: 0 (auto).

**Returns:**
int — количество слоёв символа Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен находиться в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно находиться в диапазоне от 1 до 26. Значение по умолчанию: 0.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка.

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
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


Соотношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.barcode.generation.AztecEncodeMode | режим кодирования Aztec. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Уровень коррекции ошибок для штрих‑кодов типа Aztec. Значение должно быть от 5 до 95.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | режим символа Aztec. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Устанавливает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1.

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


Уровень коррекции ошибок для штрих‑кодов типа Aztec. Значение должно быть от 5 до 95.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Устанавливает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для режима Compact и от 1 до 32 для режима Full Range. Значение по умолчанию: 0 (auto).

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


Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен находиться в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно находиться в диапазоне от 1 до 26. Значение по умолчанию: 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | режим символа Aztec. |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Строка, представляющая этот [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

