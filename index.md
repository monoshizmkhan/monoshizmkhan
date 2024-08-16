<html>
  <title>Monoshiz Mahbub Khan</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



<style>

.tab {
  overflow: hidden;
  padding-bottom: 3%;
}


.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 1% 1%;
  transition: 0.3s;
  font-size: x-large;
}


.tab button:hover {
  background: rgb(255,255,255);
  background: linear-gradient(90deg, rgba(255,255,255,1) 0%, rgba(220,220,220,1) 50%, rgba(255,255,255,1) 100%);
}


.tab button.active {
  background: rgb(255,255,255);
  background: linear-gradient(90deg, rgba(255,255,255,1) 0%, rgba(240,240,240,1) 50%, rgba(255,255,255,1) 100%);
}


.tabcontent {
  display: none;
}


  footer {
  display: none !important;
}

header {
  display: none !important;
}

::-webkit-scrollbar {
  background: #ffffff
}

::-webkit-scrollbar-track {
  background: #eeeeee;
}

::-webkit-scrollbar-thumb {
  background-color: #bbbbbb;
}

img {
  max-width: 400px;
  max-height: 400px;
  width:auto;
  height:auto;
  border-radius: 50%;
}

.fa:hover {
  opacity: 0.7;
}

.fa-facebook {
  background: #FFFFFF;
  color: #000000;
}

.fa-twitter {
  background: #FFFFFF;
  color: #000000;
}

.fa-github {
  background: #FFFFFF;
  color: #000000;
}

.fa-skype {
  background: #FFFFFF;
  color: #000000;
}

.fa-envelope {
  background: #FFFFFF;
  color: #000000;
}

.fa {
  padding: 20px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  border-radius: 50%;
  filter: grayscale(100%);
}

</style>


<script>

window.onload = function(){document.getElementById('Hm').click();}

function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>




<div>
  
<div style="position: fixed; left: 1%; width: 30%; height: 100%; overflow: auto; background: white">
  <div style="display: flex; align-items: center; justify-content: center"><img src="https://github.com/monoshizmkhan/monoshizmkhan/blob/master/me_in_bonn.jpg?raw=true" style="margin: 0 auto"></div><br><br>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 150%; margin: 0 auto">Monoshiz Mahbub Khan</p></div>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 130%; margin: 0 auto; font-weight: normal; padding-bottom: 2%">(মনসিজ মাহবুব খান)</p></div>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 130%; margin: 0 auto; font-weight: normal">Dhaka, Bangladesh</p></div>
  <div style="display: flex; align-items: center; justify-content: center">
    <a href="mailto:mk7989@g.rit.edu" class="fa fa-envelope"></a>
    <a href="mailto:jishnukhan@gmail.com" class="fa fa-envelope"></a>
    <!-- 
	<a href="live:jishnukhan" class="fa fa-skype"></a> 
    -->
  </div>
  <div style="display: flex; align-items: center; justify-content: center">
    <a href="https://twitter.com/monoshizjishnu" class="fa fa-twitter"></a>
    <a href="https://github.com/monoshizmkhan" class="fa fa-github"></a>
    <a href="https://www.linkedin.com/in/monoshiz-mahbub-khan-85959924b/" class="fa fa-linkedin"></a>
  </div>
  <div style="display: flex; align-items: center; justify-content: center">
    <a href="CV - Monoshiz Mahbub Khan.pdf" class="fa fa-file" download="CV - Monoshiz Mahbub Khan" title="Download my CV!"></a>
  </div>
  
</div>

<div style="position: fixed; top: 5%; right: 2%; width: 65%; height: 100%; padding-bottom: 5%; overflow: auto">
<div class="tab">
	<button id="Hm" class="tablinks" onclick="openTab(event, 'Home')">Home</button>
	<button class="tablinks" onclick="openTab(event, 'Education')">Education</button>
	<button class="tablinks" onclick="openTab(event, 'Experience')">Experience</button>
	<button class="tablinks" onclick="openTab(event, 'ResearchInterests')">Research Interests</button>
	<button class="tablinks" onclick="openTab(event, 'PastProjects')">Past Projects</button>
</div>

<div id="Home" class="tabcontent">
  <p style="font-size: 155%"><b>Hello There!</b></p>
  <p style="font-size: 135%">
  My name is Monoshiz Mahbub Khan. I am a PhD candidate in the PhD in Computing and Information Sciences program at Rochester Institute of Technology, having started in Fall 2021. I am also a graduate research assistant under <a href="https://zhe-yu.github.io/">Dr. Zhe Yu</a> at <a href="https://github.com/hil-se/hil-se/blob/main/README.md">hil-se lab</a>. I am from Dhaka, Bangladesh. I completed my B.Sc. from the department of Computer Science and Engineering, University of Dhaka in 2020. <br> <br>
  I have also worked as a graduate teaching assistant for the course IDAI-720: Research Methods for Artificial Intelligence at Rochester Institute of Technology, taught by Dr. Zhe Yu and Dr. Esa Rantanen. <br> <br>
  From June to August of 2024, I worked as an Intern at ABB AG in Mannheim, Germany through the DAAD Rise Professional Program 2024.
  </p>
</div>

<div id="Experience" class="tabcontent">
  <p style="font-size: 155%">
	<b>Graduate Research Assistant (August 2021 - December 2023, September 2024 - Present)</b><br>
	   I have been working as a graduate research assistant in the Lab of Human-In-the-Loop Software Engineering at Rochester Institute of Technology under the guidance of Dr. Zhe Yu, conducting research primarily on 	   the code search and preference learning tasks.<br><br>
	  
	<b>Graduate Teaching Assistant</b><br>
 	   Worked as a graduate teaching assistant for the course IDAI-720: Research Methods for Artificial Intelligence at Rochester Institute of Technology. Responsibilities included grading and hosting office hours. 	   Course was taught by Dr. Zhe Yu and Dr. Esa Rantanen.<br><br>
     
	<b>Intern</b><br>
 	   Worked as an intern at ABB AG at the Mannheim, Germany office. Work during the internship focused on a Named Entity Recognition project using various methods, including language models, deep learning models 	   and more. The project was conducted under the supervision of Nika Strem. The internship was obtained through the DAAD Rise Professional Program 2024. <br><br>
  </p>
</div>

<div id="Education" class="tabcontent">
  <p style="font-size: 155%">
	I am currently pursuing my PhD in Computing and Information Sciences from Rochester Institute of Technology, having started in 2021.<br><br>
	I completed my undergraduate studies on Computer Science and Engineering from University of Dhaka in 2020. <br><br>
	Before that, I studied at Udayan Higher Secondary School and College from 2002 to 2015.
  </p>
</div>

<div id="ResearchInterests" class="tabcontent">
  <p style="font-size: 155%">
	I am primarily interested in research involving the collaboration between AI and humans to better understand human decision-making and thought processes.<br><br>
	Throughout my doctoral studies, I have worked on the code search task to retrieve programming language artifacts for natural language queries. I have also been working on the preference learning task of modeling 
	comparative human decisions through deep learning models.
  </p>
</div>

<div id="PastProjects" class="tabcontent">

<p style="font-size: 155%;"><b>Video Games</b></p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Kabaddi">Kabaddi (2016)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A video game based on Kabaddi, the national sport of Bangladesh. Made using BGI library in <b>C++</b>. Served as the project for the course Fundamentals of Programming Lab project, in the second semester (2016). A preview of the game can be seen <a href="https://www.youtube.com/watch?v=xQOrrPYQ0u8">here<a/>.<p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Trapped">Trapped (2017)</a></p>
<p style="font-size: 125%; padding-bottom: 3%">A point-and-click puzzle game. Made in <b>JAVA</b>. Served as the project for the course Object Oriented Programming Lab in the third semester (2017).</p>




<p style="font-size: 155%;"><b>Software</b></p>



<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Musyc">Musyc (2017)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A music-based social networking app with a built-in offline music player made for <b>Android</b> in <b>JAVA</b>. Served as the project for the course Application Development Lab in the fourth semester (2017). A preview of the app can be seen <a href="https://www.youtube.com/watch?v=CIsQwhyS0SA">here</a>.</p>


<p style="font-size: 135%"><a href="https://github.com/Saad-Mahmud/EasyML">EasyML (2018)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A web-based application for the purpose of applying and visualizing several machine learning algorithms on datasets. Written using <b>Python</b> and <b>JavaScript</b>. Served as the project in the course Software Engineering Lab in the fifth semester (2018). A preview of the application can be seen <a href="https://www.youtube.com/watch?v=0J6srbmF1pA">here</a>.</p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Pharmassistant">Pharmassistant (2018)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A web-based application designed for the purpose of aiding in a medicine dispensaries, as a tool for inventory, searching, selling and buying of medical products. Written using <b>Python</b> and <b>JavaScript</b>. Served as the project in the course Software Design Patterns Lab in the sixth semester (2018).</p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/CSEDU-Project-Hub">CSEDU Project Hub (2019)</a></p>
<p style="font-size: 125%; padding-bottom: 4%">A web-based application for the purpose of storing, sharing and viewing undergrad research projects. Written in <b>Python</b> and <b>JavaScript</b> as the Internet Programming Lab project in the seventh semester (2019).</p>
	
<p style="font-size: 135%">BackPack (2022)</p>
<p style="font-size: 125%; padding-bottom: 4%">An e-store application for selling hiking, fishing, camping and other miscellaneous equipment. Written using the <b>Java Spring</b> framework and <b>Angular</b> as the Foundations of Software Engineering project (2021).</p>

<p style="font-size: 155%"><b>Undergraduate Research Project</b></p>

<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Bangla-Abstractive-Text-Summarization">Bangla Abstractive Text Summarization using Encoder-Decoder Model (2019)</a></p>
<p style="font-size: 125%; padding-bottom: 8%">A research project on constructing a dataset for the task of abstractive text summarization in Bangla, and constructing a <b>deep learning</b> based model capable of using said dataset. The dataset was constructed after translating the GigaWord dataset for the task of abstractive summarization in English. The model was written in <b>Python</b> using <b>Tensorflow</b> modules. The research was conducted as part of the fourth year final project. Research was conducted under the supervison of <a href="http://www.cse.du.ac.bd/profile/?faculty=AHK">Dr. Muhammad Asif Hossain Khan</a>, Professor, Department of Computer Science and Engineering, University of Dhaka.</p>



</div>

</div>


<div id="Research" class="tabcontent">
  <p style="font-size: 155%">
	I am primarily interested in research involving the collaboration between AI and humans to better understand human decision-making and thought processes.<br><br>
	Throughout my doctoral studies, I have worked on the code search task to retrieve programming language artifacts for natural language queries. I have also been working on the preference learning task of modeling 
	comparative human decisions through deep learning models.
  </p>
</div>
</div>
</html>
