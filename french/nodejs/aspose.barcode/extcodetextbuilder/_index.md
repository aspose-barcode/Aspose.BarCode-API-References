---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe d'assistance pour la génération automatique de codetext du mode texte de code étendu"
type: docs
weight: 400
url: /fr/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Classe d'assistance pour la génération automatique de codetext du mode texte de code étendu

```js
new ExtCodetextBuilder()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Ajoute du texte de code avec Extended Channel Identifier |
| [addPlainCodetext(codetext)](#addplaincodetext) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| [clear()](#clear) | Efface les éléments de texte de code étendu |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le texte de code étendu à partir de la liste des éléments de génération |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Ajoute du texte de code avec Extended Channel Identifier

| Paramètre | Description |
| --- | --- |
| ECIEncoding | Identifiant de Canal Étendu |
| codetext | Texte de code en Unicode à ajouter comme élément de texte de code étendu avec Extended Channel Identifier |

### addPlainCodetext(codetext) {#addplaincodetext}

Ajoute du texte de code simple aux éléments de texte de code étendu

| Paramètre | Description |
| --- | --- |
| codetext | Codetext en Unicode à ajouter en tant qu'élément de codetext étendu |

### clear() {#clear}

Efface les éléments de texte de code étendu

### getExtendedCodetext() {#getextendedcodetext}

Génère le texte de code étendu à partir de la liste des éléments de génération

**Returns:** Return string of extended codetext
