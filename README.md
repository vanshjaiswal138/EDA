📊 Exploratory Data Analysis (EDA) - AI Companies in Indore
This project performs an Exploratory Data Analysis (EDA) on a dataset containing information about AI and tech companies based in Indore. The aim is to extract meaningful insights from company profiles, such as location distribution, technology domains, and customer feedback metrics.

📁 Dataset
File: ai companies in indore_GMS_output.csv

Source: Company listings with attributes like name, address, rating, total reviews, category, and booking links.

🧪 EDA Overview
The analysis includes:

✅ Data Preprocessing
Converted all columns to string type for consistency.

Cleaned special characters and missing values.

Extracted numerical values from the "Total Reviews" column.

Handled missing values in "Booking Links" and "Total Reviews".

📍 Location Analysis
Extracted location info from address.

Visualized company distribution by location using a bar chart.

🧠 Domain Categorization
Classified companies into:

AI/ML

Data Analytics

Software

Other

Visualized distribution using a pie chart.

📂 Category Distribution
Analyzed the frequency of company categories.

Displayed using a bar chart.

⭐ Reviews vs Ratings
Plotted scatter plots to study the correlation between:

Number of reviews and ratings.

Identified outliers based on review counts and rating thresholds.

📌 Key Libraries Used
pandas

numpy

matplotlib

seaborn

📈 Sample Insights
Majority of companies are clustered in a few key locations.

Significant number fall into the AI/ML and Software domains.

Companies with high review counts typically maintain good ratings.
