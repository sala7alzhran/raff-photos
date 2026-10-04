# raff-photos

Box-photo packs for the Raff pharmacy app, downloaded by the app when a pharmacy chooses its country.

- `packs.json`: one entry per country (version, photo count, zip parts with their size and SHA-256).
- `SY/photos-v<N>-<part>.zip`: WebP photos (480 px) named by the medicine's number in the Ministry of Health list.

Packs are built with `tools/photo_pack.py` in the app's (private) repository. A new version replaces the old one on
the next weekly check in the app.

The photos show the manufacturers' own packaging and remain theirs; they are used with the manufacturers'
permission as a temporary reference, until the pharmacies' own photos replace them.
