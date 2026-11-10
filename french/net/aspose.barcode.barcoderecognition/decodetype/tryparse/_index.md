---
title: "DecodeType.TryParse"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "DecodeType méthode. Convertit la représentation sous forme de chaîne d’un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué"
type: docs
weight: 980
url: /fr/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | String | Une chaîne contenant un SingleDecodeType au format "EAN8" ou "EAN13" ou "CodaBar"... à convertir. |
| résultat | SingleDecodeType& | Un SingleDecodeType réel est renvoyé lorsque la conversion s’est terminée avec succès ; sinon il renvoie le type indéfini : DecodeType.None. |

### Valeur de retour

**true** if parsingType was converted successfully; otherwise, **false**.

### Voir aussi

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse}

Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | String | Une chaîne au format "AllSupportedTypes" ou "EAN8,EAN13,CodaBar" à convertir. |
| résultat | MultiDecodeType& | Un MultiDecodeType réel est renvoyé lorsque la conversion s'est terminée avec succès ; sinon il renvoie le type indéfini : new MultiDecodeType(DecodeType.None) |

### Valeur de retour

**true** if parsingType was converted successfully; otherwise, **false**.

### Voir aussi

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


