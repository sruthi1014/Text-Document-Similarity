# Text-Document-Similarity
<h3>Table of Content:</h3>
</br>
<ul>
  <li>Introduction</li>
  <li>Data Cleaning</li>
  <li>Similarities</li>
  <li>Results</li>
  <li>Data Source</li>
</ul>
<h3>1) Introduction</h3></br>Python code to construct document presentations for documents and measure their similarity
 </br>     
<h3>2) Data Cleaning</h3></br> 
Initial data cleaning process includes removing punctuations, converting to lower case and removing apostrophe. In addition to these, stop words and digits were removed, and stemming was performed. </br>
<h3>3) Similarities</h3></br>
<b>Jaccard similarity</b> was calculated using the formula A <span>&#8745;</span> B / A U B</br>
<b>Cosine similarity</b> was found using the TD/IDF vectorizer and cosine_similarity in Sklearn package
   </br>
<h3>4) Results</h3></br> Similarities of UIC text file with other documents have been obtained(results_git.pdf) based on jaccard and cosine similarity. </br></br>
<h3>5) Data Source</h3></br> The text files that were used in this project are attached in the respository. namely - mit.txt,uiuc.txt,uic.txt,stanford.txt,tesla.txt,uis.txt
 </p>
