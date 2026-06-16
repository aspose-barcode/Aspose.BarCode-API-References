---
title: DataMatrixParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات DataMatrix.
type: docs
weight: 34
url: /ar/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

معلمات DataMatrix.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | عدد الأعمدة. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | يحصل على نوع ECC للـ Datamatrix. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | يحصل على حجم رمز Datamatrix. |
| [getECIEncoding()](#getECIEncoding--) | يسترجع ترميز ECI. |
| [getEccType()](#getEccType--) | يحصل على نوع ECC للـ Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. |
| [getRows()](#getRows--) | عدد الصفوف. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | معرّف الباركود لوضع الإلحاق المنظم لباركود Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | عدد الباركودات لوضع الإلحاق المنظم لباركود Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | معرّف الملف لوضع الإلحاق المنظم لباركود Datamatrix. |
| [getVersion()](#getVersion--) | يحصل على حجم رمز Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [setColumns(int value)](#setColumns-int-) | عدد الأعمدة. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | يضبط نوع ECC للـ Datamatrix. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | يضبط حجم رمز Datamatrix. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | يضبط نوع ECC للـ Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setRows(int value)](#setRows-int-) | عدد الصفوف. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | معرّف الباركود لوضع الإلحاق المنظم لباركود Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | عدد الباركودات لوضع الإلحاق المنظم لباركود Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | معرّف الملف لوضع الإلحاق المنظم لباركود Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | يضبط حجم رمز Datamatrix. |
| [toString()](#toString--) | يعيد تمثيل نصي قابل للقراءة البشرية لهذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


عدد الأعمدة.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


يحصل على نوع ECC للـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


يحصل على حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


يحصل على ترميز ECI. يُستخدم عندما يكون EncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Returns:**
عدد صحيح - ترميز ECI.
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


تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يمكن استخدامها فقط مع DataMatrixEccType.Ecc200 أو DataMatrixEccType.EccAuto. لا يمكن استخدامها مع EncodeTypes.GS1DataMatrix. القيمة الافتراضية: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


عدد الصفوف.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


معرّف الباركود لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


عدد الباركودات لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


معرّف الملف لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


يحصل على حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
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


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false

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


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


عدد الأعمدة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


يضبط نوع ECC للـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | نوع ECC للـ Datamatrix. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


يضبط حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | حجم رمز Datamatrix. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يضبط ترميز ECI. يُستخدم عندما يكون EncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


يضبط نوع ECC للـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | نوع ECC للـ Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يمكن استخدامها فقط مع DataMatrixEccType.Ecc200 أو DataMatrixEccType.EccAuto. لا يمكن استخدامها مع EncodeTypes.GS1DataMatrix. القيمة الافتراضية: MacroCharacters.None.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


عدد الصفوف.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


معرّف الباركود لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


عدد الباركودات لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


معرّف الملف لوضع الإلحاق المنظم لباركود Datamatrix. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


يضبط حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | حجم رمز Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيل نصي قابل للقراءة البشرية لهذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

