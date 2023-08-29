# DSE I2700-3FG - 📀📊️🌎🪲 Visual Analytics

**Instructor:** Professor Madeline Blount \
**Term:** Fall 2023 \
**Time:** Wednesdays 4:50-7:20pm \
**Space:** Shepard S-275 \
**Office Hours:** virtual by appointment, [schedule here](https://www.cal.com/mab253) \
**E-mail:** `mblount@ccny.cuny.edu`
City College, City University of New York

## course description

This is a graduate-level course on the theory, practice, design, and critique of data visualization. If "technology has built the house in which we all live" ([Ursula Franklin](https://www.cbc.ca/radio/ideas/the-1989-cbc-massey-lectures-the-real-world-of-technology-1.2946845)), data certainly makes up the materials for this house, how it works, and how it looks. How does data do its work, and why is visualization a crucial part of this? What are the limits of data, and some potential pitfalls of data visualization? How can visualization help us make _sense_ of the ever-increasing deluge of data in our world? How do we determine what are "good" data visualizations, and how do we make them? Can we automate them - and should we? We'll see how creating strong, evocative, and informative data visualization involves techniques from art, design, math, psychology, computer science, and other fields.

Our explorations in this class will be technical as well as conceptual. We will dive into interdisciplinary readings as we learn the nuts and bolts of designing, coding, and analyzing data visualizations.

## what will we do in this class?

- learn some basic and advanced tools of data visualization in Python and Javascript
- refine our visualizations based on design principles from interdisciplinary sources
- work with real datasets from a wide variety of domains
- develop techniques in interactivity, geospatial mapping, and machine learning visualization
- get comfortable reading documentation and using new tools quickly
- interrogate the concept of data as a form of knowledge production, and learn to approach visualizations critically
- iterate and collaborate on a final data project at the end of the semester

## course format

This course will generally meet **in-person** for 2.5 hours on Wednesdays. Each class session will likely involve:

- **Short Lecture + Group Discussion**
    - Based on the readings, due before class each week
- **Student Presentations**
    - Mini-talk based on visualization found in the world ([see assignment](https://github.com/mab253/dataviz_fall23/blob/main/found-visualizations.md))
- **Lab + Workshop**
    - Programming and hands-on work; this will sometimes be guided by the professor, and sometimes involve documentation-based tutorials and group work

👾 We will also build an asynchronous offline community (as exists in nearly every endeavor @ this point!). We will have a class [Discord](https://github.com/mab253/dataviz_fall23/blob/main/discord.md) server where we will have multiple channels for posting updates, posing questions, commenting on readings and each others' work, sharing resources, etc.

🎥 There may be a few times throughout the semester when I will film a lecture + lab instead of giving one in-person. When I post a video instead, you will be free to watch it in your own time. These asynchronous lectures will be clearly marked on the schedule. In the case of any change in the schedule, I will announce this change ahead of time via Blackboard/e-mail.

The final for this class will be to develop a data visualization project in a small group. There is no exam in this course.

## important info:
[key dates](#key-dates) \
[materials & references](#materials-and-references) \
[tools](#tools-we-will-use-a-lot) \
[expectations & requirements](#expectations-and-requirements) \
[evaluation](#evaluation) \
[academic honesty & integrity](#academic-honesty-and-integrity) \
[contact & questions](#contact-and-questions)

## SCHEDULE, ASSIGNMENTS, READINGS:

💥*subject to change*

**Week 0: Aug. 30** \
*Introduction to Data Visualization, Hello World!*

**Assignment:** complete class survey; "hello world," post on Discord (invite/link for both will be e-mailed) \
**DUE:** Friday Sep. 1st, 5:00pm (happy labor day weekend!)

---

**Week 1: Sep. 6** \
*History of Data Visualization, Beginnings* \
🤖 _starting off w/python_

**Readings due today:**
- [_Data Visualization: A Practical Introduction_](https://socviz.co/lookatdata.html#lookatdata), Healy, Ch. 1 "Look at data" (1.1-1.8)
- _The Visual Display of Quantitative Information_, Tufte, Ch. 1 "Graphical Excellence" (p. 13-52)
- Look through: [Quick start](https://matplotlib.org/stable/tutorials/introductory/quick_start.html) and [Pyplot](https://matplotlib.org/stable/tutorials/introductory/pyplot.html), Matplotlib documentation


---

**Week 2: Sep. 13** \
*Abstraction + Fundamentals of Data Analysis* \
🤖 _python libraries_

**Readings due today:**
- [_Computational Information Design_](https://benfry.com/phd/dissertation/), Fry, Ch. 2 "Basic Example" + Ch. 5 "Process"
- _Visual Analysis and Design_, Munzner, Ch. 2 "What: Data Abstraction" and Ch. 3 "Why: Task Abstraction"
    - optional: videos by Munzner, [Data Abstraction](https://benfry.com/phd/dissertation/) and [Task Abstraction](https://www.youtube.com/watch?v=pHljd-cgIC)

---

**Week 3: Sep. 20** \
*Visual Perception, Aesthetics, and Color* \
🤖 _python libraries_

**Readings due today:**
- _Visual Thinking for Design_, Ware. Ch. 1
- [_Fundamentals of Data Visualization_](https://clauswilke.com/dataviz/aesthetic-mapping.html), Wilke, Ch. 2, 4, and 19 (they are short)
- _Envisioning Information_, Tufte, Ch. 4 "Small Multiples" and Ch. 5 "Color and Information"

---

**Week 4: Sep. 27** \
*Design Principles + Data Storytelling* \
🤖 _python libraries_

**Readings due today:**
- [_The Shape of Design_](https://shapeofdesignbook.com/chapters/07-stories-and-voids), Chimero, Ch. 7 "Stories and Voids"
- [_The Functional Art_](http://www.elartefuncional.com/images/Intro_chapter1.pdf), Cairo, intro to p. 23
- [_W.E.B. Du Bois's Data Portraits_](https://issuu.com/papress/docs/webduboisdataportraits_issuu), Battle-Baptiste and Rusert, p. 7-50 + Plates

---

**Week 5: Oct. 4** \
*Interactivity* \
🤖 _introducing javascript_

**Readings due today:**
- [_Data in Wonderland_](https://ssp3nc3r.github.io/data_in_wonderland/#interactive), Spencer, Ch. 3 "Interactive"
- [_Fundamentals of Data Visualization_](https://clauswilke.com/dataviz/telling-a-story.html), Wilke, Ch. 29
- _D3 for the Impatient: Interactive Graphics for Programmers and Scientists_, Janert, pages TBD
- _Thick Mapping in the Digital Humanities_, pages TBD


---

**Week 6: Oct. 11** \
*Geospatial Data: Maps I* \
🤖 _javascript_

**Readings due today:**
- [Anatomy of a Web Map](https://maptime.io/anatomy-of-a-web-map/#0), McConchie and Schechter (interactive presentation)
- [_Fundamentals of Data Visualization_](https://clauswilke.com/dataviz/aesthetic-mapping.html), Wilke, Ch. 15
- _How to Lie With Maps_, Monmonier, pages TBD



---

**Week 7: Oct. 18** \
*Geospatial Data: Maps II* \
🤖 _javascript_

**Readings due today:**
- ["Unicorns, Janitors, Ninjas, Wizards, and Rock Stars"](https://direct.mit.edu/books/oa-monograph/4660/chapter/213289/Unicorns-Janitors-Ninjas-Wizards-and-Rock-Stars) from [_Data Feminism_](https://direct.mit.edu/books/oa-monograph/4660/Data-Feminism), D'Ignazio and Klein
- "On Exactitude in Science," Borges
- Mattern, article + pages TBD



---

**Week 8: Oct. 25** \
*Dashboards + Live Data* \
🤖 _javascript, python_

📊 **_Mid-term Mini-Project Due_**, before class

**Readings due today:**
- from _Visual Display of Quantitative Information_, Tufte, Ch. 4-6
- from _Semiology of Graphics_, Bertin, pages TBD
- Mattern, article + pages TBD

---

**Week 9: Nov. 1** \
*Visualizing Uncertainty* \
🤖 _javascript, python_

**Readings due today:**
- [_Fundamentals of Data Visualization_](https://clauswilke.com/dataviz/aesthetic-mapping.html), Wilke, Ch. 16
- ["What would feminist data visualization look like?"](https://civic.mit.edu/feminist-data-visualization), D'Ignazio
- _How Data Happened_, Wiggins, pages TBD

---

**Week 10: Nov. 8** \
*Visualizing Texts, Networks and Trees* \
🤖 _javascript, python_

📊 **Final Project Proposal + Groups Due**, before class

**Readings due today:**
- from _The Network Turn_, Ahnert, Coleman, Weingart; pages TBD


---

**Week 11: Nov. 15** \
*Data Collection and Missing Data* \
🤖 _python libraries_

**Readings due today:**
- [missingno documentation](https://github.com/ResidentMario/missingno)
- [beautifulsoup documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- ["The Great Impossibility"](https://www.dropbox.com/sh/rn8k7ded6izu2a9/AAARsVWFaKf5iRhGE2AfQvFLa?dl=0&preview=zine-GreatImpossibility.pdf) and ["The Point of Collection"](https://points.datasociety.net/the-point-of-collection-8ee44ad7c2fa#.y0xtfxi2p) Mimi Onuoha

---

**Week 12: Nov. 22** \
**NO CLASS, HOLIDAY**


---

**Week 13: Nov. 29** \
*Big Data, Multidimensions, ML*

**Readings due today:**
- ["A visual introduction to machine learning,"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/), Part I & II, R2D3
- "What is a model?" from _Weapons of Math Destruction_, pages TBD
- _Big Data, Big Design_, Armstrong, TBD

---

**Week 14: Dec. 6** \
*Questioning Automation, Wrap-Up & Final Presentations*

**Assignment:** work on final project \
FINAL REPORT DUE: Dec. 15th, 11:59pm

---


## key dates
- mid-term mini-project: due Oct. 25, 12:00pm
- final project presentation: in-class, Dec. 6th
- final project repot: due Dec. 15th, 11:59pm

## assignments

You will be responsible for:
- weekly: [Discord post](https://github.com/mab253/dataviz_fall23/blob/main/found-visualizations.md), due 4:00pm EST before every class session, starting Week 2
- 1 mini-presentation of [Discord post](https://github.com/mab253/dataviz_fall23/blob/main/found-visualizations.md) visualization (scheduled throughout course)
- 1 mid-term assignment (solo work)
- 1 final group project (proposal, presentation, and final report)

More details for each of these assignments will be given throughout the semester.

## materials and references

All course material will be linked via this page on Github. I will often post extra links, tool documentation, and further references beyond the required materials that might be helpful to you, especially as you build your own visualizations - but these extra resources will be optional. There will be no textbook for this course other than what's linked here. I will post the readings at least 2 weeks in advance, but if you look far ahead you might see some "TBDs." I will also post any in-class workshop material (slides, links, etc.) in a folder for each week. 

## tools we will use a lot

- Blackboard
- [Discord](https://discord.com)
- [Google Colab/Jupyter Notebooks](https://research.google.com/colaboratory/faq.html)
- [Repl.it](https://replit.com/)
- [Glitch.com](https://glitch.com/)

## expectations and requirements
### how can I do well in this class?

The discussion and lab combination in this class means that **attendance is very important**, both for your own learning and the learning of your fellow students. Collaborative workshops and rich critical inquiry simply will not happen if we don't have a consistently present, engaged crew of classmates. Attendance in-class, as well as engagement (active listening, asking questions, etc.), will count toward your final grade. Further, most of the technical component of the class involves in-person labs. At the end of each class section with a lab or workshop, you will need to submit your code to show your in-class work.

That said, things happen. Everyone in this course will be allowed 1 absence, no questions asked. Every absence after this 1 will result in a deduction from your partipication/attendance portion of your final grade. Lateness beyond 20 minutes is considered an absence. **If you know ahead of time that you will need to miss class, please let me know as soon as possible**, and we can arrange a way for you to make up the work.

It is crucial that we build a space where everyone can learn. This class will be an inclusive and harassment-free space for everyone, with no tolerations of discimination based on gender, race, sexual orientation, religion, disability, or appearance. Please let me know privately if you require an academic accommodation.

## evaluation:

Grading breakdown:
- Participation/Attendance (including in-class lab work): 20%
- Weekly Async Posts: 20%
- Midterm Assignment: 20%
- Final Project: 40%

on late work:

**Late assignments drop 10% per day, starting after the due time.** (If you submit a Discord post 1 hour after the due date, for example, it drops 10%. If you wait another 24 hours, it drops 20%.)

**✉️ To receive credit for late work, you will need to e-mail me once you have completed it.**

If you have a reason for needing an **extension** (where you will receive full points), please reach out to me _before_ the due date for an assignment.

## academic honesty and integrity:

Plagiarism is "the act of presenting another person's ideas, research or writings as your own." [(CUNY)](https://www.ccny.cuny.edu/it/academic-integrity-policy). **This is as true for writing code as it is for writing others' words and pretending that they are yours.**

It is important that everything you turn in for this class is your own work. I understand that collaborating with your classmates can be really helpful when learning - you are allowed and encouraged to do this! However, the code and designs you submit must reflect work you have done on your own. To outline some of the boundaries here, it is acceptable to:

- Discuss the course’s material with others in order to understand it better.
- Help a classmate identify a bug in their code.
- Incorporate a few lines of code that you find online or elsewhere into your own code, provided that those lines are not solutions to assigned work and that you cite the lines’ origins.
- Turning to the web or elsewhere for instruction beyond the course’s own, for references, and for solutions to technical difficulties, but not for outright solutions to assigned work.
- Whiteboarding solutions with others using diagrams or pseudocode but not actual code.

It is **not acceptable** to:

- Search for or solicit outright solutions to assessments online or elsewhere.
- Split an assessment’s workload with another individual and combine your work. (exception: group projects)
- Submit (after possibly modifying) the work of another individual
- Use AI-based software that suggests or completes answers to questions or lines of code.

_These terms modified and inspired by Harvard's CS50's academic honesty policy, [here](https://cs50.harvard.edu/x/2022/honesty/)._

I have ways of checking on the originality of your code and assignments. Consequences for violating this academic honesty policy will be severe, including but not limited to failing the course.

You can find CCNY’s Academic Integrity Policy in full [here](https://www.ccny.cuny.edu/it/academic-integrity-policy).  Do not plagiarize.

## contact and questions

👾 Our class will have a [Discord](https://github.com/mab253/dataviz_fall23/blob/main/discord.md) server for posting questions and communicating with each other.

If you would like to ask a question privately, please e-mail me - I am available and I try to respond within 24 hours. You are also invited to schedule some virtual office hour time to talk, [here](https://www.cal.com/mab253). If you need a time that's not on this schedule, please e-mail me.
