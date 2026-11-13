---
title: "GS1ValidationErrorCode"
second_title: "Riferimento API Aspose.Sildes per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifica una stringa di elemento GS1, un URI Digital Link o un errore di convalida del valore.

## Members
| Nome membro | Descrizione |
| :- | :- |
| EMPTY_ELEMENT_STRING | La stringa dell'elemento GS1 fornita è vuota. |
| MISSING_OPENING_PARENTHESIS | Manca una parentesi di apertura che dovrebbe iniziare un Identificatore di Applicazione. |
| MISSING_CLOSING_PARENTHESIS | Un Identificatore di Applicazione non ha una parentesi di chiusura. |
| INVALID_APPLICATION_IDENTIFIER | Un Identificatore di Applicazione non contiene da due a quattro cifre ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | L'Identificatore di Applicazione fornito non è definito dal Dizionario di Sintassi GS1 supportato. |
| MISSING_VALUE | È presente un Identificatore di Applicazione senza un valore. |
| INVALID_ESCAPE_SEQUENCE | Un valore contiene una sequenza di escape non supportata. È supportato solo \(. |
| VALUE_TOO_SHORT | Un valore è più corto della lunghezza minima definita per il suo Identificatore di Applicazione. |
| VALUE_TOO_LONG | Un valore è più lungo della lunghezza massima definita per il suo Identificatore di Applicazione. |
| INVALID_CHARACTER | Un valore contiene un carattere al di fuori del set di caratteri consentito per il suo componente. |
| INVALID_CHECKSUM | Un checksum numerico o alfabetico è non valido. |
| INVALID_DATE | Un componente data non è una data significativa secondo le regole definite per il suo Identificatore di Applicazione. |
| INVALID_TIME | Un componente temporale è al di fuori dell'intervallo consentito o ha una struttura non valida. |
| INVALID_CODE_LIST_VALUE | Il valore di un componente non è presente nella sua lista di codici chiusa consentita. |
| INVALID_COMPONENT_LENGTH | Un componente non soddisfa la sua struttura di lunghezza specifica del componente. |
| TRUNCATED_COMPONENT | Un componente a lunghezza fissa termina prima che tutti i caratteri richiesti siano presenti. |
| UNEXPECTED_DATA | I dati rimangono dopo che tutti i componenti definiti per l'Identificatore di Applicazione sono stati consumati. |
| INVALID_VALUE | Un componente viola una regola di contenuto che non ha un codice di errore di validazione più specifico. |
| GCP_PREFIX_TOO_SHORT | Un componente è troppo corto per contenere il prefisso aziendale strutturale GS1 minimo di quattro cifre. |
| INVALID_GCP_PREFIX | Il prefisso aziendale strutturale GS1 contiene un carattere diverso da una cifra ASCII. |
| INVALID_DIGITAL_LINK_URI | Il valore fornito non è un URI GS1 Digital Link assoluto ben formattato. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Un URI GS1 Digital Link utilizza uno schema diverso da HTTP o HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Il percorso di un URI GS1 Digital Link non contiene una chiave primaria supportata. |
| INVALID_DIGITAL_LINK_PATH | Il percorso di un URI GS1 Digital Link non è composto da coppie valide di AI e valore. |
| INVALID_DIGITAL_LINK_QUALIFIER | Un Identificatore di Applicazione nel percorso non è un qualificatore consentito in quella posizione. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Un parametro di query GS1 Digital Link è malformato. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Un Identificatore di Applicazione non è consentito come attributo dati di GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Un componente URI di GS1 Digital Link contiene una codifica percentuale malformata. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | È possibile selezionare più di un elemento come chiave primaria di GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | La combinazione fornita di elementi GS1 non è supportata dalla simbologia o dalla modalità di codifica selezionata. |

### Vedi anche

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

