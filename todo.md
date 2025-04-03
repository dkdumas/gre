
# New for Launch on April 15, 2021

- [ ] Set `draft: true` in:
    - [ ] Gallia
    - [ ] Hispania
    - [ ] Other ?
- [ ] Update template with new look and feel
- [ ] Page should have an alphabetical list of authors with hyperlinks to searches for those names, so that if someone clicks on it, it pulls up the search results for that author.

# General

- [x] Make a really cool project
- [ ] Check all the keywords for one standard getty url
- [ ] Check for all comments containing some mention of "cross references", add links to relevant pages
- [x] Go through punchlist for each article
- [x] Get province information into general province page (somehow)
- [x] Get keywords into tags list in header (as in bancroft example)
- [x] Get geographic regions into sidebar using categories list (as in bancroft)
- [x] DONT Put `lead:` in the header for each article to make loglines/subtitles (e.g. Dalmatia/salona/salona_tomb...)
- [ ] Check that all keywords are in controlled vocab (Programmatically)
- [ ] Figure out why there are so many unattached images (e.g. Achaea Nemea has a figure which is not in the proper images folder)
- [x] Deal with empty stuff in headers (by commenting out for now)
- [ ] Deal with empty stuff that is now commented out (by deleting)
- [ ] Should "urban villas" be removed and (if necessary) replaced with "villae urbanae"?
- [ ] Deal with all smart quotes (“”)
- [ ] Fix any quotes in `figure` attributes
- [ ] Redo all pub dates as YMD
- [ ] Implement [LOC Datetime format](https://www.loc.gov/standards/datetime/)
- [x] Add a keyword that means "hasInscription"
- [x] Check for any ">>>>>>" merge conflict stuff in the articles
- [x] Take every heading down one level
- [ ] Add a takedown notice (copy from DCAA/DSCC)
- [x] Suppress empty headings
- [ ] Finish creating documentation
- [x] Change keywords to bulleted list
- [ ] Fix all links that have [text](#) or [text](link)

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

- achaea/corinth/corinth_circus, images with no links (image folder empty -JEM)
- ger sup/dietikon, no orcid for Christa Ebnöther
- ger sup/vallon, two map images are broken, replace with new


# Image cropping and straightening

- [x] achaea
- [x] britannia
- [x] dacia_traiana
- [x] dalmatia
- [x] germania_inferior
- [x] germania_superior
- [x] macedonia
- [x] pannonia

# Pompeii Notes/Issues

- Titles (I.ii.10). Right now if a location doesn't have a specific name, using the I.ii.10 ID.
- [x] Artifacts: TBD on how to note
- [x] Green (additions to entries?). What to do? There appears to be ORANGE now as well.
- [x] Add span style color families to new green parts of entries.
- [ ] Someone should relook over the bibs to see if they know what book the author is referring to, as I can't figure it out with just an author last name.
- [x] Image PATHs might need modifying.
- [x] Note to self: relook over entries and add [statue] keyword.
- [x] Note if it has literary evidence/artifacts.
- [x] Issue: I have found a entry that is House of Epidius Fortunatus (I.iii.3) and another that is I.iii.3. If there is a distinction, should we make it clearer?
- [x] *Aedicula lararium* added as one keyword merged from the two currently listed.
- [x] Should I include excavations dates in date section?
- [x] Province edits for keywords


# TODO 2025

- [x] merge nav-merge into master-new (which will be renamed "main" and become the default branch)
- [ ] reconsider "All Gardens" when browsing by location
- [ ] rename "province" to "gardens"
- [ ] remove unused layouts
- [ ] remove PROVINCE_ID from front matter
- [ ] move province descriptions from garden to separate files?
- [ ] recover gallia aquitania entries? https://github.com/roman-gardens/gre/commit/06b191b293c531a31dca04631b02d031a3a1b32d
- [ ] document how theme files should be edited (not in mainroad directory!)
- [ ] Bibliography first item actually two? https://roman-gardens.github.io/province/italia/rome/regio_x_palatium/domus_augustana/
- [ ] rename 37 JPG files to jpg
- [ ] many dupl images in thugga -- warning!  the "2" image may be older (missing additional label/green patch)
- [ ] convert .tif, .ai, and .ppt files to .jpg or .png
- [ ] move all images to separate repo? -- experiment and assess pros/cons
- [ ] alternative names -- example https://roman-gardens.github.io/test-a/id/5c8aada6d5
