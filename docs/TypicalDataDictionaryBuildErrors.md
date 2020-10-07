## Typical errors when building data dictionaries

- `Parent` label does not appear in the `Label` column. Every term mentioned in the the `Parent` column must also be mentioned in the `Label` column somewhere (i.e. you cant declare that something is a parent that is not also a term itself.)
- Make sure all python dependencies are installed before you run `make` commands directly rather than using a dedicated DROID server. All python requirements can be found in [requirements.txt](https://github.com/IHCC-cohorts/data-harmonization/blob/master/requirements.txt)


