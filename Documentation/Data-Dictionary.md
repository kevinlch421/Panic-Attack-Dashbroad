# Data Dictionary: Panic Attack Analysis

| Column Name                          | Description                                | Data Type | Sample Value |
|--------------------------------------|--------------------------------------------|-----------|--------------|
| **PANIC_ATTACK_DATA_ID**             | Unique identifier for each patient record  | Integer   | 1            |
| **PANIC_ATTACK_DATA_AGE**            | Patient's age in years                     | Integer   | 56           |
| **PANIC_ATTACK_DATA_GENDER**         | Patient's self-identified gender           | String    | Female       |
| **PANIC_ATTACK_DATA_PANIC_ATTACK_FREQUENCY** | Number of panic attacks per week       | Integer   | 9            |
| **PANIC_ATTACK_DATA_DURATION_MINUTES** | Average duration of attacks in minutes   | Integer   | 5            |
| **PANIC_ATTACK_DATA_TRIGGER_REASON** | Primary trigger for panic attacks          | String    | Caffeine     |
| **PANIC_ATTACK_DATA_HEART_RATE**     | Average heart rate during attacks (BPM)    | Integer   | 133          |
| **PANIC_ATTACK_DATA_SWEATING**       | Presence of sweating during attacks        | Boolean   | True         |
| **PANIC_ATTACK_DATA_SHORTNESS_OF_BREATH** | Shortness of breath symptom            | Boolean   | False        |
| **PANIC_ATTACK_DATA_DIZZINESS**      | Dizziness symptom during attacks           | Boolean   | True         |
| **PANIC_ATTACK_DATA_CHEST_PAIN**     | Chest pain symptom during attacks          | Boolean   | True         |
| **PANIC_ATTACK_DATA_TREMBLING**      | Trembling/shaking symptom during attacks   | Boolean   | False        |
| **PANIC_ATTACK_DATA_MEDICAL_HISTORY**| Primary existing medical condition         | String    | Anxiety      |
| **PANIC_ATTACK_DATA_MEDICATION**     | Currently taking panic-related medication  | Boolean   | False        |
| **PANIC_ATTACK_DATA_CAFFEINE_INTAKE**| Daily caffeine servings (cups/glasses)     | Integer   | 2            |
| **PANIC_ATTACK_DATA_EXERCISE_FREQUENCY** | Weekly exercise sessions                | Integer   | 3            |
| **PANIC_ATTACK_DATA_SLEEP_HOURS**    | Average nightly sleep duration (hours)     | Float     | 6.4          |
| **PANIC_ATTACK_DATA_ALCOHOL_CONSUMPTION** | Regular alcohol consumption            | Boolean   | 5*           |
| **PANIC_ATTACK_DATA_SMOKING**        | Current smoking status                     | Boolean   | True         |
| **PANIC_ATTACK_DATA_THERAPY**        | Currently receiving therapy                | Boolean   | True         |
| **PANIC_ATTACK_DATA_PANIC_SCORE**    | Clinical severity score (1-10 scale)       | Integer   | 5            |
| **PANIC_ATTACK_DATA_Panic_Score_HML_** | Severity category (High/Medium/Low)     | String    | Medium       |
| **PANIC_ATTACK_DATA_Age_Group_IF**   | Age category (custom grouping)             | String    | Senir*       |
| **PANIC_ATTACK_DATA_Age_Group_Switch**| Standard age category                      | String    | Adult        |

\* Notes:
- ALCOHOL_CONSUMPTION: Sample value 5 appears inconsistent with Boolean type (verify data collection)
- Age_Group_IF: "Senir" likely typo for "Senior"
- Boolean fields use True/False except Alcohol_Consumption
