<!-- Readme for Medical Cost Analysis -->

<h1 style="color: red;">Medical Cost Analysis</h1>
<ul>
    <li><strong>Subject:</strong> Data Science</li>
    <li><strong>Class:</strong> MAS2</li>
    <li><strong>Lecturer:</strong> Dr. Emmanuel Lance Christopher VI M. Plan</li>
</ul>

---

<h2 style="color: red;">Team Member</h2>

<p align="center">
    <img alt="Team Member" src="https://github.com/user-attachments/assets/b74ef97e-0826-4a53-94c5-641db8353f3e">
</p>

---

<div style="color: blue;">
<h2>I. Introduction</h2>
<p>The cost of healthcare is going up everywhere, and it's a big problem for many countries. To help fix this, we need to know what makes medical expenses high. This is important for insurance companies, healthcare providers, and the government. The report looks at the "Medical Cost Personal Dataset." This dataset shows health insurance costs based on things like age, sex, BMI, smoking, and where people live. It has 1,338 records with 7 different factors that affect insurance costs. These factors include age, region, smoking habits, and BMI. The main focus is on "charges," which means the medical costs billed. The data comes from Kaggle.</p>
<p>The goal of this project is to analyze the dataset to find important patterns and relationships between different factors and medical costs. The analysis will include descriptive statistics, visualizations, and a prediction model to estimate medical expenses based on these factors. The findings could help insurance companies better understand individuals with high medical costs, which can support better risk management and adjust pricing strategies for premiums.</p>
<p>This data can be instrumental for analyzing sales performance, understanding customer preferences, and making informed business decisions.</p>

<h2>II. Data Discussion</h2>
<ul>
    <li><strong>Age:</strong> Age of the person.</li>
    <li><strong>Sex:</strong> Male or female.</li>
    <li><strong>BMI:</strong> Body fat measurement.</li>
    <li><strong>Children:</strong> Number of dependents.</li>
    <li><strong>Smoker:</strong> Yes or no.</li>
    <li><strong>Region:</strong> Area (northeast, northwest, southeast, southwest).</li>
    <li><strong>Charges:</strong> Medical costs billed.</li>
</ul>

<h2>III. Data Cleaning</h2>
<p align="center">
    <img alt="Data Cleaning" src="https://github.com/user-attachments/assets/8380c6ab-24e9-4a27-84cd-77063058214b">
</p>
<p>The data is already cleaned.</p>

<h2>IV. Charts and Insights</h2>

<h3>1. Smoking vs. Medical Charges</h3>
<p>Smokers pay way more. The box plot shows smokers have much higher charges than non-smokers. Recommendation: charge smokers more.</p>
<p align="center">
    <img alt="Smoking vs Medical Charges" src="https://github.com/user-attachments/assets/400166d9-384b-4f84-80c3-cfa311181709">
</p>

<p align="center"><strong>Chart Analysis: Smoking vs Medical Charges</strong></p>

<strong>Which One is Highest?</strong>
<ul>
    <li><strong>Smokers</strong> pay significantly higher medical charges than non-smokers. The median cost for smokers is around <strong>$35,000</strong>, while for non-smokers it's just <strong>$8,000</strong>. The highest costs for smokers go over <strong>$60,000</strong>, compared to non-smokers who rarely exceed <strong>$20,000</strong>.</li>
</ul>

<strong>Increasing/Decreasing Pattern?</strong>
<ul>
    <li>There's no specific increasing or decreasing trend shown here because this is a comparison between two groups. What it clearly shows is a <strong>huge difference</strong> in medical costs between smokers and non-smokers. Smokers always have higher costs—no exceptions.</li>
</ul>

<strong>Why is This Important?</strong>
<ul>
    <li><strong>Decision for Manager:</strong> Smokers are a high-risk group with much higher and more unpredictable medical expenses. This means <strong>higher premiums</strong> are needed for smokers to balance out the increased risk. The cost difference is too big to ignore; smokers need to pay more because they cost the company more. Straightforward decision—charge them more, minimize the company's financial risk.</li>
</ul>

<h3>2. BMI Categories vs. Medical Charges</h3>
<p>People were grouped by BMI: underweight, normal, overweight, obese. The box plot shows obese people face higher charges. This means BMI is a good factor for predicting high costs.</p>
<p align="center">
    <img alt="BMI Categories vs Medical Charges" src="https://github.com/user-attachments/assets/ec0abee4-7214-4d00-b007-54f89cced786">
</p>

<p align="center"><strong>Chart Analysis: BMI Category vs Medical Charges</strong></p>

<strong>Which One is Highest?</strong>
<ul>
    <li><strong>Obese</strong> individuals have the highest medical charges. The median cost is higher than the other BMI categories, and there are many outliers with extremely high charges (some even exceeding <strong>$60,000</strong>).</li>
    <li><strong>Underweight, Normal, and Overweight</strong> categories have similar median charges, all much lower than the obese group.</li>
</ul>

<strong>Increasing/Decreasing Pattern?</strong>
<ul>
    <li>There is an <strong>increasing pattern</strong> in medical charges as BMI goes up. Medical charges steadily rise from <strong>underweight to obese</strong>. Obese individuals have a significant jump in costs compared to the others.</li>
</ul>

<strong>Why is This Important?</strong>
<ul>
    <li><strong>Decision for Manager:</strong> Obese individuals are driving higher costs, which means they are a higher risk group. To manage this risk, insurance premiums should be higher for obese individuals. The cost difference is clear—people with higher BMIs (specifically those classified as obese) cost more in healthcare. Adjust the premiums accordingly to make sure the higher risk (higher medical expenses) is covered by higher pricing. Simple decision—higher risk, higher cost.</li>
</ul>

<h3>3. Age vs. Medical Charges</h3>
<p>Charges increase with age, especially after 50. The scatter plot shows this clearly. Older people are more likely to need higher-cost insurance. These charts directly show who has higher costs—smokers, older people, and those with higher BMI. This means insurance companies should adjust premiums accordingly.</p>
<p align="center">
    <img alt="Age vs Medical Charges" src="https://github.com/user-attachments/assets/85e7baca-e438-43b9-a7f9-5ddc387d20c5">
</p>

<p align="center"><strong>Chart Analysis: Age vs Medical Charges</strong></p>

<strong>Which One is Highest?</strong>
<ul>
    <li><strong>Smokers</strong> always have the highest medical charges compared to non-smokers, regardless of age. The <strong>blue dots</strong> represent smokers, and they are consistently above the <strong>orange dots</strong> (non-smokers).</li>
    <li>As age increases, the medical charges also increase for both smokers and non-smokers, but smokers consistently pay much more. The highest charges go well above <strong>$60,000</strong>, mostly for older smokers.</li>
</ul>

<strong>Increasing/Decreasing Pattern?</strong>
<ul>
    <li><strong>Increasing Pattern:</strong> Medical costs <strong>increase with age</strong>. The older the person, the more they pay, especially if they smoke. The charges rise for both groups, but the gap between smokers and non-smokers remains obvious and significant at every age group.</li>
</ul>

<strong>Why is This Important?</strong>
<ul>
    <li>Age and smoking are two major factors driving up medical costs. Older people cost more, and smokers cost way more. So, adjust the premiums—charge <strong>older people higher premiums</strong> based on the increased cost with age, and <strong>charge smokers even more</strong> to cover their significantly higher health risks. The costs aren't the same for everyone—insurance pricing needs to reflect this. Higher age and smoking mean higher costs, so premiums need to go up for these groups.</li>
</ul>
</div>

---

<div style="color: yellow;">
<h2>V. Conclusion</h2>
<p>Smoking, age, and BMI are the main factors driving medical costs. Smokers, older people, and those with high BMI should be charged higher premiums based on their risk. No fluff—just straight insights and recommendations.</p>
</div>
