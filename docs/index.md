<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Nicer Table</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
        <style> 
            Table {
               border: 3px solid black;
               border-collapse: collapse;
            } 

            td, th {
                border: 3px solid black;
               font-family: Arial, sans-serif;
               font-size: 28px;
               font-weight: bold;
            }

            #foo {
               color:blue; 
            }

            button {
                background-color:crimson;
                width: 200px;
                height: 50px;
                color:darkblue;
                
            }

            button:hover {
                background-color: darkblue;
                color:darkkhaki;
            }

            @media (min-width: 600px) {
                body {
                    background-color: rgb(0, 140, 150);
                }
            }

            @media (max-width: 599px) {
                body {
                    background-color: rgb(17, 4, 14);
                }
            }

            #container {
                display: flex;
                flex-wrap: wrap;
            }

            #container > div {
                background-color: deeppink;
                margin: 20px;
                padding: 20px;
                width: 200px;
                font-size: 20px;
            }

            #grid {
                background-color: rgb(238, 255, 5);
                display: grid;
                padding: 20px;
                grid-column-gap: 20px;
                grid-row-gap: 10px;
                grid-template-columns: 200px 200px auto;
            }

            .grid-items {
                background-color: rgb(247, 0, 115);
                padding: 20px;
                font-size: 20px; 
                text-align: center;
            }

            .row > div {
                padding: 20px;
                background-color: teal;
                border: 2px solid black;
            }

            ul {
                color:darkgreen;
                background-color: darksalmon;
                font-family: cursive;
            }

            ol {
                color:darkgreen;
                background-color: darksalmon;
                font-family: cursive;
            }
         </style>
    </head>
    <div>
    <body>
        <h1>Welcome RidgeWood Evaluations Web Page</h1>
        <table>
            <thead>
                <th id="foo">Teachers</th>
                <th id="foo">% of kids that learn something</th>
                <th id="foo">% of kids that lose their S**h</th>
            </thead>
            <tbody>
                <tr>
                    <td>Laub</td>
                    <td>-40% Learning</td>
                    <td>100%</td>
                </tr>
                <tr>
                    <td>Hansen</td>
                    <td>20% Learning</td>
                    <td>80%</td>
                </tr>
            </tbody>
        </div>
        </table>
        <h2>Reviews of Ridgwood</h2>
        <div id="container">
            <div>1.Nice school and surrounding area!</div>
            <div>2.Ridgewood Has A Handful Of Good Teachers</div>
            <div>3.Ridgewood Is Very Lenient</div>
            <div>4.Ridgewood tries to act professinal</div>
            <div>5.Amazing Lunch</div>
            <div>6.Most of the teachers are boring/wierd</div>
            <div>7.Mr Gyori is bad</div>
            <div>8.I get a bad vibe from this school. Just like every other suburban school Everyone here seems to be pretty fake/annoying. Teacher and staff are pretty shady. I'm just here to get my grades up as a senior and get the hell out of here lol.</div>
            <div>9.Majority of the kids in this school do drugs and drink alcohol.</div>
            <div>10.Some of the teachers will work their butts off to make sure you succeed and get far in life and others will lose your test and work and tell your mother you are doing nothing in her class. It really depends what teacher you get.</div>

        </div>
        <div id="grid">
            <div class="grid-item">29 Excellent Reviews</div>
            <div class="grid-item">91 Good Views</div>
            <div class="grid-item">53 Average Reviews</div>
            <div class="grid-item">93 Poor Reviews</div>
            <div class="grid-item">857 Terrible Reviews</div>
        </div>
        <div class="alert alert-danger" role="alert">
            You Might Have A Virus Give us your social so you can stay safe!
          </div>
          <div class="alert alert-warning alert-dismissible fade show" role="alert">
            <strong>Holy guacamole!</strong> Top Greatest Classes.
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
          </div>
          <div class="container">
            <div class="row">
                <div class="col-4">
                    Ap GOV -Rutherford
                </div>
                <div class="col-4">
                    Ap Human Geo -Nolan
                </div>
                <div class="col-4">
                   Ap Pychology -Gates
                </div>
                <div class="col-4">
                    Every English Class With Mr. A
                 </div>
                 <div class="col-4">
                    AP US History -Mr. Pomponi
                 </div>
            </div>
        </div>
        <h4>Worst Teachers</h4>
        <br/>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    Honors Biology -Laub
                </div>
                <div class="col-6">
                    Honors Chem -Forgot His Name
                </div>
                <div class="col-3">
                    Pesant English -Barleya
                </div>
            </div>
        </div>
        <div class="text-center">
            <div class="text-center">
                <img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Rebels_Logo.jpg" class="rounded" alt="width: 200px;">
              </div>   
        <ol>
            <li>For Ridgewood High the green and white</li>
            <li>A rebel yell we'll give</li>
            <li>We'll cheer our team to victory</li>
            <li>That name and fame may live</li>
            <li>For green and white we'll always fight With spirit strong and true</li>
            <li>So go you rebels fight And we will stand by you.</li>
    
        </ol>
        <div class="alert alert-primary" role="alert">
            Give <a href="#" class="alert-link">Power To Ridgewood</a>. Give it a click if you support ridgewood being a global power.
          </div>
          <!DOCTYPE html>
<html lang="en">
    <head>
        <title>Search</title>
    </head>
    <body>
        <form action="https://google.com/search">
            <input type="text" name="q">
            <input type="submit" value="Google Search">
        </form>
    </body>
</html>
        <button>Clik meeeeee</button>
    </body>
<html>
