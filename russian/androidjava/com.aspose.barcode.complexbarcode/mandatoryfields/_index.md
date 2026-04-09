---
title: USADriveIdCodetext.MandatoryFields
second_title: Справочник API Aspose.BarCode для Android через Java
description: Обязательные поля элементов карты
type: docs
weight: 10
url: /ru/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Обязательные элементы (поля) карты
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Часть города адреса держателя карты, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, Часть почтового кода адреса держателя карты в США и Канаде. |
| [getAddressState()](#getAddressState--) | DAJ, Часть штата адреса держателя карты, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Часть улицы адреса держателя карты, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Страна, в которой выдан DL/ID. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Дата, когда документ был выдан, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Юрисдикционно-специфичные коды endorsement, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, Цвет глаз держателя карты. |
| [getFamilyName()](#getFamilyName--) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Рост держателя карты. |
| [getMiddleName()](#getMiddleName--) | DAD, Отчество(а) держателя карты. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Пол держателя карты. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Часть города адреса держателя карты, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, Часть почтового кода адреса держателя карты в США и Канаде. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Часть штата адреса держателя карты, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Часть улицы адреса держателя карты, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Страна, в которой выдан DL/ID. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Дата, когда документ был выдан, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Юрисдикционно-специфичные коды endorsement, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Цвет глаз держателя карты. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Рост держателя карты. |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Отчество(а) держателя карты. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Пол держателя карты. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
```


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
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Часть города адреса держателя карты, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, нули будут использованы для заполнения конечного набора цифр до 9 знаков, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Часть штата адреса держателя карты, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Часть улицы адреса держателя карты, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG, Страна, в которой выдано DL/ID. США = USA, Канада = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Дата, когда документ был выдан, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Номер должен однозначно идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. Этот номер может использоваться для различных целей: различения документов, номера аудиторской информации и/или контроля инвентаря, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Юрисдикционно-специфичные коды endorsement, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Цвет глаз держателя карты. (Коды ANSI D-20). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Фамилия держателя карты, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Имя держателя карты, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", например 6'1'' = "073 in" Сантиметры(cm): число сантиметров, за которым следует " cm", например 181 сантиметр = "181 cm", DL/ID, F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Отчество(а) держателя карты. В случае нескольких отчеств они должны разделяться запятой ",". , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS

**Returns:**
java.lang.String
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




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, Часть города адреса держателя карты, DL/ID, V20ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, нули будут использованы для заполнения конечного набора цифр до 9 знаков, DL/ID, F11ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Часть штата адреса держателя карты, DL/ID, F2A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Часть улицы адреса держателя карты, DL/ID, V35ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Страна, в которой выдано DL/ID. США = USA, Канада = CAN, DL/ID, F3A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Дата, когда документ был выдан, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Номер должен однозначно идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. Этот номер может использоваться для различных целей: различения документов, номера аудиторской информации и/или контроля инвентаря, DL/ID, V25ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Юрисдикционно-специфичные коды endorsement, DL, V5ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Цвет глаз держателя карты. (Коды ANSI D-20). DL/ID, F3A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Фамилия держателя карты, DL/ID, V40ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Имя держателя карты, DL/ID, V40ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", например 6'1'' = "073 in" Сантиметры(cm): число сантиметров, за которым следует " cm", например 181 сантиметр = "181 cm", DL/ID, F6ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Отчество(а) держателя карты. В случае нескольких отчеств они должны разделяться запятой ",". , DL/ID, V40ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS

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

