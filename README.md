# UP221: Introduction to GIS and Spatial Data Science

Winter 2023

Mondays 5pm - 7:50pm

Fully remote instruction and attendance with in-person options to meet with T.A.'s

Zoom (https://ucla.zoom.us/j/96734931456)

## Instructor: 

Yoh Kawano (yohman@gmail.com)

## Teaching Assistants:

- Chris Giamarino (cgiamarino@g.ucla.edu)
- Elliott Shaw (ewsshaw@g.ucla.edu )

## Special Technology Assistant:

For issues regarding JupyterHub.

Ben Winjum (bwinjum@ucla.edu)

## Office Hours: 

* Yoh: Wednesdays 4PM - 6PM and by appointment
	* [Schedule an appointment](https://calendar.app.google/7iS8JsxPWxsnvAKSA)
* Chris: [Fridays 12PM - 2PM](https://ucla.zoom.us/j/91624281568?pwd=TVkwTFlRclRxd3lDUWdoR2hOSklCdz09) and by appointment (email to schedule)
* Elliott: [Thursdays 12:00pm - 2:00pm](https://elliott211.youcanbook.me/) - and by appointment via [email](ewsshaw@ucla.edu)

## Course Description

Welcome to the world of planning and spatial thinking. In recent years, our relationship with maps and map-making has changed dramatically. No longer are we limited to a mode of map-making that is dominated by industry giants like Google and ESRI. Instead, a suite of data-science tools have matured to a point where they can produce similar, if not, more powerful and creative ways that advance spatial exploration. 

Our understanding of social phenomena through spatial constructs in urban data allows us to address questions on social justice, the environment, transportation, community development and design, amongst many other themes, and how these factors may affect different population groups in different ways. This course prepares  you for challenges in urban data beyond off-the-shelf cartographic approaches. It looks at the various components of data’s journey—acquisition, exploration, modeling, and communication through visualization—and how it enables and advances your research from a data science perspective.

The goal for this course is to expose you to the foundations of spatial data science. Where once there was a dearth of available digital information, we now live in a world of too much data. How can these data be transformed to human expressions and narratives that are utilized in planning? We begin with an introduction to various data science tools, and review the basics of programming with Python. Once a foundation of Python programming and data wrangling is achieved, spatial analysis through Python Libraries, and subsequently, through advanced geoprocessing will be introduced. All lessons will be based on “real” data with analytical methods addressing relevant and contemporary urban problems. At the conclusion of this course, students will be able to critically describe, analyze, and visualize spatial data for planning practices and research.

In addition to the programming lab sessions, you will be given weekly or bi-weekly "thinking cap" assignments, where you will be asked to think critically about contemporary urban issues. Be prepared to address various topics from the perspective of your own lived experiences, how it informs the topic, and what kind of research can advance knowledge in a positive way.

While there are no prerequisites for taking this course, people who are approaching programming for the first time will admittedly find the course to be intense and challenging.

## Learning Objectives for UP206A

At the conclusion of this course, students will be able to critically describe, analyze, and visualize spatial data for planning practices and research.

Specifically, students will learn to:

- Demonstrate the value of data for planning purposes through discovery, exploration, and analysis
- Critically evaluate data and create frameworks to prepare data for research
- Apply data science programming techniques to produce relevant visualizations that inform urban policy
- Learn to visualize data spatially to communicate the importance of place-based informatics
- Learn to produce publication-ready scholarly materials in the form of tables, charts, and maps

## Classroom set up

The classroom has changed dramatically in recent days. In order to maximize learning, the following guidelines must be adhered to as much as possible.

### Fully remote learning environment

This course will be offered in a fully remote enviornment, meaning that students will be required to attend via zoom, on a lab computer, or on their own computers. While recordings will be made available a day after instruction, students must make every possible attempt to attend the course in real time. 

### Zoom and slack

The following applications must be launched at the start of every class session:

- Zoom: The course will be taught via zoom. Much of the class instruction revolves around "hands-on" lab sessions. In order for instructors to be able to troubleshoot, or to demonstrate solutions to problems, it is constructive for students to share their screens with the class. In addition, in-class presentations (midterms, finals) will use a shared zoom screen to present content to the class.
- Slack: Sharing resources, code snippets, and general commentary on class material is better situated in Slack, as unlike the zoom chat, the records are archived and made available after class. 


## Inspirations

I would be remiss if I do not mention various inspirations that have led to the creation of this course. First and foremost, the late and great [Leo Estrada](https://luskin.ucla.edu/in-memoriam-leo-estrada-urban-planning-scholar-and-champion-of-diversity), my mentor and confidant over the years, who taught GIS at our department for many decades. Leo and I spoke extensively about modifying this course to a more “modern” approach, and I am delighted and honored to uphold his legacy moving forward.

Second, I have taken the liberty (with permission) to borrow ideas and materials from other courses. I specifically took inspiration from [Paul Waddell](https://ced.berkeley.edu/ced/faculty-staff/paul-waddell)’s “[Urban Informatics and Visualization](https://github.com/waddell/CP255)” course at UC Berkeley, and [Geoff Boeing](https://geoffboeing.com/about/)’s “[Data, Evidence, and Communication for the Public Good](https://github.com/gboeing/ppd534)” at the Department of Urban Planning and Spatial Analysis at USC’s Sol Price School of Public Policy.

## Course materials

The course will almost entirely be conducted on Jupyter Notebooks. A [JupyterHub](https://jupyter.idre.ucla.edu), a web-based Jupyter Notebook environment, has been set up specifically for this class, and is available at the following [URL](https://jupyter.idre.ucla.edu). Note that you will need multi-factored authentication to login:

*   [JupyterHub](https://jupyter.idre.ucla.edu) (choose UCLA)

Weekly course materials, including presentations, interactive notebooks (.ipynb), and data will be made available through a course github repository (here) that you will interact with through your JupyterHub account.

## Assignments and Evaluation

All assignments, unless otherwise specified, must be posted on your individual GitHub accounts or on the class GitHub discussion section by midnight of the Sunday prior to our class on Monday. Assignments are posted in each week's page, so make sure to read the instructions carefully. 

- Participation, individual progress, coding and reading assignments 10%
- Group assignments 40%
   - There will be four group assignments throughout the quarter. Each assignment will be worth 25% of the total group assignment grade.
- Mid-term 20%
- Final report 30%

| Task | Number of items | Points |
|------|-----------------|--------|
| Participation and individual assignments | 7-10 | 100 |
| Group Assignments | 4 | 400 |
| Mid-term | 1 | 200 |
| Final report | 1 | 300 |

## Grading criteria

All assignments are graded on the following criteria:

- **Timeliness**: Unless otherwise specified, all assignments are due at midnight of the day before the next class. For most assignments, you will be asked to submit them as posts in the discussion section of the class repo. The timestamp of your post will be used to determine whether they were submitted on time. 
- **Cleanliness**: Nobody wants to go through unreadable code! Make sure to document your work accordingly, providing markdown cells and comments throughout.
- **Does it work?**: Unless you purposefully created code cells that produce errors to make a point, notebook assignments must run from top to bottom without any errors. Verify this by restarting the kernel, and running all cells.
- **Thinking out of the box**: It is easy to copy an existing notebook, and replace datasets and parameters to fulfill an assignment. But how well have you/your group grasped the underlying concepts? This can be demonstrated by your ability to think outside the box, and *applying* rather than *copying* each step of a given assignment. For example, you may experiment with functions not demonstrated in class, or create your own workflow that borrows certain concepts learned in class to make them your own.


Grade | Description
---|---
A/A+ | Exceptional/creative/innovative work, demonstrating grasp of material, application of concepts to your own inquiry, going above and beyond course material
A- | Good grasp of material and solid application to your own research inquiry
B+ | Average understanding of material, largely duplicating course material to fit with your own research inquiry
B and below | Submission is incomplete or produces errors

[Hints for creating an exceptional assignment](https://docs.google.com/document/d/1D4ud1I9vuDPNDudINPC4-MLG-PV7AnzvkexZ-KFqyWk/edit?usp=sharing)

## Late assignments

Late assignments will be marked down one grade for each day it is late. For example, if your assigment warrants an "A" but is a day late, you will receive an "A-." As long as you submit your assignment before 10th week, you will get at least a "C."

## Weekly Schedule 

**Note:** Weekly content is subject to change, and will be modified as needed based on class discussions, needs, and progress.

### Preparation

*   Fill out the [pre-class survey](https://forms.gle/f8ZXLgNbvFawt6cw5)
*   If you do not have a GitHub account, create one for the class
	*   [https://github.com/](https://github.com/)
*   Make sure you can log into the class JupyterHub
	*   [JupyterHub](https://jupyter.idre.ucla.edu) (choose UCLA)

Week | Date | Topic
--- | --- | ---
Week 1 | January 9, 2023 |[Introduction to spatial data science](Weeks/Week01)
Week 2 | January 16, 2023 (Holiday/Make up date TBD)| [Data in Urban Studies: The challenge in data acquisition](Weeks/Week02)
 -- | -- | [Group assignment #1: Project Proposal](Group%20Assignments/GroupAssignment1.md)
Week 3 | January 23, 2023 | [Understanding communities: Census data profiles](Weeks/Week03)
 -- | -- | [Group assignment #2: Census Data Exploration](Group%20Assignments/GroupAssignment2.md)
Week 4 | January 30, 2023 | [Open Street Maps](Weeks/Week04)
Week 5 | February 6, 2023 | [Open data and APIs](Weeks/Week05)
Week 6 | February 13, 2023| [Mid-terms](Weeks/Week06)
 -- | -- | [Midterms](Midterm%20and%20Finals)
Week 7 | February 20, 2023 (Holiday/Make up date TBD)| [Geocoding, multiple overlays, and functions](Weeks/Week07)
 -- | -- | [Group assignment #3: Data Visualization](Group%20Assignments/GroupAssignment3.md)
Week 8 | February 27, 2023 (Holiday/Make up date TBD) | [Spatial statistics](Weeks/Week08)
Week 9 | March 6, 2023 | [Point pattern analysis](Weeks/Week09)
 -- | -- | [Group assignment #4: Spatial Analysis](Group%20Assignments/GroupAssignment4.md)
Week 10 | March 13, 2023 | [Remote Sensing and Sentiment Analysis](Weeks/Week10)
Finals Week | March 20, 2023 | [Finals](Midterm%20and%20Finals)

## How to ask a technical question

Given the nature of the course, you will have many, many questions along the way. However, we ask that you adhere to the following guidelines in order to make consultations as productive as possible. Students who do not follow these guidelines will be asked to reschedule.

Before asking a question:

1. Close all open programs, restart your computer, then try your task again
2. Search google and stackoverflow for the topic/problem (for example, the name of the function you're struggling with or the error message you are seeing)
3. Go back through the relevant lecture materials to look for any insights
4. Go back through the assigned reading materials to look for any insights

If the above steps haven't solved your problem, send an email (or attend office hours) and include the following information:

1. A detailed description of what you're trying to do, why, and how
2. A complete [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example) of your code so far (never send screenshots of code)
3. What you've already tried to do to solve your problem and what you have learned from it (specifically, explain the results of steps 1-4 above, including relevant links from stackoverflow etc)

## Readings and Resources

Readings will be posted in the assignment sections for each week. The following are a list of resources to help you with the more technical aspects of the course:

*   [Geographic Data Science with PySAL and the PyData Stack](https://geographicdata.science/book/intro.html)
*   [Spatial Analysis Methods and Practice by George Grekousis](https://www.cambridge.org/core/books/spatial-analysis-methods-and-practice/4C135005A621335D06CC63EFF17E3913)   
*   Think Python 2nd Edition by Allen B. Downey
	*   [https://greenteapress.com/wp/think-python-2e/](https://greenteapress.com/wp/think-python-2e/)
*   Jupyter Notebooks
	*   [https://jupyter.readthedocs.io/en/latest/index.html](https://jupyter.readthedocs.io/en/latest/index.html) 
*   [gboeing/ppd534: USC PPD534: Data, Evidence, and Communication for the Public Good](https://github.com/gboeing/ppd534)
	*   University of Southern California
	*   Professor: Geoff Boeing
*   [CP255: Urban Informatics and Visualization](https://github.com/waddell/CP255)
	*   University of California, Berkeley Department of City and Regional Planning
	*   Professor: Paul Waddell
*   [Automating GIS-processes 2019](https://automating-gis-processes.github.io/site/)
	*   University of Helsinki, Finland
*   [Computing for the Social Sciences](https://cfss.uchicago.edu/notes/) (R focused)
	*   University of Chicago

## Statement of Affirmation

I intend to make this classroom a space that affirms all identities and perspectives, including your race, color, national origin, ethnic origin, ancestry, marital status, religion, age, sex, gender, gender expression, gender identity, transgender status, pregnancy, physical or mental disability, medical condition, genetic information (including family medical history), sexual orientation, political ideology and affiliations, citizenship, or service in the uniformed services. Regardless of background, all students have a right to an equitable education. Because of the multi-faceted and complex nature of our identities, it is imperative that we are committed to affirming one another’s perspectives as a community for all enrolled in this course. I encourage all members to embrace and learn from the diversity in this classroom, school, and university. I want to highlight that discrimination, harassment, or forms of hateful transgressions will not be tolerated in our learning environment. If you have any recommendations about how to make our environment more inclusive please feel free to let me know. 

## Accommodations based on disability

If you are already registered with the Center for Accessible Education (CAE), please request your Letter of Accommodation on the Student Portal. If you are seeking registration with the CAE, please submit your request for accommodations via the CAE website. Please note that the CAE does not send accommodations letters to instructors--you must request that I view the letter in the online Faculty Portal. Once you have requested your accommodations via the Student Portal, please notify me immediately so I can view your letter.

Students with disabilities requiring academic accommodations should submit their request for accommodations as soon as possible, as it may take up to two weeks to review the request. For more information, please visit the CAE website (www.cae.ucla.edu), visit the CAE at A255 Murphy Hall, or contact by phone at (310) 825-1501.


## Covid-19 and return to campus information 

UCLA's return to campus guidelines
- [https://covid-19.ucla.edu/ucla-return-to-campus/](https://covid-19.ucla.edu/ucla-return-to-campus/)

UCLA's Basic needs resource guide
- [https://docs.google.com/document/d/1AUbLyaeYTLGPY1tnDJTG3ROzXKVY0QvF5oOy9_ZLmKo/edit](https://docs.google.com/document/d/1AUbLyaeYTLGPY1tnDJTG3ROzXKVY0QvF5oOy9_ZLmKo/edit)

The Luskin School has a Covid-19 FAQ resource page compiling information relevant to Covid-19 and its impacts.  The page is updated periodically.
