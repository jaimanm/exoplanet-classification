# exoplanet-classification

## Concept
This is a quick project that I made to apply what I learned about data engineering and logistic regression to real-world data.
I'm using scikit-learn's LogisticRegression model to help classify discovieries by Kepler as CANDIDATE for an exoplanet or a FALSE POSITIVE discovery.

## Data
My dataset was pulled directly from the [NASA Exoplanet Archive](http://exoplanetarchive.ipac.caltech.edu)

Below are the descriptions for each column:
kepid:          KepID
kepoi_name:     KOI Name
kepler_name:    Kepler Name
koi_disposition: Exoplanet Archive Disposition
koi_pdisposition: Disposition Using Kepler Data
koi_score:      Disposition Score
koi_fpflag_nt:  Not Transit-Like False Positive Flag
koi_fpflag_ss:  Stellar Eclipse False Positive Flag
koi_fpflag_co:  Centroid Offset False Positive Flag
koi_fpflag_ec:  Ephemeris Match Indicates Contamination False Positive Flag
koi_period:     Orbital Period [days]
koi_time0bk:    Transit Epoch [BKJD]
koi_impact:     Impact Parameter
koi_duration:   Transit Duration [hrs]
koi_depth:      Transit Depth [ppm]
koi_prad:       Planetary Radius [Earth radii]
koi_teq:        Equilibrium Temperature [K]
koi_insol:      Insolation Flux [Earth flux]
koi_model_snr:  Transit Signal-to-Noise
koi_tce_plnt_num: TCE Planet Number
koi_tce_delivname: TCE Delivery
koi_steff:      Stellar Effective Temperature [K]
koi_slogg:      Stellar Surface Gravity [log10(cm/s**2)]
koi_srad:       Stellar Radius [Solar radii]
ra:             RA [decimal degrees]
dec:            Dec [decimal degrees]
koi_kepmag:     Kepler-band [mag]

## Results
The model had around 95% accuracy on the test data, which is very good. I see this as an absolute win!
