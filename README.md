# MSBA-Capstone-Group-Portfolio
**IS 6813 MSBA Capstone**: Leilanie Coker, Gaurav Mishra, Alina Vannarath, Charlotte Wang

## Business Problem
MasterControl's Manufacturing Solutions product (Mx) converts at 13%, compared to 20.2% for its Quality Solutions product (Qx), a 55% performance gap. MasterControl believes it may not be targeting the right companies or the right people within those companies, leading to missed revenue opportunities and wasted marketing expenditures.

## Approach
We analyzed 16,644 qualified leads (QALs) from 2024–2025, modeling Mx (4,081 records) and Qx (12,169 records) separately using logistic regression. Leads were labeled as converted if they reached SQL, SQO, or Won status. Features included account type, industry, site function, contact title, channel, and priority signals.

## Key Findings
### Ideal Mx Target Account
The strongest Mx accounts are small to medium-sized CMOs and CDMOs in life sciences, specifically Blood & Biologics, Medical Device, and Pharma & BioTech. The site should be an actual manufacturing location. Non-manufacturing sites convert at a fraction of the rate. Large accounts and non-life science industries should be deprioritized.

### Ideal Mx Contact
Within target accounts, outreach should focus on VP and Head-level contacts. Leads arriving through direct/inbound channels or SEO convert at significantly higher rates, while email, events, external demand generation, and outbound prospecting all underperform. High-intent signals like "Contact Us," Live Demo, and Video Demo requests are strong positive indicators. Priority 2 leads and Webinar Demo signals should be avoided.

### How Mx Differs from Qx
The most important structural difference is site function: manufacturing sites are essential for Mx, while Qx performs neutrally across site types. CMO accounts are Mx's single strongest predictive signal but are neutral for Qx. Conversely, VP/Head title targeting is meaningful for Qx but less decisive for Mx at the model level.

### Cross-Sell Opportunities
Medical Device accounts at the small to medium tier, contacted at the VP/Head level, represent the strongest overlap between high-converting Mx and Qx profiles, making them the best candidates for cross-sell outreach.

## Business Impact
The current Mx conversion rate is 13%. Shifting focus to CMO/CDMO accounts alone is projected to raise that to 17%, and applying high-intent signal filters on top pushes it to 28%.
Shifting focus to CMO/CDMO accounts is projected to yield 163 additional conversions per year. Reallocating budget from email and events toward inbound and SEO maintains pipeline volume while improving conversion rate.
