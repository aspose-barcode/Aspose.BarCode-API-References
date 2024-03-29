---
title: License
second_title: Referencia de API de Aspose.BarCode para .NET
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 1010
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
| [License](license)() | Constructor predeterminado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.barcode/license/setlicense#setlicense_1)(string) | Licencia el componente. |

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en el incrustado recursos del ensamblado que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ver también

* espacio de nombres [Aspose.BarCode](../../aspose.barcode)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
