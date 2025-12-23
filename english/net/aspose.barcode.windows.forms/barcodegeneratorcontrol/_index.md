---
title: Class BarCodeGeneratorControl
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl class. BarCode Windows Control goto your toolbox panel and add Aspose.BarCode.dll and you will see BarcodeGeneratorControl appears. Just drag it and drop to your Windows form. see  see
type: docs
weight: 1680
url: /net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, goto your toolbox panel and add Aspose.BarCode.dll, and you will see BarcodeGeneratorControl appears. Just drag it and drop to your Windows form. see  see

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Gets or sets the mode by which the barcode automatically resizes. Default value is AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Background color of the barcode image. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode image height when [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Gets or sets Barcode paddings parameters [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | BarCode's encode type (symbology). Use [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) to get current symbology. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode image width when [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Bars color. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Height of 1D barcodes' bars. Ignored if [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Gets or sets Border parameters [`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Caption Above the BarCode image. See [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Caption Below the BarCode image. See [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Data to be encoded, different types of BarCode may have different CodeText length restrictions. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Gets or sets CodeText parameters [`CodetextParametersUI`](../codetextparametersui/). |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \\CR stands for CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | BarCode's encode type (symbology). Use [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) to get current symbology. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Gets or sets a value indicating whether bars filled. Only for 1D barcodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Enable checksum during generation 1D barcodes. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Gets or sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Specific parameters |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 symbology if codetext is incorrect. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Gets or sets a value indicating whether is used anti-aliasing mode to render image. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |

### See Also

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


