<h1>Pathrise Career Conversation NLP Project</h1>

<p>
  This project demonstrates how <strong>Natural Language Processing (NLP)</strong>
  and data preprocessing can be used to better understand career coaching conversations
  and job-search challenges.
</p>

<p>
  The goal of this project is to prepare Pathrise candidate data for a future chatbot
  or recommendation system that can support users with career guidance based on their
  background, job-search stage, and biggest challenges.
</p>

<h2>Project Overview</h2>

<p>
  Pathrise supports job seekers through coaching, interview preparation, and career guidance.
  In this project, I worked with structured candidate data and text-based career challenge
  responses to explore how NLP can help organize and interpret user needs.
</p>

<p>
  The dataset includes information such as career track, employment status, education level,
  job-search length, work authorization, number of applications, number of interviews, and
  each candidate’s biggest challenge in the job search.
</p>

<h2>Workflow</h2>

<ul>
  <li>Loaded the Pathrise dataset from Excel</li>
  <li>Explored candidate information and placement outcomes</li>
  <li>Cleaned text from the <strong>biggest_challenge_in_search</strong> field</li>
  <li>Removed special characters, extra spaces, and stopwords</li>
  <li>Converted text to lowercase for consistency</li>
  <li>Encoded categorical fields such as career track and employment status</li>
  <li>Created additional features such as placement flag and job-search group</li>
  <li>Prepared the dataset for future chatbot training or predictive modeling</li>
</ul>

<h2>Exploratory Data Analysis</h2>

<p>
  The analysis helps identify common job-search pain points, such as hearing back from
  applications, passing interviews, choosing the right jobs, and improving technical skills.
</p>

<!-- Add your EDA screenshot here -->
<img src="images/pathrise_challenge_distribution.png" alt="Pathrise Job Search Challenge Distribution" width="850">

<p>
  This step is important because it shows what candidates struggle with most, which can help
  design a more useful chatbot or coaching support system.
</p>

<h2>Text Preprocessing</h2>

<p>
  The text preprocessing step focused on cleaning the candidate challenge responses so they
  could be used in NLP workflows.
</p>

<p>
  For example, a response like:
</p>

<p>
  <em>"Hearing back on my applications"</em>
</p>

<p>
  was cleaned into:
</p>

<p>
  <strong>"hearing back applications"</strong>
</p>

<!-- Add text cleaning screenshot here -->
<img src="images/text_preprocessing_sample.png" alt="Text Preprocessing Example" width="850">

<h2>Feature Engineering</h2>

<p>
  In addition to text cleaning, categorical and numerical features were prepared for modeling.
  This included encoding career tracks, employment status, placement outcome, and grouping
  job-search duration into simpler categories.
</p>

<h2>Key Insight</h2>

<p>
  The project shows that career-support data can be transformed into a structured NLP-ready
  format. By cleaning job-search challenge text and combining it with candidate profile data,
  the foundation is created for a chatbot that can provide more personalized career guidance.
</p>

<h2>Output</h2>

<p>
  The final output is a cleaned and preprocessed dataset that can be used for future NLP modeling,
  chatbot development, or candidate success prediction.
</p>

<h2>Project Files</h2>

<ul>
  <li><strong>01_NLP_Proposal_NLP for Pathrise Conversations.docx</strong> — project proposal</li>
  <li><strong>02_Data_Wrangling_Pathrise_NLP.ipynb</strong> — data cleaning and preparation</li>
  <li><strong>03_EDA_Pathrise_NLP.ipynb</strong> — exploratory data analysis</li>
  <li><strong>04_Pre_Processing_Pathrise_NLP.ipynb</strong> — NLP preprocessing and feature engineering</li>
  <li><strong>Data_Pathrise.xlsx</strong> — source dataset</li>
</ul>

<h2>Tools and Technologies</h2>

<ul>
  <li><strong>Python</strong></li>
  <li><strong>Pandas</strong> and <strong>NumPy</strong></li>
  <li><strong>NLTK</strong></li>
  <li><strong>Scikit-learn</strong></li>
  <li><strong>Matplotlib</strong> and <strong>Seaborn</strong></li>
  <li><strong>WordCloud</strong></li>
  <li><strong>Jupyter Notebook / Google Colab</strong></li>
</ul>

<h2>Skills Demonstrated</h2>

<ul>
  <li>Natural Language Processing</li>
  <li>Text cleaning and preprocessing</li>
  <li>Exploratory data analysis</li>
  <li>Feature engineering</li>
  <li>Categorical encoding</li>
  <li>Career analytics and chatbot data preparation</li>
</ul>

<h2>Author</h2>

<p>
  <strong>Nahid Mozhdehi</strong><br>
  Data & GIS Analyst with experience in Python, NLP, data analysis, and machine learning workflows
</p>
