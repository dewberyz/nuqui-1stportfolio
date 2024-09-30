<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="stylesheet" href="style.css">
</head>
<body>
<section class="home" id="home">
<div class="circle"></div>
<header>
<a href="#"><img src="C:\Users\acer\Downloads\logo (1).jpg" class="logo"></a>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#activities">Activities</a></li>
<li><a href="#lessons">Lessons</a></li>
<li><a href="#reflection">Reflection</a></li>
</ul>
</header>
<div class="content">
<div class="textBox">
<h2>Dewi Nuqui's<br>ICT <span>e-portfolio!</span></h2>
<p>Welcome to my e-portfolio, a curated collection showcasing my activities, outputs, and reflection. Here, you'll delve into my journey of growth and learning, highlighting key projects and experiences that illustrate my skills and insights during the first quarter of 9th grade. I hope this reflects my ultimate commitment to continuous improvement and personal development.</p>
<a href="#">Learn More</a>
</div>
<div class="imgBox">
<img src="C:\Users\acer\Downloads\sonnyangel.png" class="dewi">
</div>
</div>
<ul class="sonnyangel">
<li><img src="C:\Users\acer\Downloads\sonnyangel.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel.png')"></li>
<li><img src="C:\Users\acer\Downloads\sonnyangel1.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel1.png')"></li>
<li><img src="C:\Users\acer\Downloads\sonnyangel2.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel2.png')"></li>
</ul>
<ul class="sci">
<li><a href="#"><img src="C:\Users\acer\Downloads\facebook.png"></a></li>
<li><a href="#"><img src="C:\Users\acer\Downloads\twitter.png"></a></li>
<li><a href="#"><img src="C:\Users\acer\Downloads\instagram.png"></a></li>
</ul>
</section>
<script type="text/javascript">
function imgSlider(anything){
document.querySelector('.dewi').src=anything;
}
</script>

<section class="about" id="about">
<div class="content1">
<div class="textBox1">
<h2>Get to Know<br><span>Dewi Nuqui!</span></h2>
<p>Hello! My name is Princess Dewi L. Nuqui, please call me Dewi. I’m 14 years old and my birthday is on July 26, 2010. I study at Las Pinas City National Science High School. I love dancing, listening to music, graphic designing, doing math, and eating.<br><br>
I am currently in 9 - Family, but I was once in 8 - Consideration and 7 - Blessedness. I was the class muse of 8 - Consideration ('23-'24). </p><br><br>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<div class="table">
<table style="width:50%" align="center">
  <tr>
    <td><img src="C:\Users\acer\Downloads\baby1.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby2.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby3.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby4.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby5.png" alt="baby" style="width:250px;height:250px;"></img></td>
  </tr>
</table>
</div>
</div>
</div>

</section>



<section class="activities" id="activities">
    <div class="container">

        <div class="slide">

            <div class="item" style="background-image: url(https://tinyurl.com/4tbxn5v6);">
                <div class="content">
                    <div class="name">Volleyball Practice</div>
                    <div class="des">This is my group (RBC) after our volleyball practice. This practice occured before our first match against BINI. Sadly, we lost.</div>
                    <button>See More</button>
                </div>
            </div>
            
            <div class="item" style="background-image: url(https://tinyurl.com/33cp34p4);">
                <div class="content">
                    <div class="name">Activities of 9-Family</div>
                    <div class="des">In this section, you will be able to see the activities that our section, 9-Family did.</div>
                    <button>See More</button>
                </div>
            </div>
            <div class="item" style="background-image: url(https://tinyurl.com/yzmsj6mb);">
                <div class="content">
                    <div class="name">Volleyball</div>
                    <div class="des">We had volleyball for the 1st quarter in Physical Education. There were 3 groups: Group 1 White Blood Cells, Group 2 Bini, and Group 3 Red Blood Cells (my group!). The overall winner is group BINI (2-0). This photo was taken on the last day of our volleyball session.</div>
                    <button>See More</button>
                </div>
            </div>
            <div class="item" style="background-image: url(https://tinyurl.com/yd7n62vz);">
                <div class="content">
                    <div class="name">Extemporaneous Speech</div>
                    <div class="des">We had our extemporaneous speech for English just recently. It was an unplanned speech and we will be given a topic that other sections wrote. It took 4 days for this to finish.</div>
                    <button>See More</button>
                </div>
            </div>
            <div class="item" style="background-image: url(https://tinyurl.com/yk3fvx9j);">
                <div class="content">
                    <div class="name">Inaugural Speech</div>
                    <div class="des">Before extemporaneous speech, we had our inaugural speech. We were given a week to draft and practice our speech. We were grouped into 4 so that other members of the group can give feedback and suggestions to the speaker.</div>
                    <button>See More</button>
                </div>
            </div>
            <div class="item" style="background-image: url(https://tinyurl.com/3wxk2v27);">
                <div class="content">
                    <div class="name">Lipunang Sibil Making in ESP & A.P</div>
                    <div class="des">This was a performance task for ESP and A.P. 'Lipunang Sibil' is the place outside the family, the state, and the economy where people interact to promote common aspirations or goals.</div>
                    <button>See More</button>
                </div>
            </div>

        </div>

        <div class="button">
            <button class="prev"><</button>
            <button class="next">></button>
        </div>

    </div>
</section>
<script>
let next = document.querySelector('.next')
let prev = document.querySelector('.prev')

next.addEventListener('click', function(){
let items = document.querySelectorAll('.item')
document.querySelector('.slide').appendChild(items[0])
})

prev.addEventListener('click', function(){
    let items = document.querySelectorAll('.item')
    document.querySelector('.slide').prepend(items[items.length - 1]) // here the length of items = 6
})
</script>
</section>


<section class="lessons" id="lessons">
<div class="content2">
<div class="textBox2">
<h2>Lessons in<br><span>1st Quarter</span></h2>
</div>
<div class="lesson">

<ol>
<li><b>XHTML</b></li>
<ul>
<li>eXtensible HyperText Markup Language.</li>
<li>The ”x” came from XML or eXtensible Mark-up Language.</li>
<li>Though different from HTML, XHTML also uses the filename extension .html</li>
<li>The content of the actual coding might change because of XHTML conventions but it still holds the same filename extension.</li>
<li>Stricter and cleaner version of HTML</li>
<li>Aimed to replace HTML</li>
<li>All new Web browsers support XHTML</li>
</ul><br>

<li><b>HTML LISTS</b></li>
<ul>
<li>Used to specify lists of information</li>
<li>All lists may contain one or more list elements. 3 types of HTML lists:</li>
<ol>
<li>Ordered List or Numbered List (ol)</li>
<li>Unordered List or Bulleted List (ul)</li>
<li>Description List or Definition List/Glossary List (dl)</li>
</ol>
</ul><br>

<li><b>HTML TABLES</b></li>
<ul>
<li>Allow you to organize and arrange data into columns and rows.</li>
<li>Allow you to divide your page into sections where you can place headers, footers and navigation links.</li>
<li>Made up of rows and columns</li>
<li><table>
  <tr>
    <th>Likes</th>
    <th>Dislikes</th>
    <th>Neutral</th>
  </tr>
  <tr>
    <td>Mathematics</td>
    <td>Science</td>
    <td>Araling Panlipunan</td>
  </tr>
  <tr>
    <td>Purple</td>
    <td>Brown</td>
    <td>Orange</td>
  </tr>
</table>
</ul><br>

<li><b>HYPERLINKS</b></li>
<ul>
<li>A reference link that allows you to navigate to another page of the same document or to another document.</li>
<li><a href=”mailto:princess0726.nuqui@gmail.com”>Email me now</a>
</ul><br>

<li><b>HTML FORMS</b></li>
<ul>
<li>Allows you to gather feedback to provide better service</li>
<li>Purposely designed for gathering information on the Internet. These HTML documents are sent back to the server once the user submits them.</li>
<li><form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname"><br>
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
</form></li>
<li><form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form></li>
<li><form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a phone</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a laptop</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a tablet</label>
</form></li>
<li><textarea name=“sanrio”></textarea></li>
</ul><br>
</ol>
</div>
</section>

<section id="reflection">


<div class="content3">
<div class="textBox3">
<h2>Reflection</h2>
<p>As I look back on the first quarter of the school year, I’m amazed at how much I’ve learned about HTML and how it has shaped my understanding of web development. Starting from scratch, I was initially overwhelmed by the quantities of tags and attributes, but with practice and persistence, I’ve made significant strides.<br><br>

As I delved deeper, I learned about the importance of semantic HTML. A pivotal skill I developed was working with links and images. I learned how to use the <a> tag to create hyperlinks and the < img > tag to embed images, which brought my web pages to life. Experimenting with attributes like target, alt, and src enhanced my understanding of how to optimize web content for different devices and improve usability.<br><br>

I started exploring forms, which opened up new possibilities for interaction on my web pages. Implementing < form >, < input >, and < button > elements helped me understand how to gather user input and create a more dynamic experience. I found it rewarding to see how HTML can facilitate communication between users and websites.<br><br>

Looking ahead, I’m excited to build on these foundational skills. I recognize that mastering HTML is just the beginning of my journey in web development, and I’m eager to integrate CSS and JavaScript into my skill set. Overall, the first quarter has been a fantastic introduction to HTML, and I feel more confident in my abilities as I continue to explore the world of web design.<br><br>

</p>
</body>
</html>





