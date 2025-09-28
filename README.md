# WEB-DEV-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhavesh Singh Naula | Portfolio</title>
    <link rel="stylesheet" href="style.css"/>

</head>

<body>
    <!-- The "Skip to main content" link -->
    <a href="#main-content">Skip to main content</a>

    <header>
       <div id="name">
        <h1>Bhavesh Singh Naula</h1>
        </div>
        
        <nav id="linkshare">
            <!-- Navigation links -->
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main id="main-content">

        <!-- HERO SECTION -->
        <section id="hero">
            <div id="front">
            <h2>Welcome to My Portfolio</h2></section></div>
            <p>
                Hello! I am a web development student. This is my personal portfolio website.
            </p>
        </section>

        <!-- ABOUT SECTION -->
        <section id="about">
           <div id="self">
            <h2>About Me</h2></div>
            
                <div class="profile-container">
                <!-- Profile Image with placeholder URL (will show as a standard image) -->
                <div class="profile-container">
                    <div id="image-card">
                    <img
                    src="C:\Users\mdsha\OneDrive\Desktop\WhatsApp Image 2025-09-28 at 13.43.07_4d4d836d.jpg" alt="A profile image of Bhavesh Singh Naula, a student." height="100px" width="100";>
                    ></div>
                </div>
            
            <p>
                I am passionate about learning web development and building creative projects.
            </p>
        </section>
       
        <!-- project section -->
        <section id="my-project">
            <h2>Projects</h2>
            <!-- Using a simple unordered list -->
            <ul>
                <li>
                    <strong><h3>Portfolio Website</h3></strong> Hi, I am <b>Bhavesh Singh Naula</b>. I am a B.Tech CSE student at KR Mangalam University. 
                     I am passionate about web development, coding, and learning new technologies
                </li>
                <hr>
              
                <li>
                    <strong><h3>Medium Clone</h3></strong><h3>How I Started Learning Web Development</h3>
                    <p><b>By Pratik Raj Sir</b> | </p>
                    <p>Web development is one of the most exciting skills to learn in today’s world... 
                    <a href="#">Read more</a></p>
                    <hr>
                </li>
                

                    <li>
                        <strong>Birthday Card :</strong> A creative greeting card webpage designed with HTML structure and CSS styling.
                    </li>
                <li>
                    <strong><h3>User Form</h3></strong> <h2>User Registration Form</h2>

                    <form>
                    <!-- Name -->
                    <label>Full Name:</label>
                    <input type="text" name="fullname"><br><br>

                    <!-- Email -->
                    <label>Email:</label>
                    <input type="email" name="email"><br><br>

                    <!-- Password -->
                    <label>Password:</label>
                    <input type="password" name="password"><br><br>

                    <!-- Gender -->
                    <label>Gender:</label>
                    <input type="radio" name="gender" value="male"> Male
                    <input type="radio" name="gender" value="female"> Female
                    <input type="radio" name="gender" value="other"> Other
                    <br><br>

                    <!-- Hobbies -->
                    <label>Hobbies:</label>
                    <input type="checkbox" name="hobby" value="reading"> Reading
                    <input type="checkbox" name="hobby" value="sports"> Sports
                    <input type="checkbox" name="hobby" value="music"> Music
                    <br><br>

                    <!-- DOB -->
                    <label>Date of Birth:</label>
                    <input type="date" name="dob"><br><br>

                    <!-- File Upload -->
                    <label>Upload Photo:</label>
                    <input type="file" name="photo"><br><br>

                    <!-- Country -->
                    <label>Country:</label>
                    <select name="country">
                        <option>India</option>
                        <option>USA</option>
                        <option>UK</option>
                        <option>Canada</option>
                    </select>
                    <br><br>

                    <!-- Message -->
                    <label>Message:</label><br>
                    <textarea name="message" rows="5" cols="30"></textarea>
                    <br><br>

                    <!-- Buttons -->
                    <input type="submit" value="Submit">
                    <input type="reset" value="Reset">
                    </form>
                    A form webpage with fields like name, email, and message for practicing form handling.
                </li>
            </ul>
        </section>
        <hr>
        <!-- SKILLS SECTION (Table) -->
        <section id="skills">
            <h3>Technical Skills</h3>
            
            <!-- Simple table structure -->
           <h1>My Technical Skills</h1>

    <table border="1" cellpadding="10" cellspacing="0">
        <tr>
            <th>Skill</th>
            <th>Level</th>
        </tr>
        <tr>
            <td>Python</td>
            <td>Learning</td>
        </tr>
        <tr>
            <td>HTML</td>
            <td>Advanced</td>
        </tr>
        <tr>
            <td>CSS</td>
            <td>Basic</td>
        </tr>
        <tr>
            <td>JavaScript</td>
            <td>Learning</td>
        </tr>
    </table>


        <!-- CONTACT SECTION (Form) -->
        <section id="contact">
            <h2>Contact Me</h2>
            
            <form id="contact-form" class="contact-form" action="#">
                
                <div id="form-message">
                    <!-- Note: This message will be visible initially without CSS hiding it -->
                    Thank you! Your message has been received (client-side simulation).
                </div>

                <!-- Name Field -->
                <div>
                    <label for="name">Name</label><br>
                    <input type="text" id="name" name="name" required
                        placeholder="Enter your name"
                    >
                </div>
                <br>

                <!-- Email Field -->
                <div>
                    <label for="email">Email</label><br>
                    <input type="email" id="email" name="email" required
                        placeholder="Enter your email"
                    >
                </div>
                <br>

                <!-- Message Field -->
                <div>
                    <label for="message">Message</label><br>
                    <textarea id="message" name="message" rows="4" required
                        placeholder="Enter your message"
                    ></textarea>
                </div>
                <br>

                <!-- Submit Button -->
                <button type="submit">Send</button>
            </form>
        </section>

    </main>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2025 Bhavesh Singh Naula Portfolio. All rights reserved.</p>
    </footer>

    <script>
        // Client-side JavaScript for form submission handling (updated to use class for hiding/showing)
        const messageDiv = document.getElementById('form-message');
        
        // Add a class to hide the message initially, since we can't use inline style
        messageDiv.classList.add('hidden-message');

        document.getElementById('contact-form').addEventListener('submit', function(event) {
            // Prevent the default form submission (which would reload the page)
            event.preventDefault();

            const form = event.target;

            if (!form.checkValidity()) {
                return;
            }

            // Simulate successful submission
            messageDiv.classList.remove('hidden-message');
            
            setTimeout(() => {
                messageDiv.classList.add('hidden-message');
            }, 5000);

            form.reset();
        });
    </script>
    
    <!-- Since CSS is removed, we add a tiny script to simulate "display: none" for the message -->
    <script>
        // Note: In a real environment, this class would be in the CSS file.
        // We use JS here as a workaround since the user requested no CSS.
        document.head.insertAdjacentHTML('beforeend', '<style>.hidden-message { display: none !important; }</style>');
    </script>
</body>
</html>
