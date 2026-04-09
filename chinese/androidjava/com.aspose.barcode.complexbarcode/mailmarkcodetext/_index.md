---
title: MailmarkCodetext
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。
type: docs
weight: 24
url: /zh/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Initializes a new instance of the  MailmarkCodetext  class. |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 获取条形码类型。 |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | The PC and DP must comply with a PAF format. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null or Test "1" \\u2013 Letter "2" \\u2013 Large Letter |
| [getItemID()](#getItemID--) | Maximum value is 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [getVersionID()](#getVersionID--) | Currently "1" \\u2013 For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | The PC and DP must comply with a PAF format. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null or Test "1" \\u2013 Letter "2" \\u2013 Large Letter |
| [setItemID(int value)](#setItemID-int-) | Maximum value is 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Currently "1" \\u2013 For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Initializes a new instance of the  MailmarkCodetext  class.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


获取条形码类型。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - 已构建的编码文本
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null or Test "1" \\u2013 Letter "2" \\u2013 Large Letter

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Maximum value is 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Maximum values are 99 for Barcode C and 999999 for Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Currently "1" \\u2013 For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

**Returns:**
int
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 已构建的编码文本。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null or Test "1" \\u2013 Letter "2" \\u2013 Large Letter

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Maximum value is 99999999.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Maximum values are 99 for Barcode C and 999999 for Barcode L.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Currently "1" \\u2013 For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

