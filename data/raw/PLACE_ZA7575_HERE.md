# Survey microdata goes here (not included)

`analysis/02_multilevel_models.qmd` expects the Eurobarometer 91.4 Stata file at:

```
data/raw/ZA7575.dta
```

This file is not in the repository because GESIS does not allow it to be redistributed.
To get it:

1. Create a free account at https://search.gesis.org
2. Open study **ZA7575** (Eurobarometer 91.4, May 2019): https://search.gesis.org/research_data/ZA7575
3. Download the Stata (`.dta`) data file and save it here as `ZA7575.dta`.

`.gitignore` blocks this file, so it won't be committed by accident.
