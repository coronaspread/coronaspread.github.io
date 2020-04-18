---
title: Data Layer
permalink: /docs/data-layer/
---

The data layer downloads datasets and harmonizes each dataset, so that it is consistent to a defined data model.
Finally the datasets can easily be merged into one complete dataset.

![Data Layer]({{ "/assets/img/data_layer.png" | relative_url }} "Data Layer")

We will also enrich the datasets with population and measure datasets, which we have started to collect.

Regarding the implementation:
We created a single CountryManager which serves as a singel point of entry for a user of the software.
It provides caching and detailed checks that confirm that the individual data harmonization functions are implemented correctly.
