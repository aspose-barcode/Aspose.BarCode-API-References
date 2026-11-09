---
title: "USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for Java API Reference"
description: "Обязательные поля элементов карты"
type: docs
weight: 10
url: /ru/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
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
| [getAddressCity()](#getAddressCity--) | DAI, часть адреса держателя карты, указывающая город, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, часть адреса держателя карты, указывающая почтовый код в США и Канаде. |
| [getAddressState()](#getAddressState--) | DAJ, Часть адреса держателя карты, указывающая штат, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Часть адреса держателя карты, указывающая улицу, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Страна, в которой выдан DL/ID. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Номер должен однозначно идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Коды подтверждения, специфичные для юрисдикции, DL, V5ANS |
| [getExpirationDate()](#getExpirationDate--) | DBA, Дата истечения срока действия документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [getEyeColor()](#getEyeColor--) | DAY, Цвет глаз держателя карты. |
| [getFamilyName()](#getFamilyName--) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Рост держателя карты. |
| [getIssueDate()](#getIssueDate--) | DBD, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [getMiddleName()](#getMiddleName--) | DAD, Отчество(а) держателя карты. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Коды ограничений, специфичные для юрисдикции, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Пол держателя карты. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Класс/группа транспортного средства, специфичный для юрисдикции, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, часть адреса держателя карты, указывающая город, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, часть адреса держателя карты, указывающая почтовый код в США и Канаде. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Часть адреса держателя карты, указывающая штат, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Часть адреса держателя карты, указывающая улицу, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Страна, в которой выдан DL/ID. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Номер должен однозначно идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Коды подтверждения, специфичные для юрисдикции, DL, V5ANS |
| [setExpirationDate(LocalDate value)](#setExpirationDate-java.time.LocalDate-) | DBA, Дата истечения срока действия документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Цвет глаз держателя карты. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Рост держателя карты. |
| [setIssueDate(LocalDate value)](#setIssueDate-java.time.LocalDate-) | DBD, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Отчество(а) держателя карты. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Коды ограничений, специфичные для юрисдикции, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Пол держателя карты. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Класс/группа транспортного средства, специфичный для юрисдикции, DL, V6ANS |
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


DAI, часть адреса держателя карты, указывающая город, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, нули будут использованы для заполнения до 9 цифр, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Часть адреса держателя карты, указывающая штат, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Часть адреса держателя карты, указывающая улицу, DL/ID, V35ANS

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


DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A

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


DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

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


DCD, Коды подтверждения, специфичные для юрисдикции, DL, V5ANS

**Returns:**
java.lang.String
### getExpirationDate() {#getExpirationDate--}
```
public final LocalDate getExpirationDate()
```


DBA, Дата истечения срока действия документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A

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


DDE, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

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


DDF, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Рост держателя карты. Дюймы (in): количество дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры(cm): количество сантиметров, за которым следует " cm", напр. 181 сантиметр = "181 cm", DL/ID, F6ANS

**Returns:**
java.lang.String
### getIssueDate() {#getIssueDate--}
```
public final LocalDate getIssueDate()
```


DBD, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Отчество(а) держателя карты. В случае нескольких отчеств они должны быть разделены запятой ","., DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Коды ограничений, специфичные для юрисдикции, DL, V12ANS

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


DCA, Класс/группа транспортного средства, специфичный для юрисдикции, DL, V6ANS

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


DAI, часть адреса держателя карты, указывающая город, DL/ID, V20ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, нули будут использованы для заполнения до 9 цифр, DL/ID, F11ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Часть адреса держателя карты, указывающая штат, DL/ID, F2A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Часть адреса держателя карты, указывающая улицу, DL/ID, V35ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A

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


DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

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


DCD, Коды подтверждения, специфичные для юрисдикции, DL, V5ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setExpirationDate(LocalDate value) {#setExpirationDate-java.time.LocalDate-}
```
public final void setExpirationDate(LocalDate value)
```


DBA, Дата истечения срока действия документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A

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


DDE, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

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


DDF, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Рост держателя карты. Дюймы (in): количество дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры(cm): количество сантиметров, за которым следует " cm", напр. 181 сантиметр = "181 cm", DL/ID, F6ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setIssueDate(LocalDate value) {#setIssueDate-java.time.LocalDate-}
```
public final void setIssueDate(LocalDate value)
```


DBD, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Отчество(а) держателя карты. В случае нескольких отчеств они должны быть разделены запятой ","., DL/ID, V40ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Код, указывающий, обрезано ли поле (T), не обрезано (N) или неизвестно (U), DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Коды ограничений, специфичные для юрисдикции, DL, V12ANS

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


DCA, Класс/группа транспортного средства, специфичный для юрисдикции, DL, V6ANS

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

