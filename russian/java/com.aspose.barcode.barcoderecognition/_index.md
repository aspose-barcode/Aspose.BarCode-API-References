---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode for Java API Reference"
description: "Этот пакет содержит инструменты для распознавания 1D/2D штрих-кодов."
type: docs
weight: 12
url: /ru/java/com.aspose.barcode.barcoderecognition/
---

Этот пакет содержит инструменты для распознавания 1D/2D штрих-кодов.


## Классы

| Класс | Описание |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Параметры декодирования AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Сохраняет специальные данные распознанного Aztec штрих-кода |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Сохраняет расширенные параметры распознанного штрих-кода |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрих-кодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрих-кодов. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Общее исключение, выбрасываемое BarCodeReader, наследуемое от BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Представляет регион распознанного штрих-кода и угол штрих-кода |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Сохраняет данные распознанного штрих-кода, такие как тип SingleDecodeType, строка codetext, параметры региона BarCodeRegionParameters и другие параметры |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Основные параметры декодирования BarCode. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Настройки детектора штрих-кодов. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Базовый класс для MultiDecodeType и SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Базовый класс для хранения расширенных параметров распознанного штрих-кода |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Сохраняет дополнительную информацию Codabar распознанного штрихкода |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Содержит данные подтипа для штрихкода типа Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Сохраняет специальные данные распознанного штрихкода Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Сохраняет дополнительную информацию DataBar распознанного штрихкода BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Сохраняет специальные данные распознанного штрихкода DataMatrix |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Укажите тип штрихкода для чтения. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Сохраняет специальные данные распознанного штрихкода DotCode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Сохраняет специальные данные распознанного штрихкода **GS1 Composite Bar** |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Сохраняет дополнительную информацию MaxiCode распознанного штрихкода |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Составной тип декодирования. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный codetext и контрольная сумма |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Сохраняет метаданные MacroPdf417 распознанного штрихкода |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings позволяют распознавать штрихкоды с многопоточным повышением производительности |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Сохраняет информацию QR Structured Append распознанного штрихкода |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Сохраняет набор из четырёх точек Point, представляющих регион Quadrangle |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings позволяют вручную настраивать качество и скорость распознавания. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Представляет исключение прерывания распознавания, которое выбрасывается при превышении времени ожидания во время распознавания с BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Одиночный тип декодирования. |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Публичный интерфейс для декодирования поля Customer Information Field, используемого в символьной системе AustraliaPost. |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Содержит уровень уверенности распознавания |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Содержит типы подмножества Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Определяет тип интерпретации (C_TABLE или N_TABLE) клиентской информации для штрих‑кода AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
