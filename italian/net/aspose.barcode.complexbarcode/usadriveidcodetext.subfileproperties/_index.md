---
title: "Classe USADriveIdCodetext.SubfileProperties"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties. Le proprietà offset e lunghezza del subfile USA DL sono impostate automaticamente"
type: docs
weight: 840
url: /it/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

Le proprietà del subfile USA DL, offset e lunghezza, sono impostate automaticamente.

```csharp
public class SubfileProperties
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. Ogni subfile deve iniziare con il tipo Subfile a due caratteri e questi due caratteri devono essere inclusi nella lunghezza. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | Valore numerico a 4 cifre che specifica il numero di byte dalla testa o dall'inizio del file fino a dove si trovano i dati relativi al particolare sub-file. Il primo byte del file si trova all'offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | Tipo di subfile a 2 byte, ad esempio \"DL\" |

### Vedi anche

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


