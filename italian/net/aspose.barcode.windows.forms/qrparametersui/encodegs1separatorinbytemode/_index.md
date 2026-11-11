---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Proprietà QrParametersUI. Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR"
type: docs
weight: 30
url: /it/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR.

Se false, i separatori GS1 possono essere codificati come '%' in modalità Alfanumerica secondo la specifica QR.

Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come il carattere 0x1D, e i caratteri '%' sono anch'essi codificati in modalità Byte per preservarli come dati.

Questa opzione può migliorare la compatibilità con i decodificatori che si aspettano separatori di gruppo GS1 a livello di byte e impedisce che i caratteri dati '%' vengano interpretati come separatori GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Vedi anche

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


