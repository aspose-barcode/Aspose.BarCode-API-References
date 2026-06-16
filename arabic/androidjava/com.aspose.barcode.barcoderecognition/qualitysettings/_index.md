---
title: QualitySettings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا.
type: docs
weight: 44
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

تسمح QualitySettings بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxQuality أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لـ QualitySettings هي NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | منشئ QualitySettings |
## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | يسمح للمحرك بالتعرف على الباركودات التي تحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. |
| [getBarcodeQuality()](#getBarcodeQuality--) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | الوضع الذي يتيح أو يعطل التعرف الإضافي على باركودات اللون في الصور الملونة. |
| [getDeconvolution()](#getDeconvolution--) | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. |
| [getHighPerformance()](#getHighPerformance--) | إعداد مسبق لجودة التعرف HighPerformance. |
| [getHighQuality()](#getHighQuality--) | إعداد مسبق لجودة التعرف HighQuality. |
| [getImageScalingMode()](#getImageScalingMode--) | يسمح بتكبير الصورة باستخدام ImageScaleMode المحدد. |
| [getInverseImage()](#getInverseImage--) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة). |
| [getMaxQuality()](#getMaxQuality--) | إعداد مسبق لجودة التعرف MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | إعداد مسبق لجودة التعرف NormalQuality. |
| [getXDimension()](#getXDimension--) | وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) العنصر الأدنى للباركود: خلية المصفوفة أو الشريط. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | يسمح للمحرك بالتعرف على الباركودات التي تحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | الوضع الذي يتيح أو يعطل التعرف الإضافي على باركودات اللون في الصور الملونة. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | يسمح بتكبير الصورة باستخدام ImageScaleMode المحدد القيمة: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) العنصر الأدنى للباركود: خلية المصفوفة أو الشريط. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


منشئ QualitySettings

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


يسمح للمحرك بالتعرف على الباركودات التي تحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح.

القيمة: يسمح للمحرك بالتعرف على الباركودات غير الصحيحة.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

القيمة: الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة.

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


الوضع الذي يتيح أو يعطل التعرف الإضافي على باركودات اللون في الصور الملونة.

القيمة: التعرف الإضافي على باركودات اللون في الصور الملونة.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المطوية) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. نظرًا لعدم قدرتنا على اكتشاف دالة الصورة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل Sharpen أو التشكل الرياضي.

القيمة: وضع فك الالتفاف الذي يحدد مستوى تدهور الصورة.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


إعداد مسبق لجودة التعرف HighPerformance. يتم التعرف على الباركودات عالية الجودة بشكل جيد في هذا الوضع.

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

القيمة: إعداد مسبق لجودة التعرف HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


إعداد جودة التعرف HighQuality. تم تطوير هذا الإعداد للباركودات منخفضة الجودة. يسمح باكتشاف الباركودات المتضررة بشدة.

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

القيمة: إعداد جودة التعرف HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


يسمح بتكبير الصورة باستخدام ImageScaleMode المحدد.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة).

القيمة: التعرف الإضافي على الباركودات في الصور ذات الألوان العكسية

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


إعداد جودة التعرف MaxQuality. تم تطوير هذا الإعداد للتعرف على جميع الباركودات الممكنة، حتى الباركودات غير الصحيحة.

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

القيمة: إعداد جودة التعرف MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

القيمة: الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


إعداد جودة التعرف NormalQuality. مناسب لمعظم الباركودات

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

القيمة: إعداد جودة التعرف NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) العنصر الأدنى للباركود: خلية المصفوفة أو الشريط.

القيمة: حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية المصفوفة أو الشريط.

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


يسمح للمحرك بالتعرف على الباركودات التي تحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح.

القيمة: يسمح للمحرك بالتعرف على الباركودات غير الصحيحة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

القيمة: الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


الوضع الذي يتيح أو يعطل التعرف الإضافي على باركودات اللون في الصور الملونة.

القيمة: التعرف الإضافي على باركودات اللون في الصور الملونة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المطوية) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. نظرًا لعدم قدرتنا على اكتشاف دالة الصورة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل Sharpen أو التشكل الرياضي.

القيمة: وضع فك الالتفاف الذي يحدد مستوى تدهور الصورة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


يسمح بتكبير الصورة باستخدام ImageScaleMode المحدد القيمة:

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.barcoderecognition.ImageScalingMode | قيمة ImageScalingMode |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة).

القيمة: التعرف الإضافي على الباركودات في الصور ذات الألوان العكسية

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

القيمة: الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) العنصر الأدنى للباركود: خلية المصفوفة أو الشريط.

القيمة: حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية المصفوفة أو الشريط.

**Parameters:**
| Parameter | Type | الوصف |
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

