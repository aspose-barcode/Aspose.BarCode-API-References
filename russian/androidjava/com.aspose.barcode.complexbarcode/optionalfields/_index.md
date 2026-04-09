---
title: USADriveIdCodetext.OptionalFields
second_title: Справочник API Aspose.BarCode для Android через Java
description: Опциональные поля элементов карты.
type: docs
weight: 11
url: /ru/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Опциональные элементы (поля) карты
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Строка букв и/или цифр, определяющая когда, где и кем была изготовлена водительская лицензия/ID карта. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Обязательное поле DHS, указывающее соответствие: \\u201cF\\u201d = соответствует; и, \\u201cN\\u201d = не соответствует, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Текст, объясняющий юрисдикционно-специфические коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Дата, после которой разрешение на перевозку опасных материалов, предоставленное документом, более не действительно. |
| [getHairColor()](#getHairColor--) | DAZ, Лысый, черный, блондин, коричневый, седой, рыжий/каштановый, светловолосый, белый, неизвестно. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Строка букв и/или цифр, прикрепленная к сырьевым материалам (карточный материал, ламинация и т.д.), используемым при производстве водительских лицензий и ID карт. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = \\u201c1\\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть собран и отображён на DL/ID и в MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Поле, указывающее, что держатель карты является донором органов = \\u201c1\\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Текст, описывающий юрисдикционно-специфические коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Стандартные коды endorsement для держателя карты. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Стандартные коды ограничений для держателя карты. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Стандартные коды классификации транспортных средств для держателя карты. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Дата, когда держатель карты достигает 18 лет. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Дата, когда держатель карты достигает 19 лет. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Дата, когда держатель карты достигает 21 лет. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Текст, объясняющий специфические для юрисдикции коды классификации транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Поле, указывающее, что держатель карты является ветераном = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Вес держателя карты в килограммах, Пример. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Вес держателя карты в фунтах, Пример. |
| [getWeightRange()](#getWeightRange--) | DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 \\u2013 45 кг (71 \\u2013 100 фунтов), 2 = 46 - 59 кг (101 \\u2013 130 фунтов), 3 = 60 - 70 кг (131 \\u2013 160 фунтов), 4 = 71 - 86 кг (161 \\u2013 190 фунтов), 5 = 87 - 100 кг (191 \\u2013 220 фунтов), 6 = 101 - 113 кг (221 \\u2013 250 фунтов), 7 = 114 - 127 кг (251 \\u2013 280 фунтов), 8 = 128 \\u2013 145 кг (281 \\u2013 320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Строка букв и/или цифр, определяющая когда, где и кем была изготовлена водительская лицензия/ID карта. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Обязательное поле DHS, указывающее соответствие: \\u201cF\\u201d = соответствует; и, \\u201cN\\u201d = не соответствует, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Текст, объясняющий юрисдикционно-специфические коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Лысый, черный, блондин, коричневый, седой, рыжий/каштановый, светловолосый, белый, неизвестно. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Строка букв и/или цифр, прикрепленная к сырьевым материалам (карточный материал, ламинация и т.д.), используемым при производстве водительских лицензий и ID карт. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = \\u201c1\\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть собран и отображён на DL/ID и в MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Поле, указывающее, что держатель карты является донором органов = \\u201c1\\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Текст, описывающий юрисдикционно-специфические коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Стандартные коды endorsement для держателя карты. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Стандартные коды ограничений для держателя карты. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Стандартные коды классификации транспортных средств для держателя карты. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Дата, когда держатель карты достигает 18 лет. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Дата, когда держатель карты достигает 19 лет. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Дата, когда держатель карты достигает 21 лет. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Текст, объясняющий специфические для юрисдикции коды классификации транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Поле, указывающее, что держатель карты является ветераном = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Вес держателя карты в килограммах, Пример. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Вес держателя карты в фунтах, Пример. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 \\u2013 45 кг (71 \\u2013 100 фунтов), 2 = 46 - 59 кг (101 \\u2013 130 фунтов), 3 = 60 - 70 кг (131 \\u2013 160 фунтов), 4 = 71 - 86 кг (161 \\u2013 190 фунтов), 5 = 87 - 100 кг (191 \\u2013 220 фунтов), 6 = 101 - 113 кг (221 \\u2013 250 фунтов), 7 = 114 - 127 кг (251 \\u2013 280 фунтов), 8 = 128 \\u2013 145 кг (281 \\u2013 320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
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
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Строка букв и/или цифр, идентифицирующая когда, где и кем была изготовлена водительская лицензия/ID‑карта. Если аудиторская информация не используется на карте или в MRT, она должна быть включена в запись водителя, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, Обязательное поле DHS, указывающее соответствие: \\u201cF\\u201d = соответствует; и, \\u201cN\\u201d = не соответствует, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Текст, объясняющий юрисдикционно-специфические коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Дата, когда разрешение по опасным материалам, выданное документом, перестаёт быть действительным. (MMDDCCYY для США, CCYYMMDD для Канады), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Лысый, чёрный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать названия цветов, необходимо использовать трёхсимвольные коды, указанные в AAMVA D20, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (бумага, ламинация и т.д.), используемым при производстве водительских лицензий и ID‑карт. (рекомендованное поле DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть собран и отображён в DL/ID и в MRT). JR (Junior), SR (Senior), 1ST или I (First), до 9TH или IX (Ninth), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Поле, указывающее, что держатель карты является донором органов = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Текст, описывающий юрисдикционно-специфические коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих попыток стандартизации кодов endorsement, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих попыток стандартизации кодов ограничений, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных является заполнительным для будущих попыток стандартизации классификаций транспортных средств, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Дата, когда держатель карты достигает 18 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Дата, когда держатель карты достигает 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Дата, когда держатель карты достигает 21 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Текст, объясняющий специфические для юрисдикции коды классификации транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Поле, указывающее, что держатель карты является ветераном = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Вес держателя карты в килограммах, Пример: 84 кг = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Вес держателя карты в фунтах, Пример: 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 \\u2013 45 кг (71 \\u2013 100 фунтов), 2 = 46 - 59 кг (101 \\u2013 130 фунтов), 3 = 60 - 70 кг (131 \\u2013 160 фунтов), 4 = 71 - 86 кг (161 \\u2013 190 фунтов), 5 = 87 - 100 кг (191 \\u2013 220 фунтов), 6 = 101 - 113 кг (221 \\u2013 250 фунтов), 7 = 114 - 127 кг (251 \\u2013 280 фунтов), 8 = 128 \\u2013 145 кг (281 \\u2013 320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N

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




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Строка букв и/или цифр, идентифицирующая когда, где и кем была изготовлена водительская лицензия/ID‑карта. Если аудиторская информация не используется на карте или в MRT, она должна быть включена в запись водителя, DL/ID, V25ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Обязательное поле DHS, указывающее соответствие: \\u201cF\\u201d = соответствует; и, \\u201cN\\u201d = не соответствует, DL/ID, F1A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Текст, объясняющий юрисдикционно-специфические коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Лысый, чёрный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать названия цветов, необходимо использовать трёхсимвольные коды, указанные в AAMVA D20, DL/ID, V12A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (бумага, ламинация и т.д.), используемым при производстве водительских лицензий и ID‑карт. (рекомендованное поле DHS), DL/ID, V25ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть собран и отображён в DL/ID и в MRT). JR (Junior), SR (Senior), 1ST или I (First), до 9TH или IX (Ninth), DL/ID, V5ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Поле, указывающее, что держатель карты является донором органов = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Текст, описывающий юрисдикционно-специфические коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих попыток стандартизации кодов endorsement, DL, F5AN

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих попыток стандартизации кодов ограничений, DL, F12AN

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных является заполнительным для будущих попыток стандартизации классификаций транспортных средств, DL, F4AN

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Дата, когда держатель карты достигает 18 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Дата, когда держатель карты достигает 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Дата, когда держатель карты достигает 21 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Текст, объясняющий специфические для юрисдикции коды классификации транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Поле, указывающее, что держатель карты является ветераном = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Вес держателя карты в килограммах, Пример: 84 кг = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Вес держателя карты в фунтах, Пример: 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 \\u2013 45 кг (71 \\u2013 100 фунтов), 2 = 46 - 59 кг (101 \\u2013 130 фунтов), 3 = 60 - 70 кг (131 \\u2013 160 фунтов), 4 = 71 - 86 кг (161 \\u2013 190 фунтов), 5 = 87 - 100 кг (191 \\u2013 220 фунтов), 6 = 101 - 113 кг (221 \\u2013 250 фунтов), 7 = 114 - 127 кг (251 \\u2013 280 фунтов), 8 = 128 \\u2013 145 кг (281 \\u2013 320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N

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

