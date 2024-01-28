<h1>Project Description</h1>

<p>This GitHub repository encapsulates a streamlined data preparation project conducted in Google Colab. Focused on the <a href="Bitter.csv">"Bitter" dataset</a> from Bitter DB, the project systematically transforms raw data into a refined state, meticulously tailored for machine learning applications. The Bitter DB dataset contains 1527 Non-bitter compounds and 547 Bitter compounds. For more information about the dataset, visit the <a href="http://bitterdb.agri.huji.ac.il/dbbitter.php">Bitter DB website</a>. From binary transformations to feature selection and visualization, each step is intricately designed to distill meaningful insights. The repository includes the <a href="data_prep_BitterDB.ipynb">notebook with the script</a>, code snippets, visualizations, and exported datasets (<a href="raw_prepared_dataframe.xlsx">raw_prepared_dataframe</a> and <a href="normalized_dataframe.xlsx">normalized_dataframe</a>).</p>

<h2>Project Steps:</h2>

<ol>
  <li><strong>Data Introduction:</strong>
    <ul>
      <li>Loading and preliminary exploration revealed the dataset's structure.</li>
    </ul>
  </li>

  <li><strong>Binary Transformation:</strong>
    <ul>
      <li>Columns with two unique values were seamlessly transformed to numeric format.</li>
    </ul>
  </li>

  <li><strong>Numeric Transition:</strong>
    <ul>
      <li>Non-numeric columns were systematically removed for a fully numeric representation.</li>
    </ul>
  </li>

  <li><strong>Missing Values Handling:</strong>
    <ul>
      <li>Rigorous identification and imputation using the median ensured data completeness.</li>
    </ul>
  </li>

  <li><strong>Feature Focus:</strong>
    <ul>
      <li>Unnecessary features were systematically dropped, streamlining the dataset.</li>
    </ul>
  </li>

  <li><strong>Key Feature Identification:</strong>
    <ul>
      <li>Utilizing a Random Forest classifier, influential features were pinpointed.</li>
    </ul>
  </li>

  <li><strong>Visual Insight:</strong>
    <ul>
      <li>Histograms and boxplots visually depicted feature characteristics.</li>
    </ul>
  </li>

  <li><strong>Data Export:</strong>
    <ul>
      <li>Two Excel files, encapsulating the prepared dataset and a normalized version, were crafted for further analysis.</li>
    </ul>
  </li>
</ol>
