<html>
<head>
<img src="AngellicaM.png" alt="" width="130" height="180">
<style>
.button {
  display: inline-block;
  padding: 15px 25px;
  font-size: 12px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: white;
  background-color: black;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}

.button:hover {background-color: black}

.button:active {
  background-color: black;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
.button1 {
  background-color: white;
  color: black;
  border: 2px solid #e7e7e7;
}
.button2 {
  background-color: white;
  color: black;
  border: 2px solid #555555;
}
.button3 {
  background-color: white; 
  color: black; 
  border: 2px solid #008CBA;
}
#background1 {
  border: none;
  padding: 35px;
  background: #e0ffff;
}
#background2 {
  border: 1px solid black;
  padding: 15px;
  background: #e0ffff;
  background-repeat: no-repeat;
}
</style>
</head>
<body>
  <h1>Hello! Welcome to Angellica's Webpage</h1>
<!---------------------------------------------------About Me Start---------------------------------------------------------->
  <h2>About me</h2>
  <div id="background1">
    <p> I am a Senior at Baruch College majoring in Data Analytics. My programming skills are Python, SQL, and R. I am currently a student at CUNY Tech Prep where I am learning in-demand technologies like Python 3, Jupyter Notebooks, Pandas, Numpy, Scikit-learn, and SQL as well as industry best practices for exploratory data analysis (EDA), feature engineering, data collection and processing, statistical modeling, data visualization, machine learning techniques, data science process, and big data. </p>
  </div>
    
    
  <h2>Check Out My Resume:</h2>
    <button class="button button1" w-50>
     <a href="https://github.com/AngellicaM/AngellicaM.github.io/blob/main/Angellica_Resume.docx">Resume</a>
    </button>
<!-------------------------------------------------------About Me End---------------------------------------------------------->
<!-----------------------------------------------------Project Start----------------------------------------------------------->
  <h2>Projects:</h2>
  <h3>Stock Statistics Project</h3>
  <div id="background2">
    <p> In this project I collected data by use beautiful soup in python to webscrape and used stock API's to collect information about different companies by there stock tickers, which gave generated current infomation such as the stock trading price, opening price, and previous closing price.</p>
  </div>

<!------------------------------------------------------Project End------------------------------------------------------------>
  <h2>Links to LinkedIn and Github:</h2>
    <button class="button button3" w-50>
      <a href="https://www.linkedin.com/in/angellica-munyati/">LinkedIn</a>
    </button>
    <button class="button button2" w-50>
      <a href="https://github.com/AngellicaM">Github</a>
    </button>
</body>
</html>
