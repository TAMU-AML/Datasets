This folder contains the datasets used in the paper: `The temporal overfitting problem with applications in wind power curve modeling`.

There are two datasets used in the paper:

1. Main case study datasets: Main case study datasets comprise of four wind turbine data, two inland and two offshore. These datasets are not a part of this repository, but are available on the book webiste of Ding(2019) at the URL: https://aml.engr.tamu.edu/book-dswe/dswe-datasets/ (Dataset 6). The data are in the `CSV` file format with the first row as the headers. The meaning of the headers for the inland turbines (WT1 and WT2) are as follows:

    - `time`: time stamp for the observations.
    - `V` : wind speed in m/s.
    - `Vadj :` adjusted wind speed using the air density correction. This column is not used in the paper.
    - `D` : wind direction in degrees.
    - `rho` : air density in kg/m<sup>3</sup>.
    - `I` : turbulence intensity.
    - `S` : wind shear. 
    - `normPw` : normalized power.

    For the offshore turbines, wind shear `S` is replaced by humidity `H`, and the rest of the variables stay the same.

2. Extended case study datasets: Extended case study datasets contain thirty inland wind turbine data. These datasets are available in the sub-folder `extended_case_study_datasets/`. These datasets are also in the `CSV` file format with the column headers in the first row. The column headers are:
    
    - `turbine_id`: anonymized turbine id; same as the turbine number in the file name.
    - `time_stamp`: time stamp for the observations.
    - `wind_spedd`: wind speed in m/s.
    - `wind_direction`: wind direction in degrees.
    - `air_density` : air density in kg/m<sup>3</sup>.
    - `turbulence_intensity` : turbulence intensity.
    - `wind shear` : wind shear. 
    - `power` : normalized power.
    - `outlier` : a binary value (0/1) indicating whether the data point is an outlier. `0` is equal to `FALSE`, that is, the data point is not an outlier. Similarly, `1` implies an outlier data point.



