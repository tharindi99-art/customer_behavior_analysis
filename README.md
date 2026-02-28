<h1>📊 Customer Shopping Behavior Analysis</h1>

<h2>🔎 Overview</h2>
<p>
This project analyzes customer shopping behavior using transactional data from <b>3,900 purchases</b> across multiple product categories.
The goal is to uncover insights related to customer demographics, spending patterns, product performance, and subscription behavior.
</p>
<p>
The project follows a complete data analytics workflow from Python-based data cleaning to SQL analysis and Power BI visualization,
concluding with a professional report and presentation using Gamma AI.
</p>

<h2>📂 Dataset</h2>
<ul>
    <li><b>Total Rows:</b> 3,900</li>
    <li><b>Total Columns:</b> 18</li>
    <li><b>Missing Values:</b> 37 (Review Rating column)</li>
</ul>

<h3>Key Features</h3>
<ul>
    <li><b>Customer Information:</b> Age, Gender, Location, Subscription Status</li>
    <li><b>Purchase Details:</b> Item Purchased, Category, Purchase Amount, Season, Size, Color</li>
    <li><b>Shopping Behavior:</b> Discount Applied, Promo Code Used, Frequency of Purchases, Review Rating, Shipping Type</li>
</ul>

<h2>🛠 Tools & Technologies</h2>
<ul>
    <li>Python</li>
    <li>PostgreSQL</li>
    <li>Power BI</li>
    <li>Gamma AI</li>
    <li>Jupyter Notebook</li>
</ul>

<h2>🔄 Project Steps</h2>

<h3>1. Data Loading & EDA (Python)</h3>
<ul>
    <li>Loaded dataset using Pandas</li>
    <li>Checked structure using <code>df.info()</code> and summary statistics using <code>df.describe()</code></li>
    <li>Identified missing values and explored trends</li>
</ul>

<h3>2. Data Cleaning & Preparation</h3>
<ul>
    <li>Handled missing values in Review Rating using median by category</li>
    <li>Renamed columns to snake_case</li>
    <li>Created new features: age_group and purchase_frequency_days</li>
    <li>Removed redundant column (promo_code_used)</li>
</ul>

<h3>3. Database Integration</h3>
<ul>
    <li>Connected Python to PostgreSQL</li>
    <li>Loaded cleaned dataset into database</li>
</ul>

<h3>4. SQL Analysis (PostgreSQL)</h3>
<ul>
    <li>Revenue analysis by gender</li>
    <li>Identified high-spending discount users</li>
    <li>Top-rated products analysis</li>
    <li>Shipping type comparison</li>
    <li>Subscriber vs non-subscriber insights</li>
    <li>Customer segmentation (New, Returning, Loyal)</li>
</ul>

<h3>5. Power BI Dashboard</h3>
<ul>
    <li>Built interactive dashboard with KPIs and charts</li>
    <li>Visualized customer behavior and sales trends</li>
</ul>

<h3>6. Reporting & Presentation</h3>
<ul>
    <li>Created analytical report</li>
    <li>Designed presentation using Gamma AI</li>
</ul>

<h2>📊 Dashboard</h2>
<p>
The Power BI dashboard includes key performance indicators, customer segmentation, product insights, and interactive filters
to support business decision-making.
</p>

<h2>📈 Results & Insights</h2>
<ul>
    <li>Identified high-revenue customer segments</li>
    <li>Subscribers show higher spending behavior</li>
    <li>Loyal customers contribute consistently to revenue</li>
    <li>Some products depend heavily on discounts</li>
</ul>
