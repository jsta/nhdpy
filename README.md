# nhdpy 

A python port of the [nhdR](https://jsta.github.io/nhdR) package for querying, downloading, and networking the [National
Hydrography Dataset (NHD)](https://nhd.usgs.gov/) dataset.

## Installation

```
conda env create -n nhdpy -f environment.yml
make install
```

## Usage

``` python
import nhdpy

nhdpy.nhd_get("DC")
```
