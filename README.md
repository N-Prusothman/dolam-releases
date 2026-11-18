# DOLAM EXISTENCE CROCHET

Crochet court à travers la forêt, et des slimes foncent sur elle.
Tire-leur dessus au laser, écrase-les en sautant, et tiens le plus longtemps
possible. Le jeu accélère toutes les 20 secondes.

Joue en **solo** pour grimper au classement mondial, ou défie un ami en
**1 contre 1 en ligne**.

---

## Télécharger

👉 **[Page des téléchargements](https://github.com/N-Prusothman/dolam-releases/releases/latest)**

Prends le fichier de ton système :

| Système | Fichier |
|---|---|
| Windows | `DOLAM-windows.zip` |
| macOS | `DOLAM-macos.zip` |
| Linux | `DOLAM-linux.zip` |

Rien d'autre à installer, Java est déjà inclus.

## Lancer le jeu

### Windows
1. Clic droit sur le zip, puis **Extraire tout**.
2. Ouvre le dossier `DOLAM` et double-clique sur **`DOLAM.exe`**.
3. Si Windows affiche *« Windows a protégé votre ordinateur »*, clique sur
   **Informations complémentaires**, puis **Exécuter quand même**. Ça arrive
   avec tous les petits jeux indépendants qui ne sont pas signés.

### macOS
1. Double-clique sur le zip pour le décompresser.
2. **La première fois** : clic droit sur `DOLAM.app`, puis **Ouvrir**, puis
   **Ouvrir** encore une fois. Après ça, un double-clic suffit.

### Linux
```bash
unzip DOLAM-linux.zip
./DOLAM/bin/DOLAM
```

---

## Comment jouer

| Commande | Action |
|---|---|
| **Clic gauche** | Tire au laser. Un clic directement sur un slime le tue. |
| **Espace** | Saute. Retombe sur un slime pour l'écraser (tu rebondis !). |
| **Bouton pause** (en haut à droite) | Met le jeu en pause. |
| **Échap** | Quitte un menu ou un duel. |

Si un slime te touche (sauf par le dessus), c'est perdu.

### Les slimes

| Slime | Points | Comment il bouge |
|---|---|---|
| 🔵 Bleu | 1 | Avance tranquillement |
| 🟢 Vert | 3 | Ondule de haut en bas |
| 🩷 Rose | 5 | Fonce très vite |
| 🟡 Jaune | 10 | Rebondit haut, et il est rare |

Tous les **200 points**, tu gagnes une récompense, affichée en haut à gauche.

---

## Compte et classement

Crée un compte pour que tes scores comptent dans le **classement mondial**.

1. Menu, puis **COMPTE**, puis **CREER UN COMPTE**.
2. Choisis un pseudo (3 à 16 lettres, chiffres ou `_`), ton email et un mot
   de passe de 6 caractères minimum.
3. Tu restes connecté d'une partie à l'autre.

Quand tu es connecté, chaque partie solo est **classée** : à la fin, le jeu
affiche *« SCORE VALIDE ! RECORD : … »* avec ton rang.
Le bouton **CLASSEMENT** du menu montre le top 10 en solo et en 1v1.

> **Scores vérifiés.** Le jeu envoie toutes tes actions au serveur, qui
> rejoue ta partie pour calculer ton vrai score. Si quelqu'un modifie son
> score, le serveur le refuse.
> Si tu quittes une partie par **Pause, puis Menu**, elle n'est pas
> enregistrée.

Sans compte, tu peux jouer quand même, mais tes scores ne sont pas classés.

---

## 1 contre 1 en ligne

Ta partie s'affiche **en bas** de l'écran et celle de ton adversaire
**en haut**. Chacun joue de son côté. Quand les deux sont K.O.,
**le meilleur score gagne**.

### Créer une partie (l'hôte)
1. Menu, puis **ONLINE 1VS1**, puis **HEBERGER**.
2. Le jeu affiche un **code** (par exemple `52C-JTSA`). Envoie-le à ton ami.
3. La partie démarre dès qu'il se connecte.

### Rejoindre une partie
1. Menu, puis **ONLINE 1VS1**, puis **REJOINDRE**.
2. Tape le code de l'hôte (ou colle-le avec `Ctrl+V`), puis **Entrée**.

Après chaque manche : **REJOUER** pour une revanche, ou **MENU** pour quitter.
Si vous êtes **tous les deux connectés** à un compte, la manche compte pour
le classement 1v1.

### Le code ne marche pas ?
- **Même wifi / même box** : utilisez le **code « MEME RESEAU »**. C'est le
  cas le plus simple.
- **Pas sur le même réseau** : deux solutions.
  - **La plus simple** : installez tous les deux un réseau privé virtuel
    gratuit comme [Tailscale](https://tailscale.com) ou
    [Radmin VPN](https://www.radmin-vpn.com), puis utilisez le code
    « MEME RESEAU » affiché par l'hôte.
  - **Ou** : l'hôte ouvre le **port TCP 4242** sur sa box internet
    (« redirection de port ») et donne le **code INTERNET**.
- **Windows** : au premier « HEBERGER », Windows peut demander l'accès au
  réseau pour Java. Clique sur **Autoriser**.

---

## Problèmes fréquents

| Problème | Solution |
|---|---|
| *« SERVEUR INJOIGNABLE »* | Vérifie ta connexion internet. |
| *« EMAIL OU MOT DE PASSE INCORRECT »* | Vérifie les deux, attention aux majuscules. |
| *« CONFIRME D'ABORD TON EMAIL »* | Clique sur le lien reçu par email (regarde dans les spams). |
| *« PORT 4242 DEJA UTILISE »* | Une autre partie hébergée est déjà ouverte : ferme-la. |
| *« IMPOSSIBLE DE SE CONNECTER »* | Mauvais code, hôte pas encore en attente, ou pas sur le même réseau (voir plus haut). |
| *« VERSION DU JEU DIFFERENTE »* | Vous devez avoir la même version : retéléchargez la dernière. |

---

Bon jeu ! 🎮
