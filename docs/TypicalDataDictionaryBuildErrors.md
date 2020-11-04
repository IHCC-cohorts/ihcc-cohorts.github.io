## Typical errors when building data dictionaries

- `Parent` label does not appear in the `Label` column. Every term mentioned in the the `Parent` column must also be mentioned in the `Label` column somewhere (i.e. you can't declare that something is a parent that is not also a term itself.)
- Make sure all Python dependencies are installed before you run `make` commands directly, if not using a dedicated DROID server. All Python requirements can be found in [requirements.txt](https://github.com/IHCC-cohorts/data-harmonization/blob/master/requirements.txt).


