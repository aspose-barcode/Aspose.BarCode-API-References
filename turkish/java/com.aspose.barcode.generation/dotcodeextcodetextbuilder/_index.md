---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Referansı"
description: 
type: docs
weight: 33
url: /tr/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

DotCodeEncodeMode'un ExtendedCodetext Modu için 2D DotCode barkodları için genişletilmiş kod metni oluşturucu

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Genişletilmiş kod metni öğelerine FNC1 format tanımlayıcısı ekler |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Genişletilmiş kod metni öğelerine FNC3 okuyucu başlatmasını ekler |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Genişletilmiş kod metni öğelerine FNC3 sembol ayırıcı ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz kodmetni genişletilmiş kodmetin öğelerine ekler |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Genişletilmiş kod metni öğelerine yapılandırılmış ekleme modunu ekler |
| [clear()](#clear--) | Genişletilmiş kodmetin öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genişletilmiş kodmetin listesinden Genişletilmiş kodmetin oluşturur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Genişletilmiş Kanal Tanımlayıcısı |
| codetext | java.lang.String | Genişletilmiş Kanal Tanımlayıcısı ile genişletilmiş kodmetin öğesi olarak eklemek için unicode'daki kodmetin |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Genişletilmiş kod metni öğelerine FNC1 format tanımlayıcısı ekler

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Genişletilmiş kod metni öğelerine FNC3 okuyucu başlatmasını ekler

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Genişletilmiş kod metni öğelerine FNC3 sembol ayırıcı ekler

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Düz kodmetni genişletilmiş kodmetin öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | Unicode'da kod metni, genişletilmiş kod metni öğesi olarak eklemek için |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Genişletilmiş kod metni öğelerine yapılandırılmış ekleme modunu ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeId | int | Barkod kimliği |
| barcodesCount | int | Barkod sayısı |

### clear() {#clear--}
```
public void clear()
```


Genişletilmiş kodmetin öğelerini temizler

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Genişletilmiş kodmetin listesinden Genişletilmiş kodmetin oluşturur.

**Returns:**
java.lang.String - Genişletilmiş kod metni dize olarak
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
public final native void wait(long arg0)
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

