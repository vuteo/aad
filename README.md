<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <title>Medical Cost Analysis</title>
</head>

<body>
    <!-- Header Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-8 text-center">
                    <h1>Medical Cost Analysis</h1>
                    <ul class="list-unstyled">
                        <li><strong>Subject:</strong> Data Science</li>
                        <li><strong>Class:</strong> MAS2</li>
                        <li><strong>Lecturer:</strong> Dr. Emmanuel Lance Christopher VI M. Plan</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Members Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-8 text-center">
                    <h1>Team Members</h1>
                    <img alt="Team Members" class="img-fluid" src="https://github.com/user-attachments/assets/b74ef97e-0826-4a53-94c5-641db8353f3e">
                </div>
            </div>
        </div>
    </section>

    <!-- Introduction Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row justify-content-center pb-5">
                <div class="col-12 col-lg-8 text-center">
                    <h1>Introduction</h1>
                    <p class="lead">The cost of healthcare is rising everywhere, and it is a big problem for many countries. Understanding what makes medical expenses high is crucial for insurance companies, healthcare providers, and governments. This report focuses on the "Medical Cost Personal Dataset," with 1,338 records covering various factors like age, sex, BMI, smoking habits, and region. The dataset comes from Kaggle.</p>
                    <p class="lead">The goal of this project is to analyze the dataset to identify key patterns and relationships affecting medical costs. The insights gained can help adjust pricing strategies and improve risk management for insurance premiums.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Data Discussion Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row text-left align-items-center">
                <div class="col-12 col-lg-8 m-auto">
                    <h1>Data Discussion</h1>
                    <ul class="lead">
                        <li><strong>Age:</strong> Age of the person.</li>
                        <li><strong>Sex:</strong> Male or female.</li>
                        <li><strong>BMI:</strong> Body fat measurement.</li>
                        <li><strong>Children:</strong> Number of dependents.</li>
                        <li><strong>Smoker:</strong> Yes or no.</li>
                        <li><strong>Region:</strong> Area (northeast, northwest, southeast, southwest).</li>
                        <li><strong>Charges:</strong> Medical costs billed.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Data Cleaning Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row text-center">
                <div class="col-12">
                    <h1>Data Cleaning</h1>
                    <img alt="Data Cleaning" class="img-fluid" src="https://github.com/user-attachments/assets/8380c6ab-24e9-4a27-84cd-77063058214b">
                    <p class="lead mt-4">The data was already clean and required no modifications.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Charts and Insights Section -->
    <section class="fdb-block">
        <div class="container">
            <!-- Smoking vs. Medical Charges -->
            <div class="row pb-5">
                <div class="col-12">
                    <h1>Charts and Insights</h1>
                    <h2>1. Smoking vs. Medical Charges</h2>
                    <img alt="Smoking vs Medical Charges" class="img-fluid" src="https://github.com/user-attachments/assets/400166d9-384b-4f84-80c3-cfa311181709">
                    <p class="lead"><strong>Which One is Highest?</strong><br>
                        Smokers pay significantly higher medical charges than non-smokers. The median cost for smokers is around <strong>$35,000</strong>, while for non-smokers, it's just <strong>$8,000</strong>. The highest costs for smokers go over <strong>$60,000</strong>, compared to non-smokers who rarely exceed <strong>$20,000</strong>.
                    </p>
                    <p class="lead"><strong>Increasing/Decreasing Pattern?</strong><br>
                        No specific increasing or decreasing trend, just a huge difference. Smokers always have higher costs—no exceptions.
                    </p>
                    <p class="lead"><strong>Why is This Important?</strong><br>
                        Smokers are high-risk with unpredictable, high expenses. To balance the risk, higher premiums are needed for smokers.
                    </p>
                </div>
            </div>

            <!-- BMI Categories vs. Medical Charges -->
            <div class="row pb-5">
                <div class="col-12">
                    <h2>2. BMI Categories vs. Medical Charges</h2>
                    <img alt="BMI Categories vs Medical Charges" class="img-fluid" src="https://github.com/user-attachments/assets/ec0abee4-7214-4d00-b007-54f89cced786">
                    <p class="lead"><strong>Which One is Highest?</strong><br>
                        Obese individuals have the highest medical charges. The median cost is higher, with many outliers exceeding <strong>$60,000</strong>.
                    </p>
                    <p class="lead"><strong>Increasing/Decreasing Pattern?</strong><br>
                        There is an increasing pattern. Charges rise as BMI increases, with the obese group having significantly higher costs.
                    </p>
                    <p class="lead"><strong>Why is This Important?</strong><br>
                        People with higher BMI have higher medical costs. They should be charged more to cover increased risk.
                    </p>
                </div>
            </div>

            <!-- Age vs. Medical Charges -->
            <div class="row">
                <div class="col-12">
                    <h2>3. Age vs. Medical Charges</h2>
                    <img alt="Age vs Medical Charges" class="img-fluid" src="https://github.com/user-attachments/assets/85e7baca-e438-43b9-a7f9-5ddc387d20c5">
                    <p class="lead"><strong>Which One is Highest?</strong><br>
                        Smokers consistently have higher charges at every age. Charges increase with age for both smokers and non-smokers, with smokers being significantly higher.
                    </p>
                    <p class="lead"><strong>Increasing/Decreasing Pattern?</strong><br>
                        There is an increasing pattern—costs go up with age, especially for smokers.
                    </p>
                    <p class="lead"><strong>Why is This Important?</strong><br>
                        Older individuals and smokers cost more. Adjust premiums accordingly to reflect their increased risks.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Conclusion Section -->
    <section class="fdb-block">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-8 text-center">
                    <h1>Conclusion</h1>
                    <p class="lead">Smoking, age, and BMI are the key factors driving medical costs. Higher premiums should be charged for smokers, older individuals, and people with higher BMI. Simple—higher risk, higher cost.</p>
                </div>
            </div>
        </div>
    </section>
</body>

</html>
