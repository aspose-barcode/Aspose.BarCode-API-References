---
title: "CodetextParameters"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Параметры Codetext."
type: docs
weight: 26
url: /ru/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Параметры Codetext.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает выравнивание кодтекста. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Укажите цвет отображаемого CodeText. |
| [getFont()](#getFont--) | Укажите шрифт отображаемого CodeText. |
| [getFontMode()](#getFontMode--) | Укажите FontMode. |
| [getLocation()](#getLocation--) | Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Укажите переносы слов (разрывы строк) в тексте.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Расстояние между CodeText и BarCode в единицах измерения. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Текст, который будет отображаться вместо кода в 2D штрих-кодах. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого CodetextParameters. |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Получает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER.

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


Укажите цвет отображаемого CodeText. Значение по умолчанию: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.BELOW для 1D штрих-кодов и CodeLocation.None для 2D штрих-кодов.

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


Расстояние между CodeText и BarCode в единицах измерения. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Текст, который будет отображаться вместо кода в 2D штрих-кодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
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


Устанавливает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Укажите цвет отображаемого CodeText. Значение по умолчанию: Color.BLACK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.BELOW для 1D штрих-кодов и CodeLocation.None для 2D штрих-кодов.

**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Расстояние между CodeText и BarCode в единицах измерения. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Текст, который будет отображаться вместо кода в 2D штрих-кодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого CodetextParameters.

**Returns:**
java.lang.String — строка, представляющая этот CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

