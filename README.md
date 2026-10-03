# pack-feed-8b5f68a6

Selvania — packs de mods publiés, lus par le panel (distribution aux joueurs) et par Selvania Ops
(déploiement sur les serveurs). Rien n'est publié ici à la main : tout passe par Selvania Ops.

## Pack Selvania — releases `pack-vX.Y`

Un zip par version (`Selvania-vX.Y.zip`) et son empreinte (`SHA256SUMS.txt`) : mods Selvania, client,
écran de démarrage et plugins Velocity, rangés par destination (`LISEZMOI.txt` dans le zip).

Dans Ops, carte « Pack de mods » : « Construire le pack X.Y » (compilation sur GitHub), puis
« Publier le pack X.Y » (copie ici). « Suspendre » retire une version en cas de problème.

## Mods tiers — fichier `mods-tiers.json`

Tous les autres mods (Create, JEI, TerraBlender…), tels qu'ils sont dans le profil Modrinth
« Server » du PC d'administration. Ce n'est pas une release : le panel ne surveille que les releases.

Le fichier ne contient que des liens `cdn.modrinth.com`, les empreintes SHA-1 / SHA-512, la version et
le côté de chaque mod (client, serveur) : aucun fichier n'est redistribué. Les rares mods absents de
Modrinth sont listés sans lien et envoyés aux serveurs depuis le PC d'administration.

Dans Ops, section « Mods tiers » : « Comparer au pack publié », « Publier le pack de mods tiers »,
puis « Préparer le déploiement » pour les serveurs.
