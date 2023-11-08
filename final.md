# 🤖🗺️📈 final assignment

For this assignment, you will work with a team to research, analyze, develop, refine, and produce **web-based data visualizations**, going through the entire life cycle of [computational information design](https://benfry.com/phd/dissertation/5.html).

### 🤸‍♀️ #1: form teams

- Your Discord post due Nov. 8th should include the following:
    - write 1 post suggesting 2 possible data domains you are interested in exploring, along with links to 2 sample possible datasets. I recommend checking out the sources listed [here](https://github.com/mab253/dataviz_fall23/blob/main/sources-list.md) if you need inspiration, but you may find data elsewhere as well!
    - include your strengths for your potential team, and what you are hoping to get help with on the final project (from other students or the professor), for example: Python/analysis, Javascript, visual design, report writing, etc.
- Those Discord posts are like "pitches" to the rest of the class - does someone have a similar data interest? Does another student have complementary skills that you might want to work with? **Use your week Nov. 8th-15th** to form teams as a class, preferably 2-4 people.
- Your team list, a short description of the domain, and a link to possible datasets are due by **Nov. 15th before class**, via e-mail or Discord DM. Only 1 submission necesary per team!
- If you would like me to match you to a team, please send me an e-mail before Nov. 15th.

### 📑 #2: collaborative data work!

- Go through a brief research phase as you explore the data domain and your dataset attributes. What context do you need to learn to understand the data? What key research questions might you focus on?
- Conduct exploratory data analysis - I suggest Python and `pandas`, but you are welcome to use any tool.
- Perform any data transformation that your project requires.
- Find a **story** in the data. What do you want to communicate in your final visualizations?

### 📀 #3: deliverables

Every team will be responsible for:
- Presentation, 7-10 minutes, showing work-in-progress, including telling the story of your domain and any research questions, and giving the class a look into your process and analysis. Include a slide deck of visuals, on **Dec. 6th** in-class.
- Online-accessible, interactive version of your project, hosted at a [Glitch.com](https://glitch.com) URL, **due Dec. 15th** by 11:59pm
- Methodology section included as Markdown file (`README.md`) in Glitch project (more info coming)
- Final project written report, 1000-1200 words, **due Dec. 15th** by 11:59pm (more info coming)
- Any supporting code (Jupyter notebook for Pandas, for example), with comments, **due Dec. 15th** by 11:59pm

Every person will be responsible for:
- A short (500 word) personal reflection on how the division of labor went for your team; how you personally showed up for the project work; and how you synthesized what you have learned in this class.

SOME SUGGESTIONS ON PROCESS:
- some class time will be dedicated to teamwork on Nov. 15th and Nov. 29th, but this project also assumes significant work outside of class for the rest of the semester. I recommend using Discord, Glitch, Google Colab, and Zoom to collaborate, and to meet in-person if you can!
- ask for help! Please use the Discord to: post code that confuses you, request help debugging, ask for feedback on any drafts, etc. - from me or your classmates
- do create rough drafts - I recommend sketching by hand if that helps you, or use simple tools before your complex visualizations. If making a map, for example, you could try a draft in [Felt](https://felt.com/) before you work in code.
- you may delegate and divide the labor among your team members, but your final project needs to come together cohesively as 1 complete whole
- you may (and are encouraged to!) find outside sources to help with code, new libraries, online examples, etc. When you use these, remember to cite your sources!
- document your process as you go; it will be helpful for your reflection and your final report

SOME THOUGHTS ON SCOPE & EXAMPLES:
- The goal here is to push beyond the defaults in all the platforms that we've learned to create something **original, beautiful, and full of useful information.**
- The work and final visualization(s) should be more intensive than your mid-term mini project, as you have more time and team members at your disposal. How deeply can you dive into the data? How many drafts and exploratory visuals might you need? What new techniques or libraries might you need to learn?  How polished and user-friendly can the final viz be?
- Ideally, this project could go in your professional portfolios!
- The best scope here is a bit of a _stretch_, something you might not quite know how to make right now, but with help and 1 month you could design and build.

The project is open-ended for a reason - let your curiosity be your guide, and your final work should be unique rather than a copy of any of the following examples!

if you make multiple simple charts:
- 💥 YOU MAY USE Plotly to export HTML/CSS/JS from Python, but these charts need to be interactive and combined in a single portal hosted online
- they should be at least 3 different kinds of charts - you are not limited to bar, line, scatter! This chart type list could get you thinking: [d3](https://d3-graph-gallery.com/), [Python](https://python-graph-gallery.com/)
- for example: "[The New Geography of the Russian Elite](https://www.nytimes.com/interactive/2022/06/17/world/europe/russia-private-jets.html)", NYT
- for example: "[Uber Data Dash](https://dash.gallery/dash-uber-rides-demo/)", Plotly example
- for example: "[US Opioid Data](https://dash.gallery/dash-opioid-epidemic/)", Plotly example
- for example: ["Tracking the Global Outbreak](https://www.nytimes.com/interactive/2021/world/covid-cases.html), NYT Covid data + map

if you make 1 more complex, interactive custom visualization:
- a map, for example, could have area + points + pop-ups, multiple layers, or a scrolling story map - you could use your Leaflet skills or try [Mapbox](https://docs.mapbox.com/mapbox-gl-js/example/)
- for example: [Mapping Stop and Frisk, NYC](https://docs.mapbox.com/mapbox-gl-js/example/), NYT
- for example: [AAPI Census Data](https://ucla-center-for-neighborhood-knowledge.github.io/hub-census-map/), Movement Hub
- for example: [Shipmap!](https://www.shipmap.org/)
- for example: [A Map of Citi Bike](https://projects.newyorker.com/story/citi-bike.html), New Yorker
- for example: [2020 Election Results Map](https://www.nytimes.com/interactive/2021/upshot/2020-election-map.html), NYT

maybe you make a complex hand-drawn based visualization, (I am open to this! - with online documentation)
- for example: "[Bats and the Origins of Outbreaks](https://www.reuters.com/graphics/HEALTH-CORONAVIRUS/BATS/qzjpqglbxpx/)"
- for example: "[Dear Data](http://www.dear-data.com/theproject)"
maybe you make a custom interactive graphic, entirely unique in form! I am open to this too. Describe your idea when you turn in your initial team proposal and we'll talk!

## 🔎 evaluation criteria

Your work will be evaluated based on your analysis process, final visualizations, and your report. In general I am looking for:
  - Relevant data transformation in pandas or other methods, documented
  - Breadth and depth of exploratory analysis, documented
  - Clear explanation of your process in your methodology, and your choices in your report
  - Expressive and effective visualizations, solid design choices based on what we've learned (color, shape, interactivity, information density/placement, etc.)
  - Complexity: final visualizations should both tackle complexity, and present complex information in an inviting way ("rewards study", Tufte)
  - Final visualizations are polished, presented cleanly for the user, clearly labelled and documented, and they can "stand alone" and tell a story

Grading:
  - Proposal complete & on-time (5%)
  - Presentation (10%)
  - Report + Documentation (25%)
  - Final Visualization(s) (50%)

## ✉️ submit your work
  - The report text can be inside the Jupyter notebook, at the end after your final visualization renderings.
  - Please use [this form](https://airtable.com/appJ1zoJbOnRhJYPQ/shrQLr3zxT02wTSZ2) to submit your work **by Dec. 15, 11:59pm.**

