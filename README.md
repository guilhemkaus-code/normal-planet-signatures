# Signatures mail · Normal Planet (César 2027)

Trois bannières, chacune en quatre largeurs d'affichage (300, 400, 500 et 600 px). Chaque image a deux fois plus de pixels que sa largeur d'affichage (600 à 1200 px de large), pour rester nette sur les écrans haute résolution, en JPEG qualité 82 : de 23 Ko (300 px) à 83 Ko (600 px). Une version « Haute résolution » existe aussi pour toutes les largeurs : la même image 1200 px en JPEG qualité 95, couleurs en pleine résolution, de 161 à 189 Ko.

```
signatures_mail/
├── index.html   ← à ouvrir dans un navigateur : aperçu + boutons « Copier »
├── README.md
└── images/
    ├── signature-1-foret.jpg
    ├── signature-2-musee.jpg
    └── signature-3-avatars.jpg
```

## Où sont les images
Elles sont hébergées publiquement sur GitHub (https://github.com/guilhemkaus-code/normal-planet-signatures), et `index.html` pointe déjà vers elles. Il n'y a rien à configurer.

Pour changer une bannière plus tard, il suffit de remplacer le JPEG dans `images/` sous le même nom et de le pousser sur GitHub. Toutes les signatures se mettent à jour. GitHub peut garder l'ancienne version en cache quelques minutes.

---

## Pour chaque membre de l'équipe
1. Ouvrir **https://guilhemkaus-code.github.io/normal-planet-signatures/** dans Chrome, Edge ou Firefox (ou `index.html` en local).
2. Choisir une bannière, puis cliquer sur **Copier la signature**.
3. Coller (Ctrl+V / Cmd+V) dans le champ signature de sa messagerie. Au besoin, ajouter au-dessus son nom et son téléphone en texte.

### Où coller, selon la messagerie
| Messagerie | Chemin |
|---|---|
| **Gmail** (web) | ⚙️ → Voir tous les paramètres → Général → Signature → Créer → coller → **Enregistrer** en bas de page |
| **Outlook web / Outlook.com** | ⚙️ → Courrier → Composer et répondre → Signature → coller → Enregistrer |
| **Outlook (Windows/Mac)** | Fichier → Options → Courrier → Signatures (Mac : Outlook → Réglages → Signatures) → Nouvelle → coller |
| **Apple Mail (Mac)** | Mail → Réglages → Signatures → **+** → décocher « Toujours utiliser ma police par défaut » → coller |
| **iPhone / iPad** | Réglages → Apps → Mail → Signature → coller (ouvrir `index.html` dans Safari, puis appui long sur la bannière → Copier) |
| **Infomaniak Mail** | ⚙️ → Signatures → Ajouter → coller dans l'éditeur |
| **Thunderbird** | Paramètres des comptes → cocher « Utiliser HTML » → cliquer **Copier le code HTML** → coller dans la zone signature |
| **Proton Mail** | Paramètres → Identité et adresses → Signature → coller |
| **Gmail Android / Yahoo / autres** | Si seul le texte est accepté, utiliser la version web pour régler la signature. Sur l'appli mobile Gmail, on ne peut pas mettre d'image. |

**Ça ne colle pas l'image ?** Cliquer **Copier le code HTML** et l'utiliser dans un champ « HTML / source », ou faire un glisser-déposer de la bannière depuis la page.

## Questions fréquentes
- **L'image ne s'affiche pas chez le destinataire** : certains destinataires bloquent les images distantes par défaut ; c'est normal.
- **Poids** : environ 25 Ko par bannière, téléchargée par le lecteur et non jointe au mail.
