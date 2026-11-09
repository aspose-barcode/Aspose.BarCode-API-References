---
title: "DotCodeParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Параметры DotCode."
type: docs
weight: 34
url: /ru/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

Параметры DotCode.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Определяет количество столбцов. |
| [getECIEncoding()](#getECIEncoding--) | Определяет кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Определяет режим кодирования DotCode. |
| [getRows()](#getRows--) | Определяет количество строк. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Определяет идентификатор штрихкода режима структурного добавления DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Определяет количество штрихкодов режима структурного добавления DotCode. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setColumns(int value)](#setColumns-int-) | Определяет количество столбцов. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Определяет кодировку ECI. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Определяет режим кодирования DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. |
| [setRows(int value)](#setRows-int-) | Определяет количество строк. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Определяет идентификатор штрихкода режима структурного добавления DotCode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Определяет количество штрихкодов режима структурного добавления DotCode. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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


Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Определяет кодировку ECI. Используется, когда DotCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Определяет идентификатор штрихкода режима структурного добавления DotCode. Идентификатор начинается с 1 и не должен превышать количество штрихкодов. Значение по умолчанию: -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Определяет количество штрихкодов режима структурного добавления DotCode. Значение по умолчанию: -1. Количество должно быть в диапазоне от 1 до 35.

**Returns:**
int
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


Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Определяет кодировку ECI. Используется, когда DotCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Определяет идентификатор штрихкода режима структурного добавления DotCode. Идентификатор начинается с 1 и не должен превышать количество штрихкодов. Значение по умолчанию: -1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Определяет количество штрихкодов режима структурного добавления DotCode. Значение по умолчанию: -1. Количество должно быть в диапазоне от 1 до 35.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String — строка, представляющая этот [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

