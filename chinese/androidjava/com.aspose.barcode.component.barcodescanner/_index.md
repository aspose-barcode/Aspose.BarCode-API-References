---
title: com.aspose.barcode.component.barcodescanner
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 
type: docs
weight: 13
url: /zh/androidjava/com.aspose.barcode.component.barcodescanner/
---

## 类

| 类 | 描述 |
| --- | --- |
| [BarcodeRecognitionContract](../com.aspose.barcode.component.barcodescanner/barcoderecognitioncontract) | 内部 BarcodeRecognitionContract 需要用于从客户端活动调用 BarcodeScannerActivity |
| [BarcodeRecognitionSettings](../com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings) | BarcodeRecognitionSettings 包含用于自定义 BarcodeRecognitionFragment 和条码识别设置的 API，添加 RecognitionResultsHandler 必须在启动 BarcodeScannerFragment 中的识别过程之前调用。 |
| [BarcodeScanner](../com.aspose.barcode.component.barcodescanner/barcodescanner) | BarcodeScanner 包含与 Android 设备摄像头条码识别相关的功能。 |
| [BarcodeScannerActivity](../com.aspose.barcode.component.barcodescanner/barcodescanneractivity) | 包含 BarcodeScannerFragment 的 Activity。它是内部类，客户端不应调用此类，但客户端应在 AndroidManifest.xml 中注册 BarcodeScannerActivity。 |
| [BarcodeScannerFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerfragment) | 用于条码识别的 Fragment。 |
| [BarcodeScannerFragmentSettings](../com.aspose.barcode.component.barcodescanner/barcodescannerfragmentsettings) | BarcodeScannerFragmentSettings 的设置 |
| [BarcodeScannerPreferences](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferences) | BarcodeScanner 的首选项。 |
| [BarcodeScannerPreferencesFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferencesfragment) | PreferencesFragment 可用于使用自定义 GUI 定制条码识别过程。 |
| [BarcodeScannerView](../com.aspose.barcode.component.barcodescanner/barcodescannerview) |  |
| [CameraProcessingFragment](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragment) | 内部 |
| [CameraProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings) | CameraProcessingFragment 的设置 |
| [RecognitionAreaSettings](../com.aspose.barcode.component.barcodescanner/recognitionareasettings) |  |
| [RecognitionAreaView](../com.aspose.barcode.component.barcodescanner/recognitionareaview) |  |
| [RecognitionProcessFragmentBitmapBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentbitmapbackground) | 表示将在识别过程中渲染的图像背景 |
| [RecognitionProcessFragmentCameraPhotoBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcameraphotobackground) | 表示从摄像头获取的图像背景，将在识别过程中渲染 |
| [RecognitionProcessFragmentColorBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcolorbackground) | 表示在识别过程中将渲染的单色背景 |
| [RecognitionProcessingFragment](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragment) | 内部包含在识别过程中渲染的 GUI |
| [RecognitionProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings) |  |

## 接口

| 接口 | 描述 |
| --- | --- |
| [BarcodeRecognitionResultsHandler](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandler) | 用于处理识别结果的处理器，在识别活动端使用。 |
| [BarcodeRecognitionResultsHandlerParcelable](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandlerparcelable) | OnScannerRecognitionFinishedListener 的实现，且实现了 Parcelable 接口。 |
| [OnBarcodeScannerCompletedCallback](../com.aspose.barcode.component.barcodescanner/onbarcodescannercompletedcallback) | 当扫描过程完成时调用的回调的接口定义。 |
| [OnRecognitionPreferencesChangedListener](../com.aspose.barcode.component.barcodescanner/onrecognitionpreferenceschangedlistener) |  |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CameraMode](../com.aspose.barcode.component.barcodescanner/cameramode) | 包含从相机获取图像的模式 |
