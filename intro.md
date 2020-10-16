# Python
Python is a programming language that allows us to communicate with and control our computers.
Python est un langage de programmation qui nous permet de communiquer avec nos ordinateurs et de les contrôller.

Python is a powerful, popular language - we use it a lot in science!
Python est un langage puissant et populaire - on l'utilise très souvent dans les sciences!

---

## Dictionaries / Dictionnaires

Dictionaries are containers, inside which we find other objects. Each object inside is associated with a key.
Les dictionnaires sont des objets conteneurs, dans lesquels on trouve d'autres objets. Chaque object est associé avec un clé.

```
>>> mon_dictionnaire = {}
>>> mon_dictionnaire["nom"] = "Bond"
>>> mon_dictionnaire["prenom"] = "Anna"
>>> mon_dictionnaire
{'nom': 'Bond'', 'prenom': 'Anna'}
>>> mon_dictionnaire["nom"]
'Bond'
>>>
```

Source: https://openclassrooms.com/fr/courses/235344-apprenez-a-programmer-en-python/232273-utilisez-des-dictionnaires
License: CC BY-NC-SA 2.0

---

## Lists

Lists are objects that contain a sequence of other objects.
Les listes sont des objets qui peuvent en contenir d'autres en sequence.

```
>>> ma_liste = ["a", "b", 11]
>>> ma_liste[0] # On accède au premier élément de la liste
'a'
>>> ma_liste.append(56) # On ajoute 56 à la fin de la liste
>>> ma_liste
['a', 'b', 11, 56]
>>> ma_liste.append({"prenom" : "Anna"}) # On ajoute une dictionnaire
>>> ma_liste
['a', 'b', 11, 56, {'prenom' : 'Anna'}]
>>> ma_liste[4]["prenom"]
'Anna'
>>>
```

Source: https://openclassrooms.com/fr/courses/235344-apprenez-a-programmer-en-python/232026-creez-des-listes-et-des-tuples-1-2
License: CC BY-NC-SA 2.0
