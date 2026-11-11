---
title: "BarcodeGenerator.SetCodeText"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Metodo BarcodeGenerator. Imposta il codetext come sequenza di byte"
type: docs
weight: 100
url: /it/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Imposta il codetext come sequenza di byte.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codeBytes | Byte[] | Byte del codetext |

### Vedi anche

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Codifica il Unicode **codeText** in una sequenza di byte utilizzando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta, la funzione inserisce automaticamente un [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Questa funzione è destinata all'uso solo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale del testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per casi d'uso moderni, si raccomanda la codifica [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codici a barre corrispondenti e può portare a risultati imprevedibili.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codeText | String | Stringa CodeText |
| encoding | Codifica | Codifica applicata |

## Esempi

Questo esempio mostra come utilizzare `SetCodeText` impostando testo codificato in Unicode per i codici a barre 2D usando diverse codifiche:

```csharp
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

### Vedi anche

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Codifica il testo Unicode **codeText** in una sequenza di byte usando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta e **insertBOM** è impostato su `true`, la funzione include un [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Questa funzione è destinata all'uso solo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale del testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per casi d'uso moderni, si raccomanda la codifica [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codici a barre corrispondenti e può portare a risultati imprevedibili.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codeText | String | Stringa CodeText |
| encoding | Codifica | Codifica applicata |
| insertBOM | Boolean | Indica se inserire un byte order mark (BOM) quando la codifica specificata lo supporta (ad es., UTF-8, UTF-16, UTF-32). Se impostato su `true`, il BOM viene aggiunto; se `false`, il BOM viene omesso anche se la codifica normalmente ne utilizza uno. |

## Esempi

Questo esempio mostra come utilizzare `SetCodeText` con o senza un BOM per i codici a barre 2D.

```csharp
[C#]
//Codifica codetext usando UTF-8 con BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codifica codetext usando UTF-8 senza BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Vedi anche

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


