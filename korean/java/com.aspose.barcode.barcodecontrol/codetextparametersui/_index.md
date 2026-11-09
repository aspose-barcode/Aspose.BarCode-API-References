---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "UI 래퍼 for com.aspose.barcode.generation.CodetextParameters 클래스."
type: docs
weight: 13
url: /ko/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI 래퍼 for com.aspose.barcode.generation.CodetextParameters 클래스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 코드 텍스트의 정렬을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 표시되는 CodeText의 색상을 지정합니다. |
| [getFont()](#getFont--) | 표시되는 CodeText의 글꼴을 지정합니다. |
| [getFontMode()](#getFontMode--) | FontMode를 지정합니다. |
| [getLocation()](#getLocation--) | 표시되는 CodeText 위치를 지정하고, CodeText를 숨기려면 CodeLocation.None으로 설정합니다. |
| [getSpace()](#getSpace--) | CodeText와 BarCode 사이의 간격을 값으로 지정합니다. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | 2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | 코드 텍스트의 정렬을 설정합니다. |
| [setColor(Color value)](#setColor-java.awt.Color-) | 표시되는 CodeText의 색상을 지정합니다. |
| [setFont(Font value)](#setFont-java.awt.Font-) | 표시되는 CodeText의 글꼴을 지정합니다. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | FontMode를 지정합니다. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | 표시되는 CodeText 위치를 지정하고, CodeText를 숨기려면 CodeLocation.None으로 설정합니다. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. |
| [toString()](#toString--) | 이 CodetextParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


코드 텍스트의 정렬을 가져옵니다. 기본값: StringAlignment.Center.

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
public Color getColor()
```


표시되는 CodeText의 색상을 지정합니다. 기본값: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

**Returns:**
java.awt.Font
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


표시되는 CodeText 위치를 지정하고, CodeText를 숨기려면 CodeLocation.None으로 설정합니다. 기본값: 1D 바코드의 경우 CodeLocation.BELOW, 2D 바코드의 경우 CodeLocation.None.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText와 BarCode 사이의 간격을 값으로 지정합니다. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에는 적용되지 않습니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


코드 텍스트의 정렬을 설정합니다. 기본값: StringAlignment.Center.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


표시되는 CodeText의 색상을 지정합니다. 기본값: Color.BLACK.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.AUTO로 설정된 경우 무시됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. 특히 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION에서 FontMode.AUTO를 사용하는 것이 권장됩니다. 기본값: FontMode.AUTO.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


표시되는 CodeText 위치를 지정하고, CodeText를 숨기려면 CodeLocation.None으로 설정합니다. 기본값: 1D 바코드의 경우 CodeLocation.BELOW, 2D 바코드의 경우 CodeLocation.None.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| 매개변수 | 유형 | 설명 |
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

