# m3_GBM_market
This repository is for generating data cleaning, tidying, and analyzing to understanding the structure of Glioblastoma Multiforme (GBM) market using data from GBM patients.

Following is me guessing what each variable might represent, given the data entries and research on GBM.

MD_ID: Identifier for a medical doctor or healthcare provider.

PATIENT_ID: Identifier for individual patients.

COUNTRY: The country in which the patient is located or being treated. There is only 1 unique entry: US.

Line of therapy: Indicates which line of treatment or therapy the patient is on (first or second).

Year of birth: The birth year of the patient.

Age at diagnosis: The age of the patient at the time of GBM diagnosis.

Gender: Male, Female.

Race: White/Caucasian, Black/African, Spanish/Hispanic/Latino, Asian, and Other.

Adequate caretaker support: Indicates whether the patient has adequate support from caretaker. Likely a binary variable (0 = no, 1 = yes, 9 = unknown).

Travel time to your office < 30 min: Indicates whether the patient's travel time to a medical facility is less than 30 minutes. Likely a binary variable (0 = no, 1 = yes, 9 = unknown).

Patient's level of involvement in GBM: Average level of engagement, Active, and Passive.

Patient's treatment goals: More focused on survival, or More focused on quality of life.

Primary insurance: The primary type of health insurance coverage for the patient. HMO, PPO, Medicare, Medicaid, VA/Other government, Exchange, Uninsured, Other, 9 (likely entry for unknown).

Comorbidity_: Indicates the presence or absence of various comorbid health conditions (0 = no, 1 = yes).

ECOG At 1st Line: Likely related to the patient's health status or performance at the time of the first treatment line.

ECOG At 2nd Line: Similar to the above but for the second treatment line.

ECOG Performance Status is a scale used to assess the functional status of cancer patients, with lower values indicating better functional status and higher values indicating worse functional status.
  ECOG 0: Fully active, able to carry on all activities without restriction.
  ECOG 1: Restricted in physically strenuous activity but able to walk and carry out light work.
  ECOG 2: Ambulatory and capable of self-care, but unable to work; out of bed more than 50% of waking hours.
  ECOG 3: Capable of only limited self-care, confined to bed or chair more than 50% of waking hours.
  ECOG 4: Completely disabled, cannot carry out any self-care, confined to bed or chair all the time.
  ECOG 9: Unknown

MGMT methylated: May refer to the methylation status of the O-6-methylguanine-DNA methyltransferase (MGMT) gene (0 = no, 1 = yes, 9 = unknown).

EGFR mutated: Likely indicates the presence of epidermal growth factor receptor (EGFR) mutations (0 = no, 1 = yes, 9 = unknown).

TP53 mutated: Indicates the presence of mutations in the TP53 gene (0 = no, 1 = yes, 9 = unknown).

IDH1/IDH2 mutated: Refers to mutations in the isocitrate dehydrogenase (IDH) genes (0 = no, 1 = yes, 9 = unknown).

PD-L1 overexpressed: Indicates overexpression of programmed death-ligand 1 (PD-L1) (0 = no, 1 = yes, 9 = unknown).

% of tumor mass surgically resected: The percentage of the tumor mass that was surgically removed (numeric variable ranges from 0 to 100, with 999 = unknown).

Regimen in 1st Line: Describes the treatment regimen used in the first line of therapy.

Regimen in 1st Line (Other): Additional details about the first-line treatment regimen. 

Regimen in 2nd Line: Describes the treatment regimen used in the second line of therapy. 999 = unknown.

Regimen in 2nd Line (Other): Additional details about the second-line treatment regimen. 
