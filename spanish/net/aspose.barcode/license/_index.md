---
title: "Clase License"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.License. Proporciona métodos para licenciar el componente"
type: docs
weight: 1760
url: /es/net/aspose.barcode/license/
---
## License class

Proporciona métodos para licenciar el componente.

```csharp
public class License
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Licencia la biblioteca. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Licencia la biblioteca. |

## Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ver también

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


