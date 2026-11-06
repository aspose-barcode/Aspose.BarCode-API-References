---
title: "MailmarkCodetext"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Класс для кодирования и декодирования текста, встроенного в 4‑состояний код Royal Mailmark."
type: docs
weight: 24
url: /ru/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Класс для кодирования и декодирования текста, встроенного в 4‑состояний код Royal Mailmark.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Инициализирует новый экземпляр класса  MailmarkCodetext  . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Получает тип штрих‑кода. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null или Тест "1" - 1C (Розничный) "2" - 2C (Розничный) "3" - 3C (Розничный) "4" - Premium (РозничныйПубликационный Письмо) (для потенциального будущего использования) "5" - Deferred (Розничный) "6" - Air (Розничный) (для потенциального будущего использования) "7" - Surface (Розничный) (для потенциального будущего использования) "8" - Premium (Сетевой Доступ) "9" - Standard (Сетевой Доступ) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Создать кодтекст из данных Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC и DP должны соответствовать формату PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null или Тест "1" \\u2013 Буква "2" \\u2013 Большая Буква |
| [getItemID()](#getItemID--) | Максимальное значение равно 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Максимальные значения: 99 для штрихкода C и 999999 для штрихкода L. |
| [getVersionID()](#getVersionID--) | В настоящее время "1" \\u2013 Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Инициализирует данные Mailmark из построенного кодтекста. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null или Тест "1" - 1C (Розничный) "2" - 2C (Розничный) "3" - 3C (Розничный) "4" - Premium (РозничныйПубликационный Письмо) (для потенциального будущего использования) "5" - Deferred (Розничный) "6" - Air (Розничный) (для потенциального будущего использования) "7" - Surface (Розничный) (для потенциального будущего использования) "8" - Premium (Сетевой Доступ) "9" - Standard (Сетевой Доступ) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC и DP должны соответствовать формату PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null или Тест "1" \\u2013 Буква "2" \\u2013 Большая Буква |
| [setItemID(int value)](#setItemID-int-) | Максимальное значение равно 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Максимальные значения: 99 для штрихкода C и 999999 для штрихкода L. |
| [setVersionID(int value)](#setVersionID-int-) | В настоящее время "1" \\u2013 Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Инициализирует новый экземпляр класса  MailmarkCodetext  .

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Получает тип штрих‑кода.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null или Тест "1" - 1C (Розничный) "2" - 2C (Розничный) "3" - 3C (Розничный) "4" - Premium (РозничныйПубликационный Письмо) (для потенциального будущего использования) "5" - Deferred (Розничный) "6" - Air (Розничный) (для потенциального будущего использования) "7" - Surface (Розничный) (для потенциального будущего использования) "8" - Premium (Сетевой Доступ) "9" - Standard (Сетевой Доступ)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Создать кодтекст из данных Mailmark.

**Returns:**
java.lang.String - построенный кодовый текст
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный "XY11 " (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null или Тест "1" \\u2013 Буква "2" \\u2013 Большая Буква

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Максимальное значение равно 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Максимальные значения: 99 для штрихкода C и 999999 для штрихкода L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


В настоящее время "1" \\u2013 Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Инициализирует данные Mailmark из построенного кодтекста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Построенный кодовый текст. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null или Тест "1" - 1C (Розничный) "2" - 2C (Розничный) "3" - 3C (Розничный) "4" - Premium (РозничныйПубликационный Письмо) (для потенциального будущего использования) "5" - Deferred (Розничный) "6" - Air (Розничный) (для потенциального будущего использования) "7" - Surface (Розничный) (для потенциального будущего использования) "8" - Premium (Сетевой Доступ) "9" - Standard (Сетевой Доступ)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный "XY11 " (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null или Тест "1" \\u2013 Буква "2" \\u2013 Большая Буква

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Максимальное значение равно 99999999.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Максимальные значения: 99 для штрихкода C и 999999 для штрихкода L.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


В настоящее время "1" \\u2013 Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

