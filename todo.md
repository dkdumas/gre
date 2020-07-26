
# General

- [x] Make a really cool project
- [ ] Check all the keywords for one standard getty url
- [ ] Check for all comments containing some mention of "cross references", add links to relevant pages
- [ ] Go through punchlist for each article
- [ ] Get province information into general province page (somehow)
- [ ] Get keywords into tags list in header (as in bancroft example)
- [ ] Get geographic regions into sidebar using categories list (as in bancroft)
- [ ] Put `lead:` in the header for each article to make loglines/subtitles (e.g. Dalmatia/salona/salona_tomb...)
- [ ] Check that all keywords are in controlled vocab (Programmatically)
- [ ] Figure out why there are so many unattached images (e.g. Achaea Nemea)
- [ ] Deal with empty stuff in headers
- [ ] Should "urban villas" be removed and (if necessary) replaced with "villae urbanae"?
- [ ] Deal with all smart quotes
- [ ] Fix any quotes in `figure` attributes
- [ ] Redo all pub dates as YMD
- [ ] Implement [LOC Datetime format](https://www.loc.gov/standards/datetime/)

# Article Punchlist

- Title in title case with spaces?
- Province `relref` correct?
- Location
  - folder `relref`
  - Pleiades ID
- Keywords, separated by newline (`\` at end of line)
- Sublocation `relref` present? -> comment out for now
- Pleiades ID
  - Numbers in link?
  - `"(Pleiades)"` in link? -> delete
  - Two links present, one with `relref` -> delete `relref`
- figures linked correctly?
- check all `ref`s to other gardens, should be `relref`s

# Articles in need of a second look

- achaea/athens/athens_neoplatonic..., no author
- achaea/corinth/corinth_circus, images with no links
- achaea/eua/villa..., editor seems to be author, no editor/author listed
- achaea/athens/athenian_schools, need to make sure this info gets in the right places
- ger sup/dietikon, no orcid for Christa Ebnöther
- ger sup/vallon, two map images are broken, replace with new


# Image cropping and straightening

- [x] achaea
- [ ] britannia
- [ ] dacia_traiana
- [ ] dalmatia
- [ ] germania_inferior
- [ ] germania_superior
- [ ] macedonia
- [ ] pannonia