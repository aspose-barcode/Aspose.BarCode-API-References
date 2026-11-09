---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode for Java API Referansı"
description: "com.aspose.barcode.generation.Pdf417Parameters sınıfı için UI sarmalayıcısı."
type: docs
weight: 16
url: /tr/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

com.aspose.barcode.generation.Pdf417Parameters sınıfı için UI sarmalayıcısı.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Sütun sayısı. |
| [getECIEncoding()](#getECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getEncodeMode()](#getEncodeMode--) | BarCode'un kodlama modunun Pdf417 semboloji türü. |
| [getErrorLevel()](#getErrorLevel--) | BarCode'un hata düzeltme seviyesi için Pdf417 semboloji türünü alır; seviye0'dan seviye8'e kadar değişir, seviye0 hata düzeltme bilgisi yok demektir, seviye8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir. |
| [getMacroCharacters()](#getMacroCharacters--) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Macro Pdf417 barkodunun dosya kimliğini alır. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 barkod dosya adı (isteğe bağlı alan). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 dosya boyutu (isteğe bağlı alan). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Macro Pdf417 barkodunun segment kimliğini alır; 0'dan başlayarak MacroSegmentsCount - 1'e kadar. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Macro Pdf417 barkod segment sayısını alır. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Kodlayıcıya segment'e Makro PDF417 Terminator (kod sözcüğü 922) eklenip eklenmeyeceğini söylemek için kullanılır. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). |
| [getRows()](#getRows--) | Satır sayısı. |
| [getTruncate()](#getTruncate--) | BarCode'un Pdf417 semboloji türünün kırpılmış olup olmadığı (alanı azaltmak için). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bunlar sadece tanımlanan MicroPdf417'in Code 128 olarak yorumlanabileceğini gösterir. |
| [isLinked()](#isLinked--) | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [isReaderInitialization()](#isReaderInitialization--) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bunlar sadece tanımlanan MicroPdf417'in Code 128 olarak yorumlanabileceğini gösterir. |
| [setColumns(int value)](#setColumns-int-) | Sütun sayısı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | BarCode'un kodlama modunun Pdf417 semboloji türü. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | BarCode'un hata düzeltme seviyesi için Pdf417 semboloji türünü ayarlar; seviye0'dan seviye8'e kadar, seviye0 hata düzeltme bilgisi yok, seviye8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir. |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Macro Pdf417 barkodunun dosya kimliğini ayarlar. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 barkod dosya adı (isteğe bağlı alan). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 dosya boyutu (isteğe bağlı alan). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Macro Pdf417 barkodunun segment kimliğini ayarlar; 0'dan başlayarak MacroSegmentsCount - 1'e kadar. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Makro Pdf417 barkod segment sayısını ayarlar. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Kodlayıcıya segment'e Makro PDF417 Terminator (kod sözcüğü 922) eklenip eklenmeyeceğini söylemek için kullanılır. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [setRows(int value)](#setRows-int-) | Satır sayısı. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | BarCode'un Pdf417 semboloji türünün kırpılmış olup olmadığı (alanı azaltmak için). |
| [toString()](#toString--) | Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Sütun sayısı.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içinde veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


BarCode'un kodlama modunun Pdf417 semboloji türü. Varsayılan değer: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode'un hata düzeltme seviyesi için Pdf417 semboloji türünü alır; seviye0'dan seviye8'e kadar değişir, seviye0 hata düzeltme bilgisi yok demektir, seviye8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 barkod alıcı adı (isteğe bağlı alan). MicroPDF417 barkod alıcı adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 barkod sağlama toplamı (isteğe bağlı alan). MicroPDF417 barkod sağlama toplamı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Sağlama toplamı alanı, CCITT-16 polinomu kullanılarak 16-bit (2 bayt) CRC sağlama toplamı değerini içerir. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Macro PDF417 metin alanları için geçerlidir.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Makro Pdf417 barkodunun dosya kimliğini alır. MacroPdf417 için kullanılır.

**Returns:**
int - makro Pdf417 barkodunun dosya kimliği.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 barkod dosya adı (isteğe bağlı alan). MicroPDF417 barkod dosya adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Macro Pdf417 barkodunun segment kimliğini alır; 0'dan başlayarak MacroSegmentsCount - 1'e kadar.

**Returns:**
int - makro Pdf417 barkodunun segment kimliği, 0'dan başlayarak MacroSegmentsCount - 1'e kadar.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Macro Pdf417 barkod segment sayısını alır.

**Returns:**
int - makro Pdf417 barkod segment sayısı.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 barkod gönderici adı (isteğe bağlı alan). MicroPDF417 barkod gönderici adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Kodlayıcıya segment'e Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 barkod zaman damgası (isteğe bağlı alan). MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Satır sayısı.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


BarCode'un Pdf417 semboloji türünün kırpılmış olup olmadığı (alanı azaltmak için).

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bunlar sadece tanımlanan MicroPdf417'in Code 128 olarak yorumlanabileceğini gösterir.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bunlar sadece tanımlanan MicroPdf417'in Code 128 olarak yorumlanabileceğini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Sütun sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içinde veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


BarCode'un kodlama modunun Pdf417 semboloji türü. Varsayılan değer: Pdf417EncodeMode.Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


BarCode'un hata düzeltme seviyesi için Pdf417 semboloji türünü ayarlar; seviye0'dan seviye8'e kadar, seviye0 hata düzeltme bilgisi yok, seviye8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | BarCode'un hata düzeltme seviyesinin Pdf417 semboloji türü, level0'dan level8'e kadar değişir; level0 hata düzeltme bilgisi yok demektir, level8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 barkod alıcı adı (isteğe bağlı alan). MicroPDF417 barkod alıcı adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 barkod sağlama toplamı (isteğe bağlı alan). MicroPDF417 barkod sağlama toplamı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Sağlama toplamı alanı, CCITT-16 polinomu kullanılarak 16-bit (2 bayt) CRC sağlama toplamı değerini içerir. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Macro PDF417 metin alanları için geçerlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Makro Pdf417 barkodunun dosya kimliğini ayarlar. MacroPdf417 için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | makro Pdf417 barkodunun dosya kimliği. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 barkod dosya adı (isteğe bağlı alan). MicroPDF417 barkod dosya adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Macro Pdf417 barkodunun segment kimliğini ayarlar; 0'dan başlayarak MacroSegmentsCount - 1'e kadar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | makro Pdf417 barkodunun segment kimliği, 0'dan başlayarak MacroSegmentsCount - 1'e kadar. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Makro Pdf417 barkod segment sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | makro Pdf417 barkod segment sayısı. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 barkod gönderici adı (isteğe bağlı alan). MicroPDF417 barkod gönderici adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Kodlayıcıya segment'e Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 barkod zaman damgası (isteğe bağlı alan). MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Satır sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


BarCode'un Pdf417 semboloji türünün kırpılmış olup olmadığı (alanı azaltmak için).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesini temsil eden bir dize.
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

