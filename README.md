# 🧪 Gestion et explication des erreurs courantes en Python

Ce projet contient des exemples de code Python illustrant **plusieurs types d’erreurs courantes**, ainsi que la manière de les **identifier, comprendre et corriger**.

---

## 📜 Contenu du script

### 1️⃣ `IndexError: list index out of range`

```python
mylist = [14, "hello", 967]
print(mylist[6])
```
🔴 Erreur : L'index 6 n'existe pas, car la liste ne contient que 3 éléments (indices 0, 1, 2).  
✅ Correction : Vérifier la longueur de la liste avant d’accéder à un index.

---

### 2️⃣ `ImportError: No module named 'pandas'`

```python
!pip install pandas numpy
import pandas as pd
import numpy as np
```
🔴 Erreur : Le module `pandas` n’est pas installé dans l’environnement.  
✅ Solution : Installer avec `pip install pandas`.

---

### 3️⃣ `SyntaxError: invalid syntax`

```python
print("hello world")
```
🔴 Erreur fréquente quand on oublie des guillemets, parenthèses ou on utilise une mauvaise indentation.  
✅ Ici, la syntaxe est correcte.

---

### 4️⃣ `KeyError: 'True'`

```python
mydictionnary = {True: "hello", False: "bye", '3': "python"}
print(mydictionnary['True'])
```
🔴 Erreur : `'True'` (chaîne) est différent de `True` (booléen).  
✅ Corriger ou ajouter une nouvelle clé `'True'` dans le dictionnaire si nécessaire.

---

### 5️⃣ `IndentationError: expected an indented block`

```python
i = 14
while i < 78:
    print(i)
    i += 1
```
🔴 Erreur si le corps de la boucle n'est pas indenté.  
✅ Solution : Indenter correctement les lignes dans les boucles et conditions.

---

## ✅ Objectif pédagogique

- Comprendre la cause des erreurs les plus fréquentes en Python
- Apprendre à les corriger
- S’exercer avec des cas concrets

---

## 👨‍💻 Auteur

**Cheikh Niang**  
📧 cheikhniang159@gmail.com  
📆 Avril 2025

---

