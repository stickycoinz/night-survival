# Riposte: Frontline, ce qui n'est pas sous licence MIT

Le code du jeu est sous licence MIT (fichier `LICENSE`). Les éléments ci-dessous n'en relèvent pas : ils restent sous leurs propres
conditions, que la licence MIT ne remplace pas. Pour faire votre propre jeu à partir de ce code, remplacez-les ou vérifiez que leurs
conditions vous le permettent.

1. **Nom et logo.** Le nom « Riposte: Frontline » et le logo appartiennent à l'auteur, tous droits réservés : `assets/logo.webp`,
   les images de `assets/icon/` et `assets/deck/`, et leurs copies dans `dist/` (`icons/`, `deck/`, `favicon.ico`). Une copie ou une
   adaptation du jeu porte un autre nom et un autre logo, et ne se présente pas comme le jeu officiel.
2. **Musiques de fin de partie et alarme de brèche (Night Survival).** `assets/sfx/fin/m_victory.mp3` et `assets/sfx/fin/m_defeat.mp3`,
   et leurs copies intégrées dans `dist/sfx/fin.*.js`, ont été générées avec ElevenLabs Music v2.5 par Cody (compte ElevenLabs
   de Cody Breedlove) : stingers instrumentaux, usage dans ce jeu. Les musiques d'origine Riposte faites avec Suno (offre
   gratuite, usage non commercial : notamment `assets/rankup.mp3` et `dist/menu-theme.mp3`) ne sont pas livrées dans cette
   version de Night Survival ; elles restent uniquement dans une sauvegarde locale. L'alarme de brèche `assets/sfx/alarm/a_breach.mp3`, et sa copie intégrée dans `dist/sfx/alarm.*.js`, a été générée avec ElevenLabs (effets sonores) par Cody (compte ElevenLabs de Cody Breedlove), puis adoucie pour le jeu.
3. **Animations des soldats**, cuites à partir d'animations Mixamo (Adobe) : `assets/anim/clips.bin`, `assets/anim/clips.json`, et
   leur copie intégrée dans `dist/riposte-frontline.html`. Les conditions de Mixamo permettent de s'en servir dans un jeu, pas de les
   redistribuer à part. Pour votre jeu, refaites-les depuis votre compte Mixamo (`tools/dev/anim/cuire.mjs`).
4. **Son de touche** (`HIT_SAMPLE` dans `src/05-audio.js`, et sa copie dans `dist/`) : échantillon d'origine flashkit.com, sous les
   conditions de son auteur.
5. **Sons et voix** (`assets/sfx/`, `dist/sfx/`) : chaque source garde sa licence, donnée dans `assets/sfx/credits.json`. La plupart
   sont en CC0 ; celles en CC BY demandent de citer leur auteur comme le fait ce fichier.
6. **Textures et ciels** (`assets/tex/`, `assets/sky/`, `assets/vendor/hdri/`, `dist/tex/`) : Poly Haven et ambientCG, licence CC0.
7. **Bibliothèques** : three.js (licence MIT, notice en tête de `assets/vendor/three-r147.js`) ; les paquets npm dont dépendent le site
   et les outils gardent leur licence.

---

# Riposte: Frontline, what is not under the MIT License

The game code is under the MIT License (`LICENSE` file). The items below are not: they keep their own terms, which the MIT License
does not replace. To build your own game from this code, replace them or check that their terms allow it.

1. **Name and logo.** The name "Riposte: Frontline" and the logo belong to the author, all rights reserved: `assets/logo.webp`, the
   images in `assets/icon/` and `assets/deck/`, and their copies in `dist/` (`icons/`, `deck/`, `favicon.ico`). A copy or adaptation
   of the game uses another name and another logo, and does not present itself as the official game.
2. **End-of-match music and breach alarm (Night Survival).** `assets/sfx/fin/m_victory.mp3` and `assets/sfx/fin/m_defeat.mp3`, and their
   copies packed into `dist/sfx/fin.*.js`, were generated with ElevenLabs Music v2.5 by Cody (Cody Breedlove's ElevenLabs
   account): instrumental stingers, for use in this game. Riposte's original Suno free-plan tracks (non-commercial terms),
   including `assets/rankup.mp3` and `dist/menu-theme.mp3`, are not shipped in this Night Survival build; they remain only
   in a local backup. The breach alarm `assets/sfx/alarm/a_breach.mp3`, and its copy packed into `dist/sfx/alarm.*.js`, was generated with ElevenLabs (sound effects) by Cody (Cody Breedlove's ElevenLabs account), then softened for this game.
3. **Soldier animations**, baked from Mixamo (Adobe) animations: `assets/anim/clips.bin`, `assets/anim/clips.json`, and their copy
   embedded in `dist/riposte-frontline.html`. Mixamo's terms allow using them in a game, not redistributing them on their own. For your
   game, bake them again from your own Mixamo account (`tools/dev/anim/cuire.mjs`).
4. **Hit sound** (`HIT_SAMPLE` in `src/05-audio.js`, and its copy in `dist/`): sample from flashkit.com, under its author's terms.
5. **Sounds and voices** (`assets/sfx/`, `dist/sfx/`): each source keeps its license, listed in `assets/sfx/credits.json`. Most are
   CC0; the CC BY ones require crediting their author, as that file does.
6. **Textures and skies** (`assets/tex/`, `assets/sky/`, `assets/vendor/hdri/`, `dist/tex/`): Poly Haven and ambientCG, CC0.
7. **Libraries**: three.js (MIT License, notice at the top of `assets/vendor/three-r147.js`); the npm packages used by the site and
   the tools keep their own licenses.
