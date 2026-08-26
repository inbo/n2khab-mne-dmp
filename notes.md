# Notes

Reference: https://quarto.org/docs/books/

For creation of a new subfolder:

```sh
#| eval: false

quarto create project book mnm-dmp-v2

# git init
# echo "*.png" >> .gitignore
```


The book can be rendered by navigating to the git folder and executing

```sh
#| eval: false
quarto render <subfolder>
```


# Questions for Discussion
## organizational

+ [ ] license: (which) should we add to the repo? -> CC-BY 4.0 per recommendation on DMP template
+ [ ] add this repo to <https://github.com/inbo/n2khab-monitoring>
+ [ ] potentially add RSE, STAT and MO's as authors? -> rather not, but distribute afterwards "FYI"

(done)
+ [x] primary/secondary data categorization
+ [x] dynamic updates of and links to data storage and repositories
+ [x] replace / mention REP
+ [x] link to project protocols
+ [x] links to github repos are useful and recommended
+ [x] links to documentation
  - <https://github.com/inbo/n2khab-monitoring>
  - <https://inbo.github.io/mnedesigndata/reference>
+ [x] but add disclaimer: date of the data / status as of date of DMP
+ [x] capitalize WATINA


## `_quarto.yml`
+ [ ] adjust date and title.version 


## index

+ [ ] add DOI if possible

## 01_information

+ [x] update version
+ [x] note major changes

## 02_datasets

+ [ ] `datasets/010_fieldassessment.qmd` is that loceval?
+ [ ] `datasets/020_samplingframe.qmd` headline sounds "REP", but description says "loceval"
+ [ ] is ANB still involved? (datasets `010_fieldassessment.qmd` and `020_samplingframe.qmd`)
+ [ ] new: Fieldwork Organization and Auxiliary Data
+ [ ] `datasets/110_sampleunit_attributes.qmd` distinction from fieldwork apps? publication ambitions?
+ [ ] `datasets/310_surfacewater_quality.qmd` are the site/observation estimates still accurate?

+ [x] ++ protocols
+ [x] split surface water level (RTK) from groundwater level? -> yes, rework
