---
title: SecondaryAndAdditionalData
second_title: Справочник API Aspose.BarCode для Android через Java
description: Класс для хранения вторичных и дополнительных данных HIBC LIC.
type: docs
weight: 35
url: /ru/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Класс для хранения вторичных и дополнительных данных HIBC LIC.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению  SecondaryAndAdditionalData . |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Определяет дату производства. |
| [getExpiryDate()](#getExpiryDate--) | Определяет дату истечения срока. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Определяет формат даты истечения срока. |
| [getLotNumber()](#getLotNumber--) | Определяет номер партии или лота. |
| [getQuantity()](#getQuantity--) | Определяет количество, должно быть целым числом от 0 до 500. |
| [getSerialNumber()](#getSerialNumber--) | Определяет серийный номер. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Создаёт вторичные и дополнительные вспомогательные данные из строкового формата в соответствии со спецификацией HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Определяет дату производства. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Определяет дату истечения срока. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Определяет формат даты истечения срока. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Определяет номер партии или лота. |
| [setQuantity(int value)](#setQuantity-int-) | Определяет количество, должно быть целым числом от 0 до 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Определяет серийный номер. |
| [toString()](#toString--) | Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному значению  SecondaryAndAdditionalData .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение  SecondaryAndAdditionalData  для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Определяет дату производства. Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле. Значение по умолчанию: DateTime.MinValue.

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Определяет формат даты истечения срока.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Определяет количество, должно быть целым числом от 0 до 500. Количество можно установить в -1, чтобы не использовать это поле. Значение по умолчанию: -1.

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Создаёт вторичные и дополнительные вспомогательные данные из строкового формата в соответствии со спецификацией HIBC LIC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Отформатированная строка. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Определяет дату производства. Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле. Значение по умолчанию: DateTime.MinValue.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Определяет формат даты истечения срока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Определяет количество, должно быть целым числом от 0 до 500. Количество можно установить в -1, чтобы не использовать это поле. Значение по умолчанию: -1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC.

**Returns:**
java.lang.String - Отформатированная строка.
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

