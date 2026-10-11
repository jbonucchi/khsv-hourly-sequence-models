# Small sequence models on an hourly station series

Next-hour temperature at KHSV from a 24-hour window of temperature, dewpoint, wind speed, and sea-level pressure. Persistence, a temporal CNN, and a small 1D Transformer.

The Transformer beats persistence by 0.24°F. That gain is the diurnal cycle: it sits on the morning rise and the evening drop, and it vanishes when each hour is measured against its training-set mean (−0.008°F). On dewpoint the same model loses to persistence by 0.20°F. At one station and a one-hour horizon, the last observation plus the daily cycle is the forecast.

Figures are stored in the notebook, so they render on GitHub without a rerun. Data are the Iowa Environmental Mesonet ASOS archive for HSV, 2024. No account. Packages are in `requirements.txt`.

## License

Code in this repository is MIT. The observations are from the Iowa Environmental Mesonet and are not relicensed here.
