<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Troy McMahon | Roboticist </title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            color: #333;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1000px;
            margin: 50px auto;
            padding: 40px;
            background: white;
        }

        /* Name header */
        header {
            border-bottom: 2px solid #e5e5e5;
            padding-bottom: 20px;
            margin-bottom: 35px;
        }

        h1 {
            font-size: 36px;
            font-weight: 600;
            color: #183153;
            margin: 0;
        }

        /* Two-column introduction */
        .intro {
            display: grid;
            grid-template-columns: 1fr 280px;
            gap: 50px;
            align-items: start;
        }

        .contact h2,
        .research h2 {
            color: #183153;
            font-size: 23px;
            margin-top: 0;
            margin-bottom: 15px;
        }

        .contact p {
            margin: 8px 0;
        }

        .contact a {
            color: #2865a6;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }

        .profile-photo {
            width: 100%;
            max-width: 280px;
            height: auto;
            object-fit: cover;
            border-radius: 4px;
        }

        /* Research interests */
        .research {
            margin-top: 50px;
            border-top: 2px solid #e5e5e5;
            padding-top: 30px;
        }

        .research ul {
            padding-left: 25px;
        }

        .research li {
            margin-bottom: 10px;
        }

        /* Mobile layout */
        @media (max-width: 650px) {
            .container {
                margin: 15px;
                padding: 25px;
            }

            .intro {
                grid-template-columns: 1fr;
                gap: 25px;
            }

            .profile-photo {
                max-width: 220px;
            }

            h1 {
                font-size: 29px;
            }
        }
    </style>
</head>

<body>

    <main class="container">

        <!-- Name -->
        <header>
            <h1>Troy A. McMahon</h1>
        </header>

        <!-- Contact Information and Photo -->
        <section class="intro">

            <div class="contact">
                <h2>Contact Information</h2>

                <p><strong>Position:</strong> Postdoctoral Research Associate and Project Manager</p>

                <p>
                    <strong>Department:</strong><br>
                    Department Name<br>
                    University Name
                </p>

                <p>
                    <strong>Email:</strong><br>
                    <a href="troymcmahon1@gmail.com">
                        troymcmahon1@gmail.com
                    </a>
                </p>

                <p>
                    <strong>Office:</strong><br>
                    Building Name, Room Number
                </p>

                <p>
                    <strong>Website:</strong><br>
                    <a href="#">Google Scholar / Research Profile</a>
                </p>
            </div>

            <div>
                <img
                    src="Troy_McMahon.jpg"
                    alt="Profile photograph"
                    class="profile-photo"
                >
            </div>

        </section>

        <!-- Projects -->
        <section class="research">
           links to all the labs I worked at
        </section>

        
        <!-- Documents -->
        <section class="research">
           CV, Research Statement, Teaching Statement
        </section>

        <!-- Research Interests -->
        <section class="research">
            <h2>Research Profile</h2>
paragraph about research
            <ul>
                <li>Motion Planning</li>
                <li>Grasping and Manipulation</li>
                <li>Kinodynamic Planning</li>
                <li>Task and Motion Planning</li>
                <li>Industrial Automation</li>
            </ul>
        </section>

        <!-- Teaching Interests -->
        <section class="research">
            <h2>Teaching Interests</h2>

            <ul>
                <li>Robotics</li>
                <li>Artificial Intelligence</li>
                <li>Computational Geometry</li>
                <li>Algorithms</li>
            </ul>
        </section>

        <!-- Teaching Interests -->
        <section class="research">
            <h2>Research Profile</h2>

            <ul>
Text goes here
            </ul>
        </section>

        <!-- projects -->
        <section class="research">
            <h2>Projects</h2>
Boxes go here
        </section>

    </main>

</body>
</html>
