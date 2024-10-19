# Medical Cost Analysis

**Subject:** Data Science  
**Class:** MAS2  
**Lecturer:** Dr. Emmanuel Lance Christopher VI M. Plan

---

## Team Members

![Team Photo](https://github.com/user-attachments/assets/b74ef97e-0826-4a53-94c5-641db8353f3e)

---

## I. Introduction

The cost of healthcare is going up everywhere, and it's a big problem for many countries. To help fix this, we need to understand **what makes medical expenses high**. This is crucial for **insurance companies, healthcare providers, and government** organizations. This report focuses on analyzing the "Medical Cost Personal Dataset," which contains health insurance costs based on various attributes like **age, sex, BMI, smoking habits, and region**.

- The dataset has **1,338 records** with 7 factors that influence insurance costs.
- The main variable is **"charges"**, which indicates the medical costs billed.
- The data comes from **Kaggle**.

**Goal**: To analyze and find key patterns affecting medical costs. We use descriptive statistics, visualizations, and a predictive model to estimate medical expenses. This can support insurance companies in better understanding individuals with high medical costs and adjusting their risk management and pricing strategies.

---

## II. Data Discussion

The dataset includes the following attributes:

- **Age**: Age of the person.
- **Sex**: Male or female.
- **BMI**: Body fat measurement.
- **Children**: Number of dependents.
- **Smoker**: Yes or no.
- **Region**: Area (northeast, northwest, southeast, southwest).
- **Charges**: Medical costs billed.

---

## III. Data Cleaning

![Data Cleaning](https://github.com/user-attachments/assets/8380c6ab-24e9-4a27-84cd-77063058214b)

The data was already clean, requiring no additional modifications.

---

## IV. Charts and Insights

### 1. Smoking vs. Medical Charges

- **Smokers pay way more**.
- The box plot clearly shows smokers have **higher charges** than non-smokers.
- **Recommendation**: Charge smokers more to compensate for higher costs.

![Smoking vs Medical Charges](https://github.com/user-attachments/assets/400166d9-384b-4f84-80c3-cfa311181709)

**Chart Analysis**:
- **Which One is Highest?**  
  Smokers pay significantly higher medical charges than non-smokers. The median cost for smokers is around **$35,000**, while for non-smokers, it's just **$8,000**. The highest costs for smokers go over **$60,000**, whereas non-smokers rarely exceed **$20,000**.
  
- **Increasing/Decreasing Pattern?**  
  There’s no increasing or decreasing pattern. It simply shows a **huge difference** in costs—smokers always have higher expenses.
  
- **Why is This Important?**  
  **Decision for Manager**: Smokers are high-risk and have unpredictable, high expenses. **Charge higher premiums** for smokers to balance the increased financial risk.

### 2. BMI Categories vs. Medical Charges

- People are grouped by BMI: underweight, normal, overweight, obese.
- The box plot shows **obese people face higher charges**.
- **BMI is a strong predictor** of high medical costs.

![BMI Categories vs Medical Charges](https://github.com/user-attachments/assets/ec0abee4-7214-4d00-b007-54f89cced786)

**Chart Analysis**:
- **Which One is Highest?**  
  **Obese** individuals have the highest medical charges, with many outliers exceeding **$60,000**. Underweight, normal, and overweight categories have lower median charges.
  
- **Increasing/Decreasing Pattern?**  
  There is a clear **increasing pattern**—charges rise with BMI, with **obese** individuals having a significant jump in costs.
  
- **Why is This Important?**  
  **Decision for Manager**: Obese individuals are high-risk, so they need higher premiums to cover the increased expenses. Higher BMI = Higher Costs = Higher Premiums.

### 3. Age vs. Medical Charges

- Charges **increase with age**, especially after 50.
- **Older people** need higher-cost insurance.
- Smokers consistently pay more at every age.

![Age vs Medical Charges](https://github.com/user-attachments/assets/85e7baca-e438-43b9-a7f9-5ddc387d20c5)

**Chart Analysis**:
- **Which One is Highest?**  
  **Smokers** always have higher medical charges compared to non-smokers. The **blue dots** represent smokers and are consistently above the **orange dots** (non-smokers). Medical charges increase as age increases.
  
- **Increasing/Decreasing Pattern?**  
  **Increasing Pattern**: Costs increase with age, and smokers have higher costs than non-smokers. The gap remains significant across all age groups.
  
- **Why is This Important?**  
  **Decision for Manager**: **Older individuals** have higher costs, and **smokers** cost even more. Adjust premiums based on **age** and **smoking status** to cover these higher costs.

---

## V. Conclusion

**Key Factors**:
- Smoking, age, and BMI are the main factors driving medical costs.
- Smokers, older individuals, and people with high BMI should pay **higher premiums** based on their risk. Simple—higher risk means higher cost.

---

### Summary:

1. **Smoking** significantly increases costs.
2. **BMI**—higher categories mean higher medical charges.
3. **Age**—older people pay more, especially if they smoke.

The report uses insights and visualizations to make clear recommendations on premium pricing to manage risk efficiently.

