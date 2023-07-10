---
title: "Identifying, attributing, and overcoming common data quality issues of manned station observation"
author: "Hunziker et al."
year: "2017"
date: "2022-10-23"
categories:
- Articles
tags:
- Stations
slug: "Hunziker-2017"
---

# Information

**Identifying, attributing, and overcoming common data quality issues of manned
station observations**

- Authors: Hunziker et al.
- Year: 2017
- Journal: International Journal of Climatology
- DOI: 10.1002/joc.5037
- Tags:
    - [Pe] Peru.
    - [WS] Weather stations.
    - [DQ] Data quality.

# Notes

## Introduction

To ensure high quality of climatological analysis (such as trends and extremes),
the need of high quality data is a must. As a consequence, quality control
becomes then an important step to do. However, there is no standard regarding the
techniques to use by weather services or researchers, and some of them do not
produce satisfactory results.

"Although satellite and reanalysis data find widespread use in climate science,
they are not a substitute for ground-based observations due to limitations such
as a lower precision, shorter record lengths, calibration problems, and the need
for _in situ_ data for validation."

Metadata is another type of data that should be collected with the same "care" as
normal data, but this rarely happens, especially in countries like Peru and
Bolivia.

Data quality also depends on the density of the stations network because many
quality control methods depends on the use of neighbor stations. Also, if there
is the need to remove records in a weather stations, the lose of information will
be lower in a high density network.

"According to Vuille et al. (2008), data quality problems and the lack of
long-term weather observations hinder reliable trend analyses in the Central
Andean area. [...] Analysing weather observations from the Central Andean area is
challenging, as the regions is characterized by complex terrain and strong
climate gradients. Consequently, the impacts of climate change vary. This would
require investigations on relatively small spatial scales, but station networks
are sparse in the region."

## Data

Maximum temperature, minimum temperature and precipitation records were collected
from Peru and Bolivia through their respective national weather services.
Additionally, weather stations from the airports of Bolivia was also included.

"Both institutions (SENAMHI of Peru and Bolivia) work with limited resources,
which may increase the risk of the occurrence of quality issues".

"A large fraction of the Central Andean station records cover only a short
measurement period or contain large data gaps. [...] which drastically lowers the
amount of time series suitable for climatological studies."

In Bolivia, there has been a decline in the number of daily observations. This
pattern is present in many developing countries which has a variety of reasons,
like inadequate institutional frameworks and the lack of appreciation of the
worth of long-term data. The situation in Peru is better compared to Bolivia.

Vast majority of the weather stations in the Central Andes are manned. Although
automatic weather stations are know to be better then manned stations in many
variable recording, it needs the continuous maintenance of qualified
professionals, as well as the possibility of being stolen. This becomes
a challenge in the Central Andes where remote access is an impediment for
frequent check ups. Hence, a sudden automatization of the network could carry
a decrease on the quality of the data.

## Metadata generation

Authors propose a 5-step procedure to generate metadata, the first 3 steps can be
done easily since there is no need to be on the site.

1. Check for weather stations "characteristics" discrepancies, like two
   coordinates for the location.
2. Check for surroundings with Google Earth.
3. Extract metadata from the data, like a change in the measurement precision.
4. Screening of original documents. A change in handwriting could point to
   a observer change.
5. Station visits. The history of the station can be reconstructed by
   interviewing in the vicinity or the observer.

## Description of common quality issues

Data issues can come from different sources, have different impacts on the
quality of the data, and can be solved with different methodologies. They
calculated several indices from the Expert Team on Climate Change Detection and
Indices (ETCCDI) to check if the quality issues have an effect over the indices.

Some of the errors are listed:

- Temperature records suffer from missing range temperatures, especially with
  minimum temperature around 0°C due to erroneous reading of the instrument.
- Precipitation can suffer from a "heavy precipitation truncation", where the
  precipitation in much higher of what an instrument container can hold and
  observers do not know how to deal with this issue.
- On the opposite site, precipitation records can suffer from "small
  precipitation gap" where a low range of values can be missing from the records.
  This could be associated with the observers behavior, where they only check
  precipitation under heavy rain and fill the rest of day with 0's, or due to old
  wear-off measure tools that impedes a correct lecture of low values, recurring
  to approximations by the observer.
- Precipitation can suffer from "weekly cycles" where a weird pattern is
  presented in specific days, usually on weekends. This is related to the
  behavior of the observer that can take the weekend off and all the
  precipitation is accumulated until Monday's lecture.
- "Measurement precision inconsistencies" is related to errors in the lecture of
  the instrument. This can be cause by the observers, where they misread the
  decimals and some of them could be missing (like only decimals from 0 to 4 are
  present). The instrument and its measurement tool could also be a problem,
  specially when there is a change in the instrument.
- "Reduced variability in time series segments" can be detected visually where
  the time series is less or more "noisy". Usually, this could happen due to
  error in the readings for external reasons (like the internal conflict in Peru
  in the 80s and 90s) or broken instruments.
- "Transcription errors" may appear during the digitalization process due to
  misreading of the records.

## Discussion

One way to check and correct suspicious records is by doing spatial consistency
test, however, most of the times this cannot be done in Central Andes due to the
complex terrain and sparse station network.

"visual QC allows the detection of all sorts of quality issues, independent of
specific error characteristics. Furthermore, visual QC allows for the assessment
of systematic errors, which is crucial for the further use of the data."

Many of the errors found in the Central Andes are related to the observer, so
a proper training and easy to follow guidelines should improve the quality of the
data. Unfortunately, this only solve future issues, the past errors in the data
will be still present and data users have to deal with it.

The authors suggests four options to restore data:

1. Error assessment: Identifying the type of error can enable users to decide if
   the data is still useful or not.
2. Data correction: If the error is detectable, a correction can be applied to
   restore some data.
3. Time series trimming: In case the error cannot be corrected, consider removing
   those records. The remaining time series could still be useful.
4. Data adjustment for certain analysis. Some approximations of the original data
   can be done for certain analysis.

## Conclusions

"Most of the data quality issues are related to observer errors."

The low density of stations in the Central Andes reduces the performance of data
homogenization methods.

# Bibtex

@article{Hunziker_2017,
    author = {Hunziker, Stefan and Gubler, Stefanie and Calle, Juan and Moreno, Isabel and Andrade, Marcos and Velarde, Fernando and Ticona, Laura and Carrasco, Gualberto and Castellón, Yaruska and Oria, Clara and Croci-Maspoli, Mischa and Konzelmann, Thomas and Rohrer, Mario and Brönnimann, Stefan},
    title = {Identifying, attributing, and overcoming common data quality issues of manned station observations},
    journal = {International Journal of Climatology},
    volume = {37},
    number = {11},
    pages = {4131-4145},
    keywords = {quality control, error attribution, station observations, data rescue, metadata, data homogenization, Bolivia, Peru},
    doi = {https://doi.org/10.1002/joc.5037},
    url = {https://rmets.onlinelibrary.wiley.com/doi/abs/10.1002/joc.5037},
    eprint = {https://rmets.onlinelibrary.wiley.com/doi/pdf/10.1002/joc.5037},
    year = {2017}
}

