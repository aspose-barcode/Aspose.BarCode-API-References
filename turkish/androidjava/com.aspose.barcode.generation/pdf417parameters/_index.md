---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "PDF417 parametreleri."
type: docs
weight: 58
url: /tr/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 parametreleri. PDF417, MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. Structured Append modundaki MicroPDF417 (MacroPDF417 moduna eşdeğer) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.

Bu örnekler, GS1MicroPdf417 içinde UCC/EAN-128 bağlı olmayan modların nasıl kodlanacağını gösterir.

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Sütun sayısı. |
| [getECIEncoding()](#getECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getEncodeMode()](#getEncodeMode--) | Pdf417 kodlama modunu tanımlar. |
| [getErrorLevel()](#getErrorLevel--) | BarCode'un hata düzeltme seviyesini (level0'dan level8'e kadar) belirten Pdf417 semboloji tipini alır; level0 hata düzeltme bilgisi yok demektir, level8 en iyi hata düzeltmeyi ifade eder ve bu daha büyük bir görüntü anlamına gelir. |
| [getMacroCharacters()](#getMacroCharacters--) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 barkodunun dosya kimliği (gerekli alan). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 barkod dosya adı (isteğe bağlı alan). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 dosya boyutu (isteğe bağlı alan). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 barkodunun segment kimliği (gerekli alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 barkod segment sayısı (isteğe bağlı alan). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Kodlayıcıya segment'e Makro PDF417 Terminatörü (kod kelimesi 922) ekleyip eklemeyeceğini söylemek için kullanılır. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). |
| [getRows()](#getRows--) | Satır sayısı. |
| [getTruncate()](#getTruncate--) | BarCode'un Pdf417 semboloji tipinin kesilip kesilmediği (alanı azaltmak için). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 taklit modlarını kodlar. İkinci konumdaki FNC1 modları 908 ve 909'da kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir. |
| [isLinked()](#isLinked--) | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, bir EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [isReaderInitialization()](#isReaderInitialization--) | Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 taklit modlarını kodlar. İkinci konumdaki FNC1 modları 908 ve 909'da kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir. |
| [setColumns(int value)](#setColumns-int-) | Sütun sayısı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 kodlama modunu tanımlar. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | BarCode'un hata düzeltme seviyesini (level0'dan level8'e kadar) belirten Pdf417 semboloji tipini ayarlar; level0 hata düzeltme bilgisi yok, level8 en iyi hata düzeltmeyi ifade eder ve bu daha büyük bir görüntü anlamına gelir. |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, bir EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 barkodunun dosya kimliği (gerekli alan). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 barkod dosya adı (isteğe bağlı alan). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 dosya boyutu (isteğe bağlı alan). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 barkodunun segment kimliği (gerekli alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 barkod segment sayısı (isteğe bağlı alan). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Kodlayıcıya segment'e Makro PDF417 Terminatörü (kod kelimesi 922) ekleyip eklemeyeceğini söylemek için kullanılır. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [setRows(int value)](#setRows-int-) | Satır sayısı. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | BarCode'un Pdf417 semboloji tipinin kesilip kesilmediği (alanı azaltmak için). |
| [toString()](#toString--) | Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
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


2D Barkod modülünün Yükseklik/Genişlik oranı.

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


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içinde veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417 kodlama modunu tanımlar. Varsayılan değer: Otomatik.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode'un hata düzeltme seviyesini (level0'dan level8'e kadar) belirten Pdf417 semboloji tipini alır; level0 hata düzeltme bilgisi yok demektir, level8 en iyi hata düzeltmeyi ifade eder ve bu daha büyük bir görüntü anlamına gelir.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None.

Bu örnekler, MicroPdf417 içinde Macro Karakterlerin nasıl kodlanacağını gösterir.

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

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


MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). MicroPDF417 barkod kontrol toplamı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). Kontrol toplamı alanı, CCITT-16 polinomu kullanılarak hesaplanan 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1

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


MacroPdf417 barkodunun dosya kimliği (Zorunlu alan). MicroPDF417 barkodunun dosya kimliği (Yapılandırılmış Ekleme modu için zorunlu alan).

**Returns:**
int
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


MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan). Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 barkodunun segment kimliği (Zorunlu alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar. MicroPDF417 barkodunun segment kimliği (Yapılandırılmış Ekleme modu için zorunlu alan).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 barkod segment sayısı (isteğe bağlı alan). MicroPDF417 barkod segment sayısı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Returns:**
int
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


Kodlayıcıya, segment'e Macro PDF417 Terminator (kod sözcüğü 922) eklenip eklenmeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır.

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


BarCode'un Pdf417 semboloji tipinin kırpılmış (alanı azaltmak için) olup olmadığı. CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durdurma deseni kaldırılır.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 taklit modlarını kodlar. İkinci konumdaki FNC1 modları 908 ve 909'da kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir.

Bu örnekler, FNC1'in ikinci konumda olduğu ve olmadığı Code 128 taklit modlarının nasıl kodlanacağını gösterir. Bu şekilde MicroPdf417, Code 128 barkod olarak çözümlenebilir.

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, bir EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar.

Bu örnekler, GS1MicroPdf417 içinde "Linked" UCC/EAN-128 modlarının ve MicroPdf417 ile Pdf417 barkodlarında Bağlantı Bayrağı (918)'nin nasıl kodlanacağını gösterir.

```

```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

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


2D Barkod modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 taklit modlarını kodlar. İkinci konumdaki FNC1 modları 908 ve 909'da kodlayabilir, ayrıca 910 ve 911'i de kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir.

Bu örnekler, FNC1'in ikinci konumda olduğu ve olmadığı Code 128 taklit modlarının nasıl kodlanacağını gösterir. Bu şekilde MicroPdf417, Code 128 barkod olarak çözümlenebilir.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

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


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içinde veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417 kodlama modunu tanımlar. Varsayılan değer: Otomatik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


BarCode'un hata düzeltme seviyesini (level0'dan level8'e kadar) belirten Pdf417 semboloji tipini ayarlar; level0 hata düzeltme bilgisi yok, level8 en iyi hata düzeltmeyi ifade eder ve bu daha büyük bir görüntü anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | BarCode'un Pdf417 semboloji tipinin hata düzeltme seviyesi level0'dan level8'e kadar değişir; level0 hata düzeltme bilgisi yok, level8 ise en iyi hata düzeltmeyi sağlar ve daha büyük bir görüntü anlamına gelir. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını, bir EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar.

Bu örnekler, GS1MicroPdf417 içinde "Linked" UCC/EAN-128 modlarının ve MicroPdf417 ile Pdf417 barkodlarında Bağlantı Bayrağı (918)'nin nasıl kodlanacağını gösterir.

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None.

Bu örnekler, MicroPdf417 içinde Macro Karakterlerin nasıl kodlanacağını gösterir.

```

```

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


MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). MicroPDF417 barkod kontrol toplamı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). Kontrol toplamı alanı, CCITT-16 polinomu kullanılarak hesaplanan 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1

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


MacroPdf417 barkodunun dosya kimliği (Zorunlu alan). MicroPDF417 barkodunun dosya kimliği (Yapılandırılmış Ekleme modu için zorunlu alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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


MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan). Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 barkodunun segment kimliği (Zorunlu alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar. MicroPDF417 barkodunun segment kimliği (Yapılandırılmış Ekleme modu için zorunlu alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 barkod segment sayısı (isteğe bağlı alan). MicroPDF417 barkod segment sayısı (Yapılandırılmış Ekleme modu için isteğe bağlı alan).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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


Kodlayıcıya, segment'e Macro PDF417 Terminator (kod sözcüğü 922) eklenip eklenmeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır.

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


Okuyucuya sembolde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.

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


BarCode'un Pdf417 semboloji tipinin kırpılmış (alanı azaltmak için) olup olmadığı. CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durdurma deseni kaldırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesinin insan tarafından okunabilir bir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) nesnesini temsil eden bir dize.
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

