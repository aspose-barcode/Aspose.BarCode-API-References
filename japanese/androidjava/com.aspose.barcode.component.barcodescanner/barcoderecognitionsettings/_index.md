---
title: "BarcodeRecognitionSettings"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "BarcodeRecognitionSettings は、BarcodeRecognitionFragment のカスタマイズとバーコード認識設定、RecognitionResultsHandler の追加のための API を含みます。これは BarcodeScannerFragment で認識プロセスを開始する前に呼び出す必要があります。"
type: docs
weight: 11
url: /ja/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings は、BarcodeRecognitionFragment のカスタマイズとバーコード認識設定、RecognitionResultsHandler の追加のための API を含みます。これは BarcodeScannerFragment で認識プロセスを開始する前に呼び出す必要があります。 //TODO applyChanges メソッドまたは importSettings について議論する
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | 内部 |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | 主要なBarCodeデコードパラメータです。 |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | 未実装 |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | 指定された xml-stream から BarCode プロパティをインポートし、現在の BarCodeReader インスタンスに適用します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 認識のためにデコードタイプを設定します。 |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | 認識のために SingleDecodeType 型配列を設定します。 |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | OnRecognitionFinishedListener のカスタム実装を設定します。カスタム OnRecognitionFinishedListener は BarcodeScannerFragment 内の認識プロセス完了後に呼び出されます。 |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings は、認識の品質と速度を手動で構成できるようにします。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeRecognitionSettings> CREATOR
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
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```




**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeReaderSettings() {#getBarcodeReaderSettings--}
```
public InputStream getBarcodeReaderSettings()
```


内部

**Returns:**
java.io.InputStream -
### getBarcodeScannerFragmentSettings() {#getBarcodeScannerFragmentSettings--}
```
public BarcodeScannerFragmentSettings getBarcodeScannerFragmentSettings()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeScannerFragmentSettings
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


メインの BarCode デコードパラメータです。認識されたデータに影響を与えるパラメータを含みます。

**Returns:**
[BarcodeSettings](../../com.aspose.barcode.barcoderecognition/barcodesettings) - The main BarCode decoding parameters
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQualitySettings() {#getQualitySettings--}
```
public QualitySettings getQualitySettings()
```


未実装

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) - quality settings
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettingsFromXml(InputStream barcodeReaderExportedToXml) {#importSettingsFromXml-java.io.InputStream-}
```
public void importSettingsFromXml(InputStream barcodeReaderExportedToXml)
```


指定された xml-stream から BarCode プロパティをインポートし、現在の BarCodeReader インスタンスに適用します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | 読み込み用の xml-stream |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


認識のためにデコードタイプを設定します。ReadBarCodes() メソッドの前に呼び出す必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 読み取るバーコードのタイプです。 |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


認識のために SingleDecodeType 型配列を設定します。BarcodeScannerFragment での認識プロセス開始前に呼び出す必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 読み取る SingleDecodeType 型配列です。 |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


OnRecognitionFinishedListener のカスタム実装を設定します。カスタム OnRecognitionFinishedListener は BarcodeScannerFragment 内の認識プロセス完了後に呼び出されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings は認識の品質と速度を手動で構成できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用してすばやく設定することも、個別のオプションを手動で構成することもできます。QualitySettings のデフォルト値は NormalQuality です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | 認識の品質と速度を構成するために。 |

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

