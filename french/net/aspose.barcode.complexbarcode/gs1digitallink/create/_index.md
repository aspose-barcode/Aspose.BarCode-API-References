---
title: "GS1DigitalLink.Create"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode GS1DigitalLink. Crée un GS1 Digital Link en copiant tous les éléments du codetext GS1 et en sélectionnant la seule clé primaire disponible"
type: docs
weight: 20
url: /fr/net/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## Create(string, GS1Codetext) {#create}

Crée un lien numérique GS1 en copiant tous les éléments du codetext GS1 et en sélectionnant la seule clé primaire disponible.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| uriStem | String | Préfixe d'URI HTTP ou HTTPS absolu avant la clé primaire. |
| codetext | GS1Codetext | Codetext GS1 dont les éléments sont copiés. |

### Valeur de retour

Un GS1 Digital Link contenant les éléments copiés.

### Voir aussi

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)

---

## Create(string, GS1Codetext, string) {#create_1}

Crée un lien numérique GS1 en copiant tous les éléments du codetext GS1 et en utilisant la clé primaire spécifiée.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext, 
    string primaryApplicationIdentifier)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| uriStem | String | Préfixe d'URI HTTP ou HTTPS absolu avant la clé primaire. |
| codetext | GS1Codetext | Codetext GS1 dont les éléments sont copiés. |
| primaryApplicationIdentifier | String | AI de la clé primaire. |

### Valeur de retour

Un GS1 Digital Link contenant les éléments copiés.

### Voir aussi

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


