---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Опциональные элементы (поля) карты."
type: docs
weight: 730
url: /ru/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Опциональные элементы (поля) карты.

```js
new OptionalFields()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Строка букв и/или цифр, определяющая когда, где и кем была выдана водительская лицензия/удостоверение личности. Если a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата t |
| [getComplianceType()](#getcompliancetype) | DDA, обязательное поле DHS, указывающее соответствие: “F” = соответствует; и, “N” = не соответствует, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Текст, объясняющий специфические для юрисдикции коды, указывающие дополнительные водительские привилегии, предоставленные ca |
| [getHairColor()](#gethaircolor) | DAZ, Лысый, черный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Дата, когда endorsement по опасным материалам, предоставленный документом, перестаёт быть действительным. (MMDDCCYY для США, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (картон, ламинат и т.д.), используемым в производ |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Поле, указывающее, что держатель карты является донором органов = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Текст, описывающий специфические для юрисдикции коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных является заполнительным для будущих усилий по st |
| [getUnder18Until()](#getunder18until) | DDH, Дата, когда держателю карты исполняется 18 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Дата, когда держателю карты исполняется 21 год. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Текст, объясняющий специфические для юрисдикции коды классификаций транспортных средств, на которые держатель карты имеет право управлять |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Поле, указывающее, что держатель карты является ветераном = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Вес держателя карты в килограммах, напр. 84 кг = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Вес держателя карты в фунтах, напр. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 – 45 кг (71 – 100 фунтов |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Строка букв и/или цифр, определяющая когда, где и кем была выдана водительская лицензия/удостоверение личности. Если a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата t |
| [setComplianceType()](#setcompliancetype) | DDA, обязательное поле DHS, указывающее соответствие: “F” = соответствует; и, “N” = не соответствует, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Текст, объясняющий специфические для юрисдикции коды, указывающие дополнительные водительские привилегии, предоставленные ca |
| [setHairColor()](#sethaircolor) | DAZ, Лысый, черный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (картон, ламинат и т.д.), используемым в производ |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и т.д.), суффикс должен быть |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Поле, указывающее, что держатель карты является донором органов = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Текст, описывающий специфические для юрисдикции коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных является заполнительным для будущих усилий по st |
| [setUnder18Until()](#setunder18until) | DDI, Дата, когда держателю карты исполняется 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Дата, когда держателю карты исполняется 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Дата, когда держателю карты исполняется 21 год. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Текст, объясняющий специфические для юрисдикции коды классификаций транспортных средств, на которые держатель карты имеет право управлять |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Поле, указывающее, что держатель карты является ветераном = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Вес держателя карты в килограммах, напр. 84 кг = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Вес держателя карты в фунтах, напр. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 – 45 кг (71 – 100 фунтов |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Строка букв и/или цифр, определяющая когда, где и кем была изготовлена водительская лицензия/ID карта. Если информация аудита не используется на карте или MRT, она должна быть включена в запись водителя, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, обязательное поле DHS, указывающее соответствие: “F” = соответствует; и, “N” = не соответствует, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Текст, объясняющий специфические для юрисдикции коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Лысый, чёрный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать названия цветов, необходимо использовать трёхсимвольные коды, указанные в AAMVA D20, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Дата, после которой endorsement по опасным материалам, предоставленный документом, более не действителен. (MMDDCCYY для США, CCYYMMDD для Канады), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (бумага, ламинат и т.д.), используемым при изготовлении водительских лицензий и ID‑карт. (рекомендованное поле DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и др.), суффикс должен быть собран и отображён в DL/ID и в MRT). JR (Junior), SR (Senior), 1ST или I (First), до 9TH или IX (Ninth), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Поле, указывающее, что держатель карты является донором органов = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Текст, описывающий специфические для юрисдикции коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных служит заполнительным для будущих попыток стандартизации кодов endorsement, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных служит заполнительным для будущих попыток стандартизации кодов ограничений, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных служит заполнительным для будущих попыток стандартизации классификаций транспортных средств, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Дата, когда держателю карты исполняется 18 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Дата, когда держателю карты исполняется 21 год. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Текст, объясняющий специфические для юрисдикции коды классификаций транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Поле, указывающее, что держатель карты является ветераном = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Вес держателя карты в килограммах, напр. 84 кг = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Вес держателя карты в фунтах, напр. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32–45 кг (71–100 фунтов), 2 = 46–59 кг (101–130 фунтов), 3 = 60–70 кг (131–160 фунтов), 4 = 71–86 кг (161–190 фунтов), 5 = 87–100 кг (191–220 фунтов), 6 = 101–113 кг (221–250 фунтов), 7 = 114–127 кг (251–280 фунтов), 8 = 128–145 кг (281–320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Другой суффикс, под которым известен держатель карты, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Строка букв и/или цифр, определяющая когда, где и кем была изготовлена водительская лицензия/ID карта. Если информация аудита не используется на карте или MRT, она должна быть включена в запись водителя, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, обязательное поле DHS, указывающее соответствие: “F” = соответствует; и, “N” = не соответствует, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Текст, объясняющий специфические для юрисдикции коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Лысый, чёрный, блондин, коричневый, серый, рыжий/каштановый, песочный, белый, неизвестно. Если выдающая юрисдикция желает сокращать названия цветов, необходимо использовать трёхсимвольные коды, указанные в AAMVA D20, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Строка букв и/или цифр, прикрепляемая к сырьевым материалам (бумага, ламинат и т.д.), используемым при изготовлении водительских лицензий и ID‑карт. (рекомендованное поле DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и др.), суффикс должен быть собран и отображён в DL/ID и в MRT). JR (Junior), SR (Senior), 1ST или I (First), до 9TH или IX (Ninth), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Поле, указывающее, что держатель карты является донором органов = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Текст, описывающий специфические для юрисдикции коды ограничений, которые ограничивают водительские привилегии, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Стандартные коды endorsement для держателя карты. См. коды в D20. Этот элемент данных служит заполнительным для будущих попыток стандартизации кодов endorsement, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных служит заполнительным для будущих попыток стандартизации кодов ограничений, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных служит заполнительным для будущих попыток стандартизации классификаций транспортных средств, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Дата, когда держателю карты исполняется 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Дата, когда держателю карты исполняется 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Дата, когда держателю карты исполняется 21 год. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Текст, объясняющий специфические для юрисдикции коды классификаций транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Поле, указывающее, что держатель карты является ветераном = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Вес держателя карты в килограммах, напр. 84 кг = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Вес держателя карты в фунтах, напр. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32–45 кг (71–100 фунтов), 2 = 46–59 кг (101–130 фунтов), 3 = 60–70 кг (131–160 фунтов), 4 = 71–86 кг (161–190 фунтов), 5 = 87–100 кг (191–220 фунтов), 6 = 101–113 кг (221–250 фунтов), 7 = 114–127 кг (251–280 фунтов), 8 = 128–145 кг (281–320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N
