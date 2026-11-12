---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Обязательные элементы (поля) карты"
type: docs
weight: 590
url: /ru/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Обязательные элементы (поля) карты

```js
new MandatoryFields()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, часть адреса держателя карты — город, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, часть адреса держателя карты — почтовый код в США и Канаде. Если завершающая часть почтового кода в |
| [getAddressState()](#getaddressstate) | DAJ, часть адреса держателя карты — штат, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, часть адреса держателя карты — улица, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Юрисдикционно-специфичные коды одобрения, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [getFirstName()](#getfirstname) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [getHeight()](#getheight) | DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры(cm): число |
| [getMiddleName()](#getmiddlename) | DAD, Отчество(а) держателя карты. В случае нескольких отчеств они разделяются запятой ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS |
| [getSex()](#getsex) | DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, часть адреса держателя карты — город, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, часть адреса держателя карты — почтовый код в США и Канаде. Если завершающая часть почтового кода в |
| [setAddressState()](#setaddressstate) | DAJ, часть адреса держателя карты — штат, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, часть адреса держателя карты — улица, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Юрисдикционно-специфичные коды одобрения, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [setFirstName()](#setfirstname) | DAC, Имя держателя карты, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [setHeight()](#setheight) | DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры(cm): число |
| [setMiddleName()](#setmiddlename) | DAD, Отчество(а) держателя карты. В случае нескольких отчеств они разделяются запятой ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS |
| [setSex()](#setsex) | DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, часть адреса держателя карты — город, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, заполняются нулями до 9 цифр, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, часть адреса держателя карты — штат, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, часть адреса держателя карты — улица, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. Этот номер может использоваться для различных целей: различения документов, номера аудиторской информации и/или контроля инвентаря, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Юрисдикционно-специфичные коды одобрения, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Фамилия держателя карты, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Имя держателя карты, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры (cm): число сантиметров, за которым следует " cm", напр. 181 сантиметр = "181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Отчество(а) держателя карты. В случае нескольких отчеств они разделяются запятой ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS

### getSex() {#getsex}

DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, часть адреса держателя карты — город, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Часть почтового кода адреса держателя карты в США и Канаде. Если конечная часть почтового кода в США неизвестна, заполняются нулями до 9 цифр, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, часть адреса держателя карты — штат, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, часть адреса держателя карты — улица, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Номер должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. Этот номер может использоваться для различных целей: различения документов, номера аудиторской информации и/или контроля инвентаря, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Юрисдикционно-специфичные коды одобрения, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Цвет глаз держателя карты. (коды ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Фамилия держателя карты, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Имя держателя карты, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Рост держателя карты. Дюймы (in): число дюймов, за которым следует " in", напр. 6'1'' = "073 in" Сантиметры (cm): число сантиметров, за которым следует " cm", напр. 181 сантиметр = "181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Отчество(а) держателя карты. В случае нескольких отчеств они разделяются запятой ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Код, указывающий, было ли поле усечено (T), не усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Юрисдикционно-специфичные коды ограничений, DL, V12ANS

### setSex() {#setsex}

DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Юрисдикционно-специфичный код класса/группы транспортного средства, DL, V6ANS
