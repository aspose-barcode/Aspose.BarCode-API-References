---
title: "QualitySettings"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "QualitySettings は、認識の品質と速度を手動で構成できるようにします。"
type: docs
weight: 42
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings は、認識品質と速度を手動で構成できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxQuality）で迅速に設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings コンストラクター |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | エンジンがチェックサムまたは不正な値を持つバーコードを認識できるようにします。 |
| [getBarcodeQuality()](#getBarcodeQuality--) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。 |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。 |
| [getDeconvolution()](#getDeconvolution--) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モード。 |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 認識品質プリセット。 |
| [getHighQuality()](#getHighQuality--) | HighQuality 認識品質プリセット。 |
| [getImageScalingMode()](#getImageScalingMode--) | 特定の ImageScaleMode を使用して画像のスケーリングを許可します |
| [getInverseImage()](#getInverseImage--) | 反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。 |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 認識品質プリセット。 |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。 |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 認識品質プリセット。 |
| [getXDimension()](#getXDimension--) | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | エンジンがチェックサムまたは不正な値を持つバーコードを認識できるようにします。 |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。 |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。 |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モード。 |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | 特定の ImageScaleMode の値で画像のスケーリングを許可します： |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。 |
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


QualitySettings コンストラクター

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


チェックサムまたは値が不正なバーコードをエンジンが認識できるようにします。このモードは、テキストが不正な損傷バーコードの認識にも使用できます。

値: エンジンが不正なバーコードを認識できるようにします。

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低い要素は、より高度なメソッドが必要となり、認識速度が低下します。

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


カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。

値: カラー画像上のカラーバーコードの追加認識。

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


デコンボリューション（画像復元）モードは、画像劣化のレベルを定義します。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

値: 画像劣化のレベルを定義するデコンボリューションモード。

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 認識品質プリセット。このモードでは高品質のバーコードが適切に認識されます。

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


HighQuality 認識品質プリセット。このプリセットは低品質のバーコード向けに開発され、極度に損傷したバーコードの検出を可能にします。

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


特定の ImageScaleMode を使用して画像のスケーリングを許可します

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。

値: 反転色の画像上でのバーコードの追加認識

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 認識品質プリセット。このプリセットは、正しくないバーコードを含むすべての可能なバーコードを認識できるように開発されています。

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

値: UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています

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

値: バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）。

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


チェックサムまたは値が不正なバーコードをエンジンが認識できるようにします。このモードは、テキストが不正な損傷バーコードの認識にも使用できます。

値: エンジンが不正なバーコードを認識できるようにします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低い要素は、より高度なメソッドが必要となり、認識速度が低下します。

値: 選択された品質でバーコード要素を認識するメソッドを有効にするモード。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。

値: カラー画像上のカラーバーコードの追加認識。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


デコンボリューション（画像復元）モードは、画像劣化のレベルを定義します。デコンボリューションはもともと、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

値: 画像劣化のレベルを定義するデコンボリューションモード。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


特定の ImageScaleMode の値で画像のスケーリングを許可します：

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode の値 |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。

値: 反転色の画像上でのバーコードの追加認識

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。

値: UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大）を設定する認識モード。

値: バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）。

**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

