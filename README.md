# portfolio

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <link rel="stylesheet" href="styles.css">

    <style>

        .message {

            display: none;

            text-align: center;

            margin-top: 20px;

            padding: 10px;

            background-color: #f0f0f0;

            border: 1px solid #ccc;

            border-radius: 5px;

        }

    </style>

</head>

<body>

    <header>

       

<h1 style="text-align:center;"><marquee behavior="scroll" direction="left" scrollamount="12">My Portfolio</marquee></h1>

        <nav>

            <ul>

                <li><a href="#home">Home</a></li>

                <li><a href="#about">About</a></li>

                <li><a href="#projects">Projects</a></li>

                <li><a href="#skills">Skills</a></li>

                                                                <li><a href="#experience">Experience</a></li>

                <li><a href="#contact">Contact</a></li>

            </ul>

                                               

        </nav>

    </header>

 

    <section id="home">

        <center><p>Welcome to Pragna's Portfolio<p></center>

    </section>

 

    <section id="about">

        <h2>About Me</h2>

        <p>Hi!, myself Pragna a student of 2nd year B.tech at Vignan's Institute Of Information Technology.</p>

    </section>

 

    <section id="projects">

    <h2>Projects</h2>

    <ul>

        <li>

            <h3><u>Calculator:</u></h3>

            <p>A simple calculator application built using HTML, CSS and JavaScript.</p>

        </li>

        <li>

            <h3><u>Landing Page:</u></h3>

            <p>A landing page for a fictional product or service showcasing its features and benefits.</p>

        </li>

                                <li>

            <h3><u>Registration Form:</u></h3>

            <p>A registration form using HTML, CSS and JavaScript.</p>

        </li>

    </ul>

</section>

 

 

    <section id="skills">

        <h2>Skills</h2>

        <ul>

            <li>

                <p>Ms.Office</p>

            </li>

                                                <li>

                 <p>Excel</p>

            </li>

                                    <li>

                <p>C language</p>

            </li>

                                    <li>

                <p>C++ language</p>

            </li>

                                    <li>

                <p>Research skills</p>

            </li>

                                    <li>

                <p>Communication skills</p>

            </li

        </ul>

    </section>

                <section id="experience">

        <h2>Experience</h2>

                                <ul>

                                    <li>

                                                    <p>1 month internship at plasmid</p>

                                                </li>

                                                <li>

                                                    <p>1 month internship at Technohacks</p>

                                                </li>

                                </ul>

      

    </section>

 

    <section id="contact">

        <h2>Contact Me</h2>

        <table border="0" cellpadding="15" cellspacing="0" width="80%" align="center">

            <tr>

                <td align="center" valign="top">

                    <form id="contact-form" action="#" method="post">

                        <label for="name">Name:</label><br>

                        <input type="text" id="name" name="name" size="40"><br>

                        <label for="email">Email:</label><br>

                        <input type="email" id="email" name="email" size="40"><br>

                        <label for="number">Number:</label><br>

                        <input type="number" id="number" name="number" size="12"><br>

                        <label for="message">Message:</label><br>

                        <textarea id="message" name="message" rows="5" cols="37"></textarea><br>

                        <button type="submit" onclick="showMessage()">Submit</button>

                    </form>

                    <div id="success-message" class="message">Your message has been sent!</div>

                </td>

            </tr>

        </table>

    </section>

 

  

    <script>

        function showMessage() {

            var successMessage = document.getElementById("success-message");

            successMessage.style.display = "block";

            setTimeout(function() {

                successMessage.style.display = "none";

            }, 40000);

        }

    </script>

</body>
</html>
