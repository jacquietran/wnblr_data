# wnblr_data

A store of data sets for WNBL game stats, called upon by the {wnblr} R package.

:basketball: :zap: The 2021 / 2022 season started on Dec 5, 2021 and is currently underway. The data stored in this repo will be updated regularly as games are played. :zap: :basketball:

## Known issues

Note that the data is largely provided "as scraped". These are known issues with data quality:

| Issue | Status |
|---|---|
| Data is missing from some games where it is only partially complete or entirely missing from the FIBA Livestats database. There are several games missing from each of the 2017 / 2018, 2018 / 2019, and 2019 / 2020 seasons. [Click here to view a full listing of missing games.](https://github.com/jacquietran/wnblr/issues/23) | Live stats from these games are not available in the data sets stored here; no further action required as at 2021-12-06. |
| There are issues with data accuracy in terms of team and player minutes, as scraped. Ways I have sought to address these issues through post-scrape data tidying are documented [here](https://github.com/jacquietran/wnblr/issues/31). | The data sets stored here have been tidied as per the linked issue; no further action required as at 2021-12-06. |
| There are erroneous action types assigned to some shots, a data quality issue identified by [@davescroggs](https://www.github.com/davescroggs), in [this issue](https://github.com/jacquietran/wnblr/issues/29). Thanks Dave! | This needs fixing and will be done in mid-December 2021. |