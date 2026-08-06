---
title: HanXinParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры Han Xin.
type: docs
weight: 50
url: /ru/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Параметры Han Xin.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getEncodeMode()](#getEncodeMode--) | Режим кодирования HanXin. |
| [getErrorLevel()](#getErrorLevel--) | Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | Идентификаторы расширенной интерпретации канала. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | Режим кодирования HanXin. |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. |
| [getHanXinVersion()](#getHanXinVersion--) | Версия кода HanXin. |
| [getVersion()](#getVersion--) | Версия кода HanXin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Идентификаторы расширенной интерпретации канала. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | Режим кодирования HanXin. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | Версия кода HanXin. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters). |
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


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрихкода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация содержит все известные кодировки наборов символов.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


Режим кодирования HanXin. Значение по умолчанию: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. От низкого к высокому: L1, L2, L3, L4. см. ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрихкода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация содержит все известные кодировки наборов символов.

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


Режим кодирования HanXin. Значение по умолчанию: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. От низкого к высокому: L1, L2, L3, L4. см. ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


Версия кода HanXin. От Version01 до Version84 для кода Han Xin. Значение по умолчанию — Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


Версия кода HanXin. От Version01 до Version84 для кода Han Xin. Значение по умолчанию — Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Идентификаторы расширенной интерпретации канала. Они используются для передачи считывателю штрихкода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация содержит все известные кодировки наборов символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


Режим кодирования HanXin. Значение по умолчанию: EncodeMode.Mixed.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Уровень коррекции ошибок Рида-Соломона для штрихкода Han Xin. От низкого к высокому: L1, L2, L3, L4. см. ErrorLevel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


Версия кода HanXin. От Version01 до Version84 для кода Han Xin. Значение по умолчанию — Version.Auto.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).

**Returns:**
java.lang.String — строка, представляющая этот [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).
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

