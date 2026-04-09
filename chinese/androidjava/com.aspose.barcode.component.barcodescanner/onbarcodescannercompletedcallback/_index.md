---
title: OnBarcodeScannerCompletedCallback
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 当扫描过程完成时调用的回调的接口定义。
type: docs
weight: 30
url: /zh/androidjava/com.aspose.barcode.component.barcodescanner/onbarcodescannercompletedcallback/
---```
public interface OnBarcodeScannerCompletedCallback
```

Interface definition for a callback to be invoked when a scan process is finished.
## Methods

| Method | Description |
| --- | --- |
| [onScanFinished(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResult)](#onScanFinished-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-) |  |
### onScanFinished(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResult) {#onScanFinished-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-}
```
public abstract void onScanFinished(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResult)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeRecognitionResult | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable | Custom class extended from RecognitionResultsHandler. Contains a data that will returned from recognition activity after finishing the recognition of scanned image. These data will be obtained and processed according the implementation of BarcodeRecognitionResultHandlerParcelable interface. |

