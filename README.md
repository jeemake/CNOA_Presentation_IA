# L'IA en agence d'architecture — OACI

Site interactif de la présentation « L'architecte comme artisan augmenté », atelier pratique (session 2) de l'Ordre des Architectes de Côte d'Ivoire, 9 octobre 2026.

Intervenants : Ange Djoké, Jean-Marc Don Mello, Gaston Koffi.

## Ouvrir le site

Ouvrir `site/index.html` dans un navigateur (connexion internet requise pour Three.js et les polices).

## Contenu

- `site/index.html` : page, styles dans `site/style.css`
- `site/assets/video` : boucles vidéo (Seedance 2.5) et portraits animés de 4 s des intervenants (`spk-*.mp4`, MiniMax H3 Max, fal.ai)
- `site/assets/img` : images de la présentation, portraits améliorés (Topaz Recover 3, fal.ai), QR code de la démo
- `site/assets/3d` : arbres 3D générés avec Hunyuan 3D v3.1 Pro (fal.ai) et textures BTC / béton (Nano Banana 2.1), embarqués dans `parti-assets.js` pour fonctionner aussi en ouverture directe du fichier

Les informations des intervenants se modifient dans le bloc `SPEAKERS` du script de `index.html`.
La maquette 3D de la partie 02 se règle dans le bloc `parti3d` (programmes, façades, ambiances, intentions, points de vue).
Les questions-réponses de la partie 07 sont dans le bloc `qa`.
