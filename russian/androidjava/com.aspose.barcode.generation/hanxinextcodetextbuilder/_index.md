---
title: HanXinExtCodetextBuilder
second_title: Справочник API Aspose.BarCode для Android через Java
description: 
type: docs
weight: 49
url: /ru/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Расширенный генератор кодового текста для Han Xin Code в расширенном режиме HanXinEncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>  codeTextBuilder.addGB18030TwoByte("\u6f04");
>  codeTextBuilder.addGB18030FourByte("\u3401");
>  codeTextBuilder.addCommonChineseRegionOne("\u5168");
>  codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>  codeTextBuilder.addNumeric("123");
>  codeTextBuilder.addText("qwe");
>  codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>  codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>  codeTextBuilder.addAuto("abc");
>  codeTextBuilder.addBinary("abc");
>  codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
>  codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10");
>  String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10";
>  //generate codetext
>  String str = codeTextBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str);
>  bg.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>  BufferedImage img = bg.generateBarCodeImage();
>  BarCodeReader r = new BarCodeReader(img, DecodeType.HAN_XIN))
>  BarcodeResult[] found = r.readBarCodes();
>  Assert.assertEquals(1, found.length);
>  Assert.assertEquals(expectedStr, found[0].getCodeText());
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Auto |
| [addBinary(String text)](#addBinary-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Binary |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Common Chinese Region One |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Common Chinese Region Two |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Добавляет фрагмент кодового текста в режиме ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Добавляет фрагмент кодового текста в режиме GB18030 Four Byte |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Добавляет фрагмент кодового текста в режиме GB18030 Two Byte |
| [addGS1(String text)](#addGS1-java.lang.String-) | Добавляет фрагмент кодового текста в режиме GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Numeric |
| [addText(String text)](#addText-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Text |
| [addURI(String text)](#addURI-java.lang.String-) | Добавляет фрагмент кодового текста в режиме URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Добавляет фрагмент кодового текста в режиме Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Возвращает кодовый текст из построителя кодового текста в расширенном режиме |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HanXinExtCodetextBuilder() {#HanXinExtCodetextBuilder--}
```
public HanXinExtCodetextBuilder()
```


### addAuto(String text) {#addAuto-java.lang.String-}
```
public void addAuto(String text)
```


Добавляет фрагмент кодового текста в режиме Auto

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Добавляет фрагмент кодового текста в режиме Binary

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Добавляет фрагмент кодового текста в режиме Common Chinese Region One

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Добавляет фрагмент кодового текста в режиме Common Chinese Region Two

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Добавляет фрагмент кодового текста в режиме ECI

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |
| encoding | int | Кодирование ECI в целочисленном формате |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Добавляет фрагмент кодового текста в режиме GB18030 Four Byte

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Добавляет фрагмент кодового текста в режиме GB18030 Two Byte

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Добавляет фрагмент кодового текста в режиме GS1

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Добавляет фрагмент кодового текста в режиме Numeric

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Добавляет фрагмент кодового текста в режиме Text

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Добавляет фрагмент кодового текста в режиме URI

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Добавляет фрагмент кодового текста в режиме Unicode

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Строка кодового текста |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Возвращает кодовый текст из построителя кодового текста в расширенном режиме

**Returns:**
java.lang.String - кодовый текст в расширенном режиме
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

