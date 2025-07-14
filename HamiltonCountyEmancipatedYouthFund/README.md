# Hamilton County Emancipated Youth Emancipated - Longitudinal Analysis

## Project Overview
Analysis of the impact of unconditional cash transfers on youth who were emancipated from the foster system. 

## Files in this folder: 
- `1_Descriptives_Midline.R` - Descriptive statistics and exploratory analysis for midline survey data 
- `1b_LongitudinalAnalysis_Baseline_Midline.R` - Longitudinal analysis comparing baseline and midline data 
- `2a_Markdown_MidlineDescriptives.html` - HTML report with comprehensive midline descriptive analysis 
- `2b_Markdown_LongitudinalAnalysis.html` - HTML report with baseline-midline longitudinal analysis results - `README.md` - This file with project documentation 
- `3_PolicyReport.pdf` - Policy report with findings and recommendations for Hamilton County stakeholders

## Key Methods
- Longitudinal data analysis
- Advanced data visualization in R

# Data Information 
## Data Sources 
- Hamilton County Emancipated Youth Fund Baseline and Midline Survey Data 

## Data Characteristics 
- Sample size: 53 households.
- Variables: 
Variable Subgroups Documentation
This document provides a comprehensive overview of the variable subgroups used in the dataset.
Table of Contents
* Work & Employment
* Housing & Living Situation
* Education
* Healthcare
* Program Impact & Feedback
* Identifier
Work & Employment
Variables related to employment status, work hours, and employment changes.
VariableDescriptionworkEmployment statuswork_employ_lengthDuration of employmentwork_hours_per_weekWeekly work hourswork_hours_changeChanges in work hourswork_increaseWork hour increaseswork_increase_5_TEXTReasons for work increase (text)work_decreaseWork hour decreaseswork_decrease_6_TEXTReasons for work decrease (text)work_no_reasonNo reason for work changeswork_no_reason_7_TEXTDetails on no reason (text)Housing & Living Situation
Variables tracking housing status, living arrangements, and residential mobility.
VariableDescriptionhousing_situationCurrent housing statushousing_situation_7_TEXTHousing details (text)housing_sharedShared housing arrangementshousing_shared_3_TEXTShared housing details (text)housing_burdenHousing cost burdenhousing_behindBehind on housing paymentsmoved_last_yearRecent relocation statusmoved_last_year_numNumber of movesmove_reasonGeneral moving reasonsmove_reason_positivePositive moving reasonsmove_reason_positive_12_TEXTPositive move details (text)move_reason_negativeNegative moving reasonsmove_reason_negative_4_TEXTNegative move details (text)Education
Variables measuring educational attainment, progress, and barriers.
VariableDescriptionedu_highest_levelHighest education achievededu_highest_level_9_TEXTEducation level details (text)edu_completeEducation completion statusedu_type_completeType of education completededu_type_complete_9_TEXTEducation type details (text)edu_cert_progCertificate program participationedu_cert_prog_whichSpecific certificate programsedu_cert_prog_which_9_TEXTCertificate program details (text)edu_progressEducational progressedu_progress_5_TEXTProgress details (text)edu_barriersEducational barriersedu_barriers_9_TEXTBarrier details (text)edu_stop_continueEducation continuation decisionsHealthcare
Variables related to health insurance and healthcare access.
VariableDescriptioninsurance_typeType of health insuranceinsurance_type_8_TEXTInsurance details (text)doctor_whoPrimary care providerdoctor_not_seeBarriers to seeing doctordoctor_how_longTime since last doctor visitProgram Impact & Feedback
Variables measuring program effectiveness and participant feedback.
VariableDescriptionimpact_fund_receiveProgram funding receivedimpact_fund_receive_9_TEXTFunding details (text)impact_fund_specificSpecific funding impactssurvey_feedbackSurvey feedback responsesIdentifier
VariableDescriptionentity_uuidUnique participant identifier
## Note on Data Access Raw data files are not included in this repository due to privacy and confidentiality requirements. The analysis code demonstrates the methodological approach and can be adapted for similar datasets.


