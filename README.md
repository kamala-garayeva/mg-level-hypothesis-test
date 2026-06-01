# Blood Magnesium Level Hypothesis Test 🧪

## Objective
Statistically evaluate whether a medication has a significant effect on blood magnesium (Mg) levels by comparing two independent patient groups.

## Research Question
**Is there a statistically significant difference in blood Mg levels between patients who received the medication and those who did not?**

- H₀ (Null hypothesis): There is no significant difference in mean Mg levels between the two groups
- H₁ (Alternative hypothesis): The medication significantly affects blood Mg levels

## Dataset
Patient blood test records containing Mg level measurements for two groups:
- **Group 1:** Patients who received the medication
- **Group 2:** Control group (no medication)

## Method: Welch Two-Sample t-Test
Welch's t-test was chosen over Student's t-test because it does not assume equal variances between the two groups — making it more robust for real-world medical data.

**Steps:**
1. Checked normality assumptions for both groups
2. Assessed variance equality (Levene's / F-test)
3. Applied Welch two-sample t-test
4. Interpreted p-value against α = 0.05 significance level
5. Reported confidence interval and effect direction

## Key Finding
The Welch t-test results indicated whether the medication produced a statistically significant change in blood Mg levels, providing evidence to support or reject the null hypothesis at the 95% confidence level.

## Tools & Technologies
- **Language:** R
- **Libraries:** stats, ggplot2
- **Output:** Documented results in `mg_level_results.docx`
- **Analysis type:** Inferential statistics / hypothesis testing
