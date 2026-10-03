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

Pour chaque mod : son lien de téléchargement, ses empreintes SHA-1 / SHA-512, sa version et son côté
(client, serveur). Les mods présents sur Modrinth pointent vers `cdn.modrinth.com`. Les mods absents
de Modrinth (CurseForge…) sont des fichiers de la release `mods-tiers` de ce dépôt : une pré-release,
jamais « la dernière », que le panel et Ops ne confondent pas avec un pack Selvania. Ce dépôt est
public : ces fichiers sont téléchargeables par tous.

Dans Ops, section « Mods tiers » : « Comparer au pack publié », « Publier le pack de mods tiers »,
puis « Préparer le déploiement » pour les serveurs.
