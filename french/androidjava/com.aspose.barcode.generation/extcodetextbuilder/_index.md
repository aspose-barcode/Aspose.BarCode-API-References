---
title: ExtCodetextBuilder
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe d'assistance pour la génération automatique de texte de code du mode texte de code étendu
type: docs
weight: 40
url: /fr/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Classe d'assistance pour la génération automatique de texte de code du mode texte de code étendu
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Ajoute du codetext avec un identifiant de canal étendu. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| [clear()](#clear--) | Efface les éléments de texte de code étendu |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Génère le texte de code étendu à partir de la liste des éléments de génération. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Vérifie la nécessité de protéger l'élément précédent par "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Ajoute du codetext avec un identifiant de canal étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Identifiant de canal étendu |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu avec l'identifiant de canal étendu |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Ajoute du texte de code simple aux éléments de texte de code étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu |

### clear() {#clear--}
```
public void clear()
```


Efface les éléments de texte de code étendu

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


Génère le texte de code étendu à partir de la liste des éléments de génération.

**Returns:**
java.lang.String - Retourne la chaîne du texte de code étendu.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Vérifie la nécessité de protéger l'élément précédent par "\\000000"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Indice | int | Indice dans m\_List |

**Returns:**
booléen - Nécessité de protéger
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

