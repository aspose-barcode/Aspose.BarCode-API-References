---
title: "Mailmark2DCodetext"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Класс для кодирования и декодирования текста, встроенного в 2‑D код Mailmark Royal Mail."
type: docs
weight: 23
url: /ru/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Класс для кодирования и декодирования текста, встроенного в 2‑D код Mailmark Royal Mail.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Создать экземпляр по умолчанию класса Mailmark2DCodetext. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Получает тип штрих‑кода. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Создать кодтекст из данных Mailmark. |
| [getCustomerContent()](#getCustomerContent--) | Опциональное пространство для использования клиентом. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Режим кодирования штрихкода Datamatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. |
| [getInformationTypeID()](#getInformationTypeID--) | Идентифицирует полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. |
| [getItemID()](#getItemID--) | Идентифицирует уникальный элемент в рамках идентификатора цепочки поставок. |
| [getRTSFlag()](#getRTSFlag--) | Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Содержит почтовый код возврата отправителю, но без DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Идентифицирует уникальную группу клиентов, участвующих в рассылке. |
| [getUPUCountryID()](#getUPUCountryID--) | Идентифицирует идентификатор страны UPU. Максимальная длина: 4 символа. |
| [getVersionID()](#getVersionID--) | Идентифицирует версию штрихкода, соответствующую каждому идентификатору типа информации. |
| [getclass()](#getclass--) | Определяет класс элемента. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Инициализирует данные Mailmark из построенного кодтекста. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Опциональное пространство для использования клиентом. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Режим кодирования штрихкода Datamatrix. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Идентифицирует полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. |
| [setItemID(int value)](#setItemID-int-) | Идентифицирует уникальный элемент в рамках идентификатора цепочки поставок. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Содержит почтовый код возврата отправителю, но без DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Идентифицирует уникальную группу клиентов, участвующих в рассылке. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Идентифицирует идентификатор страны UPU. Максимальная длина: 4 символа. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Идентифицирует версию штрихкода, соответствующую каждому идентификатору типа информации. |
| [setclass(String value)](#setclass-java.lang.String-) | Определяет класс элемента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Создать экземпляр по умолчанию класса Mailmark2DCodetext.

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
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Создать кодтекст из данных Mailmark.

**Returns:**
java.lang.String - построенный кодовый текст
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Опциональное пространство для использования клиентом. Максимальная длина по типу: Тип 7: 6 символов Тип 9: 45 символов Тип 29: 25 символов

**Returns:**
java.lang.String - Содержимое клиента
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


Тип 2D Mailmark определяет размер штрихкода Data Matrix.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Содержит почтовый индекс адреса доставки с DPS. Если адрес находится в стране, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Подразделение (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

**Returns:**
java.lang.String - почтовый индекс адреса доставки с DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' — внутренний сортированный и несортированный, 'A' — онлайн‑почтовый сервис, 'B' — франкирование, 'C' — консолидация

**Returns:**
java.lang.String - Идентификатор типа информации
### getItemID() {#getItemID--}
```
public int getItemID()
```


Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать не менее 90 дней. Максимальное значение: 99999999.

**Returns:**
int — элемент в рамках идентификатора цепочки поставок
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается.

**Returns:**
java.lang.String - Флаг RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Содержит почтовый индекс возврата отправителю без DPS. Почтовый индекс (без DPS) должен соответствовать формату PAF®.

**Returns:**
java.lang.String - Почтовый индекс возврата отправителю без DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

**Returns:**
int — идентификатор цепочки поставок
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Идентифицирует идентификатор страны UPU. Максимальная длина: 4 символа.

**Returns:**
java.lang.String - Идентификатор страны
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Определяет версию штрих‑кода, соответствующую каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

**Returns:**
java.lang.String - Идентификатор версии
### getclass() {#getclass--}
```
public String getclass()
```


Определяет класс элемента. Допустимые значения: '1' — 1C (розничный), '2' — 2C (розничный), '3' — Economy (розничный), '5' — Deferred (розничный), '8' — Premium (сетевой доступ), '9' — Standard (сетевой доступ)

**Returns:**
java.lang.String - класс элемента
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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Опциональное пространство для использования клиентом. Максимальная длина по типу: Тип 7: 6 символов Тип 9: 45 символов Тип 29: 25 символов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Содержимое клиента |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: EncodeMode.C40.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Режим кодирования штрихкода Datamatrix. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


Тип 2D Mailmark определяет размер штрихкода Data Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Размер штрих‑кода Data Matrix |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Содержит почтовый индекс адреса доставки с DPS. Если адрес находится в стране, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Подразделение (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | почтовый индекс адреса доставки с DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' — внутренний сортированный и несортированный, 'A' — онлайн‑почтовый сервис, 'B' — франкирование, 'C' — консолидация

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Идентификатор типа информации |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать не менее 90 дней. Максимальное значение: 99999999.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | элемент внутри Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Флаг, указывающий, какой уровень услуги «Возврат отправителю» запрашивается.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Содержит почтовый индекс возврата отправителю без DPS. Почтовый индекс (без DPS) должен соответствовать формату PAF®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Почтовый код возврата отправителю, но без DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Идентификатор цепочки поставок |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Идентифицирует идентификатор страны UPU. Максимальная длина: 4 символа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Идентификатор страны |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Определяет версию штрих‑кода, соответствующую каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Идентификатор версии |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Определяет класс элемента. Допустимые значения: '1' — 1C (розничный), '2' — 2C (розничный), '3' — Economy (розничный), '5' — Deferred (розничный), '8' — Premium (сетевой доступ), '9' — Standard (сетевой доступ)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | класс элемента |

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

