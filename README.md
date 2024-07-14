# Google Mobility Data for Philippines in 2021-2022
A visualization of Google Mobility Data[^1] for Ph 2021-2022

## Description
This project was initially for a presentation. I tried replicating what Hugh Sheehy[^2] did for their Looker Dashboard, but it was not an exact replica due the the difference in y-axis values. In my visualization, I used the `percent change` while Sheehy used something else.

Here is the original visualization by Sheehy:
![sheehy's version.png](https://github.com/Altan-X/mobility-data/blob/main/docs/sheehy's%20version.png)

This is the one I made:
![mobility data percent change.png](https://github.com/Altan-X/mobility-data/blob/main/docs/mobility%20data%20percent%20change.png)

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
    └── mobility data.iynb                     # Jupyter notebook code
├── LICENSE
├── README.md                                  # Mobility Data README
└── .gitignore                                 # Git ignore file

```

## References
[^1]: [Google. (2022, October 17). Covid-19 Community Mobility Report](https://www.google.com/covid19/mobility/)
[^2]: [Sheehy, Hugh. (2024, July 12). Covid 19 - Google Global Mobility Report](https://lookerstudio.google.com/reporting/a529e043-e2b9-4e6f-86c6-ec99a5d7b9a4/page/yY2MB?s=ho2bve3abdM)  
