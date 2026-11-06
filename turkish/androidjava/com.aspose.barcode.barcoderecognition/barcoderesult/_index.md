---
title: "BarCodeResult"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "SingleDecodeType türü, string kod metni, BarCodeRegionParameters bölgesi ve diğer parametreler gibi tanınan barkod verilerini depolar."
type: docs
weight: 17
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

SingleDecodeType türü, string kodmetni, BarCodeRegionParameters bölgesi ve diğer parametreler gibi tanınan barkod verilerini depolar

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | BarCodeResult sınıfının bir kopyasını oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | BarCodeResult sınıfının bir kopyasını oluşturur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen BarCodeResult değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Kodlanmış kod baytlarını alır |
| [getCodeText()](#getCodeText--) | Kod metnini alır |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Kod metnini kodlamayla birlikte alır. |
| [getCodeType()](#getCodeType--) | Barkod tipini alır |
| [getCodeTypeName()](#getCodeTypeName--) | Barkod tipinin adını alır |
| [getConfidence()](#getConfidence--) | Tanımlanan barkodun tanıma güven düzeyini alır |
| [getExtended()](#getExtended--) | Tanımlanan barkodun genişletilmiş parametrelerini alır |
| [getReadingQuality()](#getReadingQuality--) | Okuma kalitesini alır. |
| [getRegion()](#getRegion--) | Barkod bölgesini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu BarCodeResult nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


BarCodeResult sınıfının bir kopyasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | BarCodeResult örneğinin bir kopyası. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


BarCodeResult sınıfının bir kopyasını oluşturur.

**Returns:**
java.lang.Object - BarCodeResult sınıfının bir kopyasını döndürür.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen BarCodeResult değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırmak için bir BarCodeResult değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Kodlanmış kod baytlarını alır

Değer: Barkodun kod baytları

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Kod metnini alır

Değer: Barkodun kod metni

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Kod metnini kodlamayla birlikte alır.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Kod metni için kodlama. |

**Returns:**
java.lang.String - Tanımlanan kod metnini içeren bir dize.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Barkod tipini alır

Değer: Tanımlanan barkodun tip bilgisi

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Barkod tipinin adını alır

Değer: Tanımlanan barkodun tip adı

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Tanımlanan barkodun tanıma güven düzeyini alır

Değer:  BarCodeConfidence.Strong  sahte veya hatalı tanıma içermez,  BarCodeConfidence.Moderate  bazen sahte veya yanlış kod metni içerebilir çünkü bu güven seviyesi zayıf denetim toplamına sahip barkodlar için veya hiç denetim toplamı olmayanlar için geçerlidir,  BarCodeConfidence.None  her zaman yanlış kod metni içerir ve sahte tanımalara neden olabilir

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Tanımlanan barkodun genişletilmiş parametrelerini alır

Değer: Tanınan barkodun genişletilmiş parametreleri

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Okuma kalitesini alır. 1D ve posta barkodları için çalışır.

Değer: Okuma kalitesi yüzdesi

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Barkod bölgesini alır

Değer: Tanınan barkodun bölgesi

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
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


Bu BarCodeResult nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  BarCodeResult  nesnesini temsil eden bir dize.
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

