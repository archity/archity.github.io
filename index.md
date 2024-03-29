---
layout: default
---

<style>
.arcimg
{
  padding: 2px;
  border-radius:50%;
  max-width: 100%;
  height: auto;
}
.iconimg
{
  padding: 4px;
  width: 40px;
}
</style>

<meta name="description" content="Personal website of Archit Yadav" />
<meta name="title" property="og:title" content="Personal Website" />
<meta property="og:type" content="_" />
<meta name="image" property="og:image" content="https://github.com/archity/archity.github.io/blob/master/images/archityadav_1000px.jpg?raw=true" />
<meta name="description" property="og:description" content="_" /><meta name="author" content="Archit Yadav" />

<a href="mailto:archityadav97@gmail.com"><img src="images/gmail_dark_circular.svg" class="iconimg" width = 50px></a>
<a href="mailto:archit.yadav@etu.univ-grenoble-alpes.fr"><img src="images/uga_146px.png" class="iconimg" width = 50px></a>
<a href="https://github.com/archity/"><img src="images/github.svg" class="iconimg" width = 50px></a>
<a href="https://www.linkedin.com/in/archit-yadav-95482b156/"><img src="images/linkedin_icon_circle.svg" class="iconimg" width = 50px></a>
<a href="https://medium.com/@archityadav97"><img src="images/medium_circular.svg" class="iconimg" width = 50px></a>
<a href="https://open.spotify.com/user/ht3095oj4tv2bn2j64ppw87mm?si=02be29f02813407b"><img src="images/spotify.svg" class="iconimg" width = 50px></a>


<img src="./images/archityadav_1000px.jpg" class="arcimg" align="right" style="margin:5px" width = "180">

Hi there!

I'm a master's student currently pursing my MSc. in Computer Science from Université Grenoble Alpes specializing in Human and Digital World Interaction (HDWI).

My main fields of interests broadly are Machine Learning, Embedded Systems, and Signal Processing.

Specific fields of interests:
* 📜 Natural Language Processing (NLP),
* 🎵 Audio-based AI, or Music Information Retrieval (MIR).
* 📡 ML-based Signal Processing

In my free time, I enjoy drawing/sketching. Reading is another hobby of mine since a long time. Here are some of my [artworks](#artworks), and my current [reading](./reads.html) list.

Organisation of rest of this website as follows:

- [Education](#education)
- [Work Experience](#work-experience)
- [Projects](#projects)
- [Publications](#publications)
- [Artworks](#artworks)

<br><br><br>


<style>
.edu table
{
  border: none;
}

.edu tr
{
  border: none;
}

.edu td
{
  background: none;
  border: 1px solid gray;

  width:500px;
  overflow:hidden;
  word-wrap:break-word;
  vertical-align: top;
}
.edu img
{
  width: 180px;
  padding: 20px;
  Padding: 0px;
}
</style>

# Education

<table align=center class="edu" style="background-color: rgb(0, 0, 0)">
  <tbody>
    <tr>
      <td>
      <h2> MSc. Computer Science (MoSIG)</h2>
      <img src="./images/ensimag_uga_logo.png" width = "200" align = "right" style="padding:10px">
      <ul>
        <li> Université Grenoble Alpes (UGA) - ENSIMAG </li>
        <li>Grenoble, France</li>
        <li>Specialization: Human and Digital World Interaction (HDWI)</li>
        <li>Grad year: 2022</li>
        <li>Courses taken in HDWI:</li>
        <ul>
          <li>Robotics</li>
          <li>Human in the Loop</li>
          <li>Augmented and Virtual Reality</li>
          <li>Computer Vision</li>
          <li>Natural Language Processing</li>
          <li>Machine Learning for Multimodal Data</li>
        </ul>
      </ul>
      <br>
      <h2>B.Tech. Electronics & Communication</h2>
      <img src="./images/snu_logo.jpg" width = "180" align = "right" style="padding:10px">
      <ul>
        <li>Shiv Nadar University (SNU)</li>  
        <li>Greater Noida, India</li>
        <li>Grad year: 2019</li>
        <li>Thesis: Background Study and Hardware/Software Implementation of MIMO</li>
      </ul>
      </td>
    </tr>
  </tbody>
</table>



<br><br><br>

<style>
.work table
{
  border: none;
  background-color: #bde9ba;
}

tr
{
  border: none;
}

.work td
{
  background: none;
  border: 1px solid gray;

  width:500px;
  overflow:hidden;
  word-wrap:break-word;
  vertical-align: top;
}
.work img
{
  height: 120px;
  padding: 25px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  Padding: 0px;
}
</style>

# Work Experience

<table align=center class="work" style="background-color: rgb(0, 0, 0)">
  <tbody>
    <tr>
      <td>
        <h2><center>Machine Learning Research Intern</center></h2>
        <h3><center>Qualcomm</center></h3>
        <img src="./images/qualcomm-logo.svg"  width=250>
      </td>
      <td>
        <h2><center>Open-Source NLP Researcher</center></h2>
        <h3><center>The Sound of AI</center></h3>
        <img src="./images/guitar_acoustic_720p.jpg">
      </td>
    </tr>
  </tbody>
</table>

<br>

More on experience [here](./Experience.html)

<br><br><br>

<style>
.project img
{
  border-radius:10%;
  Padding: 0px;
}
.project table
{
  border: none;
  vertical-align: top;
}
.project td
{
  background: none;
  border: 1px solid gray;

  width:500px;
  overflow:hidden;
  word-wrap:break-word;
  vertical-align: top;
}
ul
{
  text-align: left;
}
</style>


# Projects


<table align=center class="project" style="background-color: rgb(0, 0, 0)">
  <tbody>
    <tr>
      <!-- Cell 1 -->
      <td style="text-align: center; vertical-align: middle;"><br>
      <h3>Music Processing and Genre Classifier using DSP and Deep Learning</h3><br>
      <img src="./images/audio_signal.jpeg" height = "150" style="margin:10px">
      <ul>
        <li> Goal: Understand audio as input data and identify its characteristics; Build a model to distinguish different genres of music using Digital Signal Processing and RNN/LSTM architectures </li>
        <li> Performed basic audio data analysis like waveform, spectrogram, Extracting MFCCs </li>
        <li> Implemented a music genre classifier based on dataset of GTZAN; Built dataset based on extracted MFCCs from audio files; Experimented with Basic Neural Network, CNN and RNN (LSTM) </li>
        <li> Currently in process of predicting genre from Spotify songs </li>
        <li> <a href="https://github.com/archity/music-processing">GitHub repository</a> </li>
      </ul>
      </td>
      <!-- Cell 2 -->
      <td style="text-align: center; vertical-align: middle;">
      <h3>Understanding COVID-19 Trends on Twitter using NLP</h3><br>
      <img src="./images/wordclouds_all.png" height = "150" style="margin:10px">
      <ul>
        <li> Goal: Understand the trends and the changing trends on Twitter throughout the year 2020 related to the COVID-19 pandemic; Understand, correlate and verify the findings with respect to the real-world news/data </li>
        <li> Implemented a shell script for creating a command-line based scrapper for several 1000s of tweets from Twitter </li>
        <li> Cleaned extracted tweets; Applied various analysis techniques like wordclouds, trend of a given word w.r.t. month; TextBlob and logistic regression for sentiment analysis </li>
        <li> <a href="https://github.com/archity/covid-twitter-trends">GitHub repository</a> </li>
      </ul>
      </td>
    </tr>
    <tr>
      <!-- Cell 3 -->
      <td style="text-align: center; vertical-align: middle;"><br>
      <h3>Document Scanner and Summarizer using OpenCV and PyTextRank</h3> <br>
      <img src="./images/doc_scanner_kindle.jpg" height = "150" style="margin:10px">
      <ul>
        <li> Goal: Create an image scanner and summarizer; Understand the pipeline behind mainstream doc scanner apps and apply Computer Vision and NLP to build a doc scanning prototype </li>
        <li> Image processing pipeline utilizing OpenCV constructed; blurring, edge detection, warping, thresholding </li>
        <li> Text summarization to generate a summary and key phrases from the scanned text </li>
        <li> <a href="https://github.com/archity/doc-scanner">GitHub repository</a> </li>
      </ul>
      </td>
      <!-- Cell 4 -->
      <td style="text-align: center; vertical-align: middle;"><br>
      <h3>3D Graphics based Medieval Scene using OpenGL</h3><br>
      <img src="./images/city_view_night.jpg" height = "150">
      <ul>
        <li> Goal: Create a 3D scene with medieval period as a theme, for the course 3D Graphics </li>
        <li> Understood the basic graphics processing pipeline including rasterization, modelling, rendering and animation </li>
        <li> Added several effects including multiple point lights based on day/night, fog, multi texturing based blend-map, keyframe + procedural animation, and sound effects, to name a few </li>
        <li> Game-like interface created with 1st person POV </li>
        <li> <a href="https://github.com/archity/3d-graphics-project">GitHub repository</a> </li>
      </ul>
      </td>
    </tr> 
  </tbody>
</table>

<br><br><br>

# Publications

<table align=center class="edu" style="background-color: rgb(0, 0, 0)">
  <tbody>
    <tr>
      <td>
        <h2>Research Paper</h2>
        <ul>
          <li><i>"First Steps Towards Runtime Hardware Trojan Detection in Microprocessors through Software Diversity"</i></li>
          <li><i>"Towards Common Reference Methods to Evaluate Detection Techniques for Hardware Trojans in Microprocessors"</i></li>
          <ul>
              <li> Two joint research papers expected to be published at a conference </li>
              <li> Result of work done in internship at LIRMM under Prof. Giorgio Di Natale </li>
              <li><a href="https://drive.google.com/file/d/1AGi2RDS6ohoc4FFPb4kj4tXz4aAx9BZ-/view?usp=sharing">Paper snippet</a></li>
          </ul>
          <li><i>"From Words to Sound: Neural Audio Synthesis of Guitar Sounds with Timbral Descriptors"</i></li>
          <ul>
              <li> Accepted for publication in <a href="https://2022.aimusiccreativity.org/">AIMC 2022</a> conference on July 11</li>
              <li> Result of an Open-Source Research (OSR) work done with 150+ people of The Sound of AI OSR community </li>
              <li><a href="https://drive.google.com/file/d/1g4TyGQk9SLIa8gXHMTecLVQ7h99lc3rd/view?usp=sharing">Paper abstract</a></li>
          </ul>
        </ul>
        <br>
        <h2>Medium Articles</h2>
        <b>Towards Data Science</b>
        <ul>
        <li><a href="https://towardsdatascience.com/generating-expanding-your-datasets-with-synthetic-data-4e27716be218"><i>"Generating/Expanding your datasets with synthetic data"</i></a></li>
        <li><a href="https://towardsdatascience.com/modeling-and-generating-time-series-data-using-timegan-29c00804f54d"><i>"Modeling and Generating Time-Series Data using TimeGAN"</i></a></li>
        <ul>
            <li> Both articles featured as a   post by TDS' official LinkedIn page</li>
            <li> <a href="https://www.linkedin.com/posts/towards-data-science_generatingexpanding-your-datasets-with-synthetic-activity-6830942570487578624-cbWN">LinkedIn post 1 </a> </li>
            <li> <a href="https://www.linkedin.com/posts/towards-data-science_modeling-and-generating-time-series-data-activity-6842039187789754368-rUPi">LinkedIn post 2 </a> </li>
        </ul>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<br><br><br>

# Artworks

Some of my favourite drawings. More can be found on my [Instagram](https://www.instagram.com/architydraws/) drawing acccount.

<br>

<style>
  .art table
  {
    border: none;
  }
  .art td
  {
    background: none;
    border: 1px solid gray;
  }
</style>

<table border=0px rules=none class=art style="background-color: rgb(0, 0, 0)">
  <tbody>
    <tr>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/greenleaf_procreate.jpg" width = "200">
      <br><br><br></td>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/LaurenCohanPortrait.jpg" width = "200">
      <br><a href="./images/Drawings/LaurenCohan_1minute_Black_Audio_ZoomEffect.mp4" style="font-size: 12px">Timelapse video</a><br>
      <p style="font-size: 11px">
      (Music credits: Black by <a href="https://youtu.be/xUCxxp1IZdY" style="font-size: 11px">Kari Kimmel</a>)</p></td>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/dragon_procreate.jpg" width = "200">
      <br><br><br>
      </td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/LindseyStirlingPortrait.jpg" width = "200">
      <br><a href="./images/Drawings/LindseyStirling_15sec_NoFlicker.mp4" style="font-size: 12px">Timelapse video</a><br><br></td>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/daftpunk_procreate.jpg" width = "200">
      <br><br><br></td>
      <td style="text-align: center; vertical-align: middle;"><img src="./images/Drawings/TheNightKingPortrait.jpg" width = "200">
      <br><a href="./images/Drawings/TNKWithAudio_Cropped.mp4" style="font-size: 12px">Timelapse video</a><br>
      <p style="font-size: 11px">(Music credits: The Night King by <a href="https://youtu.be/k1frgt0D_f4" style="font-size: 11px">Ramin Djawadi</a>)</p></td>
    </tr> 
  </tbody>
</table>

<br><br>

<h2> Featured artwork </h2>

A timelapse video portrait I made of Steve Jobs was featured by my university's drawing club.

<a href="https://fb.watch/2xXxcg3SXF/" target="_blank">
<img src="./images/kalakriti_steve_jobs_fb_thumbnail.png" height = "300" align="center">
</a>

