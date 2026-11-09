---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "DataMatrix 매개변수."
type: docs
weight: 32
url: /ko/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix 매개변수.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 바코드 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEccType()](#getEccType--) | Datamatrix ECC 유형을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix 바코드의 인코드 모드. |
| [getMacroCharacters()](#getMacroCharacters--) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05 및 06 값을 사용합니다. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix 바코드의 구조적 추가 모드에 대한 바코드 ID. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. |
| [getVersion()](#getVersion--) | Datamatrix 심볼 크기를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | 리더에게 기호에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 바코드 모듈의 높이/너비 비율. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC 유형을 설정합니다. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix 바코드의 인코드 모드. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05 및 06 값을 사용합니다. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | 리더에게 기호에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix 바코드의 구조적 추가 모드에 대한 바코드 ID. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D 바코드 모듈의 높이/너비 비율.

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


Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다. EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다. 기본값: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
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
public final int hashCode()
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


2D 바코드 모듈의 높이/너비 비율.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix ECC 유형을 설정합니다. 기본값: DataMatrixEccType.Ecc200.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC 유형. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.Auto.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다. EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다. 기본값: MacroCharacters.None.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID. 기본값: 0

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수. 기본값: 0

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix 심볼 크기를 설정합니다. 기본값: Version.Auto.

**Parameters:**
| 매개변수 | 유형 | 설명 |
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
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

