# X-PoSuRe
This is a research project titled - "X-PoSuRe: Pollution Super Resolution For Finegrained Inference Using Multimodal Data Fusion And Deep Learning". 
## Abstract
This study proposes X-PoSuRe - a neural network based regression model for pollution super resolution that is trained to infer fine grained pollution information from coarse grained pollution measurements akin to image super resolution, where a generative model creates high resolution images from low resolution images. The X-PoSuRe model uses Nitrogen Dioxide (NO<sub>2</sub>) as the pollutant of choice and uses other covariates like meteorological data, traffic data, construction activity, accident information, large scale fire incidents, and building footprint information for pollution super resolution. An ensemble of neural network models are trained using gradient boosting technique and the hyper parameters are optimized using grid search methodology. The results show that fine grained NO<sub>2</sub> concentrations can be inferred from the covariates with high accuracy. The proposed X-PoSuRe model provides a promising new and novel method for pollution super resolution from existing low resolution data sources providing pollution measurements and other covariates without the need for deploying expensive measurement equipment over a large area.
## Links to data sources
1. [US EPA air data](https://aqs.epa.gov/aqsweb/airdata/download_files.html#Meta,https://aqs.epa.gov/aqsweb/airdata/download_files.html#Raw) last accessed June 1, 2022
2. [Fire incidents data](https://data.sfgov.org/widgets/nuek-vuh3) last accessed June 1, 2022
3. [California traffic information](https://pems.dot.ca.gov/?dnode=Clearinghouse&type=station_5min&district_id=12&submit=Submit) last accessed June 1, 2022
4. [Building permits information](https://data.sfgov.org/widgets/i98e-djp9,https://data.lacity.org/A-Prosperous-City/Building-Permits/nbyu-2ha9) last accessed June 1, 2022
5. [Weather data](http://weatherapi.com/) last accessed June 1, 2022
6. [ZIP code information from census data](https://catalog.data.gov/dataset/tiger-line-shapefile-2019-2010-nation-u-s-2010-census-5-digit-zip-code-tabulation-area-zcta5-na) last accessed June 1, 2022
7. 
