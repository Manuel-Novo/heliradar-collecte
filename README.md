# HéliRadar — collecte

Workflow public qui photographie **toutes les 15 minutes** la position de tous les
hélicoptères visibles dans le monde et les envoie vers la base de données HéliRadar.

- **Source des données** : [adsb.lol](https://adsb.lol) — réseau communautaire ADS-B,
  données sous licence [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
  © les contributeurs adsb.lol.
- Ce dépôt est public pour bénéficier des minutes GitHub Actions illimitées ;
  il ne contient aucun secret (la clé d'ingestion est un secret GitHub Actions).
- Cadence : requête « types » toutes les 15 min ; passe complète avec cercles
  régionaux (hélicos sans code type) toutes les 30 min, à ~1 requête/seconde
  par politesse envers adsb.lol.
