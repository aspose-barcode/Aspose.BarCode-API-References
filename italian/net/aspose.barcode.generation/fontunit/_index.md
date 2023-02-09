---
title: FontUnit
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Definisce un formato particolare per il testo inclusi il tipo di carattere le dimensioni e gli attributi di stile dove dimensione nella proprietà Valore unità.
type: docs
weight: 750
url: /it/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Definisce un formato particolare per il testo, inclusi il tipo di carattere, le dimensioni e gli attributi di stile dove dimensione nella proprietà Valore unità.

```csharp
public sealed class FontUnit
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname) { get; set; } | Ottiene o imposta il nome del volto di questo font. |
| [Size](../../aspose.barcode.generation/fontunit/size) { get; } | Ottiene o imposta la dimensione di questa FontUnit nel valore Unit. |
| [Style](../../aspose.barcode.generation/fontunit/style) { get; set; } | Ottiene o imposta le informazioni sullo stile per questa FontUnit. |

### Esempi

Questo esempio mostra come creare e salvare un'immagine di codice a barre.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Guarda anche

* spazio dei nomi [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->