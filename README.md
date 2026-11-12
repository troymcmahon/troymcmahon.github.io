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
            <h1>Dr. Troy A. McMahon</h1>
        </header>

        <!-- Contact Information and Photo -->
        <section class="intro">

            <div class="contact">
                <p><strong>Position:</strong> Postdoctoral Research Associate and Project Manager</p>


                <p>
                    <a href="troymcmahon1@gmail.com">
                        troymcmahon1@gmail.com
                    </a>
                </p>

                <p>
                    <a href="https://scholar.google.com/citations?user=gG43f88AAAAJ&hl=en">Research Profile</a>
                </p>
                <p>
                    <a href="CV.pdf">CV</a>
                </p>
                <p>
                    <a href="ResearchStatement.pdf">Research Statement</a>
                </p>
                <p>
                    <a href="TeachingStatement.pdf">Teaching Statement</a>
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
           <b>Previous Affiliations:</b>
           <a href="https://www.5gsmartproduction.aau.dk/5g-robot">
                    5G Robot
           </a>
           <a href="https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://pracsys.cs.rutgers.edu/&ved=2ahUKEwiWrL-Qi4OYAxW5l2oFHcEnN7oQFnoECA8QAQ&usg=AOvVaw0XgRc5z0-YC9tH05Nv-rKi">
                    PRACSYS Lab
           </a>           
           <a href="https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://dimacs.rutgers.edu/&ved=2ahUKEwjnzbXBi4OYAxW3lmoFHZr3A0IQFnoECCsQAQ&usg=AOvVaw1RSmznDaMB2rpoPQdQn1Mo">
                    DIMACS
           </a>
           
           <a href="https://progresslab.github.io/progress-web/index.html">
                    Laboratory for Progress
           </a>
           
           <a href="https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://parasollab.web.illinois.edu/&ved=2ahUKEwj6xbLwioOYAxXHl2oFHWyyMPsQFnoECA8QAQ&usg=AOvVaw1ROSbKomTQ_7XbR7hA8864">
                    PARASOL Lab
           </a>
        </section>

        <!-- Research Profile -->
        <section class="research">
            <h2>Research</h2>
Robotics researcher specializing in motion planning for manipulators, constrained systems, and
high-degree-of-freedom robots. My research develops novel concepts, including Reachable Volumes
and Wayfields, that combine computational geometry and sampling-based planning for grasping
and manipulation. I also integrate kinodynamic planning, machine learning, and physics-based
simulation to develop planning methods for mobile manipulators, industrial robots, and off-road
vehicles. I have collaborated with leading researchers including Nancy Amato, Kostas Bekris, Odest
Jenkins, and Ole Madsen. My work has appeared in leading robotics venues, including IJRR,
ICRA, and IROS, and I have led research projects and managed collaborations across academic and
industrial institutions.
        </section>

        <!-- Teaching Profile -->
        <section class="research">
            <h2>Teaching</h2>
have served as the instructor of record for large core courses, such as the undergraduate course in Artificial Intelligence at Rutgers University (Introduction to Artificial Intelligence). This course enrolled more than 100 students
and consisted of a combination of programming projects, exams, and written assignments.  During my time at Aalborg University, I was an instructor for the Reading in Robotics course at the Department of
Materials and Production, which was a graduate-level course designed to introduce students to the research process. My goal for this course was to instill in students good research practices that they can carry into their own research,
        </section>
        
        <!-- Bio -->
        <section class="research">
            <h2>Short Bio</h2>
            I am originally from Western Massachusetts and I received my undergraduate from the University of Massachusetts in Amherst where I double majored in Computer Science and Physics.  I received my Doctorate degree from Texas A&M University under the mentorship of Dr. Nancy Amato. I have done postdocs at institutions including The University of Michigan, Rutgers University and Aalborg University.  
        </section>
        

    </main>

</body>
</html>
