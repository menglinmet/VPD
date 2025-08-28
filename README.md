# VPD analysis for "Hot droughts in the Amazon: A window to a future hypertropical climate"

ESM used in this analysis: CNRM-CERFACS.CNRM-CM6-1-HR (3-hour resolution), MOHC.HadGEM3-GC31-MM (3-hour resolution), NOAA-GFDL.GFDL-ESM4 (3-hour resolution), NCAR.CESM2 (6-hour resolution). We also used DOE’s E3SM (3-hour temporal resolution, not included in CMIP6) for this analysis. 

calculate_VPD.ipynb: calculate VPD based on Ta and RH, for historical and SSP simulation 

calculate_threshold.ipynb: calculate threshold for extreme VPD days based on field observation and adjusted using a quantile approach

plot_projection.ipynb: figures used in the papers, including time series of extreme VPD days over years and over months. 
