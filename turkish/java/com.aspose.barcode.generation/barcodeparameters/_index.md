---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Barkod oluşturma parametreleri."
type: docs
weight: 14
url: /tr/java/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Barkod oluşturma parametreleri.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost barkod parametreleri. |
| [getAztec()](#getAztec--) | Aztec parametreleri. |
| [getBarColor()](#getBarColor--) | Çubukların rengi. |
| [getBarHeight()](#getBarHeight--) | 1D barkod çubuklarının yüksekliği [Unit](../../com.aspose.barcode.generation/unit) biriminde. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini al. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar parametreleri. |
| [getCodablock()](#getCodablock--) | Codablock parametreleri. |
| [getCode128()](#getCode128--) | Code128 parametreleri. |
| [getCode16K()](#getCode16K--) | Code16K parametreleri. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Kodmetni parametreleri. |
| [getCoupon()](#getCoupon--) | Kupon parametreleri. |
| [getDataBar()](#getDataBar--) | Databar parametreleri. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix parametreleri. |
| [getDotCode()](#getDotCode--) | DotCode parametreleri. |
| [getFilledBars()](#getFilledBars--) | Çubukların doldurulup doldurulmadığını gösteren bir değeri alır. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Bileşik Çubuk parametreleri. |
| [getHanXin()](#getHanXin--) | HanXin parametreleri. |
| [getITF()](#getITF--) | ITF parametreleri. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode parametreleri. |
| [getPadding()](#getPadding--) | Barkod doldurmaları. |
| [getPatchCode()](#getPatchCode--) | PatchCode parametreleri. |
| [getPdf417()](#getPdf417--) | PDF417 parametreleri. |
| [getPostal()](#getPostal--) | Posta parametreleri. |
| [getQR()](#getQR--) | QR, MicroQR ve RectMicroQR parametreleri. |
| [getSupplement()](#getSupplement--) | Ek parametreler. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Yalnızca 1D barkodlar için. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Geniş çubukların dar çubuklara oranı. |
| [getXDimension()](#getXDimension--) | x-boyutu, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | Çubukların rengi. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D barkod çubuklarının yüksekliği [Unit](../../com.aspose.barcode.generation/unit) biriminde. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini ayarlar. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Çubukların doldurulup doldurulmadığını gösteren bir değeri ayarlar. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Bileşik Çubuk parametreleri. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Yalnızca 1D barkodlar için. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Geniş çubukların dar çubuklara oranı. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-boyutu, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. |
| [toString()](#toString--) |  |
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
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost barkod parametreleri.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec parametreleri.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final Color getBarColor()
```


Çubukların rengi. Varsayılan değer: Color.Black.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D barkod çubuklarının yüksekliği [Unit](../../com.aspose.barcode.generation/unit) biriminde. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini al. Varsayılan değer: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


Codabar parametreleri.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock parametreleri.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128 parametreleri.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K parametreleri.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Kodmetni parametreleri.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Kupon parametreleri. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon için kullanılır.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar parametreleri.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix parametreleri.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode parametreleri.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Çubukların doldurulup doldurulmadığını gösteren bir değeri alır. Yalnızca 1D barkodlar için. Varsayılan değer: true.

**Returns:**
boolean - çubukların doldurulup doldurulmadığını gösteren bir değer.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Bileşik Çubuk parametreleri.

Bu örnek, bir GS1 Bileşik Çubuk görüntüsü oluşturmayı ve kaydetmeyi gösterir. 1D kod metni ve 2D kod metninin '|' sembolüyle ayrıldığını unutmayın.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


HanXin parametreleri.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF parametreleri.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode parametreleri.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Barkod doldurmaları. Varsayılan değer: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode parametreleri.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 parametreleri.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Posta parametreleri. Postnet ve Planet için kullanılır.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR, MicroQR ve RectMicroQR parametreleri.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Ek parametreler. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN için kullanılır.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Yalnızca 1D barkodlar için. Kod metni hatalıysa ve değer true olarak ayarlanmışsa - istisna fırlatılır. Aksi takdirde kod metni barkodun spesifikasyonuna uyacak şekilde düzeltilir. İstisna her zaman şu durumlarda fırlatılır: Databar sembolojisi kod metni hatalıysa. İstisna hiçbir zaman şu durumlarda fırlatılmaz: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi kod metni hatalıysa.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Geniş çubukların dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII için kullanılır.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-boyutu, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artırır. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


1D barkodların oluşturulması sırasında kontrol toplamını etkinleştir.

Varsayılan, denetim toplamı içermesi gereken semboloji için Evet olarak, yalnızca denetim toplamının mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Denetim toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Denetim toplamı her zaman kullanılır: Diğer semboloji

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(Color value) {#setBarColor-java.awt.Color-}
```
public final void setBarColor(Color value)
```


Çubukların rengi. Varsayılan değer: Color.Black.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D barkod çubuklarının yüksekliği [Unit](../../com.aspose.barcode.generation/unit) biriminde. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini ayarlar. Varsayılan değer: 0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değeri. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


1D barkodların oluşturulması sırasında kontrol toplamını etkinleştir.

Varsayılan, denetim toplamı içermesi gereken semboloji için Evet olarak, yalnızca denetim toplamının mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Denetim toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Denetim toplamı her zaman kullanılır: Diğer semboloji

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Çubukların doldurulup doldurulmadığını gösteren bir değeri ayarlar. Yalnızca 1D barkodlar için. Varsayılan değer: true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Çubukların doldurulup doldurulmadığını gösteren bir değer. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Bileşik Çubuk parametreleri.

Bu örnek, bir GS1 Bileşik Çubuk görüntüsü oluşturmayı ve kaydetmeyi gösterir. 1D kod metni ve 2D kod metninin '|' sembolüyle ayrıldığını unutmayın.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Yalnızca 1D barkodlar için. Kod metni hatalıysa ve değer true olarak ayarlanmışsa - istisna fırlatılır. Aksi takdirde kod metni barkodun spesifikasyonuna uyacak şekilde düzeltilir. İstisna her zaman şu durumlarda fırlatılır: Databar sembolojisi kod metni hatalıysa. İstisna hiçbir zaman şu durumlarda fırlatılmaz: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi kod metni hatalıysa.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Geniş çubukların dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-boyutu, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artırır. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

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

