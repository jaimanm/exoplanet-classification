# exoplanet-classification

## Concept
This is a quick project that I made to apply what I learned about data engineering and logistic regression to real-world data.
I'm using scikit-learn's LogisticRegression model to help classify discovieries by Kepler as CANDIDATE for an exoplanet or a FALSE POSITIVE discovery.

## Data
My dataset was pulled directly from the [NASA Exoplanet Archive](http://exoplanetarchive.ipac.caltech.edu)

Below are the descriptions for each column:
kepid:          KepID <br>
kepoi_name:     KOI Name <br>
kepler_name:    Kepler Name <br>
koi_disposition: Exoplanet Archive Disposition <br>
koi_pdisposition: Disposition Using Kepler Data <br>
koi_score:      Disposition Score <br>
koi_fpflag_nt:  Not Transit-Like False Positive Flag <br>
koi_fpflag_ss:  Stellar Eclipse False Positive Flag <br>
koi_fpflag_co:  Centroid Offset False Positive Flag <br>
koi_fpflag_ec:  Ephemeris Match Indicates Contamination False Positive Flag <br>
koi_period:     Orbital Period [days] <br>
koi_time0bk:    Transit Epoch [BKJD] <br>
koi_impact:     Impact Parameter <br>
koi_duration:   Transit Duration [hrs] <br>
koi_depth:      Transit Depth [ppm] <br>
koi_prad:       Planetary Radius [Earth radii] <br>
koi_teq:        Equilibrium Temperature [K] <br>
koi_insol:      Insolation Flux [Earth flux] <br>
koi_model_snr:  Transit Signal-to-Noise <br>
koi_tce_plnt_num: TCE Planet Number <br>
koi_tce_delivname: TCE Delivery <br>
koi_steff:      Stellar Effective Temperature [K] <br>
koi_slogg:      Stellar Surface Gravity [log10(cm/s**2)] <br>
koi_srad:       Stellar Radius [Solar radii] <br>
ra:             RA [decimal degrees] <br>
dec:            Dec [decimal degrees] <br>
koi_kepmag:     Kepler-band [mag] <br>

## Results
The model had around 95% accuracy on the test data, which is very good. I see this as an absolute win!
