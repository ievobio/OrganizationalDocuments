# iEvoBio 2019 

## Teaching Computational Biology – Summary
The [iEvoBio satellite](https://github.com/iEvoBio2019/2019-iEvoBio) meeting of the Evolution conference  had two sessions, one about careers in computational biology and one about teaching computational biology. Here I will summarize the Teaching session but am happy to discuss the careers side if it’s of interest to others.

Five people spoke about their experiences delivering computational course content in undergraduate and graduate classes and what worked and what didn’t, and then we broke out into discussion groups to dive deeper into the topics. First, I’ll synthesize some of the ideas for incorporating computational skills into biology courses, then I’ll put together some thoughts on a bioinformatics degree, and finally I’ll put my summaries of each of the talks/resources at the end.

## Thoughts and Guidelines for Incorporating Computational Skills into Biology Courses 

- Students do not always have access to good computers, and this is an equity & inclusion issue – it is therefore important to use computer labs or cloud-based servers 

- Providing freely-available written resources is key, rather than relying on purchased textbooks. Especially important are ‘cheat sheets’ with common errors. 
- It is critical to decide whether students will be evaluated on their effort or on their coding competence. And even then, evaluating pseudocode rather than actual code in timed exams is really useful – since bioinformaticians rely on google so much these days anyway. 

- We must ensure that students who need help receive it, regardless of whether or not they seek out assistance (this is an equity and inclusion issue as well). A suggestion was to provide an automatic 1 week extension on assignments to the students who come to office hours for help.
- Repeatability (across and within courses) and consistency (i.e., when teaching R, using tidyverse or not) is important for a consistent student experience.
- Using Raspberry Pi computers could be a really unique and interesting way to integrate computing throughout a degree program by using it in data collection, data management, data analysis, and presentation of results.
- Live coding in class can be rough with variation in skill levels – some students bored and some not understanding – so flipping classrooms with pre-recorded live coding and in-class exercises can work really well. 

## Useful resources:

- [QUBES](https://qubeshub.org/resources/teachingandreference) has teaching materials freely available and might contain some useful resources for us.

- The paper by Wilson-Sayres et al [2018](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0196878) provides a useful set of core competencies for incorporating bioinformatics into life sciences curricula.

## Thoughts on a Bioinformatics Degree
- Five learning outcomes of a bioinformatics degree could be:
Basic competence with a programming language (the most common one today would be python)
- Basic competence with statistics as applied to biological data (using R)
- Familiarity with fundamental algorithms in bioinformatics and the ability to apply these to novel problems
- The ability to create pipelines tying together multiple bioinformatics programs
- Fundamentals of genetics, molecular, and evolutionary biology

- A student suggested that including an independent project would be excellent to be able to demonstrate abilities and proficiency, and to be something to include in their portfolio at the end of the degree.
The Network for Integrating Life Sciences in Education (https://qubeshub.org/community/groups/niblse) probably contains some really useful resources for us.

## Notes from the presentation and discussions
- April Wright (Southeastern Louisiana University) spoke about her experiences using Jupyter notebooks with rented Jupyter cloud computing to teach python to undergraduate biology students (but this would also work for R). She used a tool called the littlest jupyter hub to host less than 100 students with personal space for each of them, which allowed the students to do personal note taking and data exploration. 
- Rachel Schwartz (University of Rhode Island) spoke about using R for data exploration and analysis in an introductory biology course (BIO102) with 600+ students. To get around the issue of troubleshooting local installations, poor equipment, and other logistics, she used RStudio Server Pro, which is free for teaching purposes (need to register lesson plans or similar). She originally set it up herself following the awesome instructions from [Dean Attali] (https://deanattali.com/2015/05/09/setup-rstudio-shiny-server-digital-ocean/) but has now transitioned to having an awesome IT person set it up for her (this saves her time adding and removing students and student passwords, even though that is all scripted anyway). She assigns students both logins and passwords so she can login to check their work if necessary. The RStudio server opens RStudio in a web browser, and can be used on basically any device. She pre-installs packages and links data across, meaning that it removes nearly all compatibility/versioning issues. She emphasized the need to talk about coding systematically (teach the students which parts of functions are variables vs commands, etc) and go straight to what to do with the data – teaching students that R is a nifty tool that makes life easier, rather than trying to convince the students that coding is necessary. She emphasized the importance of repeatability, and says that they use the exact same code to visualize three different datasets, and that increased coding throughout the course and throughout the program gives students confidence and familiarity with R.
- Jamie Oaks (Auburn University) talked about the Bioinformatics Graduate certificate that his department offers but mostly about his initiative to use Raspberry Pi Zero computers in a bioinformatics bootcamp. His whole presentation is here: http://phyletica.org/slides/ievobio-2019/#/. With regards to teaching coding, he advocated a “test driven development” method of teaching coding, in which you give the students a script that is mainly comments, or has incomplete functions, as well as the tests to see if the code the write works, and then have the students fill in the empty code/incomplete functions. With regard to [Raspberry Pi Zeros](https://www.raspberrypi.org/products/raspberry-pi-zero/), they are US$10 computer chips that can be plugged into a laptop or to keyboard and monitor and teach the students how to ssh into it and do some basic coding. Using the Raspberry Pis gives the students a much less abstract idea of how computers and remote computing works.
- Cathy Newman (University of Louisiana at Monroe) spoke about the challenges of using local installs of python in teaching a graduate level Research Methods and Bioinformatics class. The students had different computers with vastly different setups, which caused many installation issues. Additionally, the classroom did not have reliable wifi, making the use of servers difficult. She used interactive in-class tutorials in a github readme plus weekly assignments. She made students get their own private github accounts and add the instructor as a collaborator so that she could access their assignments. 
- Brian O’Meara (University of Tennessee Knoxville) showed us a number of different teaching tools that he has used. First, he showed us his [PhyloMeth course](http://phylometh.info/) which is a partly/mostly-online course using Zoom meetings and a Slack workspace for discussions. He uses an open Rmd bookdown course book, which is free. He also advocated the use of shiny apps to help the students become familiar with the idea of using code and simulations without overwhelming them with the actual code. He uses docker to run code with pre-installed packages, but it doesn’t always work well. 
Mao-Lun Weng (Westfield State University) informed us that Xsede will give HPC accounts for teaching purposes for free, and he used this with his students. However, he did not get as far as expected in actually using the HPC and most of the course ended up having students use online tools such as NCBI blast and Tree of Life.

## Take-home messages re: bioinformatics course
- Explain properties of data types
- They should learn one scripting type
- How to google!
- Reformat and convert data
- Understand assumptions of models
- Bookdown is a useful tool for making course documents, and R has many useful packages
- Gsheets to integrate with google sheets and make things automatic
- citR for citing
- make file for R can streamline data -> results

## Ideas for evaluating students:
- emphasize points for the ability to work hard and put effort in when it comes to coding
- for timed exams use pseudocode
- can do automatic evaluation of code with [mimir](https://www.mimirhq.com/)

### With regard to teaching R in courses:
- Repeatability (across courses) and consistency (i.e., using tidyverse or not) is important for a consistent student experience
- Instructors need to decide if the goal is to learn code or for the students to recognize R is a useful tool (can do both, but important to know which is the emphasis for grading etc)
- Having documentation and written guides is essential for students and also for the instructors and demonstrators (i.e. an evolving cheat sheet with answers and common errors)
- It is critical to push students to ask for help and to go around the classroom while they are working to help those not asking for help (this is an equity issue as well). A suggestion was to provide an automatic 1 week extension on assignments to the students who come to office hours for help.
- The first year or two will always be rocky as the best practices for each course get set up.
- Raspberry Pis could be really cool if integrated early:
	- Could be used to collect data in the lab, and allow students to learn how to streamline data collection -> data management -> analysis -> presentation
	- Can be useful in the field by acting as a server connected to students’ computers/raspberry pis 
	- Can be turned into a mini HPC system to teach students how to use a server without needing to hook them up to an actual server (and prevent them from causing damage)
