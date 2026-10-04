<p align="center"><img src="icon.png" width="160" alt="AI-LYRICS-FIX FOR VIRTUAL DJ"></p>

<p align="center">
  <img src="screenshot3.png?v=1.2" alt="Chord Injector for Virtual DJ 2026 interface" width="900">
</p>



# AI-LYRICS-FIX FOR VIRTUAL DJ

**Corrige les paroles karaoké générées par l'IA de VirtualDJ, avec les paroles de LRCLIB, en gardant le timing.**
*Fixes VirtualDJ's AI-generated karaoke lyrics with LRCLIB lyrics, keeping the word timing.*

## Télécharger / Download

👉 **[Dernière version / Latest release](https://github.com/owfrappier/AI-LYRICS-FIX-FOR-VIRTUAL-DJ/releases/latest)**

| Système | Fichier |
|---|---|
| macOS (Apple Silicon, 11+) | `…-macOS-AppleSilicon.pkg` — signé et notarisé Apple |
| Windows 10/11 (x64) | `…-Windows-x64.zip` — décompresser et lancer l'`.exe` |

> Windows : au premier lancement, SmartScreen peut afficher « Windows a protégé votre ordinateur ».
> Cliquer **Informations complémentaires › Exécuter quand même** (l'exe n'est pas encore signé).

## Ce que fait l'app

- Liste tous vos morceaux qui ont des paroles dans VirtualDJ (`extra.db`), avec artiste et titre.
- Cherche automatiquement les paroles sur **LRCLIB** (titre, artiste, durée).
- **LRC Sync** : recale les paroles LRCLIB sur le timing mot à mot de VirtualDJ, même quand la
  reconnaissance IA est très fausse ou que votre version a une intro différente (décalage automatique).
- Modes **Smart**, **Hard** (langues rares) et **Manuel** (édition directe, calage au clavier pendant l'écoute).
- **Pages karaoké** comme sur l'écran VirtualDJ (un point toutes les N lignes).
- Aperçu karaoké avec l'audio du morceau.
- Écriture sûre : sauvegarde automatique d'`extra.db` avant chaque modification, VirtualDJ fermé
  puis relancé automatiquement.

## Utilisation

1. Lancer l'app : elle trouve le dossier VirtualDJ (ou bouton **Dossier VirtualDJ…** → choisir `extra.db`).
2. Cliquer un morceau : les paroles LRCLIB sont chargées et alignées.
3. Onglet **2** : vérifier / écouter / corriger.
4. Onglet **3** : **Écrire dans extra.db**.

Les sauvegardes sont dans `VirtualDJ/AI-LYRICS-FIX-Backups/` (30 dernières).

## Soutenir le projet / Support

Si l'app vous rend service : **[♥ Donate (PayPal)](https://www.paypal.com/paypalme/owfrappier)**

---

Olivier W. Frappier — logiciel gratuit, code source non public.
Non affilié à VirtualDJ / Atomix Productions. Paroles fournies par [LRCLIB](https://lrclib.net).
Gardez toujours vos propres sauvegardes.
