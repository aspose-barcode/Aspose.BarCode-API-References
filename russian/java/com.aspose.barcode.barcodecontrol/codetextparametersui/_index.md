---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "Обёртка UI для класса com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /ru/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

Обёртка UI для класса com.aspose.barcode.generation.CodetextParameters.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает выравнивание текста кода. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Укажите цвет отображаемого CodeText. |
| [getFont()](#getFont--) | Укажите шрифт отображаемого CodeText. |
| [getFontMode()](#getFontMode--) | Укажите FontMode. |
| [getLocation()](#getLocation--) | Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. |
| [getSpace()](#getSpace--) | Расстояние между CodeText и BarCode в значении. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Текст, который будет отображаться вместо codetext в 2D штрих-кодах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Устанавливает выравнивание текста кода. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Укажите цвет отображаемого CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Укажите шрифт отображаемого CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Укажите FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Текст, который будет отображаться вместо codetext в 2D штрих-кодах. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого CodetextParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Получает выравнивание текста кода. Значение по умолчанию: StringAlignment.Center.

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


Укажите цвет отображаемого CodeText. Значение по умолчанию: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет вычисляться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Укажите расположение отображаемого CodeText, установите CodeLocation.None, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.BELOW для 1D штрих-кодов и CodeLocation.None для 2D штрих-кодов.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Расстояние между CodeText и BarCode в значении. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Текст, который будет отображаться вместо codetext в 2D штрих-кодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Устанавливает выравнивание текста кода. Значение по умолчанию: StringAlignment.Center.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Укажите цвет отображаемого CodeText. Значение по умолчанию: Color.BLACK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет вычисляться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

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

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Текст, который будет отображаться вместо codetext в 2D штрих-кодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого CodetextParameters .

**Returns:**
java.lang.String - Строка, представляющая этот CodetextParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

