---
title: "HanXinEncodeMode"
second_title: "Référence de l'API .NET Aspose.Sildes pour Python"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Mode d'encodage Han Xin Code. Il est recommandé d'utiliser Auto avec des caractères ASCII / chinois ou Unicode pour les caractères Unicode.

## Members
| Nom du membre | Description |
| :- | :- |
| AUTO | En mode Auto, le CodeText est encodé avec la compacité maximale des données. <br/>            Les caractères Unicode sont encodés en utilisant l'encodage GB18030 conformément à la spécification du code-barres HanXin. |
| BINARY | En mode Binaire, le CodeText est encodé avec la compacité maximale des données. <br/>            Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | En mode ECI, le message complet est ré-encodé dans le codage spécifié par ECIEncoding avec l’insertion d’un identifiant ECI.<br/>            Si un caractère est trouvé qui n’est pas pris en charge par le codage ECI sélectionné, une exception est levée.<br/>            Veuillez noter que certains anciens scanners (pré 2006) peuvent ne pas prendre en charge ce mode. |
| UNICODE | Le mode Unicode définit une façon de représenter toute donnée textuelle en référence à l'encodage/jeu de caractères UTF‑8 dans le code Han Xin. |
| URI | Le mode URI indique que les données représentées dans le code Han Xin sont un Uniform Resource Identifier (URI)<br/>            référence à la RFC 3986. |
| EXTENDED | Le mode Étendu autorise les combinaisons de modes internes : Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Le Codetext peut être construit manuellement avec des préfixes et des barres obliques inverses doublées, par ex. : @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" ou en utilisant le HanXinExtCodetextBuilder.<br/>            Si le Codetext contient un fragment ECI, alors seuls les modes suivants peuvent être présents dans ce Codetext après le fragment ECI :<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

