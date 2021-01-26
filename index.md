<html>
  <title>Monoshiz Mahbub Khan</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



<style>

.tab {
  overflow: hidden;
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
  <div style="display: flex; align-items: center; justify-content: center"><img src="https://github.com/monoshizmkhan/monoshizmkhan/blob/master/me_for_g.jpg?raw=true" style="margin: 0 auto"></div><br><br>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 150%; margin: 0 auto">Monoshiz Mahbub Khan</p></div>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 130%; margin: 0 auto; font-weight: normal; padding-bottom: 2%">(মনসিজ মাহবুব খান)</p></div>
  <div style="display: flex; align-items: center; justify-content: center"><p style="font-size: 130%; margin: 0 auto; font-weight: normal">Dhaka, Bangladesh</p></div>
  <div style="display: flex; align-items: center; justify-content: center">
    <a href="mailto:2015-318-541@student.cse.du.ac.bd" class="fa fa-envelope"></a>
    <a href="live:jishnukhan" class="fa fa-skype"></a>
  </div>
  <div style="display: flex; align-items: center; justify-content: center">
    <a href="https://twitter.com/monoshizjishnu" class="fa fa-twitter"></a>
    <a href="https://github.com/monoshizmkhan" class="fa fa-github"></a>
  </div>
  
</div>

<div style="position: fixed; top: 5%; right: 2%; width: 65%; height: 100%; padding-bottom: 5%; overflow: auto">
<div class="tab">
	<button id="Hm" class="tablinks" onclick="openTab(event, 'Home')">Home</button>
	<button class="tablinks" onclick="openTab(event, 'Education')">Education</button>
	<button class="tablinks" onclick="openTab(event, 'PastProjects')">Past Projects</button>
</div>

<div id="Home" class="tabcontent">
  <p style="font-size: 155%"><b>Hello There!</b></p>
  <p style="font-size: 135%">
  My name is Monoshiz Mahbub Khan. I am from Dhaka, Bangladesh. I completed my B.Sc. from the department of Computer Science and Engineering, University of Dhaka in 2020.
  This page exists to showcase some of the coursework projects and research projects I completed.
  </p>
</div>


<div id="Education" class="tabcontent">
  <p style="font-size: 155%">
	I completed my undergraduate studies on Computer Science and Engineering from University of Dhaka in 2020. <br>
	Before that, I studied at Udayan Higher Secondary School and College from 2002 to 2015.
  </p>
</div>


<div id="PastProjects" class="tabcontent">

<p style="font-size: 155%;">Video Games</p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Kabaddi">Kabaddi (2016)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A video game based on Kabaddi, the national sport of Bangladesh. Made using BGI library in <b>C++</b>. Served as the project for the course Fundamentals of Programming Lab project, in the second semester (2016). A preview of the game can be seen <a href="https://www.youtube.com/watch?v=xQOrrPYQ0u8">here<a/>.<p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Trapped">Trapped (2017)</a></p>
<p style="font-size: 125%; padding-bottom: 3%">A point-and-click puzzle game. Made in <b>JAVA</b>. Served as the project for the course Object Oriented Programming Lab in the third semester (2017).</p>




<p style="font-size: 155%;">Software</p>



<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Musyc">Musyc (2017)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A music-based social networking app with a built-in offline music player made for <b>Android</b> in <b>JAVA</b>. Served as the project for the course Application Development Lab in the fourth semester (2017). A preview of the app can be seen <a href="https://www.youtube.com/watch?v=CIsQwhyS0SA">here</a>.</p>


<p style="font-size: 135%"><a href="https://github.com/Saad-Mahmud/EasyML">EasyML (2018)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A web-based application for the purpose of applying and visualizing several machine learning algorithms on datasets. Written using <b>Python</b> and <b>JavaScript</b>. Served as the project in the course Software Engineering Lab in the fifth semester (2018). A preview of the application can be seen <a href="https://www.youtube.com/watch?v=0J6srbmF1pA">here</a>.</p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Pharmassistant">Pharmassistant (2018)</a></p>
<p style="font-size: 125%; padding-bottom: 1%">A web-based application designed for the purpose of aiding in a medicine dispensaries, as a tool for inventory, searching, selling and buying of medical products. Written using <b>Python</b> and <b>JavaScript</b>. Served as the project in the course Software Design Patterns Lab in the sixth semester (2018).</p>


<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/CSEDU-Project-Hub">CSEDU Project Hub (2019)</a></p>
<p style="font-size: 125%; padding-bottom: 4%">A web-based application for the purpose of storing, sharing and viewing undergrad research projects. Written in <b>Python</b> and <b>JavaScript</b> as the Internet Programming Lab project in the seventh semester (2019).</p>

<p style="font-size: 155%">Undergraduate Research Project</p>

<p style="font-size: 135%"><a href="https://github.com/monoshizmkhan/Bangla-Abstractive-Text-Summarization">Bangla Abstractive Text Summarization using Encoder-Decoder Model (2019)</a></p>
<p style="font-size: 125%; padding-bottom: 8%">A research project on constructing a dataset for the task of abstractive text summarization in Bangla, and constructing a <b>deep learning</b> based model capable of using said dataset. The dataset was constructed after translating the GigaWord dataset for the task of abstractive summarization in English. The model was written in <b>Python</b> using <b>Tensorflow</b> modules. The research was conducted as part of the fourth year final project. Research was conducted under the supervison of <a href="http://www.cse.du.ac.bd/profile/?faculty=AHK">Dr. Muhammad Asif Hossain Khan</a>, Professor, Department of Computer Science and Engineering, University of Dhaka.
This work has been submitted to the special issue "Special Issue on Deep Learning for Low-Resource Natural Language Processing" (2020) of the journal ACM Transactions on Asian and Low-Resource Language Information Processing (TALLIP).</p>


</div>


<div id="ResearchInterests" class="tabcontent">
  <p style="font-size: 155%">
	I am primarily interested in research involving the collaboration between AI and humans to better understand human decision-making and thought processes.
  </p>
</div>



</div>
</div>
</html>
