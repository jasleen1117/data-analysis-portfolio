# Austin Family Stabilization Fund - Longitudinal Analysis

## Project Overview
Analysis of the impact of unconditional cash transfers on low-income households in Austin, Texas, U.S

## Files in this folder: 
`1a_cleaning_midline.R` - Data cleaning script for midline survey data 
- `1b_cleaning_endline.R` - Data cleaning script for endline survey data 
- `1c_merging_baseline_midline_endline.R` - Script to merge baseline, midline, and endline datasets 
- `2a_Descriptives_midline.R` - Descriptive statistics and exploratory analysis for midline data 
- `2b_Descriptives_endline.R` - Descriptive statistics and exploratory analysis for endline data 
- `3a_MainLongitudinalAnalysis.R` - Main longitudinal analysis code 
- `3b_Baseline_MidlineLongitudinalAnalysis.R` - Baseline and Midline longitudinal analysis comparing pre-intervention data 
- `4a_Markdown_MidlineDescriptives.html` - HTML report with midline descriptive analysis 
- `4b_Markdown_BaselineMidline_LongitudinalAnalysis.html` - HTML report with baseline-midline longitudinal analysis 
- `4c_Markdown_EndlineDescriptives.html` - HTML report with endline descriptive analysis 
- `5_PolicyReportMidline.pdf` - Policy report with midline findings for Austin stakeholders 
- `README.md` - This file with project documentation

## Key Methods
- Longitudinal data analysis
- Advanced data visualization in R

## Results
After 6 months of grants, members report improved financial stability, employment gains, increased housing security, and stronger community ties. 
- The grants are helping members afford daily costs of life in Austin. For the majority of members, paying for basic needs like housing, transportation, food, and family caregiving, is less difficult now than it was at the start of the grants
- Workforce participation is strong and members have made considerable progress on employment goals. 55% of those who had an employment goal at the start of the grants have found a new job or increased their work hours. 
- The grants are helping members progress on housing goals, especially around moving, and catching up on housing payments. 44% of those who were behind on rent or mortgage payments at the start of the grants have now caught up. 2 members bought a house!
- Members report feeling stronger relationships with their community and they have been providing more frequent support, both monetary and non-monetary. The grants have had a ripple effect as members support their family, friends, and neighbors with basic needs. 

Comprehensive Survey Variables Documentation
This document provides a detailed overview of all survey variables used in the dataset.
Table of Contents
* Identifier & Demographics
* Income & Employment
* Housing & Living Situation
* Wellbeing & Health
* Investment & Financial Impact
* Child Care
* Transportation
* Education
* Financial Status & Budgeting
* Program Impact & Funding
* Income Ranking Matrix
* Financial Needs & Benefits
* Goals & Aspirations
* Community & Social Support
* Ripple Effects
* Program Satisfaction & Feedback
Identifier & Demographics
VariableDescriptionentity_uuidUnique participant identifieruserlanguage_eUser's preferred languageconsent_eConsent to participatedemo_hh_size_eHousehold sizeIncome & Employment
Income Brackets
VariableDescriptionincome_hh_eHousehold income levelincome_hh_0_10k_eHousehold income: $0-$10,000income_hh_10k_20_eHousehold income: $10,000-$20,000income_hh_30k_40k...8_eHousehold income: $30,000-$40,000 (option 8)income_hh_30k_40k...9_eHousehold income: $30,000-$40,000 (option 9)income_hh_40k_50k_eHousehold income: $40,000-$50,000income_hh_50k_60k_eHousehold income: $50,000-$60,000income_hh_60k_70k_eHousehold income: $60,000-$70,000income_hh_70k_80k_eHousehold income: $70,000-$80,000income_hh_80k_90k_eHousehold income: $80,000-$90,000income_hh_90k_100k_eHousehold income: $90,000-$100,000income_hh_100k_more_eHousehold income: $100,000+Employment Status
VariableDescriptionemp_status_eCurrent employment statuswork_new_6mo_eNew work in past 6 monthsemp_hours_eEmployment hoursemp_hours_change_eChange in employment hoursemp_increase_eEmployment increasework_increase_6mo_5_text_eWork increase details (text)emp_decrease_eEmployment decreasework_decrease_6mo_6_text_eWork decrease details (text)own_business_eOwn business statusown_business_5_text_eBusiness details (text)emp_unemployed_reason_eUnemployment reasonwork_no_reason_7_text_eNo work reason details (text)emp_unemployed_care_eUnemployed due to caregivingwork_no_reason_care_3_text_eCaregiving unemployment details (text)austin_programs_y_n_eAustin programs participationaustin_programs_used_eSpecific Austin programs usedHousing & Living Situation
VariableDescriptionhouse_status_eHousing statushousing_situation_7_text_eHousing situation details (text)house_burden_eHousing cost burdenhouse_payments_behind_eBehind on housing paymentshouse_moved_eRecent move statushouse_moved_count_eNumber of moveshouse_move_reason_eReason for movingmove_reason_positive_ePositive move reasonsmove_reason_positive_11_text_ePositive move details (text)move_reason_negative_eNegative move reasonsmove_reason_negative_4_text_eNegative move details (text)Wellbeing & Health
VariableDescriptionwb_anxious_eAnxiety levelswb_worry_eWorry levelswb_interest_eInterest/engagement levelswb_down_eFeeling down/depressedwb_food_security_eFood security statuswb_health_status_eOverall health statusInvestment & Financial Impact
VariableDescriptioninvestment_feel_eFeelings about investmentinvestment_positive_ePositive investment impactsinvestment__negative_eNegative investment impactsChild Care
VariableDescriptioncc_has_children_eHas childrencc_age_range_eChildren's age rangecc_under5_care_eCare for children under 5under_5_enroll_5_text_eUnder 5 enrollment details (text)cc_5to12_care_eCare for children 5-12above_5_enroll_5_text_eAges 5+ enrollment details (text)cc_above12_care_eCare for children above 12above_12_enroll_5_text_eAges 12+ enrollment details (text)cc_arrangement_eChildcare arrangementschildcare_better_eChildcare improvementschildcare_better_5_text_eChildcare improvement details (text)childcare_worse_eChildcare deteriorationchildcare_worse_5_text_eChildcare deterioration details (text)Transportation
VariableDescriptiontransport_eTransportation accesstransport_7_text_eTransportation details (text)transport_rely_eTransportation reliabilitytransport_rely_no_eTransportation unreliabilitytransport_rely_no_7_text_eTransportation issues details (text)transport_change_eTransportation changestransport_improve_eTransportation improvementstransport_worse_eTransportation deteriorationtransport_worse_5_text_eTransportation deterioration details (text)Education
VariableDescriptionedu_complete_eEducation completionedu_type_complete_eType of education completededu_type_complete_9_text_eEducation type details (text)edu_cert_prog_eCertificate program participationedu_cert_prog_which_eSpecific certificate programsedu_cert_prog_which_9_text_eCertificate program details (text)edu_progress_eEducational progressedu_progress_5_text_eEducational progress details (text)Financial Status & Budgeting
VariableDescriptiondebt_eDebt statusdebt_amount_eAmount of debtbudget_easy_hard_eBudgeting difficultybudget_easier_eBudgeting becoming easierbudget_harder_eBudgeting becoming harderProgram Impact & Funding
VariableDescriptionimpact_fund_receive_eProgram funding receivedimpact_fund_receive_9_text_eFunding details (text)impact_fund_specific_eSpecific funding impactsIncome Ranking Matrix
Matrix variables for ranking income sources (1-6 categories, 1-4 rankings each):
Variable PatternDescriptionleast_most_income_[1-6]_[1-4]_eIncome ranking matrixMatrix Breakdown:
* Categories 1-6: Different income source types
* Rankings 1-4: Least to most important/frequent
Financial Needs & Benefits
VariableDescriptionfin_expense_difficulty_eFinancial expense difficultyfin_needs_met_eFinancial needs being metspend_needs_meet_11_text_eSpending to meet needs details (text)benefits_reduce_eBenefits reductionbenefits_reduce_text_eBenefits reduction details (text)fin_emergency_fund_eEmergency fund statusfin_emergency_select_eEmergency fund selectionfin_emergency_select_11_text_eEmergency fund details (text)Goals & Aspirations
VariableDescriptiongoals_eGeneral goalsgoals_select_1_eGoal selection option 1goals_select_2_eGoal selection option 2goals_select_3_eGoal selection option 3goals_select_4_eGoal selection option 4goals_select_5_eGoal selection option 5goals_select_7_eGoal selection option 7goals_select_7_text_eGoal selection details (text)goals_experience_eGoals experiencegoal_housing_eHousing goalsgoals_house_4_text_eHousing goal details (text)goal_employment_eEmployment goalsgoals_job_5_text_eEmployment goal details (text)Community & Social Support
VariableDescriptioncomm_part_eCommunity participationcomm_part_10_text_eCommunity participation details (text)comm_part_time_eCommunity participation timecomm_give_emo_supp_eGiving emotional supportcomm_give_money_eGiving moneycomm_give_caregiving_eGiving caregivingcomm_give_knowledge_eGiving knowledgecomm_give_transport_eGiving transportationcomm_give_errands_eGiving errands helpcomm_give_food_eGiving foodcomm_relationships_eCommunity relationshipsRipple Effects
VariableDescriptionripple_fam_select_eFamily ripple effects selectionimpact_ripple_fam_eImpact on family ripple effectsripple_comm_select_eCommunity ripple effects selectionimpact_ripple_comm_eImpact on community ripple effectsProgram Satisfaction & Feedback
VariableDescriptionu2g_satisfied_eProgram satisfactionu2g_satisfied_no_eProgram dissatisfactioninvest_delay_y_n_eInvestment delay (yes/no)invest_delay_yes_eInvestment delay detailsinvest_info_eInvestment informationinvest_info_no_eNo investment informationsupport_help_eSupport helpfulnesssupport_help_rate_eSupport help ratingsupport_help_rate_no_eNo support help ratingmember_feedback_eMember feedback
