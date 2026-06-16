---
title: QualitySettings
second_title: Aspose.BarCode for Android via Java API Reference
description: QualitySettings allows to configure recognition quality and speed manually.
type: docs
weight: 44
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings は認識品質と速度を手動で構成できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxQuality）で QualitySettings をすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

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

| Constructor | Description |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings コンストラクタ |
## フィールド

| フィールド | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | エンジンがチェックサムが正しくない、または値が正しくないバーコードを認識できるようにします。 |
| [getBarcodeQuality()](#getBarcodeQuality--) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。 |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | カラー画像上のカラー バーコードの追加認識を有効または無効にするモード。 |
| [getDeconvolution()](#getDeconvolution--) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モード。 |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 認識品質プリセット。 |
| [getHighQuality()](#getHighQuality--) | HighQuality 認識品質プリセット。 |
| [getImageScalingMode()](#getImageScalingMode--) | 特定の ImageScaleMode を使用して画像のスケールを変更できるようにします |
| [getInverseImage()](#getInverseImage--) | 色が反転した画像（輝度）上のバーコードの追加認識を有効または無効にするモード。 |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 認識品質プリセット。 |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。 |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 認識品質プリセット。 |
| [getXDimension()](#getXDimension--) | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | エンジンがチェックサムが正しくない、または値が正しくないバーコードを認識できるようにします。 |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。 |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | カラー画像上のカラー バーコードの追加認識を有効または無効にするモード。 |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モード。 |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | 特定の ImageScaleMode の値で画像をスケールできるようにします: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 色が反転した画像（輝度）上のバーコードの追加認識を有効または無効にするモード。 |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。 |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings コンストラクタ

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


エンジンがチェックサムが正しくない、または値が正しくないバーコードを認識できるようにします。このモードはテキストが正しくない損傷したバーコードの認識に使用できます。

値: エンジンが不正確なバーコードを認識できるようにします。

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素は、より高度なメソッドを必要とし、認識が遅くなります。

値: 選択された品質でバーコード要素を認識するメソッドを有効にするモード。

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


カラー画像上のカラー バーコードの追加認識を有効または無効にするモード。

値: カラー画像上のカラー バーコードの追加認識。

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


画像劣化のレベルを定義するデコンボリューション（画像復元）モード。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

値: 画像劣化のレベルを定義するデコンボリューションモード。

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 認識品質プリセット。このモードでは高品質のバーコードがうまく認識されます。

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

値: HighPerformance 認識品質プリセット。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality 認識品質プリセット。このプリセットは低品質のバーコード用に開発されました。高度に損傷したバーコードの検出を可能にします。

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

値: HighQuality 認識品質プリセット。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


特定の ImageScaleMode を使用して画像のスケールを変更できるようにします

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


色が反転した画像（輝度）上のバーコードの追加認識を有効または無効にするモード。

値: 逆色画像上のバーコードの追加認識

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 認識品質プリセット。このプリセットは、誤ったバーコードも含め、可能なすべてのバーコードを認識できるように開発されました。

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

値: MaxQuality 認識品質プリセット。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。

値: UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル単位）。

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。

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

値: NormalQuality 認識品質プリセット。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。

値: バーコード最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）。

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


エンジンがチェックサムが正しくない、または値が正しくないバーコードを認識できるようにします。このモードはテキストが正しくない損傷したバーコードの認識に使用できます。

値: エンジンが不正確なバーコードを認識できるようにします。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素は、より高度なメソッドを必要とし、認識が遅くなります。

値: 選択された品質でバーコード要素を認識するメソッドを有効にするモード。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


カラー画像上のカラー バーコードの追加認識を有効または無効にするモード。

値: カラー画像上のカラー バーコードの追加認識。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


画像劣化のレベルを定義するデコンボリューション（画像復元）モード。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

値: 画像劣化のレベルを定義するデコンボリューションモード。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


特定の ImageScaleMode の値で画像をスケールできるようにします:

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode 値 |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


色が反転した画像（輝度）上のバーコードの追加認識を有効または無効にするモード。

値: 逆色画像上のバーコードの追加認識

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。

値: UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル単位）。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。

値: バーコード最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）。

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

