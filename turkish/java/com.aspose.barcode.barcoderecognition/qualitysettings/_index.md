---
title: "QualitySettings"
second_title: "Aspose.BarCode for Java API Referansı"
description: "QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir."
type: docs
weight: 40
url: /tr/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i gömülü ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxQuality veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [getDeconvolution()](#getDeconvolution--) | Görüntü bozulma seviyesini tanımlayan dekonvolüsyon (görüntü restorasyonu) modu. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance tanıma kalite ön ayarı. |
| [getHighQuality()](#getHighQuality--) | HighQuality tanıma kalite ön ayarı. |
| [getInverseImage()](#getInverseImage--) | Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality tanıma kalite ön ayarı. |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality tanıma kalite ön ayarı. |
| [getXDimension()](#getXDimension--) | Barkodun minimum öğesi (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Görüntü bozulma seviyesini tanımlayan dekonvolüsyon (görüntü restorasyonu) modu. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Barkodun minimum öğesi (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu. |
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
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir.

Değer: Motorun hatalı barkodları tanımasına izin verir.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir.

Değer: Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Değer: Renkli görüntülerde renkli barkodların ek tanımı.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Dekonvolüsyon (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyon) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir.

Value: Görüntü bozulma seviyesini tanımlayan dekonvolüsyon modu.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: HighPerformance tanıma kalite ön ayarı.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality tanıma kalite ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Aşırı hasarlı barkodların tespit edilmesini sağlar.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: HighQuality tanıma kalite ön ayarı.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Value: Ters renkli görüntülerde barkodların ek tanıması

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality tanıma kalite ön ayarı. Bu ön ayar tüm olası barkodları, hatta hatalı barkodları bile tanımak için geliştirilmiştir.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: MaxQuality tanıma kalite ön ayarı.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu.

Value: UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality tanıma kalite ön ayarı. Çoğu barkod için uygundur

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Value: NormalQuality tanıma kalite ön ayarı.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Barkodun minimum öğesi (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu.

Value: barkodun minimum öğesinin (matris hücresi veya çubuk) boyutu (1'den sonsuza).

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir.

Değer: Motorun hatalı barkodları tanımasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir.

Değer: Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Değer: Renkli görüntülerde renkli barkodların ek tanımı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Dekonvolüsyon (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyon) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir.

Value: Görüntü bozulma seviyesini tanımlayan dekonvolüsyon modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod.

Value: Ters renkli görüntülerde barkodların ek tanıması

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu.

Value: UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Barkodun minimum öğesi (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu.

Value: barkodun minimum öğesinin (matris hücresi veya çubuk) boyutu (1'den sonsuza).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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

