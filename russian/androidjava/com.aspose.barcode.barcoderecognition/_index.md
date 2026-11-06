---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Этот пакет содержит инструменты для распознавания 1D/2D штрих-кодов."
type: docs
weight: 11
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/
---

Этот пакет содержит инструменты для распознавания 1D/2D штрих-кодов.


## Классы

| Класс | Описание |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Параметры декодирования AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Сохраняет специальные данные распознанного штрихкода Aztec |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Сохраняет расширенные параметры распознанного штрихкода |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрихкодов. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Общее исключение, выбрасываемое BarCodeReader, наследуемое от BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Представляет регион распознанного штрихкода и угол штрихкода |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Сохраняет данные распознанного штрихкода, такие как тип SingleDecodeType, строка codetext, BarCodeRegionParameters region и другие параметры |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Основные параметры декодирования BarCode. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Настройки детектора штрихкода. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Базовый класс для MultiDecodeType и SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Базовый класс для хранения расширенных параметров распознанного штрихкода |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Сохраняет дополнительную информацию Codabar распознанного штрихкода |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Содержит данные подтипа для штрихкода типа Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Сохраняет специальные данные распознанного штрихкода Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Сохраняет дополнительную информацию DataBar распознанного штрихкода BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Сохраняет специальные данные распознанного штрихкода DataMatrix |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Укажите тип штрихкода для чтения. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Сохраняет специальные данные распознанного штрихкода DotCode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Сохраняет специальные данные распознанного штрихкода  **GS1 Composite Bar** |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Сохраняет дополнительную информацию MaxiCode распознанного штрихкода |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Тип декодирования Composite. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Сохраняет специальные данные распознанного 1D штрихкода, такие как отдельный код текста и контрольная сумма |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Сохраняет метаданные MacroPdf417 распознанного штрихкода |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings позволяют распознавать штрихкоды с многопоточным повышением производительности |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Сохраняет информацию о QR Structured Append распознанного штрихкода |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Сохраняет набор из четырёх  Point  s, представляющих регион  Quadrangle. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings позволяют вручную настраивать качество и скорость распознавания. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Представляет исключение прерывания распознавания, которое выбрасывается при превышении таймаута во время распознавания с BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Тип декодирования Single. |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Публичный интерфейс для декодирования поля Customer Information Field, используемый в символьной системе AustraliaPost. |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Содержит уровень уверенности распознавания |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Содержит типы подмножества Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Определяет тип интерпретации (C\_TABLE или N\_TABLE) клиентской информации для AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Укажите размер масштабированного изображения |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
