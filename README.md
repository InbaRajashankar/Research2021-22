# Medical device recall prediction project using MAUDE reports
GitHub repository for the research project: "Medical device recall prediction using MAUDE reports".
This project is was undertaken by Krish Inba Rajashankar.


### Helpful Web Links
- MAUDE Information & Data Download Website: https://www.fda.gov/medical-devices/mandatory-reporting-requirements-manufacturers-importers-and-device-user-facilities/about-manufacturer-and-user-facility-device-experience-maude
- MAUDE Online Portal: https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfmaude/search.cfm
- Medican Device Recall Database Online Portal: https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfres/res.cfm


### Overview of 'Trials'
*For a comprehensive 'walk through' of the entire process to import data, process it, create a model, and evaluate it please follow the files in the 'Trial 4' folder in order, which will replicate my results. MAUDE data can be downloaded from the MAUDE Information Website (linked above).*

Trial 1: Original importing and processing of MAUDE data.
Trial 2: More 'polished' importing and cleaning process of MAUDE data.
Trial 3: Importing, Processing, running of models, and evaluation of a dataset of ICD Lead MDRs from before 2013. 
Trial 4: Importing, Processing, running of models, and evaluation of the 'Set 1' and 'Set 2' datasets (2000-2021, ICDs and ICD Leads).


### Disporoportionality Analysis Results Comparison
Final DPA Results for 'Set 1' (above) and 'Set 2' (below) of devices:
![image](https://user-images.githubusercontent.com/95374189/161629281-e95f41c7-ec17-44d0-802e-22453a24d208.png)
![image](https://user-images.githubusercontent.com/95374189/161629312-5032c324-dc43-454b-8fa2-165ab8241358.png)

DPA reults from Dr. Ensign's Dissertation:
<img width="658" alt="Screen Shot 2022-04-04 at 3 49 34 PM" src="https://user-images.githubusercontent.com/95374189/161629688-10874200-fd16-4b6a-9275-8e301b53e016.png">


## Acknowledgements
- I thank Dr. Lisa Ensign for her previous work in the subject area: "USING TEXT MINING OF FDA REPORTS TO INFORM EARLY SIGNAL DETECTION OF CARDIOVASCULAR LEAD RECALLS", which served as a guideline for the work of this project.
- I thank David Beery for his work in creating the library vigipy for use with disproportionality analysis (https://github.com/Shakesbeery/vigipy) and his guidance with the implementation the library.
- I thank Yu-Li Chang for his counsel with this project through his suggestions and advice.
