---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "DataMatrix parametreleri."
type: docs
weight: 32
url: /tr/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix parametreleri.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEccType()](#getEccType--) | Bir Datamatrix ECC türünü alır. |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix barkodunun kodlama modu. |
| [getMacroCharacters()](#getMacroCharacters--) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix barkodunun Yapılandırılmış Ek modu için Barkod kimliği. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix barkodunun Structured Append modunda barkod sayısı. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix barkodunun Structured Append modunda Dosya Kimliği. |
| [getVersion()](#getVersion--) | Bir Datamatrix sembol boyutunu alır. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Bir Datamatrix ECC türü ayarlar. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix barkodunun kodlama modu. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix barkodunun Yapılandırılmış Ek modu için Barkod kimliği. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix barkodunun Structured Append modunda barkod sayısı. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix barkodunun Structured Append modunda Dosya Kimliği. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Bir Datamatrix sembol boyutunu ayarlar. |
| [toString()](#toString--) | Bu [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) öğesinin insan tarafından okunabilir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

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


ECI kodlamasını alır. EncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int - ECI kodlaması.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Bir Datamatrix ECC türünü alır. Varsayılan değer: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca DataMatrixEccType.Ecc200 veya DataMatrixEccType.EccAuto ile kullanılabilir. EncodeTypes.GS1DataMatrix ile kullanılamaz. Varsayılan değer: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix barkodunun Structured Append modunda Barkod Kimliği. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix barkodunun Structured Append modunda barkod sayısı. Varsayılan değer: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix barkodunun Structured Append modunda Dosya Kimliği. Varsayılan değer: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Bir Datamatrix sembol boyutunu alır. Varsayılan değer: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlaması talimatını vermek için kullanılır. Varsayılan değer: false

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


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI kodlamasını ayarlar. EncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Bir Datamatrix ECC türü ayarlar. Varsayılan değer: DataMatrixEccType.Ecc200.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | bir Datamatrix ECC türü. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca DataMatrixEccType.Ecc200 veya DataMatrixEccType.EccAuto ile kullanılabilir. EncodeTypes.GS1DataMatrix ile kullanılamaz. Varsayılan değer: MacroCharacters.None.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlaması talimatını vermek için kullanılır. Varsayılan değer: false

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix barkodunun Structured Append modunda Barkod Kimliği. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix barkodunun Structured Append modunda barkod sayısı. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix barkodunun Structured Append modunda Dosya Kimliği. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Bir Datamatrix sembol boyutunu ayarlar. Varsayılan değer: Version.Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | bir Datamatrix sembol boyutu. |

### toString() {#toString--}
```
public String toString()
```


Bu [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) öğesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) öğesini temsil eden bir dizedir.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

