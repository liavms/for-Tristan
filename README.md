# for-Tristan

The data is made of Vector and ADCP data (all in NetCDF).

The goal is to create quiver plots from data at all three sites (Gutter, Shark Alley, Green Point) - so they can be compared. 
- Measured via Vector: The Gutter data is split into 3 datasets (3 sampling windows with battery exchange in between)
- Measured via Vector: Shark Alley is split to 2 for the same reason
- Measured via ADCP: Green Point is split to 4 

For now, the Vector data (Gutter & Shark Alley) - are in one notebook (07_Vec_Feather_All-Tristan.ipynb) 
and the ADCP is in another notebook (ADCP_feather_plots.ipynb) 

I managed to combine SA and the Gutter together, just couldn't run the same code with combining the ADCP data from Green Point. 
Also, when i plot the 4 windows on one quiver plot for Green Point (ADCP data), there is something weird in the arrows and they change position when i try to change the y-axis limit. 
