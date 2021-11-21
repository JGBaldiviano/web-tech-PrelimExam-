# web-tech-PrelimsExam- index.html
<DOCTYPE html>
    <html lang="em"></html>
    <head>
        <title>My Friend's Favorite Colors and Foods</title>
        <link href= "assets/style.css" rel="stylesheet"/>
    </head>
    <h1><strong>My Friend's Favorite Colors and Foods</strong></h1>
     <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Profile</a></li>
        <li><a href="https://www.google.com/">Go to Google Search</a></li>
    </ul>
   

    <p class="p-maroon">Thank You for Visiting my page. This is the summary of my friends' <strong>favorite colors</strong> and <strong>foods</strong>. Enjoy browsing.</p>

    <body>
        <table>
            <th class="th-red">Image</th>
            <th class="th-red">Name</th>
            <th class="th-blue">Age</th>
            <th class="th-green">Favorite Color/s</th>
            <th class="th-goldenrod">Favorite Food/s</th>
        <tr>
            <td><img src = "FirstMan.png" width="120" length="120"/></a></td>
            <td class="td-JdC"> Juan dela Cruz</td>
            <td class="td-1"> 18</td>
            <td><ul>
                <li class="li-red">Red</li>
                <li class="li-green">Green</li>
                <li class="li-black">Black</li>
            </ul></td>
            <td><ol type="1">
                <li class="li-teal">Burger</li>
                <li class="li-teal">Spaghetti</li>
                <li class="li-teal">Fried Chicken</li>
            </ol></td>
        </tr>
        <tr>
            <td><img src = "SecondMan.png" width="120" length="120"/></a></td>
            <td class="td-1"> Jose Benito</td>
            <td class="td-1"> 21</td>
            <td><ul>
                <li class="li-pink">Pink</li>
                <li class="li-blue">Blue</li>
                <li class="li-green">Green</li>
            </ul></td>
            <td><ol type="1">
                <li class="li-teal">Adobob</li>
                <li class="li-teal">Sinigang</li>
                <li class="li-teal">Beef Tapa</li>
            </ol></td>
        </tr>
        <tr>
            <td><img src = "ThirdMan.png" width="120" length="100"/></a></td>
            <td class="td-1"> Jennifer Ada</td>
            <td class="td-1"> 22</td>
            <td><ul>
                <li class="li-yellow">Yellow</li>
                <li class="li-brown">Brown</li>
                <li class="li-orange">Orange</li>
                <li class="li-red"><del>Red</del></li>
            </ul></td>
            <td><ol type="1">
                <li class="li-teal">Crab</li>
                <li class="li-teal">Fried Fish</li>
                <li class="li-teal">Fried Chicken</li>
            </ol></td>
        </tr>
        </table>

        <p class="p-teal"><strong>Related blog posts</strong></p>
        <ul>
            <li class="li-skyblue"><i><strong>My first out of town</strong></i></li>
            <li class="li-red-left"><i><strong>My favorite programming language</strong></i></li>
            <li class="li-maroon"><i><strong>My favorite cars</strong></i></li>
        </ul>
    </body>

    <footer class="footer-text">Copyright 2021 Joana dela Cruz</footer>
    
    
    # web-tech-PrelimsExam- style.css
    h1 {
  color: hsl(0, 85%, 47%);
  font-size: 20px;
  font-style: unset;
  font-family: "Arial Narrow Bold", sans-serif;
  font-weight: 300;
  font-stretch: extra-condensed;
}

a:link {
  color: maroon;
  font-style: unset;
  font-family: "Arial Narrow Bold", sans-serif;
  font-weight: 300;
  font-stretch: extra-condensed;
}

a:hover {
  color: aquamarine;
}

.p-maroon {
  color: maroon;
  font-style: unset;
  font-family: "Arial Narrow Bold", sans-serif;
  font-weight: 300;
  font-stretch: extra-condensed;
}

.td-teal {
  color: teal;
  text-align: justify;
}

th,
caption {
  text-align: left;
  background-color: lightgreen;
}

table,
td {
  font-family: "Arial Narrow";
  font-weight: bold;
  color: #24505c;
  border: 1px solid black;
  border-collapse: collapse;
  border-style: solid;
  vertical-align: top;
}

th {
  border: 1px solid black;
  border-collapse: collapse;
  border-style: solid;
  font-family: "Arial Narrow";
  background-color: #d9ead3;
  height: 1px;
  width: 150px;
}

.th-red {
  color: red;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
}

.th-blue {
  color: blue;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
}

.th-green {
  color: green;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
}

.th-goldenrod {
  color: goldenrod;
  font-family: "Arial Narrow", sans-serif;
}

.td-JdC {
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.td-1 {
  color: teal;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  text-align: left;
}

.p-teal {
  color: teal;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
}

.li-redcenter {
  color: red;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}
.li-green {
  color: green;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-black {
  text-align: justify;
}

.li-blue {
  color: blue;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-pink {
  color: pink;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-yellow {
  color: yellow;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-brown {
  color: brown;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-orange {
  color: orange;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-teal {
  color: teal;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: justify;
}

.li-skyblue {
  color: skyblue;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
}
.li-red-left {
  color: red;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
}
.li-maroon {
  color: maroon;
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
}

.footer-text {
  font-family: "Arial Narrow", sans-serif;
  font-weight: bold;
  font-stretch: extra-condensed;
  text-align: center;
}

    
