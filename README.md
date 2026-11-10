# Mot de passe enfant

Générateur de mots de passe faciles à retenir pour les enfants.

**Utiliser en ligne :** https://eric-peiffer.github.io/mot-de-passe-enfant/

Le mot de passe est composé d'un animal, d'une couleur, d'un véhicule et d'une heure de départ, par exemple `Panda-Bleu-Camion-3H`, avec un emoji et une petite histoire pour s'en souvenir :

> 🐼 Un panda 🔵 tout bleu part en 🚚 camion à 🕒 3 heures.

- Au moins 12 caractères, une majuscule, une minuscule, un chiffre et un caractère spécial (`-`).
- Mots simples, sans accent ni piège d'orthographe.
- Tirage aléatoire avec `crypto.getRandomValues`, entièrement dans le navigateur : rien n'est envoyé sur internet.
- Environ 32 000 combinaisons : adapté aux sites qui bloquent les essais répétés, pas aux comptes importants.
