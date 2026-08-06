---
title: BarcodeRecognitionSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: BarcodeRecognitionSettings는 BarcodeRecognitionFragment와 바코드 인식 설정을 사용자 정의하고 RecognitionResultsHandler를 추가하기 위한 API를 포함합니다. 이 메서드는 BarcodeScannerFragment에서 인식 프로세스를 시작하기 전에 호출되어야 합니다.
type: docs
weight: 11
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings는 BarcodeRecognitionFragment 및 Barcode 인식 설정을 사용자 정의하기 위한 API를 포함하며, RecognitionResultsHandler를 추가해야 BarcodeScannerFragment에서 인식 프로세스를 시작하기 전에 호출되어야 합니다. //TODO discuss method applyChanges or importSettings
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | 내부 |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | 주요 BarCode 디코딩 매개변수입니다. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | 구현되지 않음 |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | 지정된 xml 스트림에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 인식을 위한 디코드 유형을 설정합니다. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | 인식을 위한 SingleDecodeType 유형 배열을 설정합니다. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | OnRecognitionFinishedListener의 사용자 정의 구현을 설정합니다. 사용자 정의 OnRecognitionFinishedListener는 BarcodeScannerFragment에서 인식 프로세스가 완료된 후 호출됩니다. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings는 인식 품질과 속도를 수동으로 구성하도록 허용합니다. |
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
| Parameter | Type | 설명 |
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


내부

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


주요 BarCode 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다.

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


구현되지 않음

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


지정된 xml 스트림에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | 로드용 xml 스트림 |

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


인식을 위한 디코드 유형을 설정합니다. ReadBarCodes() 메서드 호출 전에 반드시 호출되어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 읽을 바코드 유형입니다. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


인식을 위한 SingleDecodeType 유형 배열을 설정합니다. BarcodeScannerFragment에서 인식 프로세스를 시작하기 전에 반드시 호출되어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 읽을 SingleDecodeType 유형 배열입니다. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


OnRecognitionFinishedListener의 사용자 정의 구현을 설정합니다. 사용자 정의 OnRecognitionFinishedListener는 BarcodeScannerFragment에서 인식 프로세스가 완료된 후 호출됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. HighPerformance, NormalQuality, HighQuality, MaxBarCodes와 같은 내장 프리셋을 사용하여 QualitySettings를 빠르게 설정할 수 있으며, 별도의 옵션을 수동으로 구성할 수도 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | 인식 품질과 속도를 구성합니다. |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

