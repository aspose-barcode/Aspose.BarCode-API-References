---
title: "HanXinExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: 
type: docs
weight: 48
url: /el/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Εκτεταμένος δημιουργός κωδικού κειμένου για τον κώδικα Han Xin για την εκτεταμένη λειτουργία του HanXinEncodeMode

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Auto |
| [addBinary(String text)](#addBinary-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Binary |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Common Chinese Region One |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Common Chinese Region Two |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GB18030 Four Byte |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GB18030 Two Byte |
| [addGS1(String text)](#addGS1-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Numeric |
| [addText(String text)](#addText-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Text |
| [addURI(String text)](#addURI-java.lang.String-) | Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Προσθέτει τμήμα codetext σε λειτουργία Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Επιστρέφει codetext από τον δημιουργό codetext σε λειτουργία Extended |
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


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Auto

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Binary

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Common Chinese Region One

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Common Chinese Region Two

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία ECI

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |
| encoding | int | Κωδικοποίηση ECI σε μορφή ακέραιου |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GB18030 Four Byte

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GB18030 Two Byte

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία GS1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Numeric

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία Text

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Προσθέτει τμήμα κωδικού κειμένου σε λειτουργία URI

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Προσθέτει τμήμα codetext σε λειτουργία Unicode

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Συμβολοσειρά codetext |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Επιστρέφει codetext από τον δημιουργό codetext σε λειτουργία Extended

**Returns:**
java.lang.String - Codetext σε λειτουργία Extended
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

