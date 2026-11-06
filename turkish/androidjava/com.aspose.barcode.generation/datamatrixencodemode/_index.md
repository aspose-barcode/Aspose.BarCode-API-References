---
title: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "DataMatrix kodlayıcılarının kodlama modu varsayılan olarak Otomatik'tir."
type: docs
weight: 82
url: /tr/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix kodlayıcısının kodlama modu, varsayılan olarak Otomatik

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ANSIX12](#ANSIX12) | ANSI X12 kodlamasını kullanır. |
| [ASCII](#ASCII) | Her bayt için bir alfanümerik veya iki sayısal karakter kodlar. |
| [AUTO](#AUTO) | Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [BASE_256](#BASE-256) | 8 bit değerleri kodla |
| [BINARY](#BINARY) | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [C40](#C40) | C40 kodlamasını kullanır. |
| [ECI](#ECI) | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. |
| [EDIFACT](#EDIFACT) | EDIFACT kodlamasını kullanır. |
| [EXTENDED](#EXTENDED) | ExtendedCodetext modu, kod metninde kodlama şemalarını ve ECI kodlamalarını manuel olarak değiştirmeye izin verir. |
| [TEXT](#TEXT) | Metin kodlamasını kullanır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


ANSI X12 kodlamasını kullanır.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Her bayt için bir alfanümerik veya iki sayısal karakter kodlar.

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


8 bit değerleri kodla

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext modu, kodmetninde kodlama şemalarını ve ECI kodlamalarını manuel olarak değiştirmeye izin verir. Genişletilmiş kodmetin oluşturulması için DataMatrixExtCodetextBuilder kullanılması daha iyidir. Görünür metni yönetim karakterlerini kaldırarak ayarlamak için Display2DText özelliğini kullanın. ECI tanımlayıcıları tek bir eğik çizgi ve altı basamaklı "\\000026" - UTF8 ECI tanımlayıcısı olarak ayarlanır. ECI tanımlayıcısından sonraki tüm unicode karakterler otomatik olarak doğru karakter kod setine kodlanır. Kodlama şemaları aşağıdaki formatta ayarlanır: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". İzin verilen kodlama şemaları şunlardır: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Metindeki tüm ters eğik çizgiler (\\) iki kez kullanılmalıdır.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Text kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

