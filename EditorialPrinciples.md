# Editorial Principles

The Tonal Piano Corpus is a practical, machine-readable dataset prepared from publicly available printed editions. It is not a critical edition and does not attempt to reconstruct composers’ intentions or correct historical sources. The purpose of the corpus is to provide a consistent, transparent, and computationally usable representation of tonal keyboard notation.

---

## 1. Source Material

All works were engraved from printed editions available through standard library access. No manuscript sources were consulted. The TIFF scans included in each composer folder preserve the exact readings of the printed sources.

---

## 2. Scope of Editorial Intervention

The engraved files reproduce the printed sources as closely as possible. Editorial intervention is limited to:

- correcting **obvious internal contradictions** (e.g., mismatched accidentals within a repeated pattern)
- resolving **engraving errors** that would prevent computational parsing
- ensuring **consistent part?wise alignment** in polyphonic textures

All such interventions are documented in *EditorialNotes.md*.

---

## 3. Notational Consistency

The following normalizations were applied uniformly:

- consistent beaming according to meter  
- consistent placement of slurs and articulations  
- uniform treatment of ties across system breaks  
- standardized accidentals in repeated patterns  
- consistent use of courtesy accidentals where required for clarity  

These adjustments do not alter musical meaning; they ensure that the MusicXML files are machine?readable and internally coherent.

---

## 4. Digital Encoding

All works were engraved in Finale and exported to MusicXML. The following conventions were observed:

- one MusicXML file per work  
- UTF?8 encoding  
- explicit accidentals wherever required by the printed source  
- no hidden objects or layout?only markings  
- no playback?only data  

The MusicXML files are intended for analysis, not performance rendering.

---

## 5. Limitations

The corpus reflects the limitations of the printed editions used. It does not claim to represent authoritative readings, urtext principles, or historically informed editorial practice. Users requiring critical evaluation of sources should consult scholarly editions.

---

## 6. Transparency

All departures from the printed sources are documented in *EditorialNotes.md*.  
All printed readings are preserved in the TIFF scans included with each work.