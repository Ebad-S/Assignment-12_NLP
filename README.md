<div id="top"></div>

<h1 align="center">Assignment Unit 12 - Sentiment Analysis</h1>

<div align="center">    
        <img src="Images/logo.png"/>
        <section> <b>By: Ebad Salehi </b> </section>
</div>

<br><br>
<div align="center">
————————————————————————
<br>
<!-- TABLE OF CONTENTS -->
<details align="center">
  <summary> <b>Table of Contents</b></summary>
  <ul>
        <li><a href="#fetch">Fetch the News</a></li>   
        <li><a href="#NLP">NLP</a></li> 
        <li><a href="#NER">NER</a></li> 
        <li><a href="#files">Code (.ipynb)</a></li> 
        <li><a href="#tech">Technologies Used</a></li>    
  </ul>
</details>
————————————————————————
</div><br>


<h2> Overview </h2>
<div id="fetch">
    
<h3>Section 1: Fetch the News Articles</h3>    
    <p>Using the <a href="https://newsapi.org/"> newsapi</a> to fetch the latest news articles for Bitcoin and Ethereum, we can create a DataFrame of <b>Sentiment Scores</b> for each coin. Then using <u>Descriptive Statistics</u> to answer some questions.</p>
        
>You need to have your "NEWS_API_KEY" stored in `.env` file to run the code on your >local computer.
 
Ploting the Bitcoin and Ethereum Headlines Sentiment Chart:
<section align="center">    
    <img src="Images/btc_headlines_sentiment_chart.png"/>
    <img src="Images/eth_headlines_sentiment_chart.png"/>
    <img src="Images/btc_describe.PNG"/>
</section>    
    <div align="right">(<a href="#top">↥ back to top</a>)</div>
</div><br>
<hr>
<div id="NLP">
    
<h3>Section 2: Natural Language Processing (NLP)</h3>
   <li>Tokenizer: Using NLTK and Python to tokenize the text for each coin.</li>
   <li> NGrams and Frequency Analysis: looking at the ngrams and word frequency for each coin.</li>      <li>Word Clouds: Generating word clouds for each coin to summarize the news for each coin.</li>
   <section align="center">    
        <img src="Images/btc_word_cloud.png"/>
        <img src="Images/eth_word_cloud.png"/>        
    </section>    
<div align="right">(<a href="#top">↥ back to top</a>)</div>
</div><br>
<hr>
<div id="NER">
    
<h3>Section 3: Named Entity Recognition (NER)</h3>
    <p> building a NER model for both Bitcoin and Ethereum, then visualizing the tags using SpaCy.</p>  
 <section align="center">    
        <img src="Images/btc_NER.PNG"/>
        <br><br>
        <img src="Images/eth_NER.PNG"/>        
    </section>       
<div align="right">(<a href="#top">↥ back to top</a>)</div>  
</div><br>

<div id="files">

<h2> Files </h2>
    
Find the code in `.ipynb` format (Jupyter-Lab notebook):
    
[Crypto Sentiment](Codes/crypto_sentiment.ipynb)

</div><br>

<div id="tech">
	
<h2> Technologies Used: </h2>
	
   - NLTK
   - matplotlib  
   - Pandas
   - Python
   - API     
   - Jupyetr notebook

</div>

<div align="right">(<a href="#top">↥ back to top</a>)</div>
<br/>
