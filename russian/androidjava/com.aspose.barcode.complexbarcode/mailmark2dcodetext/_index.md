---
title: Mailmark2DCodetext
second_title: Справочник API Aspose.BarCode для Android через Java
description: Класс для кодирования и декодирования текста, встроенного в 2‑D код Mailmark Royal Mail.
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
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Получает тип штрих‑кода. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Флаг, указывающий, какой уровень услуги Return to Sender запрашивается. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Содержит почтовый код Return to Sender, но без DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Идентифицирует уникальную группу клиентов, участвующих в рассылке. |
| [getUPUCountryID()](#getUPUCountryID--) | Идентифицирует UPU Country ID. Максимальная длина: 4 символа. |
| [getVersionID()](#getVersionID--) | Идентифицирует версию штрих‑кода, соответствующую каждому Information Type ID. |
| [getclass()](#getclass--) | Идентифицирует класс элемента. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Флаг, указывающий, какой уровень услуги Return to Sender запрашивается. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Содержит почтовый код Return to Sender, но без DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Идентифицирует уникальную группу клиентов, участвующих в рассылке. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Идентифицирует UPU Country ID. Максимальная длина: 4 символа. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Идентифицирует версию штрих‑кода, соответствующую каждому Information Type ID. |
| [setclass(String value)](#setclass-java.lang.String-) | Идентифицирует класс элемента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - Сконструированный codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Опциональное поле для использования клиентом. Максимальная длина по типу: Type 7: 6 символов Type 9: 45 символов Type 29: 25 символов

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


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Район (1 или 2 символа) Сектор (1 символ) Единица (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

**Returns:**
java.lang.String - почтовый индекс адреса доставки с DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Идентифицирует полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:**
java.lang.String - Information type ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Идентифицирует уникальный элемент в рамках Supply Chain ID. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально определить минимум на 90 дней. Максимальное значение: 99999999.

**Returns:**
int - элемент в Supply Chain ID
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Флаг, указывающий, какой уровень услуги Return to Sender запрашивается.

**Returns:**
java.lang.String - RTS Flag
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Содержит почтовый код Return to Sender, но без DPS. PC (без DPS) должен соответствовать формату PAF®.

**Returns:**
java.lang.String - Return to Sender Post Code без DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Идентифицирует уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

**Returns:**
int - Supply chain ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Идентифицирует UPU Country ID. Максимальная длина: 4 символа.

**Returns:**
java.lang.String - Country ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Идентифицирует версию штрих‑кода, соответствующую каждому Information Type ID. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

**Returns:**
java.lang.String - Version ID
### getclass() {#getclass--}
```
public String getclass()
```


Идентифицирует класс элемента. Допустимые значения: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

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


Initializes Mailmark data from constructed codetext.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Сконструированный codetext. |

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


Опциональное поле для использования клиентом. Максимальная длина по типу: Type 7: 6 символов Type 9: 45 символов Type 29: 25 символов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Район (1 или 2 символа) Сектор (1 символ) Единица (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Идентифицирует полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Идентифицирует уникальный элемент в рамках Supply Chain ID. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально определить минимум на 90 дней. Максимальное значение: 99999999.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Флаг, указывающий, какой уровень услуги Return to Sender запрашивается.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Содержит почтовый код Return to Sender, но без DPS. PC (без DPS) должен соответствовать формату PAF®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Идентифицирует уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Идентифицирует UPU Country ID. Максимальная длина: 4 символа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Идентифицирует версию штрих‑кода, соответствующую каждому Information Type ID. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Идентифицирует класс элемента. Допустимые значения: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | class of the item |

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

