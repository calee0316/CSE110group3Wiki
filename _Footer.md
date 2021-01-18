<!DOCTYPE html>

<html lang="en">

    <head>
        <title>CSE 110 Lab 2 Github Page</title>
        <meta charset="UTF-8">
        <meta name="keywords" content="Github page, Richard Hwang">
        <meta name="description" content="Richard Hwang's Github page">
        <meta name="author" content="Richard Hwang">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://github.com/euh006/CSE110-Lab2/blob/main/dummy.css" rel="stylesheet">
        <style>
            aside {
              width: 30%;
              padding-left: 15px;
              margin-left: 15px;
              float: right;
              background-color: lightgray;
            }
        </style>
    </head>

    <body>

        <main>

            <header>

                <section>
                    <h1>Lab 2: Richard Hwang's Github page in HTML</h1>
                    <p>Hello, this is a Github page made <b>strictly with only HTML.</b></p>

                    <details>
                        <summary>Introduction (From lab 1)</summary>
                        <p>Hello, my name is Richard. I am currently a fourth year Computer Engineering major in the ECE department. I have coded in Java, C++, and Python. I also have some experience with Quartus. For our digital systems class, we built SHA-256, which used in Bitcoin blockchain technology, based on provided testbench.

                            I was born in Korea, and I am currently 22 years old. When I was about 10 years old, my father wanted me to study abroad in America because he believed that education there was better, and also partially because he wanted to see me during his a lengthy business trip in California. So ever since then, I have basically naturalized as a San Diegan; I never left San Diego. I was able to meet amazing people here, and have had awesome experience.</p>
                    </details>

                    <figure>
                        <img src="./images/1536483820170.jpg" alt="Grad picture" style="width:50%">
                        <figcaption>My graduation photo from La Jolla Country Day School with Mikael, one of my best friends.</figcaption>
                    </figure>

                    <p>More about me:</p>

                    <nav>
                        <a href="https://www.youtube.com/channel/UCs-006B89ebGLhOluA-Vkeg">Youtube</a> |
                        <a href="https://www.facebook.com/richard.hwang.9028/">Facebook</a> |
                    </nav>
                </section>

                <hr style="height:2px;border-width:0;color:gray;background-color:gray">
    
                <section>

                    <div>
                        <h2>About me (Skills)</h2>
                        <h3>List of programming languages that I have used before</h3>
                        <ul>
                            <li><strong>C++</strong></li>
                            <li>Java</li>
                            <li>Python</li>
                        </ul>

                        <h3>Coding tip (borrowed from Lab 1)</h3>
                        <p>In C++, Users can type <code>echo (message)</code> in the terminal to display the message right back, or redirect it into a file <br> by typing <code>echo (message) > (file name)</code> to avoid having to 
                            open up a text editor to create a text file.</p>

                    </div>

                    <hr>

                    <div>
                        <h2>About me (Personal)</h2>
    
                        <h3>My <em>favorite</em> top 3 games</h3>
                        <ol>
                            <li>Hades</li>
                            <li>Dead by Daylight</li>
                            <li>Heroes of the Storm</li>
                        </ol>

                        <aside><p>Hades is a <span style="color:blue;font-weight:bold">rougelike</span> <span style="color:red;font-weight:bold">action</span> role-playing game <i>released on 2018.</i></p></aside>

                        <picture>
                            <source media="(min-width:1000px)" srcset="./images/BigHOTS.jpg">
                            <img src="./images/SmallHOTS.png" alt="HOTSPic" style="width:auto;">
                        </picture>
    
                    </div>

                    <h4>Miscellaneous</h4>
                    <pre>
                        Everything within &lt;pre&gt; tag has its special     spaces and

                        
                        line breaks preserved. It also is displayed in a fixed-width font.
                    </pre>

                    <p>Here is a bedtime calculator that allows you wake up without feeling groggy.</p>
                    <iframe src="https://sleepyti.me/" title="Sleep scheduler"></iframe>

                    <p>Here is a final project music I made in MUS 173 during summer session. Pretty neat, huh?</p>
                    <audio controls>
                        <source src="./audio/final.mp3" type="audio/ogg">
                        Your browser does not support the audio tag.
                    </audio>

                    <p>Here is a funny video I recorded with my friends.</p>
                    <video width="1280" height="720" controls>
                        <source src="./videos/nice.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>

                    <p>Here's a random orange weight and yoga ball because I need to lift some weights!</p>
                    <canvas id="myCanvas">Your browser does not support the canvas tag.</canvas>

                    <script>
                    var c = document.getElementById("myCanvas");
                    var ctx = c.getContext("2d");
                    ctx.fillStyle = "#FF5000";
                    ctx.fillRect(0, 0, 60, 100);
                    ctx.fillRect(60, 25, 100, 50);
                    ctx.fillRect(150, 0, 60, 100);
                    </script>

                    <svg width="100" height="100">
                        <circle cx="50" cy="50" r="40" stroke="black" stroke-width="2" fill="blue" />
                    </svg>

                    <form>
                        <fieldset>
                         <legend>Tell me about yourself!:</legend>
                         <label for="fname">Your name:</label>
                         <input type="text" id="fname" name="fname"><br><br>

                         <label for="email">Email:</label>
                         <input type="email" id="email" name="email"><br><br>

                         <label for="birthday">Birthday:</label>
                         <input type="date" id="birthday" name="birthday"><br><br>

                         <label for="car">Preferred color of your automobile:</label>
                         <input type="color" id="car" name="car"><br><br>

                         <label for="fries">Amount of fries you can eat in one sitting: (between 1 and 10):</label>
                         <input type="number" id="fries" name="fries" min="1" max="10"><br><br>

                         <label for="estimate">Try your best to set this right on the middle:</label>
                         <input type="range" id="estimate" name="estimate" min="0" max="100"><br><br>

                         <label for="audfile">Any music you have created:</label>
                         <input type="file" id="audfile" name="audfile"><br><br>

                         <label for="drink">Favorite non-alcoholic drink:</label>
                         <select name="drink" id="drink">

                           <optgroup label="For the hydro bois">
                             <option value="water">Water</option>
                           </optgroup>

                           <optgroup label="Carbonated drinks">
                             <option value="Carbonated water">Carbonated water</option>
                             <option value="Coca-cola">Coca-cola</option>
                             <option value="Pepsi">Pepsi</option>
                             <option value="Dr. Pepper">Dr. Pepper</option>
                             <option value="Sprite">Sprite</option>
                             <option value="Fanta">Pepsi</option>
                           </optgroup>

                           <optgroup label="Milk">
                            <option value="Milk">Milk</option>
                            <option value="Coconut milk">Coconut milk</option>
                            <option value="Almond milk">Almond milk</option>
                           </optgroup>

                           <optgroup label="Juice">
                            <option value="Orange juice">Orange juice</option>
                            <option value="Grape juice">Grape juice</option>
                            <option value="Apple juice">Apple juice</option>
                           </optgroup>
                           
                           <optgroup label="Misc">
                            <option value="Soy sauce">Soy sauce</option>
                            <option value="Ketchup">Ketchup</option>
                           </optgroup>

                         </select>
                         <br><br>

                         <label for="pet">Choose your favorite pet:</label>
                         <input list="pets" name="pet" id="pet">
                            <datalist id="pets">
                             <option value="Cat">
                             <option value="Dog">
                             <option value="Bird">
                             <option value="Turtle">
                             <option value="Lion">
                            </datalist>
                        
                         <p>How did you find this website?:</p>
                         <input type="radio" id="class" name="find" value="30">
                         <label for="class">Silly Richard, I'm grading your page!</label><br>
                         <input type="radio" id="random" name="find" value="60">
                         <label for="random">Sheer luck, I was just looking at some random Github pages!</label><br>  
                         <input type="radio" id="other" name="find" value="100">
                         <label for="other">Through other methods</label><br><br>

                         <label for="comment">Comment:</label><br>
                         <textarea id="comment" name="comment" rows="4" cols="50">Leave some feedback about my website in this text box!
                         </textarea>
                         <br><br>

                         <label for="confirmGift">Want to support my cause to change all ice cream flavors to chocolate mint?:</label>
                         <input type="checkbox" id="confirmGift" name="confirmGift"><br><br>
                         <input type="submit" value="Submit">
                        </fieldset>
                    </form>

                    <h4>Lets do some table!</h4>

                    <table>
                        <caption>English to Korean table</caption>
                        <colgroup>
                            <col span="2" style="background-color:gold">
                        </colgroup>
                        <tr>
                            <th>English</th>
                            <th>Korean</th>
                        </tr>
                        <tr>
                            <td>Hello</td>
                            <td>안녕하세요</td>
                        </tr>
                        <tr>
                            <td>Sorry</td>
                            <td>죄송합니다</td>
                        </tr>
                        <tr>
                            <td>restroom</td>
                            <td>화장실</td>
                        </tr>
                        <tr>
                            <td>I'll have you know I graduated top of my class in the Navy Seals</td>
                            <td>너는 내가 네이비 실에서 가장 좋은 성적으로 졸업한걸 알아야될꺼야</td>
                        </tr>


                    </table>

                    <br><br>

                    <button type="button">Click this pointless button that does nothing (for now).</button>

                    <template>
                        <p>You shouldn't be able to see this...</p>
                    </template>

                </section>

            </header>

            <footer>
                <p>Page author: Euicheon Hwang</p>
                <a href="mailto:euh006@ucsd.edu">euh006@ucsd.edu</a>
            </footer>

        </main>

    </body>
</html>