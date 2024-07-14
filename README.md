# Google Mobility Data for Philippines in 2021-2022
A visualization of Google Mobility Data[^1] for Philippines 2021-2022

## Description
This project was initially for a presentation. I tried replicating what Hugh Sheehy[^2] did for their Looker Dashboard, but it was not an exact replica due the the difference in y-axis values. In my visualization, I used the `percent change` while Sheehy used something else.

Here is the original visualization by Sheehy[^2]:
![sheehy's version.png](https://github.com/Altan-X/mobility-data/blob/main/docs/sheehy's%20version.png)

The highest in mobility trend is the Grocery & Pharmacy percent change (colored in red) according to Sheehy's dashboard.

Comparing their graph with mine:
![mobility data percent change.png](https://github.com/Altan-X/mobility-data/blob/main/docs/mobility%20data%20percent%20change.png)

The highest mobility trend is Parks followed by Grocery and Pharmacy.  

In the Ph Mobility Report[^3], the highest mobility trend is the Grocery & pharmacy with an 80% value higher than baseline. This result agrees with Sheehy's visualization. It turns out I have not transformed the original data. This is a point of improvement for me and for future work. 

## Contents
```
mobility-data/
├── docs/
    ├── 2022-10-15_PH_Mobility_Report_en.pdf   # Summary report of Google Ph Mobility Report
    ├── mobility data percent change.png       # My visualization
    └── sheehy's version.png                   # Sheehy's visualization
├── src/                                       # Source code directory
    ├── Data/                                  # Ph mobility data in csv
      ├── 2021_PH_Region_Mobility_Report.csv
      └── 2022_PH_Region_Mobility_Report.csv          
    └── mobility_data.ipynb                    # Jupyter notebook code
├── LICENSE
├── README.md                                  # Mobility Data README
└── .gitignore                                 # Git ignore file

```

[^1]: [Google. (2022, October 17). Covid-19 Community Mobility Report](https://www.google.com/covid19/mobility/)
[^2]: [Sheehy, Hugh. (2024, July 12). Covid 19 - Google Global Mobility Report](https://lookerstudio.google.com/reporting/a529e043-e2b9-4e6f-86c6-ec99a5d7b9a4/page/yY2MB?s=ho2bve3abdM)  
[^3]: [Ph Mobility Report](https://github.com/Altan-X/mobility-data/blob/main/docs/2022-10-15_PH_Mobility_Report_en.pdf)
