HTML code
=====
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Home Page</title>
    <link rel="stylesheet" href="./mystyle.css">
    <meta charset="UTF-8">
</head>

<body>
    <div class="header">
        <p>Hi! This is Neng Zhang!</p>
    </div>
    <div class="rttop">
        <a href="#" >Top</a>
    </div>
    <div class="container">
        <div class="row">
            <div class="menu col-3">
                <ul>
                    <li><a class="button" href="#personal_inf">Personal Information</a></li>
                    <li><a class="button" href="#hobbies">Hobbies</a></li>
                    <li><a class="button" href="#flink">Favourite Links</a></li>
                    <li><a class="button" href="http://www.xjtlu.edu.cn">XJTLU</a></li>
                    <li><a class="button" href="https://www.liverpool.ac.uk/">UoL</a></li>
                    <li><a class="button" href="https://www.liverpool.ac.uk/computer-science/">Department of Computer Science</a></li>
                </ul>
            </div>
            <div class="content col-9">
                <div class="row">
                    <div id="personal_inf">
                        <h1>Personal Information</h1>
                        <p style="padding:10px">My name is Neng Zhang, and I'm a <a href="http://www.xjtlu.edu.cn"><em><strong>XJTLU</strong></em></a>
                            year 2 student. My major is Information and Computing Science.
                            In the following 2 years, I will continue to complete my undergradute degree in the
                            <a href="https://www.liverpool.ac.uk/"><em><strong>University of Liverpool(UoL)</strong></em></a>.
                             This is my home page for recording my hobbies and my favourite links.</p>

                    </div>
                    <p style="padding:10px"></p>
                    <div id="hobbies">
                        <h1>Hobbies</h1>
                        <h2 style="padding:30px">Reading</h2>
                        <div class="row">
                            <div class="image col-4">
                                <img src="./CLRS.png" alt="" style="width: 100%">
                                <div style="padding: 10px">
                                    <p>Introduction to Algorithms</p>
                                </div>
                            </div>
                            <div class="col-1"></div>
                            <div class="col-6" style="padding: 40px">
                                <p>Author: Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein.</p>
                                <p>This is one of my favourite book, which is used as the textbook for algorithms courses at many universities.
                                 This book is commonly called as "CLRS" (Cormen, Leiserson, Rivest, Stein). This book introduces a lot of
                                  famous algorithm such dynamic progranmming,
                                  greedy algoritms, and multithread algorithms.</p>
                            </div>
                        </div>
                        <p style="padding:20px"></p>
                        <div class="row">
                            <p class="col-1"></p>
                            <div class="col-6" style="padding: 40px">
                                <p>Author: Michael Dahlin, Thomas Anderson. </p>
                                <p>This book talks about the core ideas in modern operating system, including protechition, concurrency, virtualization,
                                 resource allocation and reliable storage.
                                 This book examines the both the principles and practice of modern operating systems,
                                  taking important, high-level concepts all the way down to the level of working code.</p>
                            </div>
                            <div class="col-1"></div>
                            <div class="image col-4">
                                <img src="./OSPP.png" alt="" style="width: 100%">
                                <div style="padding: 10px">
                                    <p>Operating System: Principles and Practice</p>
                                </div>
                            </div>
                        </div>
                        <p style="padding:20px"></p>
                        <div class="row">
                            <div class="image col-4">
                                <img src="./ml.jpg" alt="" style="width: 100%">
                                <div style="padding: 10px">
                                    <p>Machine Learning</p>
                                </div>
                            </div>
                            <div class="col-1"></div>
                            <div class="col-6" style="padding: 40px">
                                <p>Author: Zhihua Zhou.</p>
                                <p>This book is about machine learning which can be used as textbook for undergraduate students.
                                 There are not many mathematical formula,
                                 and this book introduces the outline of machine learning,
                                 which gives me some basic concepts for various learning algorithms. I think it is useful for my postgradute in the future.</p>
                            </div>
                        </div>
                        <h2 style="padding-top:30px;padding-left:30px">Films</h2>
                        <div class="row">
                            <div class="col-3" style="padding-left:60px">
                                <h4>My favourite films</h4>
                            </div>
                            <ul class="col-8" id="film">
                                <li>La La Land</li>
                                <li>Titanic</li>
                                <li>Beauty and the Beast</li>
                                <li>Forrest Gump</li>
                                <li>Star Wars</li>
                            </ul>
                        </div>
                    </div>
                    <p style="padding:10px"></p>
                    <div id="flink">
                        <h1>Favourite Links</h1>
                        <table>
                            <tr>
                                <th>No.</th>
                                <th>Title</th>
                                <th>URL</th>
                                <th>Description</th>
                            </tr>
                            <tr>
                                <td>1</td>
                                <td>GitHub</td>
                                <td><a href="https://github.com/">github.com</a></td>
                                <td>A development platform, can host and review code.</td>
                            </tr>
                            <tr>
                                <td>2</td>
                                <td>Stack Overflow</td>
                                <td><a href="http://stackoverflow.com/">stackoverflow.com</a></td>
                                <td>Just copy the error information and click search.</td>
                            </tr>
                            <tr>
                                <td>3</td>
                                <td>TensorFlow</td>
                                <td><a href="https://www.tensorflow.org/">www.tensorflow.org</a></td>
                                <td>An open-source software library for Machine Intelligence.</td>
                            </tr>
                            <tr>
                                <td>4</td>
                                <td>Python Docs</td>
                                <td><a href="https://docs.python.org/2.7/">docs.python.org/2.7</a></td>
                                <td>When I forget some syntax or functions of python.</td>
                            </tr>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
```
CSS code:
======
```
* {
    box-sizing: border-box;
}

html {
    font-family: "Comic Sans MS", cursive, sans-serif;
}

.row::after {
    content: "";
    clear: both;
    display: table;
}

[class*="col-"] {
    float: left;
    padding: 15px;
}

.col-1 {
    width: 8.33%;
}

.col-2 {
    width: 16.66%;
}

.col-3 {
    width: 25%;
}

.col-4 {
    width: 33.33%;
}

.col-5 {
    width: 41.66%;
}

.col-6 {
    width: 50%;
}

.col-7 {
    width: 58.33%;
}

.col-8 {
    width: 66.66%;
}

.col-9 {
    width: 75%;
}

.col-10 {
    width: 83.33%;
}

.col-11 {
    width: 91.66%;
}

.col-12 {
    width: 100%;
}

.container {
    padding: 10px;
}

.menu {
    border-radius: 6px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
}

.menu ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.menu li {
    margin-bottom: 5px;
}

.menu a {
    text-decoration: none;
    color: black;
}

.header {
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
    padding: 80px;
    background: #2196F3;
    background: -webkit-linear-gradient(bottom right, #64B5F6, #009688);
    background: -o-linear-gradient(bottom right, #64B5F6, #009688);
    background: -moz-linear-gradient(bottom right, #64B5F6, #009688);
    background: linear-gradient(to bottom right, #009688, #64B5F6);
}

.header p {
    color: floralwhite;
    text-align: center;
    font-size: 70px;
    animation-name: welcome;
    animation-duration: 6s;
}

keyframes welcome {
    0% {
        color: transparent;
    }
    100% {
        color: floralwhite;
    }
}

@-webkit-keyframes welcome {
    0% {
        color: transparent;
    }
    100% {
        color: floralwhite;
    }
}

.container {
    padding: 10px 16px
}

.button {
    display: block;
    width: 100%;
    padding: 14px;
    text-align: center;
    border-radius: 5px;
    transition: all 200ms ease-out;
}

.button:hover {
    box-shadow: 0 0 6px #2196F3;
}

#personal_inf {
    padding: 30px;
    border-radius: 6px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
}

#personal_inf a {
    text-decoration: none;
    color: black;
}

#personal_inf a:hover {
    text-decoration: none;
    text-shadow: 0 0 3px #4FC3F7;
    color: black;
}

#hobbies {
    padding: 30px;
    border-radius: 6px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
}

#hobbies a {
    text-decoration: none;
    color: black;
}

#hobbies a:hover {
    text-decoration: none;
    text-shadow: 0 0 3px #4FC3F7;
    color: black;
}

#flink {
    padding: 30px;
    border-radius: 6px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
}

#flink a {
    text-decoration: none;
    color: black;
}

#flink a:hover {
    text-decoration: none;
    text-shadow: 0 0 3px #4FC3F7;
    color: black;
}

.image {
    border-radius: 5px;
    width: 250px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
    text-align: center;
}

#film li {
    padding: 6px;
}

#flink a {
    text-decoration: none;
    color: black;
}

#flink a:hover {
    text-decoration: none;
    text-shadow: 0 0 3px #4FC3F7;
    color: black;
}

table {
    border-collapse: collapse;
    width: 100%;
}

th,
td {
    text-align: left;
    padding: 10px;
}

th {
    background-color: #42A5F5;
}

tr:nth-child(odd) {
    background-color: #E3F2FD;
}

.rttop {
    position: fixed;
    bottom: 2px;
    right: 2px;
    width: 3.8%;
    border-radius: 80px;
    box-shadow: 2px 5px 10px 1px #BDBDBD, 0 6px 20px 0 #E0E0E0;
    background: #2196F3;
    background: -webkit-linear-gradient(bottom right, #64B5F6, #009688);
    background: -o-linear-gradient(bottom right, #64B5F6, #009688);
    background: -moz-linear-gradient(bottom right, #64B5F6, #009688);
    background: linear-gradient(to bottom right, #009688, #64B5F6);
}
.rttop a{
    text-decoration: none;
    color: white;
    display: block;
    width: 100%;
    padding: 14px;
    text-align: center;
    transition: all 200ms ease-out;
    border-radius: 80px;
}

.rttop a:hover {
    box-shadow: 0 0 16px #2196F3
}
```
