---
title: "method"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает кодовый текст как последовательность байтов в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Установить codetext как последовательность байтов.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Байты кодового текста |

## См. также

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| codeText | System::String | Строка CodeText |
| кодировка | System::SharedPtr\<System::Text::Encoding\> | Применяемая кодировка |
## Примечания


Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает это, функция автоматически вставляет [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Эта функция предназначена только для использования с 2D штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и др.). Она позволяет вручную кодировать Unicode‑текст с помощью национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется использовать кодировку [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) для Unicode‑данных.

Использование этой функции с 1D штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.


В этом примере показано, как использовать **SetCodeText**, задавая Unicode‑закодированный текст для 2D штрихкодов с использованием различных кодировок:


```cpp
[C#]
//Кодировать текст QR‑кода с использованием UTF-8 с BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Кодировать текст DataMatrix с использованием Shift-JIS (японская кодировка)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## См. также

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| codeText | System::String | Строка CodeText |
| кодировка | System::SharedPtr\<System::Text::Encoding\> | Применяемая кодировка |
| insertBOM | bool | Указывает, следует ли вставлять маркер порядка байтов (BOM), когда указанная кодировка его поддерживает (например, UTF-8, UTF-16, UTF-32). Если установлено значение **true**, BOM добавляется; если **false**, BOM опускается, даже если кодировка обычно его использует. |
## Примечания


Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает это и **insertBOM** установлено в **true**, функция включает [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Эта функция предназначена только для использования с 2D штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и др.). Она позволяет вручную кодировать Unicode‑текст с помощью национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется использовать кодировку [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) для Unicode‑данных.

Использование этой функции с 1D штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.


В этом примере показано, как использовать **SetCodeText** с BOM или без него для 2D штрихкодов.


```cpp
[C#]
    //Кодировать текст кода с использованием UTF-8 с BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Кодировать текст кода с использованием UTF-8 без BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## См. также

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
