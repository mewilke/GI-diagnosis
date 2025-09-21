**GI-diagnosis**

M. Wilke

This software analyzes a dataset linking 36 features of health data to various gastrointestinal disease states. The data are very clean just needing conversion to numeric values. The dataset can be found at 

https://www.kaggle.com/datasets/amanik000/gastrointestinal-disease-dataset

Place the dataset in a directory named 'data' below the directory holding the software. 
Note that the 4 target categories in Disease_Class were replaced with 6 symptoms. This prevents the use of this dataset for actual diagnostics. Also note that the features cluster into 4 or 5 groups rather than 6. 

The features are as follows:

**Demographic and Physical Attributes**

Age: Age of the individual (in years).

Gender: Biological gender of the individual (Male/Female/Other).

BMI: Body Mass Index – a measure of body fat based on height and weight.

Body_Weight: Weight of the individual (in kilograms or pounds).

**Health and Obesity Indicators**

Obesity_Status: Classification of individual as Obese, Overweight, or Normal based on BMI and other factors.

Ethnicity: Ethnic background (e.g., Caucasian, Asian, African American, etc.).

Family_History: Indicates whether there is a family history of related diseases (Yes/No).

**Biological and Genetic Markers**

Genetic_Markers: Presence of known genetic markers associated with disease risk.

Microbiome_Index: Quantitative index representing the state of the individual's gut microbiome.

**Autoimmune and Inflammatory Indicators**

Autoimmune_Disorders: Indicates the presence of known autoimmune disorders (Yes/No).

H_Pylori_Status: Status of Helicobacter pylori infection (Positive/Negative).

Fecal_Calprotectin: Inflammatory marker found in stool; high levels may indicate IBD.

Occult_Blood_Test: Results of fecal occult blood testing (Positive/Negative).

CRP_ESR: Combined result of C-Reactive Protein and Erythrocyte Sedimentation Rate – inflammation indicators.

**Diagnostic Results**

Endoscopy_Result: Findings from endoscopy (e.g., Normal, Inflammation, Ulcers).

Colonoscopy_Result: Findings from colonoscopy (e.g., Polyps, IBD, Normal).

Stool_Culture: Results indicating presence of bacterial, viral, or parasitic infections.

**Lifestyle and Diet**

Diet_Type: Type of diet followed (e.g., Vegetarian, Vegan, Omnivore).

Food_Intolerance: Known food intolerances (e.g., Lactose, Gluten).

Smoking_Status: Current smoking behavior (Smoker/Non-Smoker/Former Smoker).

Alcohol_Use: Frequency or status of alcohol consumption.

**Mental and Physical Health**

Stress_Level: Self-reported stress level (Low/Moderate/High).

Physical_Activity: Level of physical activity (Sedentary/Moderate/Active).

**Symptoms and GI Issues**

Abdominal_Pain: Presence of abdominal pain (Yes/No).

Bloating: Whether the individual experiences bloating (Yes/No).

Diarrhoea: Presence of diarrhea symptoms (Yes/No).

Constipation: Presence of constipation symptoms (Yes/No).

Rectal_Bleeding: Observation of rectal bleeding (Yes/No).

Appetite_Loss: Decreased appetite (Yes/No).

Weight_Loss: Unintentional weight loss (Yes/No).

Bowel_Habits: Summary or description of bowel movement characteristics.

Bowel_Movement_Frequency: Frequency of bowel movements (per day/week).

**Medication Usage**

NSAID_Use: Use of Non-Steroidal Anti-Inflammatory Drugs (Yes/No).

Antibiotic_Use: Recent use of antibiotics (Yes/No).

PPI_Use: Use of Proton Pump Inhibitors (Yes/No).

Medications: Other medications currently being taken.

**Target Variable**

Disease_Class: Final disease classification (e.g., Crohn’s Disease, Ulcerative Colitis, IBS, Healthy).


