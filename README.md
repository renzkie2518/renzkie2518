<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300&family=Raleway:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" media="screen" href="https://fontlibrary.org//face/glacial-indifference" type="text/css"/>

    <link rel="stylesheet" href="./css/styles.css"/>
    <link rel="stylesheet" href="./css/font-awesome-4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/fonticons.css">
    <link rel="stylesheet" href="assets/fonts/stylesheet.css">
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">
    <!-- <link rel="stylesheet" href="assets/css/bootstrap.min.css"> -->
</head>
<body>
    <div class="main">
        <div class="container">
            <div class="diagonal1"></div>
            <div class="diagonal2"></div>
            <section id="menu_bar" class="menu">
                <!-- <div class="wave" style="height: 300px; overflow: hidden;" ><svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;"><path d="M0.00,49.98 C149.99,150.00 271.49,-49.98 500.00,49.98 L500.00,0.00 L0.00,0.00 Z" style="stroke: none; fill: #3C4458;"></path></svg></div> -->
                <div class="profile">
                    <button class="menu_btn"><i class="fa fa-bars" aria-hidden="true"></i></button>
                    <img src="./assets/images/profile_picture.jpg">
                    <div class="diagonal1-menu"></div>
                    <div class="diagonal2-menu"></div>
                    <!-- <h1>JONARD CORDERO</h1> -->
                    <ul>
                        <li><a href="#about">About</a></li>
                        <li><a href="#skills">Skills</a></li>
                        <li><a href="#educational_background">Education</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
            </section>

            <button class="menu_btn inside"><i class="fa fa-bars" aria-hidden="true"></i></button>
            <div class="content">
                <div class="info">
                    <h1>JONARD CORDERO</h1>
                    <h2>FULL STACK WEB DEVELOPER</h2>
                </div>

                <section id="about" class="about">
                    <h1>About</h1>
                    <p>
                        My name is Jonard Manalese Cordero, and I am 19 years old. On September 8, 2002, I was born. I am currently residing in Tarlac's Sitio San Jose Cutcut1st Capas. I am pursuing a Bachelor of Science in Information Technology at Dominican College of Tarlac. My interests include viewing movies, listening to music, playing online games, and working out.
                    </p>
    
                    <p>
                        My immediate aims are to complete my studies and obtain my degree. The second goal is to learn something new and to improve some of my abilities, particularly in computer science. Finally, I want to go to locations I've never gone before, both inside and outside of my nation. I want to meet new people and learn about other cultures, and I feel that knowing a few facts about a certain issue is already significant.
                    </p>
    
                    <p>
                        After receiving my degree, my long-term aspirations are to have a profession that I am passionate about, one that excites me first thing in the morning and that I look forward to. The second is to invest in things such as real estate and businesses so that when the time comes for me to just enjoy my time, I am prepared. Last but not least, I'd like to acquire health insurance so that when I'm older, I won't have to worry about medical bills since they'll be covered.
                    </p>
                </section>
                
                <section id="skills" class="skills">
                    <h1>Skills</h1>
                    <div class="skills-container">
                        <div class="skills-box">
                            <label>HTML</label>
                            <div class="progress">
                                <div class="bar primary-bg w100"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>CSS</label>
                            <div class="progress">
                                <div class="bar secondary-bg w100"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>JAVASCRIPT</label>
                            <div class="progress">
                                <div class="bar info-bg w50"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>PYTHON</label>
                            <div class="progress">
                                <div class="bar warning-bg w50"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>JAVA</label>
                            <div class="progress">
                                <div class="bar danger-bg w50"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>C++</label>
                            <div class="progress">
                                <div class="bar primary-bg w25"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>SQL</label>
                            <div class="progress">
                                <div class="bar info-bg w75"></div>
                            </div>
                        </div>
                        <div class="skills-box">
                            <label>NOSQL</label>
                            <div class="progress">
                                <div class="bar danger-bg w75"></div>
                            </div>
                        </div>
                    </div>
                </section>

                <section id="educational_background" class="educational_background">
                    <h1>Education</h1>
                    <div class="timeline">
                        <div class="tl-container">
                            <div class="timeline-list">
                                <div class="timeline-box" ng-repeat="itembx">
                                    <div class="timeline-content">
                                        <h3>Bachelor of Science in Information Technology</h3>
                                        <h4>Dominican College of Tarlac</h4>
                                        <ul class="major">
                                            <li>Major in computer science</li>
                                            <li>Minor in networks & security</li>
                                            <li>Minor in mobile applications</li>
                                        </ul>
                                        <ul class="study">
                                            <li>Data Structures & Algorithms</li>
                                            <li>Database Management System</li>
                                            <li>Computer Networks</li>
                                            <li>Python</li>
                                            <li>JavaScript</li>
                                            <li>HTML & CSS</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="timeline-box" ng-repeat="itembx">
                                    <div class="timeline-content">
                                        <h3>Technical Vocational Livelihood</h3>
                                        <h4>San Roque National High School</h4>
                                        <ul class="major">
                                            <li>Major in Information Communication Technology</li>
                                            <li>With honors</li>
                                            <li>Best in games programming</li>
                                        </ul>
                                        <ul class="study">
                                            <li>Computer Assembly and Disassembly</li>
                                            <li>Java</li>
                                            <li>Computer Networks</li>
                                            <li>Game Development</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="timeline-box" ng-repeat="itembx">
                                </div>
                            </div>    
                        </div>
                    </div>
                </section>

                <section id="contact" class="contact">
                    <h1>Contact</h1>
                    <p>If you would like to get in touch with me, be it for exploring a technology, a business, or to just say hi, feel free to send me an email at bernardjonard@gmail.com</p>
                </section>
            </div>
        </div>
    </div>
</body>
</html>

<script>
   const elements = document.querySelectorAll('.menu_btn');

    elements.forEach(el => el.addEventListener('click', event => {
        const menu_bar = document.getElementById("menu_bar")
        
        if(menu_bar.classList.contains("active")){
            menu_bar.classList.remove("active");
        }
        else {
            menu_bar.classList.add("active");
        }
    }));
</script>
