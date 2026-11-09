---
title: "HanXinModes"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Han Xin Code kodlama modu."
type: docs
weight: 89
url: /tr/java/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code kodlama modu. ASCII / Çince karakterler veya Unicode karakterler için Auto kullanılması önerilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AUTO](#AUTO) | Sayısal, Metin, ECI, İkili Bayt ve 4 GB18030 modlarının otomatik olarak değişen sırası. |
| [BINARY](#BINARY) | İkili bayt modu, ikili verileri herhangi bir biçimde kodlar ve bunları ikili baytlarıyla kodlar. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Bölge Bir'deki her yaygın Çince Karakter 12 bit ile temsil edilir. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Bölge İki'deki her yaygın Çince Karakter 12 bit ile temsil edilir. |
| [ECI](#ECI) | Genişletilmiş Kanal Yorumlaması (ECI) modu |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Her GB18030 4 baytlık Bölge karakteri 21 bit ile temsil edilir. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Her GB18030 2 baytlık Bölge karakteri 15 bit ile temsil edilir. |
| [GS_1](#GS-1) | GS1 modu, Han Xin Code içinde temsil edilen verilerin GS1 Genel Şartname tarafından tanımlanan GS1 sistemine ait GS1 verisi olduğunu gösterir. |
| [NUMERIC](#NUMERIC) | Sayısal mod, ondalık rakam kümesinden (0-9 rakamları, bayt değerleri 30HEX'den 39HEX'e) veri kodlar. |
| [TEXT](#TEXT) | Metin modu, ISO/IEC 646'da tanımlanan ortak sembollerden veri kodlar, yani. |
| [UNICODE](#UNICODE) | Unicode modu, Han Xin Kodunda UTF8 kodlaması/karakter kümesine referansla herhangi bir metin verisini temsil etmenin bir yolunu tasarlar. |
| [URI](#URI) | URI modu, Han Xin Kodunda temsil edilen verinin RFC 3986'ya referans olan Uniform Resource Identifier (URI) olduğunu gösterir. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Sayısal, Metin, ECI, İkili Bayt ve 4 GB18030 modlarının otomatik olarak değişen sırası.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


İkili bayt modu, ikili veriyi herhangi bir biçimde kodlar ve bunları ikili baytlarıyla kodlar. İkili Bayt modundaki her bayt 8 bit ile temsil edilir.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Bölge Bir'deki her ortak Çince karakter 12 bit ile temsil edilir. Bölge Bir'deki ortak Çince karakterler, ilk bayt değeri B0HEX ile D7HEX arasında ve ikinci bayt değeri A1HEX ile FEHEX arasında olan karakterleri (3760 karakter), ayrıca ilk bayt değeri A1HEX ile A3HEX arasında ve ikinci bayt değeri A1HEX ile FEHEX arasında olan karakterleri (282 karakter) ve bayt değerleri A8A1HEX ile A8C0HEX arasında olan karakterleri (32 karakter) içerir.

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Bölge İki'deki her ortak Çince karakter 12 bit ile temsil edilir. Bölge İki'deki ortak Çince karakterler, ilk bayt değeri D8HEX ile F7HEX arasında ve ikinci bayt değeri A1HEX ile FEHEX arasında olan karakterleri içerir.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Genişletilmiş Kanal Yorumlaması (ECI) modu

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Her GB18030 4-bayt Bölge karakteri 21 bit ile temsil edilir. GB18030 4-bayt Bölge, GB18030 dört-bayt bölgesindeki tüm karakterlerden veri kodlar (örneğin, ilk bayt değeri 81HEX ile FEHEX arasında, ikinci bayt değeri 30HEX ile 39HEX arasında, üçüncü bayt değeri 81HEX ile FEHEX arasında ve dördüncü bayt değeri 30HEX ile 39HEX arasında olan karakterler).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Her GB18030 2-bayt Bölge karakteri 15 bit ile temsil edilir. GB18030 2-bayt Bölge, GB18030 çift-bayt bölgesindeki tüm karakterlerden (Bölge Bir ve Bölge İki'deki ortak Çince karakterler dahil) veri kodlar (örneğin, ilk bayt değeri 81HEX ile FEHEX arasında ve ikinci bayt değeri 40HEX ile 7EHEX veya 80HEX ile FEHEX arasında olan Çince karakterler).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 modu, Han Xin Kodunda temsil edilen verinin GS1 Genel Spesifikasyonu tarafından tanımlanan GS1 sistemine ait GS1 verisi olduğunu gösterir. Girdi dizesi örneği: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Sayısal mod, ondalık rakam kümesinden (0-9 rakamları, bayt değerleri 30HEX ile 39HEX) veri kodlar. Normalde, 3 veri karakteri 10 bit ile temsil edilir.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Metin modu, ISO/IEC 646'da tanımlanan ortak sembollerden veri kodlar, yani bayt değerleri 00 HEX ile 1B HEX ve 20 HEX ile 7F HEX arasında.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode modu, Han Xin Kodunda UTF8 kodlaması/karakter kümesine referansla herhangi bir metin verisini temsil etmenin bir yolunu tasarlar.

### URI {#URI}
```
public static final HanXinModes URI
```


URI modu, Han Xin Kodunda temsil edilen verinin RFC 3986'ya referans olan Uniform Resource Identifier (URI) olduğunu gösterir.

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
public static HanXinModes fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

