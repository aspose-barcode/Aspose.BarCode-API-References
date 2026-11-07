---
title: "method"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta il codetext come sequenza di byte in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Imposta il testo del codice come sequenza di byte.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Byte del codetext |

## Vedi anche

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeText | System::String | Stringa CodeText |
| codifica | System::SharedPtr\<System::Text::Encoding\> | Codifica applicata |
## Osservazioni


Codifica il **codeText** Unicode in una sequenza di byte utilizzando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta, la funzione inserisce automaticamente un [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Questa funzione è destinata all'uso solo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale di testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per i casi d'uso moderni, si raccomanda la codifica [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codice a barre corrispondenti e può portare a risultati imprevedibili.


Questo esempio mostra come utilizzare **SetCodeText** impostando testo codificato in Unicode per i codici a barre 2D usando diverse codifiche:


```cpp
[C#]
//Codifica il testo QR Code usando UTF-8 con BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codifica il testo DataMatrix usando Shift-JIS (codifica giapponese)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Vedi anche

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeText | System::String | Stringa CodeText |
| codifica | System::SharedPtr\<System::Text::Encoding\> | Codifica applicata |
| insertBOM | bool | Indica se inserire un byte order mark (BOM) quando la codifica specificata lo supporta (ad es., UTF-8, UTF-16, UTF-32). Se impostato su **true**, il BOM viene aggiunto; se **false**, il BOM viene omesso anche se la codifica normalmente lo utilizza. |
## Osservazioni


Codifica il **codeText** Unicode in una sequenza di byte utilizzando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta e **insertBOM** è impostato su **true**, la funzione include un [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Questa funzione è destinata all'uso solo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale di testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per i casi d'uso moderni, si raccomanda la codifica [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codice a barre corrispondenti e può portare a risultati imprevedibili.


Questo esempio mostra come utilizzare **SetCodeText** con o senza un BOM per i codici a barre 2D.


```cpp
[C#]
    //Codifica il testo del codice usando UTF-8 con BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codifica il testo del codice usando UTF-8 senza BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Vedi anche

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
