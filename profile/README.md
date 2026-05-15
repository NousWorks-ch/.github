# NousWorks.org

![NousWorks.org Cover Art](cover-art-nw.jpg)

As an interface specialist, I connect the logic of complex systems to the physical reality of buildings.
Works published under the NousWorks framework are open source, drawn from daily practice.

## Projects

- **[SIA180-THERMAL-COMFORT.v01](https://github.com/NousWorksHQ/sia180-thermal-comfort)**  
  Interactive visualization of indoor thermal comfort according to the Swiss standard SIA 180:2014

  IMPLEMENTATION_LOG
  - [DATA_SYNC] Input: Concats raw hourly TS-data to DataFrame.
  - [ALG_ROLLING_MEAN] Logic: Calculates 48h rolling average of temp_oa (SIA 180 baseline).
  - [META_TAGGING] Logic: Maps season labels for color-coded plot traces.
  - [RESULT] Output: Standardized comfort data tuple for Plotly visualization.

- **[WINTERSTROMLUECKE-2050.v01](https://github.com/NousWorksHQ/Winterstromluecke-2050)**  
  Influence of Scenarios for Space Heating and Domestic Hot Water in Buildings on the Winter Electricity Demand of Switzerland in 2050

  IMPLEMENTATION_LOG
  - [DATA_SYNC] Input: Mapping of Kelevitz et al. (2025) study parameters for interactive simulation.
  - [ALG_SIMULATION] Logic: Computation of hourly residual load profiles based on winter weather constraints.
  - [VISUALIZATION] Logic: Real-time update of load-gap deltas using Plotly/JS integration.
  - [RESULT] Output: Comparative scenario analysis of Switzerland's 2050 winter electricity deficit (Gap measurement).

## License

Each repository contains a `LICENSE` file in its root directory. The terms stated therein apply exclusively to that repository.

## Contributing

Issues and pull requests are welcome. Please open an issue first to discuss proposed changes.

## Language

Works in these repositories are published in either English or German.

## System Infrastructure
- Primary Core [nousworks.org](https://nousworks.org)
- Exec & Research Layer [nwsx.org](https://nwsx.org)

## Contact

hello [aet] nousworks.org · [github.com/NousWorksHQ](https://github.com/NousWorksHQ) · [nousworks.org](https://nousworks.org)
