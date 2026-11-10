---
title: "License.SetLicense"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode License. Licence la bibliothèque"
type: docs
weight: 20
url: /fr/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licence la bibliothèque.

```csharp
public void SetLicense(string licenseName)
```

## Remarques

Essaye de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier qui contient l'assembly du composant Aspose.

3. Le dossier qui contient l'assembly appelant du client.

4. Le dossier qui contient l'assembly d'entrée (démarrage).

5. Une ressource intégrée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource intégrée dans l'assembly appelant du client.

## Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Peut être un nom de fichier complet ou court ou le nom d'une ressource intégrée.

### Voir aussi

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

Licence la bibliothèque.

```csharp
public void SetLicense(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Un flux qui contient la licence. |

## Remarques

Utilisez cette méthode pour charger une licence à partir d'un flux.

## Exemples

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Voir aussi

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


