## Qur'an vs Bible — Lexical Comparison (NLTK + Matplotlib)

Method. Tokenize two corpora (`akjv.txt`, `quran.txt`), remove English stopwords, count tokens with `Counter`. Plot (a) raw top-20, (b) normalized top-20 (percentage of each text) as grouped bars.

Key findings.
- Bible (red) emphasizes historicallegal vocabulary `lord`, `israel`, `king`, `psalm`, `son`, `house`, `land`, plus the legalprophetic marker `shall` (3% of all tokens). Style narrative + covenant law.
- Qur'an (blue) emphasizes universaltheological vocabulary `god` (~5%), `people`, `man`, `day`, `believe`, `punishment`, `messenger`. Style direct doctrinal address + eschatology.
- After normalization, differences are structural, not just length effects. The two texts are distinct rhetorical machines Bible = story of a people, Qur'an = address to humankind.

Figures.
- `figsbible_vs_quran_top20_raw.png`
- `figsbible_vs_quran_top20_normalized.png`

Repro.
- Python 3.11, `nltk`, `matplotlib`.
