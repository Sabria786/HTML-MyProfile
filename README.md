# HTML-MyProfile
An HTML Webpage about my profile. Includes a file of my resume, contact information, links to pages, etc. 

<html>
    <head>
        <title>Sabria's Webpage</title>
        <style>
            h1{
                text-align: center;
            }
            h3{
                color: maroon;
                text-align: center;
            }
        </style>

    </head>
    <body bgcolor=skyblue>
        <h1>Sabria Yaklur's Webpage</h1>
        <h3>CSULB Student, Management Information Systems (MIS)</h2>
        <h3>Email: sabria.yaklur@student.csulb.edu Phone: 562.219.7730</h2>
        <p><b>My Introduction</b></p>
        <p>
            Proactive Information Systems Management major (3.6 GPA) 
            currently attending California State University, Long Beach,
            with 1+ years of work experience. During my academic years at
            CSULB, I have gained basic programming skills in Python, Linux, 
            SQL, Microsoft Access, Excel, Power Point, and very proficient
            at Microsoft Word.Aiming to leverage a proven knowledge of database
            design, information systems, and web design skills to successfully
            fill a Data Science Intern role. Frequently praised as 
            detail oriented by my peers.
        </p>
        <p>
            During the course of my academic career, I also managed to 
            accrue nearly 8 months of work experience. I had the privilege of working 
            for East Avenue as a Sales Associate in my free time, where 
            I learned valuable professional skills such as merchandising, retail sales,
            and customer interaction. In both my academic and professional life, 
            I have been constantly praised for my time-management and organization
            skills by my professors and peers
        </p>
        <img src=profilepic1.png height=380 width=265><br>
        <ul>
            <li><a href=file:./myResume.html>My Resume</a></li>
            <li><a href=file:.\SabriaResume.pdf>Resume Download</a></li>
            <li><a href=mailto:sabria.yaklur@student.csulb.edu>Email Me</a></li>
            <li><a href=http://www.csulb.edu>Check CSULB</a></li>
        </ul>
        

    
        <p id="demo-time"></p>
        <button onclick="AlertMessage()">Show the current time</button>
        <script>
            function AlertMessage() {
                document.getElementById("demo-time").innerHTML = Date();
                alert(document.getElementById("demo-time").innerHTML = Date()); //alert gives pop up window
                
            }        
        </script>

        
    </body>
</html>


##This is another html webpage of my resumer that is linked to the main page.

<html>
    <head>
        <title>My Resume</title>
        <style>
            h1{
                text-align: center;
                font-size: 60px;
            }
            ol{
                border: 1px solid;
                padding: 40px;
            }
            ul {
                border: 1px solid;
                padding: 40px;
            }
        </style>
    </head>
    <body>
        <a href=./index.html>Go Back</a></li>
        <h1>Sabria Yaklur</h1>
        
        <!-- OBJECTIVE HEADER -->
        
        <h3>Objective</h3>
        <hr style="width:100%;height:2px;text-align:left;margin-left:0;background-color:black">
        
        <p>
            Proactive Information Systems Management major (3.6 GPA) currently attending 
            California State University, Long Beach, with 1+ years of work experience. 
            Aiming to leverage a proven knowledge of database design, information systems, 
            and web design skills to successfully fill the Data Science Intern role at your 
            company. Frequently praised as detail oriented by my peers, I can be relied 
            upon to help your company achieve its goals.  
        </p><br>
        
        <!-- EXPERIENCE HEADER -->

        <h3>Experience</h3>
        <hr style="width:100%;height:2px;text-align:left;margin-left:0;background-color:black">
        
        <div style="float: left">Mar 2018-Aug 2018</div>
        <div style="float: right">Buena Park, CA</div>
        <div style="margin: 0 auto; width: 240px;"><i>Kumon Math and Reading Center</i></div>
        
        <!-- Math Tutor section of Experience -->

        <p>
            <b><u>Math Tutor</u></b><br>
            <ol type="I">
                <li>Teach students study skills, note-taking skills, and test-taking strategies.</li>
                <li>Administer, proctor, and score academic and diagnostic assessments.</li>
                <li>Provide feedback to students using positive reinforcement techniques to encourage, motivate, and build confidence in students.</li>
            </ol>                   
        </p>

        <!-- Sales Associate section of Experience -->
        <hr style="width:100%;text-align:left;margin-left:0;background-color:black">
        
        <div style="float: left">Jan 2018-July 2018</div>
        <div style="float: right">Artesia, CA</div>
        <div style="margin: 0 auto; width: 240px;"><i>East Avenue</i></div>
        
        <p>
            <b><u>Sales Associate</u></b><br>
            <ol type="I">
                <li>Answer customers’ questions about products, prices, availability, product uses, and credit terms.</li>
                <li>Recommend products to customers, based on customers’ needs and interests.</li>
                <li>Estimate or quote prices, warranties, and delivery dates.</li>
            </ol>                   
        </p>

        <!-- Virtual Reality section of Experience -->
        <hr style="width:100%;text-align:left;margin-left:0;background-color:black">
        
        <div style="float: left">Mar 2018</div>
        <div style="float: right">Long Beach, CA</div>
        <div style="margin: 0 auto; width: 240px;"><i>Virtual Reality Day</i></div>
        
        <p>
            <b><u>Volunteer</u></b><br>
            <ol type="I">
                <li>Helped set up the VR equipment for the day</li>
                <li>Assisted a VR specialist with leading the students through the VR experience</li>
                <li>Led students in the event to their assigned rooms, where they would experiment with virtual reality software</li>
            </ol>                   
        </p><br>

        <!-- Orange County Health Fair -->
        <hr style="width:100%;text-align:left;margin-left:0;background-color:black">
        
        <div style="float: left">August 2015</div>
        <div style="float: right">Anaheim, CA</div>
        <div style="margin: 0 auto; width: 240px;"><i>Orange County Health Fair</i></div>
        
        <p>
            <b><u>Volunteer</u></b><br>
            <ol type="I">
                <li>Registered patients for the services they desired from the health fair, ranging from general medical care, to dentistry, to optometry</li>
                <li>Took blood pressures of patients and directed people to their proper stations</li>
                <li>Directed patients to where they needed to go for their requested services</li>
            </ol>                   
        </p><br>

        <!-- EDUCATION HEADER -->

        <h3>Education</h3>
        <hr style="width:100%;height:2px;text-align:left;margin-left:0;background-color:black">
        
        <div style="float: left">August 2017-present</div>
        <div style="float: right">Long Beach, CA</div>
        <div style="margin: 0 auto; width: 240px;"><i>California State University, Long Beach</i></div>
        
        <!-- Major section of Education -->

        <p>
            <b>B.A. Information Systems Management Candidate</b><br>
            <ul>
                <li><b>GPA:</b> 3.6</li>
                <li><b>Relevant Courses:</b> Information Systems 233 – Office Productivity Software, Information Systems 340 – Business Application Programming, Managerial Accounting, Microeconomics</li>
                <li><b>Award and Honor:</b> Presidential’s Honor List, 2016 Art Reflection Award</li>
                <li><b>Extracurricular Activity:</b> Health Occupation Students of America (HOSA), Multimedia, Muslim Student Association</li>
            </ul>                   
        </p><br>

        <!-- ADDITIONAL SKILLS HEADER -->
        <h3>Additional Skills</h3>
        <hr style="width:100%;height:2px;text-align:left;margin-left:0;background-color:black">
        
        <p>
            <ul>
                <li>Python Programming</li>
                <li>Linux</li>
                <li>Microsoft Access, Excel, Word, PowerPoint, and Publisher profiency</li>
                <li>Organizational skills</li>
                <li>Customer Interaction Skills</li>
                <li>Sales Associate Skills</li>
            </ul>                   
        </p>

    </body>
</html>
