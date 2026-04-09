---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: 
type: docs
weight: 49
url: /el/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Γεννήτρια εκτεταμένου κειμένου κώδικα για τον κώδικα Han Xin για την εκτεταμένη λειτουργία του HanXinEncodeMode

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
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Auto |
| [addBinary(String text)](#addBinary-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Binary |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Common Chinese Region One |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Common Chinese Region Two |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GB18030 Four Byte |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GB18030 Two Byte |
| [addGS1(String text)](#addGS1-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Numeric |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Text |
| [addURI(String text)](#addURI-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Επιστρέφει το κείμενο κώδικα από τον δημιουργό κειμένου κώδικα σε εκτεταμένη λειτουργία |
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


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Auto

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Binary

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Common Chinese Region One

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Common Chinese Region Two

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία ECI

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |
| encoding | int | Κωδικοποίηση ECI σε ακέραιο μορφή |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GB18030 Four Byte

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GB18030 Two Byte

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία GS1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Numeric

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Text

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία URI

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Προσθέτει τμήμα κειμένου κώδικα σε λειτουργία Unicode

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Συμβολοσειρά κειμένου κώδικα |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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


Επιστρέφει το κείμενο κώδικα από τον δημιουργό κειμένου κώδικα σε εκτεταμένη λειτουργία

**Returns:**
java.lang.String - Κείμενο κώδικα σε εκτεταμένη λειτουργία
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

