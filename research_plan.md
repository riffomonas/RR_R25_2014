# Research Strategy
## Significance
The NIH-funded Human Microbiome Project (HMP) Roadmap Initiative engendered
great enthusiasm in understanding how the structure and function of the
microbiome relates to human health {The Human Microbiome Consortium, 2012 #2616;
The Human Microbiome Consortium, 2012 #2617}. This initiative has resulted
in a expansion of support at the NIH, who now supports these research efforts
across 16 of the 27 institutes, centers, and offices. The funding for microbiome
research more than doubled between fiscal years 2010 and 2012 to a total between
$120 and 150 million for nearly 300 grants and contracts (Lita Proctor, NHGRI,
personal communication). This financial support, combined with the development
of next generation sequencing platforms resulted in a meteoric rise in
microbiome-related publications (see Figure 1). ![Fig. 1](citation.pdf) This
massive expansion in microbiome research has relied on biomedical researchers to
do their own bioinformatics leading to a common complaint that researchers are
either unaware of or underserved by existing tools {Mardis, 2010 #1;Gevers, 2012
#2711}. The experience across the microbiome research domain has largely
paralleled that of other biomedical research areas were, as the RFA for this
competition notes, "graduate students were often significantly dependent on the
mentor or the mentor's lab for the training received, and postdoctoral fellows
were primarily dependent on the mentor or mentor's lab at all institutions.
Rather than being learned in prescribed curricula, **training in good laboratory
practices that influence data reproducibility appears to be largely passed down
from generation to generation of working scientists**, with substantial
variation from laboratory to laboratory." It is clear that microbiome research
is an important part of the NIH portfolio and that there is a dearth of training
for its practitioners to insure reproducibility of methods. The proposed project
will provide this growing community of researchers the tools they need to
improve the reproducibility of their research. ***This will yield a significant
vertical step in the field because we will have greater confidence in the
results and we will be better enabled to use previous studies as a launch point
for further investigations.*** This project will yield multiple benefits to
NIH-funded projects and beyond. First, although the current proposal focuses on
microbiome research, it is reasonable to expect that with some customization,
the materials could be easily tailored to other disciplines where novice
practitioners are implementign their own bioinformatic analyses. Second,
microbiome research is a specialized form of microbial ecology. Other microbial
ecologists who study environments as diverse as hydrothermal vents and soil
{Lesniewski, 2012 #2732;Schloss, 2006 #992} will benefit from the training they
can receive through the proposed instructional materials.

## Innovation
Our research group has been at the forefront of microbiome research through our
development of the popular software package, mothur, which has now been cited
more than 2,200 times, making it the most widely cited software package for
analyzing microbiome data {Schloss, 2009 #1816}. The mothur project has allowed
us to engage thousands of researchers through the wiki, forum, and mailing list
and through face-to-face workshops held at conferences, universities, and as
part of larger training initiatives. We recently conducted a survey that was
advertised through our newsletter and received 170 responses. First, 41% of
users were graduate students, 41% were PhD-level scientists, and 12% were
faculty. Second, 48% of the respondents have used mothur within Windows, 32%
within Mac OS X, and 45% within Linux. Finally and perhaps most surprising, 41%
had no programming experience. The others reported knowing R (35%), Perl (32%),
Python (27%), C/C++ (16%), Java (10%), or some other language (10%).  These
results and our experiences emphasize the that most individuals carrying out
microbiome research have limited experience in performing bioinformatics
research and are largely self-taught. In fact, from these experiences, we have
met the graduate students, postdocs, and faculty that the quote from the RFA
above describes and know that we are in a unique position to engage this
community. Although there are some exceptions, the *status quo* has generally
involved incomplete methods descriptions that are frequently at odds with the
papers being referenced and the use of "in house" scripts and pipelines that are
not disseminated with the final manuscript. ***Therefore, the proposed research
is innovative, in our opinion, because it will fulfill and unmet need to develop
instructional materials to train the growing number of microbiome researchers
best practices and insure that their analyses are reproducible by others.***
Once it is possible to confidently reproduce analyses it will be possible to
move on to determining whether the analyses were done well and to build off of
previous analyses to expand our knowledge of how the microbiome affects
transitions between health and disease.


## Proposed Research Education Program
**Specific Aim: Develop a set of autotutorials to teach microbiome researchers
habits for engaging in reproducible research**

***Introduction.*** The *objective* of this aim is to create a framework within
a research team for documenting research progress, collaborating between
researchers and supervisors, and ensuring the reproducibility of their data
analysis as it is disseminated in publications and oral presentations. We
*hypothesize* that training microbiome researchers in the best practices for
documenting their analyses will lead to greater transparency in publications,
improved reproducibility, and increased collaboration within and between
research groups. The *rational* for pursuing this aim is based on personal
experiences gained through supporting the mothur software package, supervising a
number of microbiome research projects, and the observation that most microbiome
research papers provide minimalist descriptions of the methods used to analyze
sequencing data and the raw data are frequently not made publicly available. We
will achieve the objective of this aim by developing a module consisting of four
autotutorials that any microbiome researcher can follow to quickly develop the
needed skills to generate a fully reproducible and automated analysis. This will
improve the the overall *analysis and reporting* of microbiome research.
Furthermore, our autotutorials will include content for research supervisors who
are not personally doing the analyses but need an entry point for insuring the
validity and reproducibility of their trainees' research. This will improve the
*culture of microbiome science*. The content of this module will be made freely
and publicly available and will serve as a starting point for developing other
training modules to improve the rigor and reproducibility of microbiome
research.

***Justification & Feasibility***

**Review of Relevant Literature**

* Reproducible research
  * Basis for concern over reproducible research broadly
  * Basis for concern within the microbiome research world
  * Examples of microbiome research papers that co-publish computational notebooks
* Problems with paper/pen notebooks
  * Note useful to the researcher
  * Not collaborative - live most of their lives in a file cabinet or a shelf
    - this would be very collaborative
    - permanence
  * Difficult to index through
    - tags
    - search engine accessible
  * Inefficient, difficult to incorporate multi-media
    - makes writing more efficient
    - multi-media very easy to incorporate
  * Incomplete - large datasets impossible to tape into document
  * Difficult to share with potential employers
* Problems with digital notebooks
  * Learning curve - but people need to get over that in computational disciplines
  * Security/privacy concerns
  * Legal aspects
  * Doodling - apps for that?
  * Many ELN have proprietary formats
  * Can't run an analysis from the notebook



**Preliminary Studies**

* mothur instructional materials / workshop / reproducibility
* MICRBIOL612
* our papers published with digital notebooks
* preliminary autotutorials
* NESCENT Reproducible Research Hackathon


***Research Design***
**Overview of proposed autotutorials**
We have developed the outlines for an initial set of four autotutorials:

#. **The importance of reproducible research and its relevance to studying the
  human microbiome**
#. **Maintaining an "electron trail" when documenting data analysis workflows**
#. **Developing a computational laboratory notebook for iterative analyses**
#. **Making a computational notebook collaborative**

The design for each autotutorial is adapted from guidelines developed through
the HHMI-funded Scientific Teaching workshop developed by Dr. Jo Handelsman with
whom Schloss did his postdoctoral training {Handelsman, 2004 #925; Handelsman,
2007 #3429}. The guiding principle is that educational materials should be
developed using the scientific method to yield materials that accurately depict
how science is done. Furthermore, participants should be facilitated as they
construct their own knowledge using a diversity of activities. Each autotutorial
will include: (i) a rationale for how it fits within the broader module, (ii)
description of the expected prior knowledge and misconceptions that participants
may have, (iii) the expected major conceptual hurdles for participants, (iv)
statement of learning goals and learning objectives, (v) description of any
specific technology, platform, or language that is used to illustrate the
material with a justification, (vi) overview of activities that will help the
participant to meet the learning goals and objectives, (vii) description of
assessments to determine whether the participant has met the goals as well as
the effectiveness of the autotutorials, (viii) the intended audience for each
activity, and (ix) the amount of time required for each activity. The proposed
activities will be selected based on an expanded concept of the 5Es: Engage,
Explore, Explain, Evaluate, Elaborate, and Extend {Eisenkraft, 2003 #3430;
Handelsman, 2007 #3429}. Briefly, each autotutorial will start by getting the
students to ENGAGE their prior knowledge by reading and reacting to a case
study. Next, activities will be developed where the participant has to go into
the literature or their research group to EXPLORE a topic further. This will
prevent participants from merely clicking through material. Each autotutorial
will include a demonstration where the steps are highly proscribed, a more
open-ended example that is used throughout the autotutorials that requires the
participant to insert material that they have learned in the earlier activites,
and a fully open-ended activity where the participant applies the material to
their specific situation and analysis needs. This scheme will gradually "remove
the training wheels" for the participant, encourage introspection and force them
to do more EXPLAINing and less regurgitation. In addition, by the time they are
doing the final activity within the autotutorial the participant should be at a
launch point for the participant (ELABORATE/EXTEND). Finally, each autotutorial
will provide an activity where the participant can EVALUATE their practices or
those of their lab and the research community. As much as is possible in an
autotutorial, our strategy will incorporate active learning, diversity, multiple
forms of qualitative and quantitative assessment, and scientific teaching.

The autotutorials for this module will be accessible to participants through a
freely accessible website. We are using this project to launch the "Riffomonas"
project (www.riffomonas.org). The title of this project refers to the musical
idea of "riffing" and a comon suffix for bacterial genera. Riffing is where a
musician repeats a theme and alters the theme using their own style. This is
what we want for microbiome research - the ability to repeat an analysis, but
then be able to take the analysis further with additional data or new methods.
All instructional and assessment materials will be available through a
repository on GitHub so that others can fork the material to develop their own
workshops, make pull requests to suggest improvements, or provide additional
autotutorials. To gain access to the module each participant will need to
create an account. Creation of the account will require them to provide their
gender, age, race, ethnicity, level of education, career stage, institution,
email address, and self-rating of their proficiency with microbiome data
analysis.

The following outlines are the starting point in the development of four
autotutorials that seek to help microbiome researchers appreciate the
limitations to reproducibility of data analysis in our discipline and gain the
skills needed to overcome those limitations. As we develop, pilot, and assess
the reactions to the autotutorials we will modify their content, style, and
organization.


**Autotutorial 1: The importance of reproducible research and its relevance to
studying the human microbiome**

***Rationale:*** Very few published microbiome studies can be easily reproduced
based on the level of detail provided in the published paper. In some cases, it
is not possible to access the raw data and associated metadata. Thus, it is
critical to start the module by establishing the importance of reproducible
research.

***Incoming:***

* *Knowledge:* At least a general familiarity with scientific method and
  microbiome research
* *Misconceptions:*

  * Data and methods should be shrouded to protect research group from
    competitors
  * "My lab's papers don't have a reproducibility problem"  

***Conceptually difficult content:*** The idea that a lack of reproducibility
does not necessarily indicate bad science or fraud. Rather, it limits one's
ability to assess the underlying science and the ability to move the science
forward.

***Learning goals:***

* *Primary:* Understand that reproducible research refers to the ability of
  another researcher to use your methods to reproduce your results
* *Secondary:*

    * Be able to articulate the causes and possible solutions for the lack of
    reproducibility in microbiome research
    * Appreciate that an inability to reproduce another researcher's results
    limits the ability to build off of that work

***Learning outcomes:***

* Articulate the importance of making raw data and detailed methods accessible
* Identify various technologies as solutions to practices that limit
  reproducibility

***Activities (~2 hrs):***

* **Case study 1:** Lab publishes a paper and gets inundated by emails asking
  about the nitty gritty of the methods. The trainee that did the study has gone
  on to a new job. This is an example of the common problem in microbiome
  research (10 min)
* **Case study 2:** Student finds Meadow et al. {Meadow, 2014 #3431} IPython
  notebook and wants to do a secondary analysis. This is an example of a good
  practice in microbiome research (10 min)
* **Presentation:** Describe of the recent history highlighting problems in
  reproducibility across science and in the microbiome literature (20 min).
* **Go explore:** Ravel and Wommack editorial from Microbiome {Ravel, 2014
  #3432} (10 min)
* **Reflection:** What are the areas of microbiome research that are most
  prone to limit reproduciblity? (5 min)
* **Go explore:** Read and analyze a recent microbiome paper to identify where
  there are possible limitations to reproducibility (20 min)
* **Presentation:** Identify areas that are the most prone to limiting
  reproducibility and provide a technology overview that links technologies
  to specific hurdles in terms of insuring reproducibility (20 min).
* **Go explore:** Create accounts at GitHub, FigShare, and DataDryad (20 min)
* **Extend:** Perform an audit of your research group's most recent publications
  and score them for their reproducibility using a supplied checklist

***Assessments:***

* Initial responses to the Reflection activity
* Matching task linking failure to reproduce results to a practice/technology
  discussed in the Presentations
* How many reproducibility hurdles can they identify in the microbiome paper?
* Evidence that they created the GitHub, FigShare, and DataDryad accounts
* Time spent on case studies and presentations
* Indication from future publications that practices have changed



**Autotutorial 2: Maintaining an "electron trail" when documenting data analysis
workflows**

***Rationale:*** Computational analyses are not generally a step-wise process
like traditional bench science. Rather, they are iterative and involve
significant interaction with computers. This Autotutorial will give participants
the skills they need to maintain an iterative electronic notebook where they
can record and annotate the flow of ideas as their analysis takes shape.

***Incoming:***

* *Knowledge:*

  * Frustration from writing a paper that has multiple versions from different
    co-authors
  * Appreciation that an analysis is not a linear process and requires
    iterations that involve testing numerous parameters
  * Familiarity with applications such as Dropbox and Box

* *Misconceptions:*

  * "My project isn't big enough for all of this"
  * There's no difference between binary (*.docx) and text files

***Conceptually difficult content:*** Many microbiome researchers have
difficulty with command line tools and the concepts inherent in version control
are likely to be novel to most researchers.

***Learning goals:***

* *Primary:* Understand the importance of documenting one's analysis
* *Secondary:* Appreciate the value of keeping track of the evolution of an
  analysis
* *Technology:*
  * Will focus on markdown because it is used with numerous other technologies
    (e.g. knitr, IPython, GitHub, pandoc) that we will also use in later
    autotutorials.
  * Will utilize git and GitHub for version control because of its popularity,
    numerous add-on tools, and its integration with other packages (e.g.
    RStudio, XCode, etc.)

***Learning outcomes:***

* Describe the process and importance of documenting the evolution of an
  analysis pipeline
* Create and maintain a repository for their project that results in
  documentation

***Activities (~4 hrs):***

* **Case study 1:** The prospect of taping screen shots, print outs, command
  line arguments into a paper-based notebook (Limitations of paper-based
  notebooks for microbiome projects) (10 min)
* **Case study 2:** You, 3 months from now, are your most important collaborator
  (The importance of documenting and commenting your analysis) (10 min)
* **Presentation:** Define literate programming; introduce wikis, IPython
  notebooks, and knitr-based documents; differentiate between these options (30
  min)
* **Go explore:** have participants look at good and bad examples from published
  papers; have them point out strengths and weaknesses (20 min)
* **Presentation:** Markdown, RStudio, and pandoc (30 min)
* **Activity:** Format an unformatted document (30 min)
* **Case study 3:** The time stamps on my files are a mess, how and when did
  they get like this?! (Annotating document changes) (10 min)
* **Presentation:** git; simple workflows, the log, navigating the history,
  branches (30 min)
* **Activity:** Using git to track changes in formatting; go back through
  history; branches (45 min)
* **Case study 4:** Scenario that describes that there is a continuum of
  reproducibility ranging from an electronic document that details what you've
  done versus a document that has the actual analysis embeded within it. This
  is a transition to the next autotutorial (10 min)
* **Extend:** take the most recently published paper in your lab and write a
  document describing how a figure was generated

***Assessment:***

* Evaluate the strengths and weaknesses that the participants find in the papers
  that they go and explore
* Have participants rank the various platforms (i.e. wikis, knitr, IPython) in
  terms of ease of use, reproducibility, usability, and ability to use as a
  starting point to move fowrad
* Quiz asking participants to link common git commands with their function
* How well activities match what we're looking for in the canned activities
* Time spent on case studies and presentations
* Number, frequency, quality of commits in the "Extend" activity
* Evidence for more advanced git commands
* Indication from future publications that more descriptive analysis methods are
  being published



**Autotutorial 3: Developing a computational laboratory notebook for iterative
analyses**

***Rationale:*** Although marrying text and a description of a pipeline
(Autotutorial 2) is a good start towards reproducibility and explaining what
one did, it is not fully reproducible since it does not reflect the actual
results from the actual commands being run. Here we will demonstrate how to
build upon the content from the previous autotutorial by adding executable
code chunks to make a fully reproducible analysis document.

***Incoming:***

* Knowledge:

  * This will build upon the information gained from Autotutorial 2
  * Will need to have some programming knowledge to make it all the way through
    this autotutorial
  * Likely have familiarity with how to use GUI and web-based tools and their
    strengths and weaknesses

* Misconceptions:

  * Programming is hard
  * Tools with graphical interfaces or those that are available online are easy
    to use or are more reliable programs

***Conceptually difficult content:*** Although it is probably fair to expect
people who are analyzing large microbiome datasets have experience writing
scripts to analyze their data, this is often not the reality. Will have to
create branch point here for people to jump off, go do some training in R or
Python and then jump back in. Also, the idea of a program generate the text
is a very different, but welcomed, approach for most researchers.

***Learning goals:***

* *Primary:* Appreciate the value of a fully automated analysis pipeline for
  insuring reproducibility
* *Secondary:* Be able to assess their skills as an analyst and what additional
  skills they need to develop. May need to see this as an advanced topic that
  people come back to repeatedly until they develop competencies
* *Technology:*

  * make, knitr, and IPython notebooks will be discussed because they are the
    only ones widely in use although IPython may soon be replaced by Jupyter
  * This module will not focus on programming languages or specific analysis
    tools; however, we will demonstrate that these can be easily used in a
    variety of literate programming contexts

***Learning outcomes:***

* Explain what is meant by "literate" programming and its value in reproducible
  research
* Create a fully reproducible, automated, and documented analysis pipeline

***Activities (~4 hrs):***

* **Case study 1:** Postdoc performs a statistical analysis in Excel/Minitab.
  New data comes in, now what? Case study will demonstrate the value of having
  an automated analysis that can easily be adjusted to acommpany new data or
  requirements. (10 min)
* **Case study 2:** You are revising your paper and begin to notice a number of
  typos where you have either mis-transcribed a mean and 95% confidence
  interval or have the wrong one inserted. Now what? Case study will emphasize
  the problems encountered by copying and pasting or manually trainscribing
  results. (10 min)
* **Presentation:** Define literate programming; describe tools for improving
  reproducibility including open source code, make, knitr, IPython (30 min)
* **Go explore:** React to several examples in the microbiome literature of
  literate analyses (30 min)
* **Presentation:** make (30 min)
* **Activity:** Navigate students through incorporating make into the Autotutorial
  2 materials (30 min)
* **Presentation:** IPython/Jupyter notebooks (30 min)
* **Activity:** Navigate students through incorporating the Autotutorial 2
  materials into IPyton notebooks in an automated manner (30 min)
* **Presentation: knitr (30 min)
* **Activity:** Navigate students through incorporating the Autotutorial 2
  materials into a knitr document (30 min)
* **Reflection:** What would it take to consistently automate one component of
  their analsyis? an entire paper? (15 min)
* **Extend:** Take the markdown document that they created in Autotutorial 2 and
  automate it

***Assessment:***

* Time spent on case studies and presentations
* Assess knowledge of command line arguments, python, R, make
* Evaluate reactions to literate analyses from the literature
* Use of resource materials
* How well results match what we're looking for in the canned activities
* Number of executable codeblocks in markdown document
* Number, frequency, quality of commits in the "Extend" activity
* Indication from future publications that automated analyses are being
  published


**Autotutorial 4: Making a computational notebook collaborative**

***Rationale:*** By definition, science is an iterative and collaborative search
to explain the world around us. Although making an analysis reproducible and
automated are great, that is only part of the mission. By making the raw data
and code publicly accessible, it increases collaboration within and between
research groups. This also helps to insure that not only is an analysis
reproducible, but that it is also done well.

***Incoming:***

* Knowledge:

  * Familiarity with the scientific method as an iterative process
  * Knowledge of different types of public databases
  * Experience requesting strains and reagents from others for wetlab-based
    experiments

* Misconceptions: The end goal of a project is a paper, rather than building to
  a series of papers

***Conceptually difficult material:***

* Releasing data to the public
* Making analysis accessible to the research supervisor or those that do not
  understand code

***Learning goals:***

* *Primary:* Science is an iterative process, were reproducibility is only the
  starting point to moving the field forward
* *Secondary:* Understand how to use technology to engage in peer review of
  computational analysis
* *Technology:* GitHub is used throughout this autotutorial because it's free,
  popular, has a lot of features, and for academic users their repositories can
  be made private or public

***Learning outcomes:***

* Appreciate the value of different platforms for archiving raw data
* Experience forking, modifying, and submitting/receiving pull requests
* Articulate the strengths and weaknesses of different open source licenses

***Activities (~4 hrs):***

* **Case study 1:** A research group has their paper accepted at
  NatureScienceCell and another researcher that is perceived as being a
  competitor reaches out to them to get access to their raw data and data
  analysis pipeline. What would you suggest? How would you argue? This case
  study emphasizes the importance of science as an iterative and collaborative
  affair. (10 min)
* **Presentation:** Discussion of open science concepts including licensing and
  open vs. closed source code. (20 min)
* **Reflection:** Does your laboratory have a consistent practice on whether to
  make repositories public or private during development? What license does
  your lab prefer? Why? (15 min)
* **Go explore:** Journals vary in their requirements for making data accessible
  and methods transparent. Go to the websites for your five favorite journals
  and describe their policies. Which of the journals seems the most "open"? (20
  min)
* **Case study 2:** Congratulations, you just published a paper with a
  reproducible analysis! What hurdles remain to being fully reproducible? This
  case study will get the participants to realize that they now have to make
  their data and source code accessible and that there are limitations and
  benefits to the various approaches. (10 min)
* **Presentation:** Overview of storage possibilities including personal lab
  servers, public databases, and commercial options (e.g. DataDrayd, FigShare,
  Amazon, GitHub) (15 min)
* **Go explore:** Look at your five favorite papers. How accessible are the
  original raw data? Are there metadata about the data? Is the analysis
  pipeline available? (15 min)
* **Presentation:** Submitting data to a commercial repository (15 min)
* **Activity:** Submit a data file to DataDryad and automate the retrieval of
  that file (15 min)
* **Demonstration:** Creating a presence on GitHub; pull/push workflow (20 min)
* **Activity:** Post repository to GitHub (30 min)
* **Demonstration:** Forking, pull requests, and code review (20 min)
* **Activity:** Collaborative coding, code review (30 min)
* **Extend:** Post your repository to GitHub, pick a license, and privacy
  setting.
* **Extend:** engage your PI or lab mates in conducting code review of each
  other's code

***Assessment:***

* Time spent on case studies and presentations
* Go explore results
* How well results match what we are looking for in the canned activities
* Demonstration that they got data in and out of DataDryad
* Have they setup their public repository?
* How many repositories in their account after 30, 50, or 100 days?
* Number and frequency of forks and pull requests in the "Extend" activities
* Indication from future publications that automated analyses are being
  published


## Evaluation Plan
As described above, participants will register with the module through a website
where they will provide demographic data. The website will track the amount of
time spent on each item and their responses. The autotutorials will request the
participants account name so that it is possible to look for their GitHub
account to track their performance. It is important to note that aside from the
account name, the evaluation will be completely anonymous. In general, it
is not possible to ascertain a person's identity from their account name. Each
autotutorial will have a variety of quantitative and qualitative assessments
that will allow us to track a participant's progress through the module. We will
create a badge-based commendation system where participants gain varying points.
In addition, participants will receive a certificate indicating completion of
the program. As we track the participants activities within each module we will
also be able to evaluate the usefulness of each activity and modify the content
to overcome misconceptions or confusion in the material. Finally, we will assess
the overall success of the module by sending an automated email to each
participant at 1, 2, and 3 year anniversaries of the date they completed the
module. These emails will invite the participant to complete a survey that
describes their current reproducible research  practices. We will monitor how
they have changed relative to when they started the module. The evaluation plan
that we have developed blends quantitative and qualitative measures of the
participants' learning and behavior as well as the quality of the instructional
materials.


## Dissemination Plan
We hope that this project will be a seed to engage other developers and the
microbiome community to improve the reproducibility of microbiome data analysis.
All instructional materials will be made freely available through a
website at www.riffomonas.org. To disseminate these materials we will pursue
several avenues including:  

* Social media (e.g. Twitter and blogs) to promote a reproducible microbiome
research initiative. This will create enthusiasm in the microbiome community and
foster their interest in developing and improving the modules.
* At least two manuscripts that will address the issue of reproducibility in
microbiome research and the development of our teaching modules.
* Microbiome-based e-mailing lists that Schloss (PI) is part of including the
extensive mothur mailing list, which currently has more than 3,000 registered
users and the Human Microbiome Project Data Analysis and Coordination Center
website and mailing list (http://www.hmpdacc.org).
* Networking with other microbiome researchers (see letters of support) to
facilitate workshops at 3 universities each of the two years of the project (see
the letters of support). This will serve to help us develop the modules as well
as  disseminate the modules.
* Utilize our connections within the American Society for Microbiology
to advertise advertise the module through *Microbe* magazine and in workshop
offerings at the society's General Meetings in 2016 and 2017 (see letter of
support from ASM).

In addition to www.riffomonas.org, which will host information about the
instructional materials, we intend to continue to develop instructional
materials and best practices beyond the funded period of this project to foster
greater reproducibility in microbiome research (see Future Directions). Once
funding for this project has been exhausted, the project should be able to
continue on as a democratic, open source, community-supported endeavor. To
support this all materials related to the project will be maintained as a public
GitHub project repository (www.github.com/riffomonas). In fact, the
development of this proposal is available at
www.github.com/riffomonas/reproduciblity_R25.


## Principal Investigator
As indicated by his biosketch and the numerous letters of support, Schloss is a
respected member of the microbiome research community and is an excellent
teacher that is anxious to utilize innovative teaching methods to communicate
complex materials. Over the past 6 years, Schloss has been the PI on 9 research
grants funded by NIH and other agencies including 2 R01 projects related to the
microibome. He has served as a co-Investigator on 7 additional projects during
that time. From this funding he has published 32 peer-reviewed publications and
he was the senior author on 16 of these studies; all of these studies have
involved research questions related to the microbiome. At the University of
Michigan, Schloss has developed two courses: *Symbiosis* and *Microbial
informatics*. The latter is a course that is designed to teach microbiologists
in MS and PhD programs and postdocs how to use R. This semester, in preparation
for this proposal, Schloss successfully experimented with using knitr-based
documents and GitHub repositories to submit assignments. In addition, all of his
course materials have been made available through the course's GitHub site
including the lecture slides that were prepared using the R slidify package that
is based on the knitr package (microbialinformatics.github.io). Although this
course touches on the content of the proposed teaching materials, it focused on
developing R programming skills rather than data analysis practices. This couse
and Schloss's  willingness to experiment with the content is indicative of his
innovative approach to teaching. Finally, over the past 7 years, Schloss has
offered 4-5 workshops describing how microbiologists can use mothur and R to
analyze data from microbiome research projects. This experience has given him a
unique perspective into the needs and competencies of the microbiome resarch
community. Together, these data and experiences indicate Schloss is "actively
engaged in research in an area related to the mission of NIH, and can organize,
administer, monitor, and evaluate the research education program."

## Program Faculty
Schloss will be the primary Program Faculty member for this project. In
addition, we have received numerous letters of support from colleagues at the
University of Michigan and across the United States indicating their support for
this project. In addition, each has responded enthusiastically to their
willingness to have us test our initial instructional materials with them and
their research groups. These colleagues represent a diverse array of individuals
with varying research interests (alphabetical):

* Jim Cavalcoli, PhD: University of Michigan
* Claire Fraser, PhD: University of Maryland
* Elizabeth Grice, PhD: University of Pennsylvania
* Jo Handelsman, PhD: Yale University
* Gary Huffnagle, PhD: University of Michigan
* John LiPuma, MD: University of Michigan
* Harry Mobley, PhD: University of Michigan
* Eric Pamer, MD: Memorial Sloan-Ketterin Cancer Center
* Courtney Robinson, PhD: Howard University
* Julie Segre, PhD: National Human Genetics Research Institute
* Vincent Young, MD/PhD: University of Michigan


## Program Participants
The target audiences for these modules are graduate students, postdoctoral
fellows, junior faculty, and more senior investigators that lead research
groups. Although we anticipate that any researcher will gain something from the
materials, our  primary audience is the growing pool of researchers that are new
to microbiome research and have limited computational skills. An innovative
component of our project will provide training materials for those leading
research groups to help them understand how to interact with those researchers
that they supervise. A common sentiment that we have heard from colleagues is
that they do not know how to do the data analysis themselves and are left to
trust that their trainees have acquired the information they need to do the
analysis. This puts the research supervisors in a difficult position of insuring
that the analysis is done well and reproducibly. By including these individuals
in the training program, especially Autotutorials 1 and 4, they will see how
they can "collaborate" with their own research group on the analysis. By
including participants from across multiple levels we will be able to take a
more holistic approach to the problem of reproducible research within the
microbiome research area.

We pride ourselves on recruiting diverse cohorts of researchers to the workshops
we hold to instruct people on best practices for using mothur to analyze 16S
rRNA gene sequences. It is common for the number of women to outnumber men and
to have 4-5 visible minorities attend a workshop with 30 participants. This
level of diversity is uncommon in computational workshops. Our strategy is to
place a very low bar for admission to the workshops, requiring that the
researcher merely email us to register. We have identified a number of research
groups led by diverse investigators that we will use to help develop and refine
our materials prior to final dissemination. Included in these is the research
group of Dr. Courtney Robinson, an Assistant Professor at Howard University,
which is a Historically Black University. For all of our assessments we will
keep track of the researchers' gender, race, ethnicity, and academic rank to
understand whether there are individual demographic groups that we are not
accessing or that may be having greater difficulties with some materials than
others. Finally, because the materials will be made freely available to anyone
that wants to participate in the modules, there should be little difficulty in
maintaining a high level of diversity among the participants. Regardless, we
will continue to monitor the demographic distribution of the participants on the
pre-test. We are committed to making our materials accessible to anyone wanting
to engage them. Our track record with previous training efforts indicates that
our approach does an exceptional job of engaging a diverse cross section of
microbiologists.

We take seriously our commitment to maintaining a low barrier to participation
in our training modules. The activities we selected use a variety of formats to
communicate material including case studies, presentations, explorations,
discussions, reflections, and opportunities to extend the information to their
own project. In selecting these examples we will take care to represent a
diversity of examples and researchers in the case study descriptions, papers
that are selected for exploration, and stories that are used for examples. By
fostering this diversity, we will be in a better position to insure that the
proposed training modules are compliant with section 508 of the Rehabilitation
Act (29 U.S.C. '794d), as amended by the Workforce Investment Act of 1998 (P.L.
105–220). To achieve this, we will follow the recommendations provided at the
"GSA 508 Tutorials, Guidance, Checklists" website
(http://www.gsa.gov/portal/content/103565).


## Institutional Environment and Commitment
Schloss has secured institutional support for this project on multiple levels.
First, as indicated by the letter of support from Dr. Harry L.T. Mobley, Chair
of the Department of Microbiology & Immunology at the University of Michigan
School of Medicine, Schloss has the support of the university to gain access to
adequate staff, facilities, and educational resources to make the planned
research education program successful. Second, Schloss has interacted with the
Center for Research on Learning and Teaching (CRLT) at the University of
Michigan to plan the assessment program for this project (see letter of support
from Smith). The CRLT provides a mixture of complimentary and fee-based
services, but does not participate in projects as personnel on grant proposals.
The support provided by CRLT will insure that Schloss it utilizing the latest in
pedagogical theory and assessment to develop the proposed teaching modules.
Third, the letter of support from Dr. Mary O'Riordan, Director of the University
of Michigan Program in Biomedical Sciences (PIBS), Schloss has her support to
solicit incoming graduate students to help develop and assess the instructional
materials that he develops for this project. Fourth, as indicated by the
numerous letters of support from other microbiome researchers at the University
of Michigan and across the United States, Schloss has the support and commitment
of other investigators to implement this project. They all see the value of
developing instructional materials such as those described in this proposal.
Finally, at the national level, Schloss has secured the support and commitment
of the American Society of Microbiology. Their letter of support indicates that
they would be receptive of Schloss presenting his teaching materials in
workshops at the annual General Meeting and that they would be willing to help
advertise the materials in their publications. The multiple levels of commitment
and broad support that this proposal enjoys speaks to its importance and the
unique qualifications of Schloss to lead the project.


## Expected Outcomes
At the most fundamental level, we expect to raise microbiome researcher's
awareness of the growing concern regarding reproducibility and the ramifications
for a lack of reproducibility. Through the proposed autotutorials, we expect the
reproducibility of the studies published by microbiome researchers who take the
module will be significantly enhanced. Because microbiome research is a subset
of the broader field of microbial ecology that is interested in microbial
communities in everything from soils to the air, we anticipate that these
scientists will benefit from this training as well. If we are successful in
enhancing the reproducibility of microbiome research, then we anticipate that
there will be an expansion in the number of studies that build off of the data
and analyses of previous studies. This will lead to increased reuse of data and code and
greater collaboration between researchers. Each of these outcomes will have a
significant impact on microbiome research. We also expect that a secondary
outcome of this module will be the improved computational skills of those that
take the module. This expectation is based on the observation that many of the
tools employed to improve reproducibility incorporate programming languages such
as bash, R, and Python (see Autotutorial 3); it is simply too cumbersome to
develop an automated analysis document using close-sourced tools with a
graphical user interface. Finally, we expect that the success of this module
will generate the momentum needed to develop additional modules to improve
reproducibility and data analysis skills. Broader adoption of the skills needed
to insure that microbiome analyses are reproducible must occur for the science
to advance. Through the development of the mothur software package, our research
group has a track record that demonstrates that we are uniquely poised to
develop a training module that will bring about this change.  


## Potential Problems & Alternative Strategies
We foresee two potential problems that could arise during this project. First,
it may be difficult for us to monitor the long term behavioral changes in the
participants. We intend to follow-up with participants every year for three
years to complete a survey of how the material in the workshop has affected
their research strategy. For most participants this follow-up will likely extend
beyond the life of the funding mechanism. However, because it is possible to
automate the dispersal of emails asking past participants to complete a survey,
it will be possible to perform the follow-up with minimal effort. A second
potential problem is the content of the module materials. The outlines provided
for the four autotutorials in our module represent a first iteration of
developing the content. As we proceed, we may realize that the participants have
a deep prior knowledge in a particular area making some of the content
unnecessary or a more limited prior knowledge, which will require us to add
background material. We will assess the alignment of the participants' prior
knowledge with our learning goals and activities through the assessment
mechanisms provided within each autotutorial outline.


## Future Directions
The microbiome research field is rapidly expanding and has evoked some amount
of skepticism (e.g. the concept of enterotypes, the presence of a placental
microbiome). Insuring the reproducibility of our experiments and analyses is
critical. We are optimistic that the material described in this proposal will
improve the overall reproducibility of the field. One question that needs to be
addressed is how reproducible the data analysis is in the typical microbiome
study. We anticipate using this module as a starting point to evaluate the
availability of raw data, description of methods, and general reproducibility of
data analysis within the microbiome research area. Furthermore, the the four
autotutorials described in this proposal will hopefully form the nucleus of a
collection of instructional materials designed to improve the reproducibility of
microbiome research. We foresee additional materials directed at producing
reproducible quantitative blog posts (e.g. Jekyll), presentations (e.g.
slidify), and methods of rendering markdown files (e.g. LaTeX). In the future,
we hope that the microbiome resarch community will embrace this initiative and
that it will evolve because of the contributions of other researchers.  


## Timeline
The two years of this project will allow us to develop, pilot, assess, refine,
and disseminate the module. For three additional unfunded years we will provide
maintenance and follow-up assessment of the module.

|               | Q3 '15 | Q4 '15 | Q1 '16 | Q2 '16 | Q3 '16 | Q4 '16 | Q1 '17 | Q2 '17 |  Y3-Y5 |
|---------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| Initial draft |   X    |    X   |        |        |        |        |        |        |        |
| Pilot         |        |    X   |    X   |    X   |    X   |        |        |        |        |
| Assess        |        |    X   |    X   |    X   |    X   |    X   |    X   |    X   |    X   |
| Refine        |        |        |    X   |    X   |    X   |    X   |        |        |        |
| Disseminate   |        |        |        |        |        |        |    X   |    X   |    X   |
| Manuscript 1  |        |        |        |    X   |        |        |        |        |        |
| Manuscript 2  |        |        |        |        |        |        |        |    X   |        |
| ASM Workshop  |        |        |        |    X   |        |        |        |    X   |        |
