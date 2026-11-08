---
title: "DataMatrixParametersUI"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "غلاف واجهة المستخدم لفئة com.aspose.barcode.generation.DataMatrixParameters."
type: docs
weight: 14
url: /ar/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

غلاف واجهة المستخدم لفئة com.aspose.barcode.generation.DataMatrixParameters.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | يحصل على ترميز ECI. |
| [getEccType()](#getEccType--) | يحصل على نوع ECC للـ Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | وضع الترميز لباركود Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | بروتوكول الأحرف الكبيرة في الموضع الأول (ECC 200 فقط) |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | معرّف الباركود لوضع الإلحاق المُنظم. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | عدد الباركودات لوضع الإلحاق المُنظم. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | معرّف الملف لوضع الإلحاق المُنظم. |
| [getVersion()](#getVersion--) | حجم رمز DataMatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | يضبط نوع ECC للـ Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | وضع الترميز لباركود Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | بروتوكول الأحرف الكبيرة في الموضع الأول (ECC 200 فقط) |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | معرّف الباركود لوضع الإلحاق المُنظم. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | عدد الباركودات لوضع الإلحاق المُنظم. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | معرّف الملف لوضع الإلحاق المُنظم. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | حجم رمز DataMatrix. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

**Returns:**
float
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


يحصل على ترميز ECI. يُستخدم عندما يكون EncodeMode تلقائيًا.

**Returns:**
int - ترميز ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


يحصل على نوع ECC للـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


بروتوكول الأحرف الكبيرة في الموضع الأول (ECC 200 فقط)

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


معرّف الباركود لوضع الإلحاق المُنظم.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


عدد الباركودات لوضع الإلحاق المُنظم.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


معرّف الملف لوضع الإلحاق المُنظم.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


حجم رمز DataMatrix.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يضبط ترميز ECI. يُستخدم عندما يكون EncodeMode تلقائيًا.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


يضبط نوع ECC للـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | نوع ECC للـ Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


بروتوكول الأحرف الكبيرة في الموضع الأول (ECC 200 فقط)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


معرّف الباركود لوضع الإلحاق المُنظم.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


عدد الباركودات لوضع الإلحاق المُنظم.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


معرّف الملف لوضع الإلحاق المُنظم.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


حجم رمز DataMatrix.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

