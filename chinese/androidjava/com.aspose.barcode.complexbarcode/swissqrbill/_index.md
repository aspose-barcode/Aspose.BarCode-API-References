---
title: SwissQRBill
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: SwissQR 账单数据
type: docs
weight: 36
url: /zh/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR 账单数据
## Methods

| Method | 描述 |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | 获取或设置备用付款方案。 |
| [getAmount()](#getAmount--) | 获取付款金额。 |
| [getBillInformation()](#getBillInformation--) | 获取附加的结构化账单信息。 |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | 获取债权人地址。 |
| [getCurrency()](#getCurrency--) | 获取付款货币。 |
| [getDebtor()](#getDebtor--) | 获取债务人地址。 |
| [getReference()](#getReference--) | 获取债权人付款参考。 |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | 获取附加的非结构化消息。 |
| [getVersion()](#getVersion--) | 获取 SwissQR 账单标准的版本。 |
| [hashCode()](#hashCode--) | 获取此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | 设置债权人的账户号码。 |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | 获取或设置备用付款方案。 |
| [setAmount(double value)](#setAmount-double-) | 设置付款金额。 |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 设置附加的结构化账单信息。 |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | 设置债权人地址。 |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | 设置付款货币。 |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | 设置债务人地址。 |
| [setReference(String value)](#setReference-java.lang.String-) | 设置债权人付款参考。 |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 设置附加的非结构化消息。 |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | 设置 SwissQR 账单标准的版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

已从引用中移除空白字符

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawReference | java.lang.String | 原始引用。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于当前对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 如果指定的对象等于当前对象则为 true；否则为 false。
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

账户号码必须是瑞士或列支敦士登银行的有效 IBAN。账户号码中允许出现空格。

值：债权人账户号码。

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


获取或设置备用付款方案。

最多允许两个带参数的方案。

值：备用付款方案。

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


获取付款金额。

有效值范围为 0.01 到 999,999,999.99。

值：付款金额。

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


获取附加的结构化账单信息。

值：结构化账单信息。

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


获取债权人地址。

值：债权人地址。

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


获取付款货币。

有效值为 "CHF" 和 "EUR"。

值：付款货币。

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


获取债务人地址。

债务人是可选的。如果省略，则将此字段设置为  null  或将地址的所有  null  或空值设置为均可。

值：债务人地址。

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


获取债权人付款参考。

参考号是 SwissQR IBAN 的必填项，例如范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 之间的 IBAN。

如果指定，参考号必须是有效的 SwissQR 参考（对应 ISR 参考表格）或根据 ISO 11649（"RFxxxx"）的有效债权人参考。两者都可以包含空格用于格式化。

值：债权人付款参考。

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


获取附加的非结构化消息。

值：非结构化消息。

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


获取 SwissQR 账单标准的版本。

值：SwissQR 账单标准版本。

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此实例的哈希码。

**Returns:**
int - 当前对象的哈希码。
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


设置债权人的账户号码。

账户号码必须是瑞士或列支敦士登银行的有效 IBAN。账户号码中允许出现空格。

值：债权人账户号码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


获取或设置备用付款方案。

最多允许两个带参数的方案。

值：备用付款方案。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


设置付款金额。

有效值范围为 0.01 到 999,999,999.99。

值：付款金额。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


设置附加的结构化账单信息。

值：结构化账单信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


设置债权人地址。

值：债权人地址。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


设置付款货币。

有效值为 "CHF" 和 "EUR"。

值：付款货币。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


设置债务人地址。

债务人是可选的。如果省略，则将此字段设置为  null  或将地址的所有  null  或空值设置为均可。

值：债务人地址。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


设置债权人付款参考。

参考号是 SwissQR IBAN 的必填项，例如范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 之间的 IBAN。

如果指定，参考号必须是有效的 SwissQR 参考（对应 ISR 参考表格）或根据 ISO 11649（"RFxxxx"）的有效债权人参考。两者都可以包含空格用于格式化。

值：债权人付款参考。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


设置附加的非结构化消息。

值：非结构化消息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


设置 SwissQR 账单标准的版本。

值：SwissQR 账单标准版本。

**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

