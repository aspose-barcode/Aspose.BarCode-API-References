---
title: USADriveIdCodetext
second_title: Справочник API Aspose.BarCode для Android через Java
description: Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США.
type: docs
weight: 38
url: /ru/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Конструктор по умолчанию |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | Номер версии AAMVA 00-99 |
| [getBarcodeType()](#getBarcodeType--) | Возвращает тип штрихкода USA DL (Pdf417) |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Создать кодовый текст из данных USA DL |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Этот номер уникально идентифицирует выдающую юрисдикцию и может быть получен путем обращения к ISO Issuing Authority (AAMVA). |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Специфические для юрисдикции поля |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Номер версии юрисдикции 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Обязательные элементы (поля) карты |
| [getNumberOfEntries()](#getNumberOfEntries--) | Номер подпфайлов 00-99 |
| [getOptionalElements()](#getOptionalElements--) | Опциональные элементы (поля) карты |
| [getSubfileDesignator()](#getSubfileDesignator--) | Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Инициализировать объект USA DL из кодового текста |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Сохраняет в XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | Номер версии AAMVA 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Этот номер уникально идентифицирует выдающую юрисдикцию и может быть получен путем обращения к ISO Issuing Authority (AAMVA). |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Специфические для юрисдикции поля |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Номер версии юрисдикции 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Обязательные элементы (поля) карты |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Номер подпфайлов 00-99 |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Опциональные элементы (поля) карты |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Конструктор по умолчанию

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


Номер версии AAMVA 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Возвращает тип штрихкода USA DL (Pdf417)

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


Создать кодовый текст из данных USA DL

**Returns:**
java.lang.String - Сконструированный codetext
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Этот номер уникально идентифицирует выдающую юрисдикцию и может быть получен путем обращения к ISO Issuing Authority (AAMVA). Полный 6-значный IIN должен быть закодирован.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Специфические для юрисдикции поля

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Номер версии юрисдикции 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Обязательные элементы (поля) карты

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Номер подпфайлов 00-99

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Опциональные элементы (поля) карты

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. Важно: задайте только тип, смещение и длина будут установлены автоматически.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Инициализировать объект USA DL из кодового текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Сформированный codetext |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


Сохраняет в XML

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


Номер версии AAMVA 00-99

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Этот номер уникально идентифицирует выдающую юрисдикцию и может быть получен путем обращения к ISO Issuing Authority (AAMVA). Полный 6-значный IIN должен быть закодирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Специфические для юрисдикции поля

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Номер версии юрисдикции 00-99

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Обязательные элементы (поля) карты

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Номер подпфайлов 00-99

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Опциональные элементы (поля) карты

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. Важно: задайте только тип, смещение и длина будут установлены автоматически.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

