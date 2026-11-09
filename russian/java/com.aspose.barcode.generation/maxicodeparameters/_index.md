---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Параметры MaxiCode."
type: docs
weight: 55
url: /ru/java/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Параметры MaxiCode.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Отношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Получает режим кодирования MaxiCode. |
| [getMode()](#getMode--) | Получает режим кодирования MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Получает идентификатор штрих‑кода MaxiCode в режиме структурного добавления. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Получает количество штрих‑кодов MaxiCode в режиме структурного добавления. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Отношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Устанавливает идентификатор штрихкода MaxiCode в режиме структурного добавления. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Устанавливает количество штрихкодов MaxiCode в режиме структурного добавления. |
| [toString()](#toString--) | Возвращает читаемое строковое представление этого [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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


Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Returns:**
int - кодировка ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Получает режим кодирования MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Получает идентификатор штрихкода MaxiCode в режиме структурного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

**Returns:**
int — идентификатор штрих‑кода MaxiCode в режиме структурного добавления.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Получает количество штрихкодов MaxiCode в режиме структурного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрихкодов). Значение по умолчанию: -1

**Returns:**
int — количество штрих‑кодов MaxiCode в режиме структурного добавления.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
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


Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode имеет значение Auto. Значение по умолчанию: ISO-8859-1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Кодировка ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | режим кодирования MaxiCode. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Устанавливает режим кодирования MaxiCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | режим кодирования MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Устанавливает идентификатор штрихкода MaxiCode в режиме структурного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Устанавливает количество штрих‑кодов MaxiCode в режиме структурированного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | количество штрих‑кодов MaxiCode в режиме структурированного добавления. |

### toString() {#toString--}
```
public String toString()
```


Возвращает читаемое строковое представление этого [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String — строка, представляющая этот [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

