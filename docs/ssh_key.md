# Echange de clé SSH

Pour pouvoir cloner un repositorie privée, il faut taper son identifiant et mot de passe à chaque fois, sauf si vous utiliser l’authentification par clé ssh.

Comment configurer l’échange de clé ssh ? …


## 1. Générer une paire de clé ssh sur votre environnement vers lequel vous allez git cloner

```powershell
ssh-keygen -t ecdsa -b 521
```

Un message indique où se trouve la clé privée et la clé publique générée (souvent dans ~/.ssh/id_ecdsa*)

## 2. Transfert de la clé publique sur une plateforme remote Git (Github, Gitlab, Azure devops...):
