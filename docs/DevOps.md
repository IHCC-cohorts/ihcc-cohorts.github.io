## DevOps instructions

The IHCC data harmonization infrastructure comprises the following components:

- ZOOMA: Mapping service, used by the automated data dictionary mapping service 
  - Deploy location: <https://mapping.ihccglobal.app/zooma/>
  - GitHub: <https://github.com/IHCC-cohorts/zooma>
  - Dockerhub: <https://hub.docker.com/r/ihcc/zooma-web>
- OLS: term browser for data dictionary terms as well as GECKO and DUO.
  - Deploy location: <https://registry.ihccglobal.app/index>
  - GitHub: <https://github.com/IHCC-cohorts/OLS>
  - Dockerhub: <https://hub.docker.com/r/ihcc/ols-web>
- OxO: Mapping browswer that shows how the data dictionaries are mapped to the various OBO ontologies under the GECKO umbrella
  - Deploy location: <https://mapping.ihccglobal.app/>
  - GitHub: <https://github.com/IHCC-cohorts/OXO>
  - Dockerhub: <https://hub.docker.com/r/ihcc/oxo-web>
- DROID: The tool used by the *IHCC Data Steward* for mapping and building new data dictionaries
  - Deploy location: <https://droid.ontodev.com/IHCC> (currently hosted by [Knocean](http://knocean.com/))
  
The tools suite and how it is deployed is documented in the (private) [IHCC config repo](https://github.com/IHCC-cohorts/ihcc-config/blob/master/README.md).
