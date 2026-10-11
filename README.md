# Tennessee Valley cold front, 18–19 October 2025

ERA5/MetPy case study of a shallow cold front over north Alabama and southern Middle Tennessee.

At 06 UTC 18 October the Valley has no trough, no moisture gradient, and no front. On 19 October, 850 hPa cooling of about 8–9 K in 6 hours arrives from the northwest between 12 and 18 UTC. At 18 UTC that cooling sits on cold advection, frontogenesis, a mixing-ratio drop, and a southwest-to-northwest wind shift. A Madison sounding and a northwest–southeast section both confine the cold air to below about 700 hPa, with a dry slot above.

The notebook stores the figures, so they render on GitHub without a rerun. To rerun, use Colab or a local kernel with the packages in `requirements.txt`. Data are the public ARCO-ERA5 store (`gs://gcp-public-data-arco-era5/ar/full_37-1h-0p25deg-chunk-1.zarr-v3`); no Copernicus account is required. Subset before any `.load()`.

Public sounding archives did not return a KHSV profile for these hours, so the sharpness of the observed inversion is unresolved.

## License

Code in this repository is MIT. ERA5 is the Copernicus Climate Change Service reanalysis (Hersbach et al., 2020). The cloud copy is the Google Research ARCO-ERA5 public dataset. Neither dataset is relicensed here.
