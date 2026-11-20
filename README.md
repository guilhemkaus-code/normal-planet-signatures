# Signatures mail · Normal Planet (César 2027)

Trois bannières de 600 × 200 px en JPEG, de 23 à 28 Ko chacune.

```
signatures_mail/
├── signatures.html   ← à ouvrir dans un navigateur : aperçu + boutons « Copier »
├── README.md
└── images/
    ├── signature-1-foret.jpg
    ├── signature-2-musee.jpg
    └── signature-3-avatars.jpg
```

## Pourquoi héberger les images ?
Une signature qui marche partout doit pointer vers une image **en ligne** (lien public). Les images collées en pièce jointe ou en base64 sont souvent bloquées ou alourdissent chaque mail. On utilise donc kDrive.

---

## Étape 1 · À faire une seule fois (la personne qui gère le kDrive)
1. Déposer le dossier `signatures_mail/` sur le kDrive.
2. Pour **chaque** image de `images/` : clic droit → **Partager** → **Lien public** (sans mot de passe, sans date d'expiration) → copier le lien.
3. Transformer ce lien en lien d'image directe : ouvrir le lien dans un navigateur, faire un clic droit sur l'image → **Copier l'adresse de l'image**. Coller cette adresse dans un nouvel onglet : on doit voir **l'image seule**, pas la page kDrive.
4. Ouvrir `signatures.html` dans un éditeur de texte (Bloc-notes, TextEdit) et remplacer les trois `COLLER_ICI_LE_LIEN_…` par ces adresses. On peut aussi remplir `LIEN` : la page qui s'ouvre quand on clique sur la bannière.
5. Ouvrir `signatures.html` dans le navigateur : le bandeau orange doit avoir disparu. Remettre le fichier sur le kDrive et partager le dossier avec l'équipe.

> Si kDrive ne donne pas d'adresse d'image directe, n'importe quel hébergement public fait l'affaire : le site du film, ou un dépôt GitHub public, par exemple.

---

## Étape 2 · Pour chaque membre de l'équipe
1. Ouvrir `signatures.html` dans **Chrome, Edge ou Firefox**.
2. Choisir une bannière, puis cliquer sur **Copier la signature**.
3. Coller (Ctrl+V / Cmd+V) dans le champ signature de sa messagerie. Au besoin, ajouter au-dessus son nom et son téléphone en texte.

### Où coller, selon la messagerie
| Messagerie | Chemin |
|---|---|
| **Gmail** (web) | ⚙️ → Voir tous les paramètres → Général → Signature → Créer → coller → **Enregistrer** en bas de page |
| **Outlook web / Outlook.com** | ⚙️ → Courrier → Composer et répondre → Signature → coller → Enregistrer |
| **Outlook (Windows/Mac)** | Fichier → Options → Courrier → Signatures (Mac : Outlook → Réglages → Signatures) → Nouvelle → coller |
| **Apple Mail (Mac)** | Mail → Réglages → Signatures → **+** → décocher « Toujours utiliser ma police par défaut » → coller |
| **iPhone / iPad** | Réglages → Apps → Mail → Signature → coller (ouvrir `signatures.html` dans Safari, puis appui long sur la bannière → Copier) |
| **Infomaniak Mail** | ⚙️ → Signatures → Ajouter → coller dans l'éditeur |
| **Thunderbird** | Paramètres des comptes → cocher « Utiliser HTML » → cliquer **Copier le code HTML** → coller dans la zone signature |
| **Proton Mail** | Paramètres → Identité et adresses → Signature → coller |
| **Gmail Android / Yahoo / autres** | Si seul le texte est accepté, utiliser la version web pour régler la signature. Sur l'appli mobile Gmail, on ne peut pas mettre d'image. |

**Ça ne colle pas l'image ?** Cliquer **Copier le code HTML** et l'utiliser dans un champ « HTML / source », ou faire un glisser-déposer de la bannière depuis la page.

## Questions fréquentes
- **L'image ne s'affiche pas chez le destinataire** : le lien kDrive n'est pas public ou n'est pas une adresse d'image directe (voir étape 1.3). Certains destinataires bloquent aussi les images distantes par défaut ; c'est normal.
- **Changer la bannière plus tard** : remplacer le fichier sur le kDrive **sous le même nom et au même lien**. Toutes les signatures se mettront à jour sans rien refaire.
- **Poids** : environ 25 Ko par bannière, téléchargée par le lecteur et non jointe au mail.
