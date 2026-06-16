---
title: BarcodeRecognitionResultsHandler
second_title: Справочник API Aspose.BarCode для Android через Java
description: Обработчик для обработки результатов распознавания. Используется на стороне активности распознавания.
type: docs
weight: 28
url: /ru/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandler/
---```
public interface BarcodeRecognitionResultsHandler
```

Handler for processing the recognition results Use on recognition activity side. Implements Parcelable to return the userdata from recognition activity side.
## Methods

| Method | Description |
| --- | --- |
| [processResult(Context context, BarCodeResult[] results, BarcodeSettings settings)](#processResult-android.content.Context-com.aspose.barcode.barcoderecognition.BarCodeResult---com.aspose.barcode.barcoderecognition.BarcodeSettings-) | Process the recognition results. |
### processResult(Context context, BarCodeResult[] results, BarcodeSettings settings) {#processResult-android.content.Context-com.aspose.barcode.barcoderecognition.BarCodeResult---com.aspose.barcode.barcoderecognition.BarcodeSettings-}
```
public abstract boolean processResult(Context context, BarCodeResult[] results, BarcodeSettings settings)
```


Process the recognition results. If repeat flag = false, finishes the recognition process and closes recognition activity and the device camera

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| context | android.content.Context |  |
| results | [BarCodeResult\[\]](../../com.aspose.barcode.barcoderecognition/barcoderesult) | array of the recognized results. null - not recognized |
| settings | [BarcodeSettings](../../com.aspose.barcode.barcoderecognition/barcodesettings) |  |

**Returns:**
boolean - need repeat
