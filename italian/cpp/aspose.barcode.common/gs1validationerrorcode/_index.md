---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Identifica un errore di convalida di una stringa elemento GS1, URI Digital Link o valore in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Identifica un errore di convalida di una stringa di elemento GS1, URI Digital Link o valore.

```cpp
enum class GS1ValidationErrorCode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| EmptyElementString | 0 | La stringa elemento GS1 fornita è vuota. |
| MissingOpeningParenthesis | 1 | Manca una parentesi di apertura che dovrebbe avviare un Identificatore di Applicazione. |
| MissingClosingParenthesis | 2 | Un Identificatore di Applicazione non ha una parentesi di chiusura. |
| InvalidApplicationIdentifier | 3 | Un Identificatore di Applicazione non contiene da due a quattro cifre ASCII. |
| UnknownApplicationIdentifier | 4 | L'Identificatore di Applicazione fornito non è definito dal Dizionario di Sintassi GS1 supportato. |
| MissingValue | 5 | È presente un Identificatore di Applicazione senza valore. |
| InvalidEscapeSequence | 6 | Un valore contiene una sequenza di escape non supportata. È supportata solo (. |
| ValueTooShort | 7 | Un valore è più corto della lunghezza minima definita per il suo Identificatore di Applicazione. |
| ValueTooLong | 8 | Un valore è più lungo della lunghezza massima definita per il suo Identificatore di Applicazione. |
| InvalidCharacter | 9 | Un valore contiene un carattere al di fuori del set di caratteri consentito per il suo componente. |
| InvalidChecksum | 10 | Un checksum numerico o alfabetico non è valido. |
| InvalidDate | 11 | Un componente data non è una data significativa secondo le regole definite per il suo Identificatore di Applicazione. |
| InvalidTime | 12 | Un componente orario è al di fuori del suo intervallo consentito o ha una struttura non valida. |
| InvalidCodeListValue | 13 | Il valore di un componente non è presente nella sua lista di codici chiusa consentita. |
| InvalidComponentLength | 14 | Un componente non soddisfa la sua struttura di lunghezza specifica del componente. |
| TruncatedComponent | 15 | Un componente a lunghezza fissa termina prima che tutti i caratteri richiesti siano presenti. |
| UnexpectedData | 16 | I dati rimangono dopo che tutti i componenti definiti per l'Identificatore di Applicazione sono stati consumati. |
| InvalidValue | 17 | Un componente viola una regola di contenuto che non ha un codice di errore di convalida più specifico. |
| GcpPrefixTooShort | 18 | Un componente è troppo corto per contenere il prefisso aziendale strutturale GS1 minimo di quattro cifre. |
| InvalidGcpPrefix | 19 | Il prefisso aziendale strutturale GS1 contiene un carattere diverso da una cifra ASCII. |
| InvalidDigitalLinkUri | 20 | Il valore fornito non è un URI GS1 Digital Link assoluto ben formato. |
| UnsupportedDigitalLinkScheme | 21 | Un URI GS1 Digital Link utilizza uno schema diverso da HTTP o HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | Il percorso di un URI GS1 Digital Link non contiene una chiave primaria supportata. |
| InvalidDigitalLinkPath | 23 | Il percorso di un URI GS1 Digital Link non è costituito da coppie valide di AI e valore. |
| InvalidDigitalLinkQualifier | 24 | Un identificatore di applicazione nel percorso non è un qualificatore consentito in quella posizione. |
| InvalidDigitalLinkQueryParameter | 25 | Un parametro di query GS1 Digital Link è malformato. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Un Identificatore di Applicazione non è consentito come attributo dati GS1 Digital Link. |
| InvalidPercentEncoding | 27 | Un componente URI di GS1 Digital Link contiene una codifica percentuale malformata. |
| MultipleDigitalLinkPrimaryKeys | 28 | È possibile selezionare più di un elemento come chiave primaria GS1 Digital Link. |
| UnsupportedElementCombination | 29 | La combinazione fornita di elementi GS1 non è supportata dalla simbologia o dalla modalità di codifica selezionata. |

## Vedi anche

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
