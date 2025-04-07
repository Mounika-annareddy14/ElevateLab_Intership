<h1>🧹 Data Cleaning and Preprocessing - Customer Personality Analysis</h1>

<h2>📌 Objective</h2>
<p>To clean and prepare a raw dataset by handling:</p>
<ul>
  <li>Missing values</li>
  <li>Duplicate records</li>
  <li>Inconsistent formats</li>
  <li>Unclean column names</li>
  <li>Wrong datatypes</li>
</ul>

<h2>📁 Dataset</h2>
<p><strong>Customer Personality Analysis</strong> from Kaggle <br>
🔗 <a href="https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis" target="_blank">Kaggle Link</a></p>

<h3>Dataset Description:</h3>
<p>The dataset contains information about customer demographics, behavior, and responses to marketing campaigns.</p>

<ul>
  <li><strong>Demographics</strong>: ID, Year of Birth, Education, Marital Status, Income, etc.</li>
  <li><strong>Purchasing Behavior</strong>: Amount spent on different product categories.</li>
  <li><strong>Campaign Response</strong>: Responses to different promotional campaigns.</li>
  <li><strong>Channel Behavior</strong>: Web, catalog, and in-store purchase information.</li>
</ul>

<h2>🧪 Tools Used</h2>
<ul>
  <li>Python 🐍</li>
  <li>Pandas 📊</li>
</ul>

<h2>✅ Tasks Performed</h2>

<h3>1. Loading and Reading Dataset</h3>
<p>Loaded <code>.csv</code> file using <code>pandas.read_csv()</code> with <code>sep='\t'</code>.</p>

<h3>2. Identifying and Handling Missing Values</h3>
<ul>
  <li>Found missing values in the <code>Income</code> column.</li>
  <li>Filled missing values using <strong>median</strong>.</li>
</ul>

<h3>3. Removing Duplicates</h3>
<ul>
  <li>Dropped duplicate rows using <code>.drop_duplicates()</code>.</li>
</ul>

<h3>4. Standardizing Text Values</h3>
<ul>
  <li>Standardized values in <code>Education</code> and <code>Marital_Status</code>.</li>
  <li>Grouped inconsistent categories like "YOLO", "Alone" into "Single".</li>
</ul>

<h3>5. Date Format Standardization</h3>
<ul>
  <li>Converted <code>Dt_Customer</code> to <code>datetime</code> using <code>pd.to_datetime()</code>.</li>
</ul>

<h3>6. Cleaning Column Names</h3>
<ul>
  <li>Changed all columns to lowercase, used underscores, removed special characters.</li>
</ul>

<h3>7. Fixing Data Types</h3>
<ul>
  <li>Derived <code>Age</code> from <code>Year_Birth</code>.</li>
  <li>Validated numerical and datetime types.</li>
</ul>

<h2>💬 Interview Prep Questions</h2>

<table border="1" cellpadding="6">
  <thead>
    <tr>
      <th>#</th>
      <th>Question</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>What are missing values and how do you handle them?</td></tr>
    <tr><td>2</td><td>How do you treat duplicate records?</td></tr>
    <tr><td>3</td><td>Difference between <code>dropna()</code> and <code>fillna()</code>?</td></tr>
    <tr><td>4</td><td>What is outlier treatment and why is it important?</td></tr>
    <tr><td>5</td><td>Explain standardization of data.</td></tr>
    <tr><td>6</td><td>How do you handle inconsistent date/time formats?</td></tr>
    <tr><td>7</td><td>What are common data cleaning challenges?</td></tr>
    <tr><td>8</td><td>How do you check data quality?</td></tr>
  </tbody>
</table>

<p>✅ Answers are included in the colab Notebook / Script.</p>

<h2>📌 Final Outcome</h2>
<p>A clean and well-structured dataset, ready for:</p>
<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Predictive Modeling</li>
  <li>Customer Segmentation</li>
  <li>Marketing Strategy Development</li>
</ul>

<h2>🔗 Author</h2>
<p><strong>Mounika</strong><br>
Aspiring Data Scientist | Passionate about clean data & insights</p>
