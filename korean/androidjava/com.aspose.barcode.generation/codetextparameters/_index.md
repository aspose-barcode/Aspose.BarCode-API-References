---
title: CodetextParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 코드텍스트 매개변수.
type: docs
weight: 27
url: /ko/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

코드텍스트 매개변수.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 코드 텍스트의 정렬을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 표시되는 CodeText의 색상을 지정합니다. |
| [getFont()](#getFont--) | 표시되는 CodeText의 글꼴을 지정합니다. |
| [getFontMode()](#getFontMode--) | FontMode를 지정합니다. |
| [getLocation()](#getLocation--) | 표시되는 CodeText 위치를 지정하고, CodeLocation.None으로 설정하면 CodeText를 숨깁니다. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
텍스트 내에서 단어 줄 바꿈(줄 바꿈)을 지정합니다.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | CodeText와 BarCode 사이의 간격(단위 값). |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2D 바코드에서 코드 텍스트 대신 표시될 텍스트. |
| [toString()](#toString--) | 이 CodetextParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


코드 텍스트의 정렬을 가져옵니다. 기본값: TextAlignment.CENTER.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public int getColor()
```


표시되는 CodeText의 색상을 지정합니다. 기본값: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. 특히 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION에서 FontMode.AUTO를 사용하는 것이 권장됩니다. 기본값: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.None으로 설정합니다. 기본값: 1D 바코드의 경우 CodeLocation.BELOW, 2D 바코드의 경우 CodeLocation.None.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText와 BarCode 사이의 간격을 Unit 값으로 지정합니다. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D 바코드에서 codetext 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
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




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


코드 텍스트의 정렬을 설정합니다. 기본값: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


표시되는 CodeText의 색상을 지정합니다. 기본값: Color.BLACK.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. 특히 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION에서 FontMode.AUTO를 사용하는 것이 권장됩니다. 기본값: FontMode.AUTO.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.None으로 설정합니다. 기본값: 1D 바코드의 경우 CodeLocation.BELOW, 2D 바코드의 경우 CodeLocation.None.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


CodeText와 BarCode 사이의 간격을 Unit 값으로 지정합니다. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D 바코드에서 codetext 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


이 CodetextParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 CodetextParameters를 나타내는 문자열입니다.
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

