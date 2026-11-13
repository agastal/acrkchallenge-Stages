# ACRK Challenge – community stages

Custom stages for **Assetto Corsa Rally**, built on real roads, for the drivers of
[ACRK Challenge](https://ch.acrkhotlap.workers.dev). They are installed and removed by
[acrk-tray](https://github.com/agastal/acrkchallenge-Release), menu *Community stages...*:
nothing to copy by hand.

Each release is built for one Steam build of the game (its tag is `b<build>-<version>`); after a game
update the stages are rebuilt and released again. Every file is listed with its SHA-256 in
`stages-manifest.json`, signed with the key of acrk-tray's updates: the app installs nothing else.

To remove them by hand: delete the `zz_acrxs_*` files from
`Assetto Corsa Rally\acr\Content\Paks\~mods` (Steam's *Verify integrity* does not touch that folder).

---

# ACRK Challenge – stage della community

Stage aggiuntivi per **Assetto Corsa Rally**, costruiti su strade vere, per i piloti di
[ACRK Challenge](https://ch.acrkhotlap.workers.dev). Li installa e li toglie
[acrk-tray](https://github.com/agastal/acrkchallenge-Release), menu *Stage della community...*.

Ogni release vale per una build del gioco su Steam; dopo un aggiornamento del gioco gli stage vengono
ricostruiti e ripubblicati. Per toglierli a mano: cancellare i file `zz_acrxs_*` da
`Assetto Corsa Rally\acr\Content\Paks\~mods`.

## Data / Dati

Roads © OpenStreetMap contributors (ODbL); elevation Copernicus GLO-30 DEM; land cover ESA WorldCover
2021 (CC BY 4.0); textures Poly Haven (CC0). Built with
[ACR Extra Stages](https://github.com/cherrymcgerry/acr-extrastages) (MIT / Apache-2.0).
Fan project, not affiliated with the game's developers or publisher.
