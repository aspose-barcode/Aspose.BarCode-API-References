---
title: com.aspose.barcode.component.barcodescanner
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: 
type: docs
weight: 13
url: /fr/androidjava/com.aspose.barcode.component.barcodescanner/
---

## Classes

| Classe | Description |
| --- | --- |
| [BarcodeRecognitionContract](../com.aspose.barcode.component.barcodescanner/barcoderecognitioncontract) | Interne BarcodeRecognitionContract nécessaire pour configurer l'appel de BarcodeScannerActivity depuis l'activité cliente |
| [BarcodeRecognitionSettings](../com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings) | BarcodeRecognitionSettings contient l'API permettant de personnaliser BarcodeRecognitionFragment et les paramètres de reconnaissance de code-barres, l'ajout de RecognitionResultsHandler doit être appelé avant le démarrage du processus de reconnaissance dans BarcodeScannerFragment. |
| [BarcodeScanner](../com.aspose.barcode.component.barcodescanner/barcodescanner) | BarcodeScanner contient les fonctionnalités liées à la reconnaissance de codes-barres à partir de la caméra d'un appareil Android. |
| [BarcodeScannerActivity](../com.aspose.barcode.component.barcodescanner/barcodescanneractivity) | Activité qui contient BarcodeScannerFragment. C'est une classe interne et le client ne doit pas appeler cette classe, mais le client doit enregistrer BarcodeScannerActivity dans AndroidManifest.xml |
| [BarcodeScannerFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerfragment) | Fragment pour la reconnaissance des codes-barres. |
| [BarcodeScannerFragmentSettings](../com.aspose.barcode.component.barcodescanner/barcodescannerfragmentsettings) | Paramètres pour BarcodeScannerFragmentSettings |
| [BarcodeScannerPreferences](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferences) | Les préférences de BarcodeScanner. |
| [BarcodeScannerPreferencesFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferencesfragment) | PreferencesFragment peut être utilisé pour personnaliser le processus de reconnaissance de codes-barres à l'aide d'une interface graphique personnalisée. |
| [BarcodeScannerView](../com.aspose.barcode.component.barcodescanner/barcodescannerview) |  |
| [CameraProcessingFragment](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragment) | Interne |
| [CameraProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings) | Paramètres pour CameraProcessingFragment |
| [RecognitionAreaSettings](../com.aspose.barcode.component.barcodescanner/recognitionareasettings) |  |
| [RecognitionAreaView](../com.aspose.barcode.component.barcodescanner/recognitionareaview) |  |
| [RecognitionProcessFragmentBitmapBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentbitmapbackground) | Représente l'arrière-plan de l'image qui sera rendu pendant le processus de reconnaissance. |
| [RecognitionProcessFragmentCameraPhotoBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcameraphotobackground) | Représente l'arrière-plan de l'image obtenu de la caméra qui sera rendu pendant le processus de reconnaissance. |
| [RecognitionProcessFragmentColorBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcolorbackground) | Représente le fond d'une seule couleur qui sera rendu pendant le processus de reconnaissance |
| [RecognitionProcessingFragment](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragment) | Interne contient l'interface graphique qui est rendue pendant le processus de reconnaissance |
| [RecognitionProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings) |  |

## Interfaces

| Interface | Description |
| --- | --- |
| [BarcodeRecognitionResultsHandler](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandler) | Gestionnaire pour le traitement des résultats de reconnaissance. Utilisé du côté de l'activité de reconnaissance. |
| [BarcodeRecognitionResultsHandlerParcelable](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandlerparcelable) | Implémentation de OnScannerRecognitionFinishedListener qui implémente l'interface Parcelable. |
| [OnBarcodeScannerCompletedCallback](../com.aspose.barcode.component.barcodescanner/onbarcodescannercompletedcallback) | Définition d'interface pour un rappel qui sera invoqué lorsqu'un processus de numérisation est terminé. |
| [OnRecognitionPreferencesChangedListener](../com.aspose.barcode.component.barcodescanner/onrecognitionpreferenceschangedlistener) |  |

## Énumérations

| Énum | Description |
| --- | --- |
| [CameraMode](../com.aspose.barcode.component.barcodescanner/cameramode) | Contient les modes d'obtention d'images depuis la caméra |
