# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div id="menu" class="fas fa bars"></div>
        <nav class="navbar">
            <a href="#home" >Home</a>
            <a href="#about" >About</a>
            <a href="#education" >Education</a>
            <a href="#contact" >Contact</a>
        </nav>
        <a href= "anushka__cv.pdf" class="btn">Download CV</a>
        
    </header>
    
    <section class="home" id="home" >
        <div class="content">
            <h1 class="hello">Hello Everyone</h1>
            <h3 class="name">I am <span>Anushka Dolas </span></h3>
            <p>I am a Front-End Web Developer.</p>
            <a href="rutu passport pic.jpg"></a>
            <img align ="right" src="rutu passport pic.jpg" alt="Click here" height="370px" width="600px">

        </div>
    </section>
    
    
    <section class="about" id="about">
         <h1 class="heading" >About Me</h1> 
         <div class="row">
             <div class="progress-bar">
                   <h2 class="title">My skills :</h2>
                   <h4>HTML</h4>
                   <h4>CSS</h4>
                   <h4>JAVASCRIPT(basics)</h4>
                   <h4>PYTHON</h4>
                   <h4>CPP(basics)</h4>
                   <h4>SQL</h4>

                   
             </div>
         </div>    
    </section>
    <section class="education" id="education">
        <h1 class="heading">Education</h1>

        <div class="row">
            <div class="column">
                <h3 class="title">My Education :</h3>

                <div class="box">
                    <h3>S.S.C- Pius Memorial High School, Pune.</h3>
                    <div class="year"> <i class="fas fa-calender"></i>2018</div>
                </div>
                <div class="box">
                    <h3>H.S.C- Laxmanrao Apte Junior College, Pune.</h3>
                    <div class="year"> <i class="fas fa-calender"></i>2020</div>
                </div>
                <div class="box">
                    <h3>B.E in Electronics and telecommunication engineering,Pune</h3>
                    <div class="year"> <i class="fas fa-calender"></i>2023</div>
                </div>
            </div>
        </div>
    </section>
    <section class="contact" id="contact">
        <h2 class="heading">Connect With me:</h2>

        <div class="box"></div>
            <form action="">
                <div class="inputbox">
                    <label>Name :        </label>
                    <input type="text" required>
                </div>
                <div class="inputbox">
                    <label>Email :       </label>
                    <input type="email" required>
                </div>
                <div class="inputbox">
                     <label>Phone :</label>
                    <input type="number" required>    
               </div>
                <div class="inputbox">
                    <label>Subject :     </label>
                    <input type="text" required>
                </div>

                <div class="inputbox">
                    <label>Message :     </label>
                    <textarea required name="" id="" ></textarea>
                </div>

                <input type="submit" value="send message" class="btn">
            </form>
            <div class="footer">
                Created by <a href="#" >Ms.Anushka Dolas</a>
            </div>
            <script src="script.js"></script>
</body>
</html>
