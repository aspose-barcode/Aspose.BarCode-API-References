---
title: "CaptionParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Параметры подписи."
type: docs
weight: 20
url: /ru/java/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Параметры подписи.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Тест горизонтального выравнивания подписи. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Шрифт подписи. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Укажите переносы слов (разрывы строк) в тексте.
``` |
| [getPadding()](#getPadding--) | Captions paddings. |
| [getText()](#getText--) | Caption text. |
| [getTextColor()](#getTextColor--) | Caption text color. |
| [getVisible()](#getVisible--) | Caption text visibility. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Caption test horizontal alignment. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | Отступы подписи. |
| [setText(String value)](#setText-java.lang.String-) | Текст подписи. |
| [setTextColor(Color value)](#setTextColor-java.awt.Color-) | Цвет текста подписи. |
| [setVisible(boolean value)](#setVisible-boolean-) | Видимость текста подписи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionParameters() {#CaptionParameters--}
```
public CaptionParameters()
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


Тест горизонтального выравнивания подписи. Значение по умолчанию: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Шрифт подписи. Значение по умолчанию: Arial 8pt regular.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
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
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


Отступы подписи. Значение по умолчанию для CaptionAbove: 5pt 5pt 0 5pt. Значение по умолчанию для CaptionBelow: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


Текст подписи. Значение по умолчанию: пустая строка.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Цвет текста подписи. Значение по умолчанию: Color.BLACK.

**Returns:**
java.awt.Color
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Видимость текста подписи. Значение по умолчанию: false.

**Returns:**
boolean
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


Тест горизонтального выравнивания подписи. Значение по умолчанию: StringAlignment.Center.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

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

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


Отступы подписи. Значение по умолчанию для CaptionAbove: 5pt 5pt 0 5pt. Значение по умолчанию для CaptionBelow: 0 5pt 5pt 5pt.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Текст подписи. Значение по умолчанию: пустая строка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color value)
```


Цвет текста подписи. Значение по умолчанию: Color.BLACK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Видимость текста подписи. Значение по умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

