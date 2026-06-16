---
title: SwissQRBill
second_title: Справочник API Aspose.BarCode для Android через Java
description: Данные счета SwissQR
type: docs
weight: 36
url: /ru/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Данные счета SwissQR
## Методы

| Метод | Описание |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Получает или задает альтернативные схемы оплаты. |
| [getAmount()](#getAmount--) | Получает сумму платежа. |
| [getBillInformation()](#getBillInformation--) | Получает дополнительную структурированную информацию счета. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Получает адрес кредитора. |
| [getCurrency()](#getCurrency--) | Получает валюту платежа. |
| [getDebtor()](#getDebtor--) | Получает адрес должника. |
| [getReference()](#getReference--) | Получает ссылку платежа кредитора. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Получает дополнительное неструктурированное сообщение. |
| [getVersion()](#getVersion--) | Получает версию стандарта счета SwissQR. |
| [hashCode()](#hashCode--) | Получает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Задает номер счета кредитора. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Получает или задает альтернативные схемы оплаты. |
| [setAmount(double value)](#setAmount-double-) | Задает сумму платежа. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Задает дополнительную структурированную информацию счета. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Задает адрес кредитора. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Задает валюту платежа. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Задает адрес должника. |
| [setReference(String value)](#setReference-java.lang.String-) | Задает ссылку платежа кредитора. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Задает дополнительное неструктурированное сообщение. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Задает версию стандарта счета SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

Пробелы удаляются из ссылки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawReference | java.lang.String | Сырая ссылка. |

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
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

Номера счетов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Пробелы допускаются в номере счета.

Значение: номер счета кредитора.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Получает или задает альтернативные схемы оплаты.

Разрешено максимум две схемы с параметрами.

Значение: альтернативные схемы оплаты.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Получает сумму платежа.

Допустимые значения находятся в диапазоне от 0,01 до 999 999 999,99.

Значение: Сумма платежа.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Получает дополнительную структурированную информацию счета.

Значение: Структурированная информация о счете.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Получает адрес кредитора.

Значение: Адрес кредитора.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Получает валюту платежа.

Допустимые значения: "CHF" и "EUR".

Значение: Валюта платежа.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Получает адрес должника.

Дебитор является необязательным. Если он опущен, то как установка этого поля в  null  , так и указание адреса, у которого все значения  null  или пустые, допустимы.

Значение: Адрес дебитора.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Получает ссылку платежа кредитора.

Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне от CHxx30000xxxxxx до CHxx31999xxxxx.

Если указана, ссылка должна быть либо действительной SwissQR‑ссылкой (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx"). Обе могут содержать пробелы для форматирования.

Значение: Ссылка платежа кредитора.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Получает дополнительное неструктурированное сообщение.

Значение: Неструктурированное сообщение.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Получает версию стандарта счета SwissQR.

Значение: Версия стандарта счета SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Задает номер счета кредитора.

Номера счетов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Пробелы допускаются в номере счета.

Значение: номер счета кредитора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Получает или задает альтернативные схемы оплаты.

Разрешено максимум две схемы с параметрами.

Значение: альтернативные схемы оплаты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Задает сумму платежа.

Допустимые значения находятся в диапазоне от 0,01 до 999 999 999,99.

Значение: Сумма платежа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Задает дополнительную структурированную информацию счета.

Значение: Структурированная информация о счете.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Задает адрес кредитора.

Значение: Адрес кредитора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Задает валюту платежа.

Допустимые значения: "CHF" и "EUR".

Значение: Валюта платежа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Задает адрес должника.

Дебитор является необязательным. Если он опущен, то как установка этого поля в  null  , так и указание адреса, у которого все значения  null  или пустые, допустимы.

Значение: Адрес дебитора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Задает ссылку платежа кредитора.

Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне от CHxx30000xxxxxx до CHxx31999xxxxx.

Если указана, ссылка должна быть либо действительной SwissQR‑ссылкой (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx"). Обе могут содержать пробелы для форматирования.

Значение: Ссылка платежа кредитора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Задает дополнительное неструктурированное сообщение.

Значение: Неструктурированное сообщение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Задает версию стандарта счета SwissQR.

Значение: Версия стандарта счета SwissQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

