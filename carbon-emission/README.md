# Carbon Emission Analysis

## Set up
- `.env`: `EMAIL` and `PASSWORD` of the [MCRP](https://mcrp.jwfu.me) website.

## Workflow
1. Call `crawl_data()` to grab your record data, and them store in `data.json`.
2. Call `load_config()` to initialize the config of matplotlib and `data.json`.
3. Generate the chart by `amount_by_dates()` and `percent_by_items()`.