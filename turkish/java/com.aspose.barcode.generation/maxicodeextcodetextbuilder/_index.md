---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Referansı"
description: "MaxiCode barkodları için MaxiCodeEncodeMode'un ExtendedCodetext Modu'nda Extended kodmetni üreticisi; görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın."
type: docs
weight: 54
url: /tr/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

ExtendedCodetext Mode için MaxiCode barkodları için ExtendedCodetext Mode'un MaxiCodeEncodeMode içinde TwoDDisplayText özelliğini kullanarak görünür metni yönetim karakterlerini kaldıracak şekilde ayarlayan genişletilmiş kod metni oluşturucu. Bu örnek, MaxiCodeExtCodetextBuilder'ı Extended Mode'da nasıl kullanacağınızı gösterir.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz kodmetni genişletilmiş kodmetin öğelerine ekler |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
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

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Düz kodmetni genişletilmiş kodmetin öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | Unicode'da kod metni, genişletilmiş kod metni öğesi olarak eklemek için |

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

