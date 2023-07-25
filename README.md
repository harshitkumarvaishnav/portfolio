# portfolio
"Interactive portfolio website showcasing projects, skills, and creativity with HTML, CSS, and JavaScript for a dynamic user experience."

# About Project
The portfolio website is a visually appealing online showcase of an individual's or a professional's work, skills, and accomplishments. It serves as a digital resume, presenting projects, creative works, and expertise. Utilizing HTML, CSS, and JavaScript, the website ensures a dynamic and interactive user experience. The design is responsive, adapting seamlessly to various screen sizes, including small screens like mobile devices, to ensure accessibility and user-friendliness. Through a concise yet comprehensive presentation of the portfolio, visitors can easily explore and appreciate the creator's talents and capabilities, making it an essential tool for networking, job seeking, or promoting personal brand.

# Index.HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio-Website</title>
    <link rel="stylesheet" href="Style.css">
    <script src="https://kit.fontawesome.com/1e8bda6841.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                    <i class="fas fa-times" onclick="closemenu()"></i>
                </ul>
                <i class="fas fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Web Designer</p>
                <h1>Hi, I'm <span>Harshit</span><br>Kumar From Gajraula</h1>
            </div>
        </div>
    </div>
    <!------------------------------about----------------------------------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/user.png">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>B. Tech (Information Technology) from CCS University, Meerut (UP).
                        I'm Final Year Under Graduate My interest lies in Cyber Security and Web Designer. I always
                        willing to like minded people for constructive ideas .
                        Seeking full time job opportunity as penetration tester and will also do web designer.</p>

                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>UI/UX</span><br>Designing Web/App interfaces</li>
                            <li><span>Web Designer</span><br>Web app Designer</li>
                            <li><span>Wordpress</span><br>Website Making</li>
                            <li><span>Cyber Security Expert</span><br>Analytics Websites and applications</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2023 - Current</span><br>Web Development Intern at Internpe</li>
                            <li><span>2023 - Current</span><br>Web Development Internship at Bharat Intern</li>
                            <li><span>2022</span><br>JAVA Traniee at MSME Ramnagar.</li>
                            <li><span>2022-2023</span><br>Cyber Security Traniee at IIIT Allahabad & TheTechUnique
                                Academy</li>
                        </ul>
                    </div>

                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2020- Current</span><br>B.Tech From CCS University</li>
                            <li><span>2023</span><br>UI/UX Trainig from LearnVern</li>
                            <li><span>2022</span><br>Cyber Security at TheTechUnique Academy</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!------------------------------Services--------------------------->

    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Design</h2>
                    <p>Our web designing service offers creative and professional solutions tailored to meet your online
                        needs. From captivating user interfaces to seamless navigation, we strive to craft visually
                        stunning and functional websites that leave a lasting impression on your audience. Let us bring
                        your vision to life and elevate your online presence to new heights.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop-simple"></i>
                    <h2>UI/UX Design</h2>
                    <p>Our UI/UX design service is dedicated to creating intuitive and visually appealing interfaces
                        that enhance user experiences. We focus on understanding your target audience and business
                        objectives to deliver designs that not only look stunning but also drive engagement and
                        conversions. Let us transform your ideas into captivating designs that leave a lasting impact on
                        your users.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store-ios"></i>
                    <h2>Cyber Security Expert</h2>
                    <p>Our cyber security analytics service provides advanced data analysis and threat intelligence to
                        safeguard your digital assets from evolving cyber threats. Through cutting-edge technologies and
                        proactive monitoring, we deliver actionable insights to detect, mitigate, and prevent security
                        breaches. Rest assured, your business stays protected with our robust and vigilant cyber
                        security analytics solutions.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!------------------------------------------portfolio------------------------------->

    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/work-1.png">
                    <div class="layer">
                        <h3>Social Media App</h3>
                        <p>The app connects you yo the talented people around the world. Download it from play store.
                        </p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-2.png">
                    <div class="layer">
                        <h3>Music App</h3>
                        <p>The app connects you yo the talented people around the world. Download it from play store.
                        </p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-3.png">
                    <div class="layer">
                        <h3>Online Shopping App</h3>
                        <p>The app connects you yo the talented people around the world. Download it from play store.
                        </p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>
    <!-- ------------------Contact------------------ -->

    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-paper-plane"></i> Contact@example.com</p>
                    <p><i class="fa-solid fa-square-phone"></i> 0123456789</p>
                    <div class="social-icons">
                        <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                        <a href=""><i class="fa-brands fa-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="images/Harshit_Resume.pdf" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p><i class="fa-regular fa-copyright"></i>Copyright Portfolio <i class="fa-solid fa-heart"></i>Made by
                Harshit Vaishnav</p>
        </div>
    </div>


<!------------------Script----------------------------->

    <script>


        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    <script>

        var sidemeu = document.getElementById("sidemenu");

        function openmenu() {
            sidemeu.style.right = "0";
        }
        function closemenu() {
            sidemeu.style.right = "-200px";
        }
    </script>

<!--------------------Goofle form link upload script------------------------------------------>


    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbwAdm4jgLK2yxt5Lmoz2yaDg9rRXwqOrXXlw8UdPv-GChF_c-8HmGXam35O2mYhU2Y7/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")

        form.addEventListener('submit', e => {
            e.preventDefault()
            fetch(scriptURL, { method: 'POST', body: new FormData(form) })
                .then(response => {
                    msg.innerHTML = "Message sent successfully"
                    setTimeout(function () {
                        msg.innerHTML = ""
                    }, 5000)
                    form.reset()
                })
                .catch(error => console.error('Error!', error.message))
        })
    </script>
</body>

</html>
