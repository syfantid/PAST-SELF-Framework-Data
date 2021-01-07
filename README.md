# PAST-SELF-Framework-Data
The data file for the PAST SELF Framework for the design and evaluation of Self-tracking Technology (ST) for Health Behavior Change (HBC) and User Engagement (UE). Edits of existing fields are not supported on the file. However, additions based on new, published literure are highly encouraged.

Cite as:   
Sofia Yfantidou. (2020, October 2). syfantid/PAST-SELF-Framework-Data: Paper Release (Version v1.0). Zenodo. http://doi.org/10.5281/zenodo.4063377

## Column Definitions
This xlsx file contains the data related to our literature review "An mHealth Systematic Review: A Design and Evaluation Framework for Behavior Change and User Engagement in Self-Tracking" (Yfantidou et al., 2020). Specifically it contains information about 546 papers (117 included and 429 excluded) in the field of ST for HBC and UE. For the excluded papers it exhibits the exclusion criteria that led to its exclusion. The coding of the column "Exclusion Criteria" is as follows:
* NPR: Not a peer-reviewed paper
* NE: Paper not in English language
* NI: Paper does not include an intervention or longitudinal study
* NUI: Paper does not include an intervention or longitudinal study utilizing a ubiquitous device, such as a wearable device or smartphone
* NM: Paper does not include measurable outcomes or does not clearly present them
* DD: Paper comes from a different HBC domain, e.g., UE in online shopping
* NPAO: Paper does not present Physical Activity (PA) related outcomes, e.g. smoking cessation, weight loss, etc.
* NS: Paper does not rely on sensing/ubiquitous device for data acquisition
* OP: Paper utilizes an out-of-the-box product without any additional intervention features
* NDF: Paper does not provide a clear description of the intervention features
* D: Paper is published in multiple venues (duplicate)

For the included papers, we extract certain features if applicable as follows:
* General: This category includes general features of the paper utilized for quantitative analysis
  - Conference: The conference the paper was submitted
  - Journal: The journal the paper was submitted 
  - Publisher / Organizer: The publisher of the journal or the organizer of the conference the paper was submitted to
  - Year: The publication year
  - Country: The country(-ies) of the authors' universities
* Data Collection: The features related to the data collection process of the interventions
  - Data Sources: The sources of the intervention's data, e.g., ubiquitous devices, questionnaires, interviews, etc.
  - Self-reported Data: The self-reports the participants completed as part of the intervention, e.g., questionnaires
  - Measured Data - PA: The measured quantities related to PA coming from ubiquitous devices, e.g., step count
  - Measured Data - UE: The measured quantities related to UE coming from ubiquitous devices, e.g., wear-time
  - Measured Data - Metadata: The measured metadata coming from ubiquitous devices, e.g., geolocation
  - Wearables: The type and brand of wearable device utilizedfor the intervention
  - Mobile Apps: The name of the mobile app utilized for the intervention
  - Intervention Duration (in weeks): The intervention duration in number of weeks
  - Sample Size: The number of participants in the study
  - Male: The number of male participants in the study
  - Sample Mean Age: The sample's mean age
  - Special Criteria: Any special criteria for the recruitment of the participants, e.g., specific demographics
* Theoretical Background: Features related to the theoretical Foundations behind the intervention
  - Theoretical Framework: The theoretical frameworks, e.g., psychological theories, that have been utilized for the design of the intervention
  - PSD - Primary Task Support: The Primary Task Support elements from the PSD frameowrk and how they have been implemented in the specific intervention
  - PSD - Dialogue: The Dialogue elements from the PSD frameowrk and how they have been implemented in the specific intervention
  - PSD - System Credibility: The System Credibility elements from the PSD frameowrk and how they have been implemented in the specific intervention
  - PSD - Social Support: The Social Support elements from the PSD frameowrk and how they have been implemented in the specific intervention
  - Negative Results from Design Strategies: The negative results of the intervention in the format "PSD technique -> -(-) PA or UE" depending on how much decrease the technique has led to.
  - Positive Results from Design Strategies: The positive results of the intervention in the format "PSD technique -> +(+) PA or UE" depending on how much increase the technique has led to.
  - Neutral Results from Design Strategies: The neutral results of the intervention in the format "PSD technique -> ~ PA or UE" 
* Evaluation: Features related to the outcomes of the intervention
  - Independent Variable: The PSD and other techniques utilized in the intervention (for the number coding check below)
  - UE Measures: The type of UE outcome measures, e.g., wear-time
  - PA Measures: The type of PA outcome measures, e.g., step count
  - Positive Result: A number from the set [-1, -0.5, 0, 0.5, 1], depending on the success of the intervention (-1 for fully negative result and 1 for fully positive result).
  - Control N: Number of participants in the control group
  - Intervention N: Number of participants in the intervention group
  - Baseline: Outcomes of the baseline measurements in control and intrvention groups
    - Control UE: The baseline UE measurements of the control group
    - Intervention UE: The baseline UE measurements of the intervention group
    - Control PA: The baseline PA measurements of the control group
    - Intervention PA: The baseline PA measurements of the intervention group
  - Post-Intervention: Outcomes of the post-intervention measurements in control and intrvention groups		
    - Control UE: The post-intervention UE measurements of the control group
    - Intervention UE: The post-intervention UE measurements of the intervention group
    - Control PA: The post-intervention PA measurements of the control group
    - Intervention PA: The post-intervention PA measurements of the intervention group
  - Mean Change: The mean change between baseline and post-intervention outcomes (IA) in control and intrvention groups		
    - Control UE: The UE mean change of the control group
    - Intervention UE: The UE mean change of the intervention group
    - Control PA: The PA mean change of the control group
    - Intervention PA: The PA mean change of the intervention group

## PSD Techniques Mapping
This mapping is utilized by multiple columns in the file.  

technique,name,category  
1: Reduction,Primary Task Support  
2: Tailoring,Primary Task Support  
3: Tunneling,Primary Task Support  
4: Personalization,Primary Task Support  
5: Self-monitoring,Primary Task Support  
6: Simulation,Primary Task Support  
7: Rehearsal,Primary Task Support  
8: Praise,Dialogue  
9: Rewards,Dialogue  
10: Reminders,Dialogue  
11: Suggestion,Dialogue  
12: Similarity,Dialogue  
13: Liking,Dialogue  
14: Social Role,Dialogue  
15: Trustworthiness,System Credibility  
16: Expertise,System Credibility  
17: Surface Credibility,System Credibility  
18: Real-world Feel,System Credibility  
19: Authority,System Credibility  
20: Third-party Endorsements,System Credibility  
21: Verifiability,System Credibility  
22: Social Learning,Social Support  
23: Social Comparison,Social Support  
24: Normative Influence,Social Support  
25: Social Facilitation,Social Support  
26: Cooperation,Social Support  
27: Competition,Social Support  
28: Recognition,Social Support  
29: Goal Setting,Other  
30: Punishment,Other  
31: Variability,Other  
32: General Information,Other  

[![DOI](https://zenodo.org/badge/295764967.svg)](https://zenodo.org/badge/latestdoi/295764967)

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
