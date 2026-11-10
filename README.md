# Will the Lights Stay On? A Texas Grid Climate-Risk Simulator

**Live site:** https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/

An interactive web page about the Texas power grid (ERCOT) during heat waves and winter freezes. The reader plays a commissioner on the Public Utility Commission of Texas who has to decide where to push next to keep the lights on: weatherize power plants and the gas supply, add battery storage, or slow the growth of new data-center demand.

Four sliders drive a simple, transparent model of one day on the grid:

| Slider | Course concept | What it represents |
|---|---|---|
| Temperature | Hazard | Population-weighted statewide daily average temperature (°F), for a summer heat wave or a winter freeze |
| New demand | Exposure | Extra round-the-clock load (GW), e.g. data centers, added without new power plants |
| Weatherization | Vulnerability | Share of weather-caused power-plant and gas-supply failures that are prevented (0% = 2021 Winter Storm Uri) |
| Battery storage | Adaptation | Installed battery power (GW), 2-hour duration |

The page shows, live as the sliders move:

- a status banner (lights on, grid emergency, or rolling outages)
- key numbers: peak demand, the tightest hour, GW of rolling outages, and homes in the dark
- an hourly supply-vs-demand chart, with a table view
- a "cliff" chart of worst-hour outages vs. temperature, compared against a counterfactual (2021-era equipment in winter, 2023 battery fleet in summer)

It illustrates **Risk = Hazard × Exposure × Vulnerability**. It also shows **correlated failure**: extreme cold raises demand and knocks out supply at the same moment.

Default values and ranges come from ERCOT reports (2025–2026), FERC/NERC's Winter Storm Uri report, Lee & Dessler (2022, *Weather, Climate, and Society*), the Texas State Climatologist's 2024 extreme-weather report, and IEEFA. The full source list and model equations are on the page.

## Files

- `index.html`: the entire site (HTML, CSS and JavaScript in one file, with no external libraries)

## Group members

- Name 1
- Name 2
- Name 3
- Name 4
