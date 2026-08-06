---
title: DataMatrixParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: DataMatrix 매개변수.
type: docs
weight: 34
url: /ko/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 열 수. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Datamatrix ECC 유형을 가져옵니다. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Datamatrix 심볼 크기를 가져옵니다. |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEccType()](#getEccType--) | Datamatrix ECC 유형을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | 특수 모드에서 보다 압축된 인코딩을 얻기 위해 매크로 문자 05 및 06 값을 사용합니다. |
| [getRows()](#getRows--) | 행 수. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. |
| [getVersion()](#getVersion--) | Datamatrix 심볼 크기를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode 모듈의 높이/너비 비율. |
| [setColumns(int value)](#setColumns-int-) | 열 수. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC 유형을 설정합니다. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix 심볼 크기를 설정합니다. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC 유형을 설정합니다. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 특수 모드에서 보다 압축된 인코딩을 얻기 위해 매크로 문자 05 및 06 값을 사용합니다. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setRows(int value)](#setRows-int-) | 행 수. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix 심볼 크기를 설정합니다. |
| [toString()](#toString--) | 이 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D BarCode 모듈의 높이/너비 비율.

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


열 수.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Datamatrix ECC 유형을 가져옵니다. 기본값: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Datamatrix 심볼 크기를 가져옵니다. 기본값: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI 인코딩을 가져옵니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int - ECI 인코딩.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Datamatrix ECC 유형을 가져옵니다. 기본값: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


특수 모드에서 더 압축된 인코딩을 얻기 위해 Macro Characters 05 및 06 값을 사용합니다. DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다. EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다. 기본값: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


행 수.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. 기본값: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. 기본값: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Datamatrix 심볼 크기를 가져옵니다. 기본값: Version.Auto.

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


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false

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


2D BarCode 모듈의 높이/너비 비율.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


열 수.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Datamatrix ECC 유형을 설정합니다. 기본값: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC 유형. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Datamatrix 심볼 크기를 설정합니다. 기본값: Version.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix 심볼 크기. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix ECC 유형을 설정합니다. 기본값: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC 유형. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


특수 모드에서 더 압축된 인코딩을 얻기 위해 Macro Characters 05 및 06 값을 사용합니다. DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다. EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다. 기본값: MacroCharacters.None.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


행 수.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix 심볼 크기를 설정합니다. 기본값: Version.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix 심볼 크기. |

### toString() {#toString--}
```
public String toString()
```


이 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)를 나타내는 문자열입니다.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

