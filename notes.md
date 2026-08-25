# Notes


Reference: https://quarto.org/docs/books/

```sh
quarto create project book mnm-dmp-v2

git init
echo "*.png" >> .gitignore
```


The book can be rendered by navigating to the git folder and executing

```sh
quarto render <subfolder>
```


# TODO
## organizational

+ license: (which) should we add to the repo? -> CC-BY 4.0
+ add this repo to <https://github.com/inbo/n2khab-monitoring>
+ primary/secondary data categorization
+ dynamic updates of and links to data storage and repositories
+ replace / mention REP
+ link to project protocols
+ links to github repos are useful and recommended
+ links to documentation
  - <https://github.com/inbo/n2khab-monitoring>
  - <https://inbo.github.io/mnedesigndata/reference>
+ but add disclaimer: date of the data / status as of date of DMP
+ capitalize WATINA
+ potentially add RSE, STAT and MO's as authors


## `_quarto.yml`
+ adjust date and title.version 


## index
add DOI if possible

## 01_information

+ update version
+ note major changes

## 02_datasets

+ `datasets/010_fieldassessment.qmd` is that loceval?
+ `datasets/020_samplingframe.qmd` headline sounds "REP", but description says "loceval"
+ is ANB still involved? (datasets `010_fieldassessment.qmd` and `020_samplingframe.qmd`)
+ new: Fieldwork Organization and Auxiliary Data
+ `datasets/110_sampleunit_attributes.qmd` distinction from fieldwork apps? publication ambitions?
+ `datasets/310_surfacewater_quality.qmd` are the site/observation estimates still accurate?

+ ++ protocols
+ split surface water level (RTK) from groundwater level? -> yes, rework
