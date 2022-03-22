# Introduction-to-Power-BI---Independent-Project

## Background Information<br />
[Karamoja](https://en.wikipedia.org/wiki/Karamoja) is the most food-insecure region of Uganda. One of the main reasons
is the low productivity level of the crops due to intense droughts and pest and
disease outbreaks.<br />
In Karamoja, several NGOs provide technical support and farm inputs to the
farmers experiencing meager yields. Though, they lack visibility into the overall
state of the region and often need to rely on some very local sources of
information to prioritize their activities.<br />
Dalberg Data Insights (DDI) has requested you to develop a new food security
monitoring tool to support the decision-making of one of those NGOs active in
Karamoja.<br />
To do so, Dalberg Data Insights developed a methodology to remotely measure
the yield of the two main staple crops of the region (i.e., sorghum and maize)
based on satellite images. The agri-tech team just ran the model for the 2017
crop season.

As a Data Scientist, the agri-tech team is asking you to develop an interactive
visualization tool of the results for this first crop season. This visualization tool
you will develop will be used as a first mockup of the Food Security Monitoring
tool that DDI will develop for the NGO.<br />
Based on your experience, the team expects you to develop a first draft within
the coming three working days. They give you carte blanche in terms of structure
and functionalities, but they know that the client wants:<br />
● At least a map in the dashboard<br />
● The possibility of visualizing the results by district or sub-county (two
administrative levels used by the NGO)<br />

## Dataset Overview<br />
Dataset Source [Link](https://archive.org/download/data_20190829/DATA.zip)

#### Shapefiles
      ■ Boundaries of Uganda Subcounties
      ■ Boundaries of Uganda Districts
      ■ Crop Type Map for Sorghum (i.e., position of the Sorghum fields)
      ■ Crop Type Map for Maize
      
#### Tables
    ■ Yield and Population per Subcounty
            ■ POP: total population for the sub-county.
            ■ S_Yield_Ha: average yield for sorghum for the sub-county
            (Kg/Ha).
            ■ M_Yield_Ha: average yield for maize for the sub-county
            (Kg/Ha).
            ■ Crop_Area_Ha: total crop area for the sub-county (Ha)
            ■ S_Area_Ha: total sorghum crop area for the sub-county (Ha)
            ■ M_Area_Ha: total maize crop area for the sub-county (Ha)
            ■ S_Prod_Tot: total productivity for the sorghum for the
            sub-county (Kg).
            ■ M_Prod_Tot: total productivity for the maize for the
            sub-county (Kg).
    ■ Yield and Population per District.
