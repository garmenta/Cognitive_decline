BACKGROUND 

By 2050, it is projected that individuals aged 60 and older will constitute 25% of Mexico's population, a demographic shift that is expected to lead to an increase in dementia cases within the country. However, research studies suggest that up to 40% of dementia cases could be either avoided or delayed. Therefore highlighting the importance of analysis focus on this topic. 

METHODS

Cognitive decline is our output variable of interest. It is a categorical variable that was assigned class labels 0 to 3, where 0 indicates normal decline and 3 indicates dementia.  
There is some cognitive decline that is a normal part of aging. Cognitive impairment is not a normal part of aging and falls in the middle between the normal cognitive decline and dementia. Dementia is the most serious decline that is not normal of the aging process. 
This analysis used pooled longitudinal data from the Mexican Health and Aging Study for years 2012, 2015, and 2018. Descriptive statistics and visualizations were all conducted in python using libraries including but not limited to NumPy, Pandas, Matplotlib, and Seaborn

LIST OF PREDICTORS 

DEMOGRAPHIC 

1. Age--Age in years
2. Male--Male=1, Female=0
3. Lives alone--Lives alone
4. Lives with spouse--Spouse Only
5. Extended household--Living in extended household
   
ECONOMIC 

1. Early life disadvantage--Early-life disadvantage 7 categories for 2015 and 6 for 2012 2. Education--Years of education
3. Net wealth--Net wealth in USD. Asset value minus debt in household
4. Rural--community Rural community=1 
5. Years working--About how many years in total have you worked for most your life (in the last 10 years) for income or profits? 6. White collar--Managerial, professional and technical (white collar)
7. Services non-profess--Services industry (entry-level/non-professional/non-technical)
8. Agriculture/farming--Works in agriculture/farming 
9. Blue collar--Precision, production and operators (Blue collar)

HEALTH 

1. IADL difficulties--Number IADL difficulties binary: preparing a hot meal, shopping, taking medicine, managing money 2. Health insurance--Has health insurance
3. Diabetes--Doctor ever mentioned person had diabetes?
4. Respiratory illness--Doctor ever mentioned person had pulmonary condition? 
5. Brain stroke--Doctor ever mentioned person had a brain stroke?
6. Hypertension--Doctor ever mentioned person had high blood pressure?
7. Heart attack--Doctor ever mentioned person had a heart attack?
8. Poor vision--Vision ability (with glasses if applicable): Poor or legally blind
9. Poor hearing--Hearing range (with hearing aid if applicable): Poor hearing or legally deaf 
10. Mobility difficulties--Because of a health problem, do you have difficulty reaching or extending your arms above shoulder level? 11. BMIcat--1=underweight, 2=normal, 3=overweight, 4=obese 

PSYCHOLOGICAL AND MENTAL 

1.	Depression--Depression - CES-D9 Score. Higher scores indicate greater depressive symptoms 
2.	Conscientiousness--Conscientiousness scale, higher values indicate a more conscientious personality 
3.	Int locus control--Internal locus control. Higher values to indicate more locus control. Summed up all the variables and divided by 8. Final values vary from .125 to 4 
4.	Mental stimulation--Dummy de mental stimulation 1 or more 

SOCIAL 

1. Religious importance--Current Importance of religion in person's life
2. Migrant--Migrated to the US and back to Mexico=1
3. Social engagement--Chats on the phone with family/friends, uses computer/internet to send messages=1 

BEHAVIORAL 

1. Takes preventive test--Has taken sugar, high blood pressure or cholesterol test in the past two years
2. Physically active-- Has exercised or done heavy physical work three times or more per week in past two years on average 

