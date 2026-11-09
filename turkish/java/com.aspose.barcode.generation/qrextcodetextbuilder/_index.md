---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Referansı"
description: 
type: docs
weight: 61
url: /tr/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode'un ExtendedCodetext Modu için 2D QR barkodları için genişletilmiş kod metni oluşturucu

Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın.

Bu örnek, Genişletilmiş Modda FNC1'in ilk konumunun nasıl kullanılacağını gösterir.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Bu örnek, Genişletilmiş Modda FNC1'in ikinci konumunun nasıl kullanılacağını gösterir.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Bu örnek, Genişletilmiş Modda çoklu ECI modunun nasıl kullanılacağını gösterir.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Belirtilen QR sıkıştırma modu ile kod metnini genişletilmiş kod metni öğelerine ekler. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | FNC1'i ilk konuma ayarlar. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Genişletilmiş kod metni öğelerine Grup Ayırıcı (GS - '\\\\u001D') ekler |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | FNC1'i ikinci konuma ayarlar. |
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
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


Belirtilen QR sıkıştırma modu ile kod metnini genişletilmiş kod metni öğelerine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | Kod metni için QR sıkıştırma modu. |
| codetext | java.lang.String | Genişletilmiş kod metni öğesi olarak eklenecek Unicode kod metni. |

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

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


FNC1'i ilk konuma ayarlar. Daha önce başka bir FNC1 modu ayarlanmışsa, yerine geçer.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Genişletilmiş kod metni öğelerine Grup Ayırıcı (GS - '\\\\u001D') ekler

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


FNC1'i ikinci konuma ayarlar. Daha önce başka bir FNC1 modu ayarlanmışsa, yerine geçer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | İkinci konumdaki FNC1'in değeri. Değer a-z veya A-Z aralığından tek bir harf ya da 00 ile 99 arasında iki basamaklı bir sayı olmalıdır. |

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

