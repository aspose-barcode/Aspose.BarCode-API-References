---
title: MaxiCodeParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры MaxiCode.
type: docs
weight: 57
url: /ru/androidjava/com.aspose.barcode.generation/maxicodeparameters/
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
| [getAspectRatio()](#getAspectRatio--) | Соотношение высоты к ширине модуля 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Получает кодировку ECI. |
| [getEncodeMode()](#getEncodeMode--) | Получает режим кодирования MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Получает режим кодирования MaxiCode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Получает режим кодирования MaxiCode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Получает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Получает количество штрих‑кодов MaxiCode в режиме структурированного добавления. |
| [getMode()](#getMode--) | Получает режим кодирования MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Получает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Получает количество штрих‑кодов MaxiCode в режиме структурированного добавления. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Соотношение высоты к ширине модуля 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Устанавливает кодировку ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Устанавливает режим кодирования MaxiCode. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Устанавливает режим кодирования MaxiCode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Устанавливает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Устанавливает количество штрих‑кодов MaxiCode в режиме структурированного добавления. |
| [setMode(int value)](#setMode-int-) | Устанавливает режим кодирования MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Устанавливает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Устанавливает количество штрих‑кодов MaxiCode в режиме структурированного добавления. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

**Returns:**
int — кодировка ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Получает режим кодирования MaxiCode.

**Returns:**
int - режим кодирования MaxiCode.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Получает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

**Returns:**
int - идентификатор штрих‑кода MaxiCode в режиме структурированного добавления.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Получает количество штрих‑кодов MaxiCode в режиме структурированного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1

**Returns:**
int - количество штрих‑кодов MaxiCode в режиме структурированного добавления.
### getMode() {#getMode--}
```
public final int getMode()
```


Получает режим кодирования MaxiCode.

**Returns:**
int - режим кодирования MaxiCode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Получает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

**Returns:**
int - идентификатор штрих‑кода MaxiCode в режиме структурированного добавления.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Получает количество штрих‑кодов MaxiCode в режиме структурированного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1

**Returns:**
int - количество штрих‑кодов MaxiCode в режиме структурированного добавления.
### hashCode() {#hashCode--}
```
public native int hashCode()
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


Соотношение высоты к ширине модуля 2D BarCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1.

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

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | режим кодирования MaxiCode. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Устанавливает режим кодирования MaxiCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | режим кодирования MaxiCode. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Устанавливает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Устанавливает количество штрих‑кодов MaxiCode в режиме структурированного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Количество штрихкодов MaxiCode в режиме структурного добавления. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Устанавливает режим кодирования MaxiCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | режим кодирования MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Устанавливает идентификатор штрих‑кода MaxiCode в режиме структурированного добавления. Идентификатор должен быть значением от 1 до 8. Значение по умолчанию: 0

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
| значение | int | Количество штрихкодов MaxiCode в режиме структурного добавления. |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Строка, представляющая этот [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

