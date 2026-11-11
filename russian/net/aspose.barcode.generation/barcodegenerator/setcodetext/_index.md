---
title: "BarcodeGenerator.SetCodeText"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Метод BarcodeGenerator. Устанавливает кодовый текст как последовательность байтов"
type: docs
weight: 100
url: /ru/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Установить кодовый текст как последовательность байтов.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| codeBytes | Byte[] | Байты кодового текста |

### См. также

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает её, функция автоматически вставляет [маркер порядка байтов (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Эта функция предназначена только для использования с 2D‑штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и др.). Она позволяет вручную кодировать Unicode‑текст с использованием национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется кодировка [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) для Unicode‑данных.

Использование этой функции с 1D‑штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| codeText | String | Строка CodeText |
| кодировка | Кодировка | Применённая кодировка |

## Примеры

Этот пример показывает, как использовать `SetCodeText`, задавая Unicode‑закодированный текст для 2D‑штрихкодов с использованием разных кодировок:

```csharp
[C#]
//Кодировать текст QR‑кода с использованием UTF-8 и BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Кодировать текст DataMatrix, используя Shift-JIS (японская кодировка)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### См. также

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Кодирует Unicode **codeText** в последовательность байтов, используя указанную **encoding**. UTF-8 является наиболее часто используемой кодировкой. Если кодировка поддерживает это и **insertBOM** установлен в `true`, функция включает [маркер порядка байтов (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Эта функция предназначена только для использования с 2D‑штрихкодами (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и др.). Она позволяет вручную кодировать Unicode‑текст с использованием национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется кодировка [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) для Unicode‑данных.

Использование этой функции с 1D‑штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или штрихкодами HIBC (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| codeText | String | Строка CodeText |
| кодировка | Кодировка | Применённая кодировка |
| insertBOM | Boolean | Указывает, следует ли вставлять маркер порядка байтов (BOM), когда указанная кодировка его поддерживает (например, UTF-8, UTF-16, UTF-32). Если установлен в `true`, BOM добавляется; если `false`, BOM опускается, даже если кодировка обычно его использует. |

## Примеры

Этот пример показывает, как использовать `SetCodeText` с BOM и без него для 2D‑шрихкодов.

```csharp
[C#]
//Кодировать codetext, используя UTF-8 с BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Кодировать codetext, используя UTF-8 без BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### См. также

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


