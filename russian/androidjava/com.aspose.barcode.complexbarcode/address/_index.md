---
title: Адрес
second_title: Справочник API Aspose.BarCode для Android через Java
description: Адрес кредитора или должника.
type: docs
weight: 10
url: /ru/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Адрес кредитора или должника.

Вы можете либо задать улицу, номер дома, почтовый индекс и город (тип  *структурированный адрес* ), либо строки адреса 1 и 2 (тип  *комбинированные элементы адреса* ). Тип автоматически устанавливается, как только заполняется любое из этих полей. До заполнения полей тип адреса считается  *неопределённым* . Если заполнены поля обоих типов, тип адреса становится  *конфликтующим* . Имя и код страны должны всегда указываться, если только все поля не пусты.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Address()](#Address--) | Создаёт экземпляр Address |
## Методы

| Метод | Описание |
| --- | --- |
| [clear()](#clear--) | Очищает все поля и устанавливает тип в  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [getAddressLine1()](#getAddressLine1--) | Получает строку адреса 1. |
| [getAddressLine2()](#getAddressLine2--) | Получает строку адреса 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Получает двухбуквенный код страны ISO. |
| [getHouseNo()](#getHouseNo--) | Получает номер дома. |
| [getName()](#getName--) | Получает имя, либо имя и фамилию физического лица, либо название компании юридического лица. |
| [getPostalCode()](#getPostalCode--) | Получает почтовый индекс. |
| [getStreet()](#getStreet--) | Получает улицу. |
| [getTown()](#getTown--) | Получает город или населённый пункт. |
| [getType()](#getType--) | Получает тип адреса. |
| [hashCode()](#hashCode--) | Получает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Устанавливает строку адреса 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Устанавливает строку адреса 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Устанавливает двухбуквенный код страны ISO. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Устанавливает номер дома. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя, либо имя и фамилию физического лица, либо название компании юридического лица. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Устанавливает почтовый индекс. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Устанавливает улицу. |
| [setTown(String value)](#setTown-java.lang.String-) | Устанавливает город или населённый пункт. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Создаёт экземпляр Address

### clear() {#clear--}
```
public void clear()
```


Очищает все поля и устанавливает тип в  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект, с которым сравнивается текущий объект. |

**Returns:**
boolean -  true  если указанный объект равен текущему объекту; иначе,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Получает строку адреса 1.

Строка адреса 1 содержит название улицы, номер дома или абонентский ящик.

Установка этого поля устанавливает тип адреса в  AddressType.CombinedElements  если он ещё не является  AddressType.Structured , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для адресов с комбинированными элементами и является необязательным.

Значение: Строка адреса 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Получает строку адреса 2.

Строка адреса 2 содержит почтовый индекс и город.

Установка этого поля устанавливает тип адреса в  AddressType.CombinedElements  если он ещё не является  AddressType.Structured , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для адресов с комбинированными элементами. Для этого типа оно обязательно.

Значение: Строка адреса 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Получает двухбуквенный код страны ISO.

Код страны обязателен, если только весь адрес не содержит  null  или пустых значений.

Значение: ISO‑код страны.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Получает номер дома.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов и является необязательным.

Значение: номер дома.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Получает имя, либо имя и фамилию физического лица, либо название компании юридического лица.

Значение: имя.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Получает почтовый индекс.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов. Для этого типа оно обязательно.

Значение: почтовый индекс.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Получает улицу.

Улица должна быть указана без номера дома.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов и является необязательным.

Значение: улица.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Получает город или населённый пункт.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов. Для этого типа оно обязательно.

Значение: город или населённый пункт.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Получает тип адреса.

Тип адреса автоматически устанавливается либо при указании улицы/номера дома, либо строки адреса 1 и 2. До установки полей тип адреса —  *Undetermined* . Если заданы поля обоих типов, тип адреса становится  *Conflicting* .

Значение: тип адреса.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для текущего объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Устанавливает строку адреса 1.

Строка адреса 1 содержит название улицы, номер дома или абонентский ящик.

Установка этого поля устанавливает тип адреса в  AddressType.CombinedElements  если он ещё не является  AddressType.Structured , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для адресов с комбинированными элементами и является необязательным.

Значение: Строка адреса 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Устанавливает строку адреса 2.

Строка адреса 2 содержит почтовый индекс и город.

Установка этого поля устанавливает тип адреса в  AddressType.CombinedElements  если он ещё не является  AddressType.Structured , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для адресов с комбинированными элементами. Для этого типа оно обязательно.

Значение: Строка адреса 2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Устанавливает двухбуквенный код страны ISO.

Код страны обязателен, если только весь адрес не содержит  null  или пустых значений.

Значение: ISO‑код страны.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Устанавливает номер дома.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов и является необязательным.

Значение: номер дома.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя, либо имя и фамилию физического лица, либо название компании юридического лица.

Значение: имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Устанавливает почтовый индекс.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов. Для этого типа оно обязательно.

Значение: почтовый индекс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Устанавливает улицу.

Улица должна быть указана без номера дома.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов и является необязательным.

Значение: улица.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Устанавливает город или населённый пункт.

Установка этого поля задаёт тип адреса как  AddressType.Structured , если только он уже не является  AddressType.CombinedElements , в этом случае он становится  AddressType.Conflicting .

Это поле используется только для структурированных адресов. Для этого типа оно обязательно.

Значение: город или населённый пункт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

