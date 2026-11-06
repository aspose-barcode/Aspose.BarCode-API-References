---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "MaxiCode barkodları için ExtendedCodetext Modu'nda MaxiCodeEncodeMode'un Extended codetext üreteci. Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın."
type: docs
weight: 54
url: /tr/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

MaxiCodeEncodeMode'un ExtendedCodetext Modu için MaxiCode barkodları için genişletilmiş kod metni oluşturucu. Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın. Bu örnek, MaxiCodeExtCodetextBuilder'ın Genişletilmiş Modda nasıl kullanılacağını gösterir.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier ile codetext ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz codetext'i genişletilmiş codetext öğelerine ekler |
| [clear()](#clear--) | Genişletilmiş codetext öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genişletilmiş codetext listesinden Extended codetext üretir. |
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


Extended Channel Identifier ile codetext ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier ile genişletilmiş codetext öğesi olarak eklenecek unicode codetext |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Düz codetext'i genişletilmiş codetext öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | Genişletilmiş codetext öğesi olarak eklenecek unicode codetext |

### clear() {#clear--}
```
public void clear()
```


Genişletilmiş codetext öğelerini temizler

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


Genişletilmiş codetext listesinden Extended codetext üretir.

**Returns:**
java.lang.String - Extended codetext dize olarak
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

