# 📄 get_next_line

Lire une ligne depuis un descripteur de fichier, une fonction essentielle pour manipuler des flux en C.

---

## 🧠 Objectif

Écrire une fonction `get_next_line(int fd)` qui lit et retourne **une ligne** depuis un descripteur de fichier `fd`, à chaque appel, **sans perdre le reste du buffer**.

---

## ⚙️ Fonctionnalités

- Lecture **ligne par ligne**, même sur plusieurs fichiers ouverts simultanément.
- Fonction **non bloquante** qui gère les retours à la ligne, les fichiers vides ou les lectures incomplètes.
- Optimisé pour fonctionner avec n’importe quelle taille de `BUFFER_SIZE`.

---
