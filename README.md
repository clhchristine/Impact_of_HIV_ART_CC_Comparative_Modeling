# Estimating the Effect of HIV and ART on Cervical Cancer Elimination in KwaZulu-Natal, South Africa: a comparative modeling analysis

This repository contains model outputs for the DRIVE and Policy1-Cervix-HIV models between 1982 and 2124, with future projections beginning in 2024. Model outputs include HPV prevalence, cervical cancer incidence, cervical cancer case counts, HIV prevalence, and ART coverage. 

Model outputs are reported for different population subgroups (all women, HIV-negative, HIV-positive, HIV-positive and on ART, HIV-positive and untreated) and age groups (5-year age groups from 0 to 79). 

The DRIVE model presents the minimum, maximum, and median outputs of the 25 best-fitting parameter sets. The Policy1-Cervix-HIV model presents the median output. 

We modelled 8 scenarios: 

**S0: No HIV, no HIV-related interventions:**
- No HIV.
- VMMC and condom coverage in all years equal to low, pre-HIV levels.
- No ART.
- Vaccination begins in 2014. Bivalent vaccine until the end of 2023. Switch to the nonavalent vaccine in 2024. Vaccination coverage is 57%.
- Screening starts in 2000. Once in a lifetime screening frequency at age 35-39 for all women (regardless of HIV status). Screening coverage is scaled up from 0% to 18% from 2000-2003, then 18% to 48% from 2003-2016. Hold at 48% for the rest of the time horizon.  Screening with cytology. Treatment with cryotherapy/LLETZ (28% LTFU for colpo, 49% LTFU for follow up treatment for anyone with confirmed CIN).

**S1: No HIV**
- No HIV.
- VMMC and condom coverage as historically observed.
- No ART.
- Vaccination and screening the same as above.

**S2: HIV, no ART**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- No ART.
- Vaccination and screening the same as above.

**S3: HIV, observed ART (status quo)**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- ART coverage as observed (viral suppression for people living with HIV is 67% for females and 60% for males).
- Vaccination and screening the same as above.

**S4: 95-95-95 ART scale-up**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- ART coverage scaled up to 95-95-95 targets linearly from 2024 to 2030 (viral suppression for people living with HIV is 85.7% for both males and females).
- Vaccination and screening the same as above.

**S5: HPV vaccination scale-up**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- ART coverage scaled up to 95-95-95 targets.
- Vaccination begins in 2014. Bivalent vaccine until the end of 2023. Switch to the nonavalent vaccine in 2024. Vaccination coverage is 57% until 2024. 
- HPV vaccination coverage scale-up to 90% in 2024.
- Once in a lifetime screening frequency at age 35-39 for all women (regardless of HIV status). Screening coverage is scaled up from 0% to 18% from 2000-2003, then 18% to 48% from 2003-2016. Hold at 48% for the rest of the time horizon.  Screening with cytology. Treatment with cryotherapy/LLETZ (28% LTFU for colpo, 49% LTFU for follow up treatment for anyone with confirmed CIN).

**S6: HPV DNA and screening coverage scale-up**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- ART coverage scaled up to 95-95-95 targets.
- Vaccination begins in 2014. Bivalent vaccine until the end of 2023. Switch to the nonavalent vaccine in 2024. Vaccination coverage is 57% until 2024.
- HPV vaccination coverage scale-up to 90% in 2024.
- From 2000 to 2024: Once in a lifetime screening frequency at age 35-39 for all women (regardless of HIV status). Screening coverage is scaled up from 0% to 18% from 2000-2003, then 18% to 48% from 2003-2016. Hold at 48% for the rest of the time horizon.  Screening with cytology. Treatment with cryotherapy/LLETZ (28% LTFU for colpo, 49% LTFU for follow up treatment for anyone with confirmed CIN).
- Starting in 2024, switch to HPV DNA screening, screening coverage scaled up linearly to 70% in 2030, single visit screen and treat (5% loss-to-follow-up for thermal ablation, 20% loss-to-follow-up for LLETZ).

**S7: Full scale-up scenario**
- HIV turned on.
- VMMC and condom coverage as historically observed.
- ART coverage scaled up to 95-95-95 targets.
- Vaccination begins in 2014. Bivalent vaccine until the end of 2023. Switch to the nonavalent vaccine in 2024. Vaccination coverage is 57% until 2024.
- HPV vaccination coverage scale-up to 90% in 2024.
- From 2000 to 2024: Once in a lifetime screening frequency at age 35-39 for all women (regardless of HIV status). Screening coverage is scaled up from 0% to 18% from 2000-2003, then 18% to 48% from 2003-2016. Hold at 48% for the rest of the time horizon.  Screening with cytology. Treatment with cryotherapy/LLETZ (28% LTFU for colpo, 49% LTFU for follow up treatment for anyone with confirmed CIN).
- Starting in 2024, switch to HPV DNA screening, screening coverage scaled up linearly to 70% in 2030, single visit screen and treat (5% loss-to-follow-up for thermal ablation, 20% loss-to-follow-up for LLETZ).
- Starting in 2024, twice per lifetime screen for women without HIV at age 35-39 and 45-49, screening every 5 years for WLHIV starting from age 25. 
