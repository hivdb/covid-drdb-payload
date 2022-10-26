# COVID-DRDB Database

COVID-DRDB is created by the HIVDB team of Stanford University. It includes
resistance data of SARS-CoV-2 for convalescent plasma, vaccinee plasma and
monoclonal antibodies collected from published peer-reviewed/pre-print studies.
The database also provides meta-data including but not limited to:

- MAb targets, classes, epitopes
- Vaccine types, developers, efficacy
- Reference/article titles, DOIs, URLs
- Mutation references (Wuhan-Hu-1, [NC_045512.2](https://www.ncbi.nlm.nih.gov/nuccore/1798174254))

## Access DRDB

The access to DRDB database is open to the public. An end user can access this
database and summarize data via the [web
interface](https://covdb.stanford.edu/page/susceptibility-data/). This interface
is open source at [repository
hivdb/chiro-frontend](https://github.com/hivdb/chiro-frontend).

A SQLite dump file is created (almost) daily and can be retrieved from [Release
page of this repository](https://github.com/hivdb/covid-drdb-payload/releases).
Raw CSV data are available in this repository folder
[`tables`](https://github.com/hivdb/covid-drdb-payload/tree/master/tables).

The code to validate the raw CSV data and generate SQLite dump file is also open
source on GitHub: [hivdb/covid-drdb](https://github.com/hivdb/covid-drdb).


## Contribute to DRDB

Any contributions are welcome here. Currently, we accept new study suggestions,
new data pull requests, feature requests, and bug/error reports. We are still 
working on providing a pull-request pipeline for outside contributors to add 
data into our database directly.

- [New study suggestions][NEWREF]
- Feature requests:
  - [Database][DBFR], adding new tables, new columns, etc.
  - [Website][WFR] (https://covdb.stanford.edu/search-drdb/)
- Bug/error reports:
  - [Database][DBBUG]
  - [Website][WBUG]
  

[DBFR]: https://github.com/hivdb/covid-drdb/issues/new?assignees=philiptzou&labels=enhancement&title=[FR]
[WFR]: https://github.com/hivdb/chiro-frontend/issues/new?assignees=philiptzou&labels=enhancement&title=[FR]
[NEWREF]: https://github.com/hivdb/covid-drdb-payload/issues/new?assignees=&labels=enhancement&template=suggest-new-study.md&title=%5BNew%5D
[DBBUG]: https://github.com/hivdb/covid-drdb-payload/issues/new?assignees=KaimingTao%2C+philiptzou&labels=bug&template=data-error-report.md&title=%5BBUG%5D
[WBUG]: https://github.com/hivdb/chiro-frontend/issues/new?assignees=philiptzou&labels=bug&title=[BUG]

### Contribute by submitting data

We accept data submission by using Github pull requests. You can submit your data or
you can work on the studies in the issue page. You can fork the repository, extract data, 
format the data into each table, then create a pull request to the main repository. 
We will regularly check pull requests, make comments, and merge them into main branch.

For more details, please read the [wiki page](https://github.com/hivdb/covid-drdb-payload/wiki) about how we curate the database.
