---
title: MacroCharacter
second_title: Riferimento all'API Aspose.BarCode per .NET
description: I valori dei caratteri 05 e 06 della macro vengono utilizzati per ottenere una codifica più compatta nelle modalità speciali. 05 Il cratere macro viene tradotto in gtu001E05u001D come intestazione dei dati decodificati e u001Eu0004 come trailer dei dati decodificati. 06 Macro craracter è tradotto in gtu001E06u001D come intestazione dati decodificata e u001Eu0004 come trailer dati decodificato.
type: docs
weight: 790
url: /it/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

I valori dei caratteri 05 e 06 della macro vengono utilizzati per ottenere una codifica più compatta nelle modalità speciali. 05 Il cratere macro viene tradotto in "[)&gt;\u001E05\u001D" come intestazione dei dati decodificati e "\u001E\u0004" come trailer dei dati decodificati. 06 Macro craracter è tradotto in "[)&gt;\u001E06\u001D" come intestazione dati decodificata e "\u001E\u0004" come trailer dati decodificato.

```csharp
public enum MacroCharacter
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessuno dei caratteri macro viene aggiunto ai dati del codice a barre |
| Macro05 | `5` | 05 Il craracter macro viene aggiunto ai dati del codice a barre in prima posizione. Identificatore dati GS1 ISO 15434 Il carattere viene convertito in "[)&gt;\u001E05\u001D" come intestazione dati decodificata e "\u001E\u0004" come trailer dati decodificato. |
| Macro06 | `6` | 06 Il craracter macro viene aggiunto ai dati del codice a barre in prima posizione. Identificatore dati ASC MH10 ISO 15434 Il carattere viene convertito in "[)&gt;\u001E06\u001D" come intestazione dati decodificata e "\u001E\u0004" come trailer dati decodificato. |

### Guarda anche

* spazio dei nomi [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->