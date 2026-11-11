---
title: "Enum GS1ValidationErrorCode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Identifica un errore di convalida di una stringa elemento GS1, URI Digital Link o valore"
type: docs
weight: 430
url: /it/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Identifica un errore di convalida di una stringa elemento GS1, URI Digital Link o valore.

```csharp
public enum GS1ValidationErrorCode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| EmptyElementString | `0` | La stringa elemento GS1 fornita è vuota. |
| MissingOpeningParenthesis | `1` | Manca una parentesi di apertura che dovrebbe iniziare un Identificatore di Applicazione. |
| MissingClosingParenthesis | `2` | Un Identificatore di Applicazione non ha la parentesi di chiusura. |
| InvalidApplicationIdentifier | `3` | Un Identificatore di Applicazione non contiene da due a quattro cifre ASCII. |
| UnknownApplicationIdentifier | `4` | L'Identificatore di Applicazione fornito non è definito dal Dizionario di Sintassi GS1 supportato. |
| MissingValue | `5` | È presente un Identificatore di Applicazione senza valore. |
| InvalidEscapeSequence | `6` | Un valore contiene una sequenza di escape non supportata. È supportato solo \( . |
| ValueTooShort | `7` | Un valore è più corto della lunghezza minima definita per il suo Identificatore di Applicazione. |
| ValueTooLong | `8` | Un valore è più lungo della lunghezza massima definita per il suo Identificatore di Applicazione. |
| InvalidCharacter | `9` | Un valore contiene un carattere al di fuori del set di caratteri consentito per il suo componente. |
| InvalidChecksum | `10` | Un checksum numerico o alfabetico non è valido. |
| InvalidDate | `11` | Un componente data non è una data significativa secondo le regole definite per il suo Identificatore di Applicazione. |
| InvalidTime | `12` | Un componente ora è al di fuori dell'intervallo consentito o ha una struttura non valida. |
| InvalidCodeListValue | `13` | Il valore di un componente non è presente nella sua lista di codici chiusi consentita. |
| InvalidComponentLength | `14` | Un componente non soddisfa la sua struttura di lunghezza specifica per il componente. |
| TruncatedComponent | `15` | Un componente a lunghezza fissa termina prima che tutti i caratteri richiesti siano presenti. |
| UnexpectedData | `16` | Restano dati dopo che tutti i componenti definiti per l'Identificatore di Applicazione sono stati consumati. |
| InvalidValue | `17` | Un componente viola una regola di contenuto che non ha un codice di errore di convalida più specifico. |
| GcpPrefixTooShort | `18` | Un componente è troppo corto per contenere il prefisso aziendale strutturale GS1 minimo a quattro cifre. |
| InvalidGcpPrefix | `19` | Il prefisso aziendale strutturale GS1 contiene un carattere diverso da una cifra ASCII. |
| InvalidDigitalLinkUri | `20` | Il valore fornito non è un URI GS1 Digital Link assoluto ben formato. |
| UnsupportedDigitalLinkScheme | `21` | Un URI GS1 Digital Link utilizza uno schema diverso da HTTP o HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | Il percorso di un URI GS1 Digital Link non contiene una chiave primaria supportata. |
| InvalidDigitalLinkPath | `23` | Il percorso di un URI GS1 Digital Link non è composto da coppie valide di AI e valore. |
| InvalidDigitalLinkQualifier | `24` | Un Identificatore di Applicazione nel percorso non è un qualificatore consentito in quella posizione. |
| InvalidDigitalLinkQueryParameter | `25` | Un parametro di query GS1 Digital Link è malformato. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Un Identificatore di Applicazione non è consentito come attributo dati GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Un componente URI GS1 Digital Link contiene una codifica percentuale malformata. |
| MultipleDigitalLinkPrimaryKeys | `28` | Più di un elemento potrebbe essere selezionato come chiave primaria GS1 Digital Link. |
| UnsupportedElementCombination | `29` | La combinazione fornita di elementi GS1 non è supportata dalla simbologia o dalla modalità di codifica selezionata. |

### Vedi anche

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


