---
title: "method"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " method. Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 in seconda posizione nei modi 908 e 909, può anche codificare 910 e 911 che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128 in C++."
type: docs
weight: 4400
url: /it/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


Può essere usato solo con MicroPdf417 e codifica le modalità di emulazione Code 128. Può codificare FNC1 nella seconda posizione nelle modalità 908 e 909, e può anche codificare 910 e 911, che indicano semplicemente che il MicroPdf417 riconosciuto può essere interpretato come Code 128.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## Osservazioni


Questi esempi mostrano come codificare le modalità di emulazione Code 128 con FNC1 in seconda posizione e senza. In questo modo MicroPdf417 può essere decodificato come codice a barre Code 128.
```cpp
[C#]
//Codifica MicroPdf417 nella modalità di emulazione Code 128 con FNC1 in seconda posizione e Indicatore di Applicazione "a", modalità 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codifica MicroPdf417 nella modalità di emulazione Code 128 con FNC1 in seconda posizione e Indicatore di Applicazione "99", modalità 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Codifica MicroPdf417 nella modalità di emulazione Code 128, modalità 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## Vedi anche

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
