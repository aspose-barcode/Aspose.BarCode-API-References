---
title: HanXinParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات Han Xin.
type: docs
weight: 50
url: /ar/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

معلمات Han Xin.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getEncodeMode()](#getEncodeMode--) | وضع الترميز HanXin. |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | وضع الترميز HanXin. |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. |
| [getHanXinVersion()](#getHanXinVersion--) | إصدار كود HanXin. |
| [getVersion()](#getVersion--) | إصدار كود HanXin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | وضع الترميز HanXin. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | إصدار كود HanXin. |
| [toString()](#toString--) | إرجاع تمثيل نصي قابل للقراءة البشرية لهذا [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


معرفات تفسير القناة الموسعة. يتم استخدامها لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يحتوي التنفيذ الحالي على جميع ترميزات مجموعة الأحرف المعروفة.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


وضع الترميز HanXin. القيمة الافتراضية: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. من منخفض إلى عالي: L1, L2, L3, L4. انظر ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


معرفات تفسير القناة الموسعة. يتم استخدامها لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يحتوي التنفيذ الحالي على جميع ترميزات مجموعة الأحرف المعروفة.

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


وضع الترميز HanXin. القيمة الافتراضية: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. من منخفض إلى عالي: L1, L2, L3, L4. انظر ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


إصدار كود HanXin. من Version01 إلى Version84 لرمز Han Xin. القيمة الافتراضية هي Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


إصدار كود HanXin. من Version01 إلى Version84 لرمز Han Xin. القيمة الافتراضية هي Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. يتم استخدامها لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يحتوي التنفيذ الحالي على جميع ترميزات مجموعة الأحرف المعروفة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


وضع الترميز HanXin. القيمة الافتراضية: EncodeMode.Mixed.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود Han Xin. من منخفض إلى عالي: L1, L2, L3, L4. انظر ErrorLevel.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


إصدار كود HanXin. من Version01 إلى Version84 لرمز Han Xin. القيمة الافتراضية هي Version.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


إرجاع تمثيل نصي قابل للقراءة البشرية لهذا [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

