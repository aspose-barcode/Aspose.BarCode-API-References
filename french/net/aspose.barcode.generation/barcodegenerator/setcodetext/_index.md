---
title: "BarcodeGenerator.SetCodeText"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode BarcodeGenerator. Définit le codetext comme une séquence d'octets"
type: docs
weight: 100
url: /fr/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Définit le texte du code comme une séquence d'octets.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| codeBytes | Byte[] | Octets du codetext |

### Voir aussi

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge, la fonction insère automatiquement un [marque d'ordre d'octet (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Cette fonction est destinée à être utilisée uniquement avec les codes-barres 2D (p. ex., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Elle permet l’encodage manuel de texte Unicode en utilisant des encodages nationaux ou spéciaux ; cependant, cette méthode est considérée comme obsolète dans les applications modernes. Pour les cas d’utilisation modernes, l’encodage [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) est recommandé pour les données Unicode.

L’utilisation de cette fonction avec des codes-barres 1D, des codes-barres conformes à GS1 (y compris 2D), ou des codes-barres HIBC (y compris 2D) n’est pas prise en charge par les normes de codes-barres correspondantes et peut entraîner des résultats imprévisibles.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| codeText | String | Chaîne CodeText |
| encodage | Encodage | Encodage appliqué |

## Exemples

Cet exemple montre comment utiliser `SetCodeText` pour définir du texte encodé en Unicode pour les codes-barres 2D en utilisant différents encodages :

```csharp
[C#]
//Encoder le texte du QR Code en UTF-8 avec BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Encoder le texte DataMatrix en Shift-JIS (encodage japonais)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Voir aussi

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge et que **insertBOM** est défini sur `true`, la fonction inclut un [marque d'ordre d'octet (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Cette fonction est destinée à être utilisée uniquement avec les codes-barres 2D (p. ex., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Elle permet l’encodage manuel de texte Unicode en utilisant des encodages nationaux ou spéciaux ; cependant, cette méthode est considérée comme obsolète dans les applications modernes. Pour les cas d’utilisation modernes, l’encodage [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) est recommandé pour les données Unicode.

L’utilisation de cette fonction avec des codes-barres 1D, des codes-barres conformes à GS1 (y compris 2D), ou des codes-barres HIBC (y compris 2D) n’est pas prise en charge par les normes de codes-barres correspondantes et peut entraîner des résultats imprévisibles.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| codeText | String | Chaîne CodeText |
| encodage | Encodage | Encodage appliqué |
| insertBOM | Boolean | Indique s’il faut insérer un marqueur d’ordre d’octets (BOM) lorsque l’encodage spécifié le prend en charge (p. ex., UTF-8, UTF-16, UTF-32). Si la valeur est `true`, le BOM est ajouté ; si elle est `false`, le BOM est omis même si l’encodage en utilise normalement un. |

## Exemples

Cet exemple montre comment utiliser `SetCodeText` avec ou sans BOM pour les codes-barres 2D.

```csharp
[C#]
//Encoder le codetext en UTF-8 avec BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Encoder le codetext en UTF-8 sans BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Voir aussi

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


