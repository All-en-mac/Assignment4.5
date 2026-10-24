Plaintext
web-development-practice/
│
├── index.html        (Home)
├── about.html        (Club Introduction & Members)
├── registration.html (Club Registration Form)
├── contact.html      (Contact Details)
└── images/
    └── favicon.ico   (Favicon Icon)
Page 1: index.html (Home)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Official home page of the Tech & Web Developers Club. Explore upcoming activities, workshops, and hackathons.">
    <title>Home — Tech & Web Developers Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Tech & Web Developers Club</h1>
        <p>Innovate • Code • Collaborate</p>
        
        <nav aria-label="Main Navigation">
            <a href="index.html">Home</a> | 
            <a href="about.html">About Us</a> | 
            <a href="registration.html">Join the Club</a> | 
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <hr>

    <main>
        <!-- Club Introduction Section -->
        <section>
            <h2>Welcome to the Tech & Web Developers Club</h2>
            <p>We are a vibrant student-run organization dedicated to helping campus learners master modern software development, build real-world web applications, and connect with technical mentors.</p>
        </section>

        <hr>

        <!-- Key Activities Section -->
        <section>
            <h2>Our Core Activities</h2>
            <ul>
                <li><strong>Weekly Coding Workshops:</strong> Hands-on sessions covering HTML5, CSS layout, JavaScript, and Git workflows.</li>
                <li><strong>Hackathons & CodeSprints:</strong> 24-hour team programming challenges with mentor guidance.</li>
                <li><strong>Guest Tech Talks:</strong> Interactive sessions hosted by software engineers and industry alumni.</li>
            </ul>
        </section>

        <hr>

        <!-- Events Schedule Table -->
        <section>
            <h2>Upcoming Events Schedule</h2>
            <table border="1" cellpadding="8" cellspacing="0">
                <caption>Semester 1 Activity Schedule</caption>
                <thead>
                    <tr>
                        <th>Date</th>
                        <th>Event Name</th>
                        <th>Location</th>
                        <th>Time</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Nov 12, 2026</td>
                        <td>Git & GitHub Mastery Workshop</td>
                        <td>Computer Lab B</td>
                        <td>3:00 PM – 5:00 PM</td>
                    </tr>
                    <tr>
                        <td>Nov 25, 2026</td>
                        <td>Winter Hackathon 2026</td>
                        <td>Main Auditorium</td>
                        <td>9:00 AM – 6:00 PM</td>
                    </tr>
                    <tr>
                        <td>Dec 10, 2026</td>
                        <td>Frontend Web Mini-Projects Showcase</td>
                        <td>Room 304</td>
                        <td>2:00 PM – 4:00 PM</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td colspan="4"><em>* Note: All event registrations open 1 week prior to the event date.</em></td>
                    </tr>
                </tfoot>
            </table>
        </section>
    </main>

    <hr>

    <footer>
        <p>&copy; 2026 Tech & Web Developers Club. All rights reserved.</p>
    </footer>

</body>
</html>
Page 2: about.html (Club Introduction & Team)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learn about the mission, faculty advisors, and executive team of the Tech & Web Developers Club.">
    <title>About Us — Tech & Web Developers Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Tech & Web Developers Club</h1>
        <p>Innovate • Code • Collaborate</p>
        
        <nav aria-label="Main Navigation">
            <a href="index.html">Home</a> | 
            <a href="about.html">About Us</a> | 
            <a href="registration.html">Join the Club</a> | 
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <hr>

    <main>
        <!-- Detailed Club Overview -->
        <section>
            <h2>Our Mission & Vision</h2>
            <p>Founded in 2022, the Tech & Web Developers Club aims to bridge the gap between academic theory and practical software engineering practices. We welcome students from all academic majors regardless of their prior programming background.</p>
        </section>

        <hr>

        <!-- Executive Leadership Directory (Definition List) -->
        <section>
            <h2>Executive Board & Faculty Leadership</h2>
            <dl>
                <dt><strong>Faculty Advisor: Dr. Sarah Jenkins</strong></dt>
                <dd>Head of the Computer Science Department and mentor for open-source project initiatives.</dd>

                <dt><strong>Club President: Allen Macanige</strong></dt>
                <dd>Senior Computer Science student with a focus on web architecture and peer-to-peer tutoring.</dd>

                <dt><strong>Technical Lead: Priya Sharma</strong></dt>
                <dd>Junior Engineering student guiding hands-on JavaScript and UI development sessions.</dd>
            </dl>
        </section>
    </main>

    <hr>

    <footer>
        <p>&copy; 2026 Tech & Web Developers Club. All rights reserved.</p>
    </footer>

</body>
</html>
Page 3: registration.html (Membership Form)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sign up to become an official member of the Tech & Web Developers Club.">
    <title>Club Registration — Tech & Web Developers Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Tech & Web Developers Club</h1>
        <p>Innovate • Code • Collaborate</p>
        
        <nav aria-label="Main Navigation">
            <a href="index.html">Home</a> | 
            <a href="about.html">About Us</a> | 
            <a href="registration.html">Join the Club</a> | 
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <hr>

    <main>
        <section>
            <h2>Member Registration Form</h2>
            <p>Fill out the fields below to sign up for club membership and receive event notifications.</p>

            <form action="#" method="POST">
                
                <div>
                    <label for="student-name">Full Name:</label><br>
                    <input type="text" id="student-name" name="fullname" placeholder="Alex Johnson" required>
                </div>

                <br>

                <div>
                    <label for="student-email">Campus Email Address:</label><br>
                    <input type="email" id="student-email" name="email" placeholder="alex@college.edu" required>
                </div>

                <br>

                <div>
                    <label for="student-id">Student ID Number:</label><br>
                    <input type="text" id="student-id" name="studentid" placeholder="STU-102938" required>
                </div>

                <br>

                <div>
                    <label for="year">Current Academic Year:</label><br>
                    <select id="year" name="academicyear" required>
                        <option value="" disabled selected>-- Select Year --</option>
                        <option value="1">First Year (Freshman)</option>
                        <option value="2">Second Year (Sophomore)</option>
                        <option value="3">Third Year (Junior)</option>
                        <option value="4">Fourth Year (Senior)</option>
                    </select>
                </div>

                <br>

                <div>
                    <label>Areas of Interest:</label><br>
                    <input type="checkbox" id="interest-web" name="interests" value="webdev">
                    <label for="interest-web">Frontend & Web Design</label><br>

                    <input type="checkbox" id="interest-algo" name="interests" value="algorithms">
                    <label for="interest-algo">Data Structures & Problem Solving</label><br>

                    <input type="checkbox" id="interest-hack" name="interests" value="hackathons">
                    <label for="interest-hack">Hackathons & Competitive Coding</label>
                </div>

                <br>

                <div>
                    <button type="submit">Complete Registration</button>
                </div>

            </form>
        </section>
    </main>

    <hr>

    <footer>
        <p>&copy; 2026 Tech & Web Developers Club. All rights reserved.</p>
    </footer>

</body>
</html>
Page 4: contact.html (Contact Details)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contact details and campus meeting location for the Tech & Web Developers Club.">
    <title>Contact Us — Tech & Web Developers Club</title>
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Tech & Web Developers Club</h1>
        <p>Innovate • Code • Collaborate</p>
        
        <nav aria-label="Main Navigation">
            <a href="index.html">Home</a> | 
            <a href="about.html">About Us</a> | 
            <a href="registration.html">Join the Club</a> | 
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <hr>

    <main>
        <section>
            <h2>Contact Information & Location</h2>
            <p>Have questions about upcoming events or membership? Reach out to us through any of the channels below:</p>

            <ul>
                <li><strong>Email:</strong> <a href="mailto:techclub@college.edu">techclub@college.edu</a></li>
                <li><strong>Club Room Location:</strong> Student Activity Center, Building B, Room 204</li>
                <li><strong>Weekly Meeting Hours:</strong> Every Tuesday & Thursday from 4:00 PM – 6:00 PM</li>
                <li><strong>Faculty Advisor Office:</strong> Computer Science Block, Room 108</li>
            </ul>
        </section>

        <hr>

        <section>
            <h2>Send Us a Quick Message</h2>
            <form action="#" method="POST">
                <div>
                    <label for="msg-name">Your Name:</label><br>
                    <input type="text" id="msg-name" name="name" required>
                </div>

                <br>

                <div>
                    <label for="msg-email">Your Email:</label><br>
                    <input type="email" id="msg-email" name="email" required>
                </div>

                <br>

                <div>
                    <label for="message">Message / Inquiry:</label><br>
                    <textarea id="message" name="message" rows="5" cols="40" placeholder="Type your query here..." required></textarea>
                </div>

                <br>

                <div>
                    <button type="submit">Send Message</button>
                </div>
            </form>
        </section>
    </main>

    <hr>

    <footer>
        <p>&copy; 2026 Tech & Web Developers Club. All rights reserved.</p>
    </footer>

</body>
</html>
