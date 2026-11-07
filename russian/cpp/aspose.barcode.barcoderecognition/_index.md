---
title: "Пространство имён Aspose::BarCode::BarCodeRecognition"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать пространство имён Aspose::BarCode::BarCodeRecognition в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.barcode.barcoderecognition/
---



## Классы

| Класс | Описание |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Публичный интерфейс для декодирования поля информации о клиенте, используемого в символьной системе AustraliaPost. Реализацию должен предоставить пользователь. |
| [AustraliaPostSettings](./australiapostsettings/) | Параметры декодирования AustraliaPost. Содержит параметры, влияющие на распознанные данные символьной системы AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода Aztec |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Сохраняет расширенные параметры распознанного штрих‑кода |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) инкапсулирует изображение, которое может содержать один или несколько штрих‑кодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрих‑кодов. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Представляет регион распознанного штрих‑кода и угол штрих‑кода |
| [BarCodeResult](./barcoderesult/) | Сохраняет данные распознанного штрих‑кода, такие как тип [SingleDecodeType](./singledecodetype/), текст кода **System::String**, регион [BarCodeRegionParameters](./barcoderegionparameters/) и другие параметры |
| [BarcodeSettings](./barcodesettings/) | Основные параметры декодирования [BarCode](../aspose.barcode/). Содержит параметры, влияющие на распознанные данные. |
| [BaseDecodeType](./basedecodetype/) | Базовый класс для [MultiDecodeType](./multidecodetype/) и [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Базовый класс для хранения расширенных параметров распознанного штрих‑кода |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Сохраняет дополнительную информацию Codabar распознанного штрих‑кода |
| [Code128DataPortion](./code128dataportion/) | Содержит данные подтипа штрих‑кода типа Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода Code128 |
| [DataBarExtendedParameters](./databarextendedparameters/) | Сохраняет дополнительную информацию DataBar распознанного штрих‑кода |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) |
| [DecodeType](./decodetype/) | Укажите тип штрих‑кода для чтения. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Общее исключение, выбрасываемое [BarCodeReader](./barcodereader/), наследуемое от BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Представляет исключение прерывания распознавания, которое выбрасывается при превышении тайм‑аута во время распознавания с помощью [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода DotCode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода **GS1 Composite Bar** |
| [Iso15416Quality](./iso15416quality/) | Сохраняет оценки качества штрихкода, рассчитанные в соответствии со стандартом ISO/IEC 15416 для 1D штрихкодов. |
| [IsoSymbolQuality](./isosymbolquality/) | Сохраняет результаты оценки качества символа штрихкода в соответствии со стандартами ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Представляет 8‑битный кадр изображения в градациях серого. Каждый пиксель представлен одним байтом, содержащим значение его яркости. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Сохраняет дополнительную информацию MaxiCode распознанного штрихкода |
| [MultiDecodeType](./multidecodetype/) | Тип декодирования Composite. |
| [OneDExtendedParameters](./onedextendedparameters/) | Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный кодтекст и контрольная сумма |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Сохраняет метаданные MacroPdf417 распознанного штрихкода |
| [QRExtendedParameters](./qrextendedparameters/) | Сохраняет информацию Structured Append [QR](../aspose.barcode.barcoderecognition.qr/) распознанного штрихкода |
| [Quadrangle](./quadrangle/) | Сохраняет набор из четырёх [Point](../)s, представляющих регион [Quadrangle](./quadrangle/). |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро установить [QualitySettings](./qualitysettings/) с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxQuality, либо вручную настроить отдельные параметры. Значение по умолчанию для [QualitySettings](./qualitysettings/) — NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Тип одиночного декодирования. См. тип декодирования, чтобы получить экземпляр. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Содержит типы подмножества Code128 |
| [BarCodeConfidence](./barcodeconfidence/) | Содержит уровень уверенности распознавания |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
