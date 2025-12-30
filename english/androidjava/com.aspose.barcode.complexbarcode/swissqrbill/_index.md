---
title: SwissQRBill
second_title: Aspose.BarCode for Android via Java API Reference
description: SwissQR bill data
type: docs
weight: 35
url: /androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR bill data
## Methods

| Method | Description |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Gets ors sets the alternative payment schemes. |
| [getAmount()](#getAmount--) | Gets the payment amount. |
| [getBillInformation()](#getBillInformation--) | Gets the additional structured bill information. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Gets the creditor address. |
| [getCurrency()](#getCurrency--) | Gets the payment currency. |
| [getDebtor()](#getDebtor--) | Gets the debtor address. |
| [getReference()](#getReference--) | Gets the creditor payment reference. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Gets the additional unstructured message. |
| [getVersion()](#getVersion--) | Gets the version of the SwissQR bill standard. |
| [hashCode()](#hashCode--) | Gets the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Sets the creditor's account number. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Gets ors sets the alternative payment schemes. |
| [setAmount(double value)](#setAmount-double-) | Sets the payment amount. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Sets the additional structured bill information. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Sets the creditor address. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Sets the payment currency. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Sets the debtor address. |
| [setReference(String value)](#setReference-java.lang.String-) | Sets the creditor payment reference. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Sets the additional unstructured message. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Sets the version of the SwissQR bill standard. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

Whitespace is removed from the reference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawReference | java.lang.String | The raw reference. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

Value: The creditor account number.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Gets ors sets the alternative payment schemes.

A maximum of two schemes with parameters are allowed.

Value: The alternative payment schemes.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Gets the payment amount.

Valid values are between 0.01 and 999,999,999.99.

Value: The payment amount.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Gets the additional structured bill information.

Value: The structured bill information.

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


Gets the creditor address.

Value: The creditor address.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Gets the payment currency.

Valid values are "CHF" and "EUR".

Value: The payment currency.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Gets the debtor address.

The debtor is optional. If it is omitted, both setting this field to  null  or setting an address with all  null  or empty values is ok.

Value: The debtor address.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Gets the creditor payment reference.

The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx.

If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

Value: The creditor payment reference.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Gets the additional unstructured message.

Value: The unstructured message.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Gets the version of the SwissQR bill standard.

Value: The SwissQR bill standard version.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this instance.

**Returns:**
int - A hash code for the current object.
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


Sets the creditor's account number.

Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

Value: The creditor account number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Gets ors sets the alternative payment schemes.

A maximum of two schemes with parameters are allowed.

Value: The alternative payment schemes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Sets the payment amount.

Valid values are between 0.01 and 999,999,999.99.

Value: The payment amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Sets the additional structured bill information.

Value: The structured bill information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Sets the creditor address.

Value: The creditor address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Sets the payment currency.

Valid values are "CHF" and "EUR".

Value: The payment currency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Sets the debtor address.

The debtor is optional. If it is omitted, both setting this field to  null  or setting an address with all  null  or empty values is ok.

Value: The debtor address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Sets the creditor payment reference.

The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx.

If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

Value: The creditor payment reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Sets the additional unstructured message.

Value: The unstructured message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Sets the version of the SwissQR bill standard.

Value: The SwissQR bill standard version.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

