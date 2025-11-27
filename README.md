# HCP360-Glasser-atlas-mapping-Yeo-7-subnetwork
hcp360 to yeo 7 method and mapping file

## step1: get yeo
`python fetch_yeo.py`

## step2: get hcp360
[hcp link](https://github.com/brainspaces/glasser360)

## step3: resample hcp360 to yeo size
`python resample_hcp2yeo.py`

## step4: mapping hcp360 to yeo
`python mapping_hcp2yeo.py`
