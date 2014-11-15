# Research Strategy
## Significance
The NIH-funded Human Microbiome Project (HMP) Roadmap Initiative engendered
great enthusiasm in understanding how the structure and function of the
microbiome relates to human health {The Human Microbiome Consortium, 2012 #2616;
The Human Microbiome Consortium, 2012 #2617}. This initiative has resulted
in a expansion of support at the NIH, who now supports these research efforts
across 27 institutes, centers, and offices. The funding for microbiome research
more than doubled between fiscal years 2010 and 2012 to a total of more than
$180 million for nearly 300 grants and contracts (Lita Proctor, NHGRI, personal
communication). This financial support, combined with the development of next
generation sequencing platforms resulted in a meteoric rise in
microbiome-related publications (see Fig. 1). This massive expansion in
microbiome research has relied on biomedical researchers to do their own
bioinformatics leading to a common complaint that researchers are either unaware
of or underserved by existing tools {Mardis, 2010 #1;Gevers, 2012 #2711}. The
experience across the microbiome research domain has largely paralleled that of
other biomedical research areas were, as the RFA for this competition notes,
"graduate students were often significantly dependent on the mentor or the
mentor's lab for the training received, and postdoctoral fellows were primarily
dependent on the mentor or mentor's lab at all institutions.  Rather than
being learned in prescribed curricula, **training in good laboratory practices
that influence data reproducibility appears to be largely passed down from
generation to generation of working scientists**, with substantial variation
from laboratory to laboratory." It is clear that microbiome research is an
important part of the NIH portfolio and that there is a dearth of training for
its practitioners in the development of best practices related to insuring
reproducibility of methods. The contribution of the proposed project will
provide this growing community of researchers the tools they need to improve the
reproducibility of their research. ***This will yield a significant vertical step
in the field because we will have greater confidence in the results and we are
better enabled to use previous studies as a launch point for further
investigations.*** The support of this project will yield multiple benefits to
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
analyzing microbiome data [refs]. Through our development of mothur, we have
engaged thousands of researchers through a wiki, forum, and mailing list that
support mothur and through face-to-face workshops held at conferences,
universities, and as part of larger training initiatives. We recently conducted
a survey that was advertised through our newsletter and received 170 responses.
First, 41% of users were graduate students, 41% were PhD-level scientists, and
12% were faculty. Second, 48% of the respondents have used mothur within
Windows, 32% within Mac OS X, and 45% within Linux. Finally and perhaps most
surprising, 41% have no programming background. The others reported knowing R
(35%), Perl (32%), Python (27%), C/C++ (16%), Java (10%), or some other language
(10%).  These results and our experiences emphasize the that most individuals
carrying out microbiome research have limited experience in performing
bioinformatics research and are largely self-taught. In fact, from these
experiences, we have met the graduate students, postdocs, and faculty that the
quote from the RFA above describes and know that we are in a unique position to
engage this community. Although there are some exceptions, the *status quo* has
generally involved incomplete methods descriptions that are frequently at odds
with the papers being referenced and the use of "in house" scripts and pipelines
that are not disseminated with the final manuscript. ***Therefore, the proposed
research is innovative, in our opinion, because it will fulfil and unmet need to
develop instructional materials to train the growing number of microbiome
researchers best practices and insure that their analyses are reproducible by
others.*** Once it is possible to confidently reproduce analyses it will be
possible to move on to determining whether the analyses were done well and to
build off of previous analyses to expand our knowledge of how the microbiome
affects transitions between health and disease.


## Proposed Research Education Program
**Specific Aim: Develop a set of autotutorials to teach microbiome researchers
habits for engaging in reproducible research**

***Introduction.*** The *objective* of this aim is to create a framework within
a research team for documenting research progress, collaborating between
researchers and supervisors, and ensuring the reproducibility of their research
as it is disseminated in publications and oral presentations. We *hypothesize*
that training microbiome researchers in the best practices for documenting their
analyses will lead to greater transperancy in publications, improved
reproducibility, and increased collaboration within and between research groups.
The *rational* for pursuing this aim is based on personal experiences gained
through supporting the mothur software package, supervising a number of
microbiome research projects, and the observation that most microbiome research
papers provide minimalist descriptions of the methods used to analyze sequencing
data and the raw data are frequently not made publicly available. We will
achieve the objective of this aim by developing a module consisting of a series
of autotutorials that any microbiome researcher can follow to quickly develop
the needed skills to generate a fully reproducible and automated analysis. This
will improve the the overall *analysis and reporting* of microbiome research.
Furthermore, our autotutorials will include content for research supervisors who
are not personally doing the analyses but need an entry point for insuring the
validity and reproducibility of their trainees' research. This will imporove the
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



**Preliminary Studies**

* mothur instructional materials / workshop / reproducibility
* MICRBIOL612
* our papers published with digital notebooks
* preliminary autotutorials


***Research Design***
**Overview of proposed autotutorials**
We have developed the outlines for an initial set of four autotutorials:

* **Autotutorial 1: The importance of reproducible research and its relevance to
    studying the human microbiome**
* **Autotutorial 2: Maintaining an "electron trail" when documenting data
    analysis workflows**
* **Autotutorial 3: Developing a computational laboratory notebook for iterative
    analyses**
* **Autotutorial 4: Making a computational notebook collaborative**

Each autotutorial will include: (i) a rationale, (ii) description of the
expected prior knowledge and misconceptions that participants may enter with,
(iii) the expected major conceptual hurdles for participants, (iv) statement of
learning goals and learning objectives, (v) description of any specific
technology, platform, or language that is used to illustrate the material with a
justification, (vi) overview of activities that will help the participant to
meet the learning goals and objectives, (vii) description of assessments to
determine whether the participant has met the goals as well as the effectiveness
of the autotutorials, (viii) the intended audience for each activit, and (ix)
the amount of time required for each activity. The proposed activities will be
selected based on the idea of the 5Es of Engage, Explore, Explain, Evaluate,
Elaborate, and Extend. Briefly, we each autotutorial starts by getting the
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
doing the final activity within the autotutorial, the participant should be at a
launch point for the participant (ELABORATE/EXTEND). Finally, each autotutorial
will provide an activity where the participant can EVALUATE their practices or
those of their lab and the research community. As much as is possible in an
autotutorial, our strategy will reinforce several themes including active
learning, diversity, multiple forms of qualitative and quantitative assessment,
and scientific teaching.

These autotutorials will be accessible to participants through a freely
accessible website. Also, all materials will be available through a repository
on GitHub so that others can develop their own workshops, suggest improvements,
or provide additional autotutorials. To gain access to the autotutorial each
participant will need to create an account. Creation of the account will require
them to provide their gender, age, race, ethnicity, level of education, career
stage, institution, and self-ranking of proficiency with microbiome data
analysis. Each autotutorial will have a variety of quantitative and qualitative
assessments that will allow us to track a participant's progress through the
module. We will create a badge-based system where participants gain varying
points. At different thresholds we will supply the participant with a
certificate indicating their progress.



### Autotutorials
**Autotutorial 1: The importance of reproducible research and its relevance to studying the
   human microbiome**

* Rationale:

* Incoming:
  * Knowledge: At least a general familiarity with scientific method and
    microbiome research
  * Conceptually difficult: A lack of reproduciblity indicates bad science or
    fraud
  * Misconceptions:
    * Data and methods should be shrouded to protect research group from
      competitors
    * Their lab doesn't put out results that are not reproducible

* Learning goals:
  * Primary: Understand that reproducible research refers to the ability of
    another researcher to use your methods to reproduce your results
  * Secondary: Be able to articulate the causes and possible solutions for the
    lack of reproducibility in microbiome research
  * Secondary: Appreciate that an inability to reproduce another researcher's
    results limits the ability to build off of that work

* Learning outcomes:
  * Articulate the importance of making raw data and detailed methods
    accessible (Understanding)
  * Identify various technologies as solutions to practices that limit
    reproducibility (Comprehension)

* Activities (2 hrs):
  * Case study 1: PI publishes a paper and gets inundated by emails asking
    about the nitty gritty of the methods (10 min)
  * Case study 2: Student finds Meadows et al. IPython notebook and wants to do
    a secondary analysis (10 min)
  * Presentation: describe of the recent history highlighting problems in
    reproducibility across science and in the microbiome literature (20 min).
  * Read: Wommack and Ravel editorial from Microbiome (5 min)
  * Think-pair-share: what are the areas of microbiome research that are most
    prone to limit reproduciblity? (5 min)
  * Read and analyze a recent microbiome paper to identify where there are
    possible limitations to reproducibility (20 min)
  * Presentation: identify areas that are the most prone to limiting
    reproducibility and provide a technology overview that links technologies
    to specific hurdles in terms of insuring reproducibility (20 min).
  * Go and do: create accounts at GitHub, FigShare, and DataDryad (20 min)
  * Extend: go through an audit of your research group's most recent
    publications and score them for their reproducibility using a checklist (?)

* Assessment:
  * Take in responses to think-pair-share activity
  * Matching task linking reproducibility fail to a practice/technology
  * How many reproducibility fails can they identify in the microbiome paper?
  * Evidence that they created the GitHub, FigShare, and DataDryad accounts
  * Time spent on case studies and presentations
  * Indication from future publications that practices have changed? ($$$)



**Autotutorial 2: Maintaining an "electron trail" when documenting data analysis
workflows**

* Rationale:

* Incoming:
  * Knowledge:
    * Experience writing a paper with a million versions (PhD comics)
    * Appreciation that an analysis is not a linear process
    * History of using applications like Dropbox and Box
  * Misconceptions:
    * My project isn't big enough for all of this
    * Difference between binary (*.docx) and text files
  * Conceptually difficult:
    * difficulty with command line tools
    * version control is a novel concept

* Learning goals:
  * Primary: Understand the importance of documenting one's analysis
  * Secondary: Appreciate the value of keeping track of the evolution of an
    analysis
  * Topic/Technology:
    * Will focus on markdown because of it's tie in with so many other
      technologies (knitr, IPython, GitHub, pandoc) that we will use in later
      autotutorials.
    * Will utilize git and GitHub for version contorl because of its popularity,
      numerous add-on tools, and integration with other packages (e.g. RStudio,
      XCode, etc.)

* Learning outcomes:
  * Describe the process and importance of documenting the evolution of an
    analysis pipeline
  * Create and maintain a repository for their project that results in
    documentation

* Activities:
  * Case study 1: The prospect of taping screen shots, print outs, command line
    arguments into a paper-based notebook
  * Case study 2: You, 3 months from now, are your most important collaborator.
  * Presentation: Define literate programming; introduce wikis, IPython
    notebooks, and knitr-based documents; differentiate between these options
  * Go explore: have participants look at good and bad examples from published
    papers; have them point out strengths and weaknesses
  * Get input: How do the participants rank the options in terms of ease of use,
    reproducibility, usability, and ability to riff off of?
  * Demonstration: learning markdown (cook book)
  * Activity: Format an unformatted document
  * Case study 3: The time stamps on my files are a mess, how and when did they
    get like this?!
  * Demonstration: learning git (cook book); simple workflows, the log,
    navigating the history, branches
  * Quiz: link common git commands with their function
  * Activity: Using git to track changes in formatting; go back through
    history; branches
  * Case study 4: Continuum of reproducibility -> document electronically what
    you've done vs. a fully executable paper
  * Extend: take the most recently published paper in your lab and write a
    document describing how a figure was generated

* Assessment:
  * Evaluate submitted strengths and weaknesses of their exploration of papers
    documentation
  * Quiz results
  * How well activities match what we're looking for in the canned activities
  * Time spent on case studies and presentations
  * Number, frequency, quality of commits in the "Extend" activity
  * Evidence for more advanced git commands
  * Indication from future publications that more descriptive analysis methods
    are being published? ($$$)



**Autotutorial 3: Developing a computational laboratory notebook for iterative
analyses**

* Rationale:

* Incoming:
  * Knowledge:
    * information from Autotutorial 2
    * some programming knowledge
    * how to use GUI and web-based tools
  * Misconceptions:
    * Programming is hard
    * GUIs/web-based tools are easy
  * Conceptually difficult:
    * limited programming knowledge
    * very different way of thinking

* Learning goals:
  * Primary: Appreciate the value of a fully automated analysis pipeline for
    insuring reproducibility
  * Secondary: Be able to assess their skills as an analyst and what additional
    skills they need to develop. May need to see this as an advanced topic that
    people come back to repeatedly until they develop competencies
  * Topic/Technology:
    * RStudio/knitr, but will also highlight IPython notebooks and the
      developing Jupyter project
    * R / Python

* Learning outcomes:
  * Explain what is meant by "literate" programming and its value in
    reproducible research
  * Create a fully reproducible, automated, and documented analysis pipeline

* Activities:
  * Case study 1: Postdoc performs a statistical analysis in
    Excel/Minitab. New data comes in, now what?
  * Case study 2: You are revising your paper and begin to notice a number of
    typos where you have either mis-transcribed a mean and 95% confidence
    interval or have the wrong one inserted. Now what?
  * Survey: Assess knowledge of command line arguments, python, R, make
  * Presentation: define literate programming; describe tools for improving
    reproducibility including open source code, make, knitr, IPython
  * Go explore: React to several examples in the microbiome literature of
    literate analyses
  * Demonstration: make
  * Activity: Navigate students through incorporating make into the Autotutorial
    2 materials
  * Demonstration: IPython/Jupyter notebooks
  * Activity: Navigate students through incorporating the Autotutorial 2
    materials into IPyton notebooks in an automated manner
  * Demonstration: knitr
  * Activity: Navigate students through incorporating the Autotutorial 2
    materials into a knitr document
  * Introspection: what would it take to consistently automate one component of
    their analsyis? an entire paper?
  * << Case study 3: ??? >>
  * Extend: take the markdown document that they created in Autotutorial 2 and
    automate it

* Assessment:
  * Time spent on case studies and presentations
  * Survey results
  * Evaluate reactions to literate analyses from the literature
  * Use of resource materials
  * How well results match what we're looking for in the canned activities
  * Number of executable codeblocks in markdown document
  * Number, frequency, quality of commits in the "Extend" activity
  * Indication from future publications that automated analyses are being
    published? ($$$)



**Autotutorial 4: Making a computational notebook collaborative**

* Rationale:

* Incoming:
  * Knowledge:
    * Familiarity with the scientific method as an iterative process
    * Knowledge of different types of databases
    * Experience requesting strains and reagents from others
  * Misconceptions:
    * The end goal is a paper, rather than the next paper going forward
  * Conceptually difficult:
    * Releasing data into the wild
    * Making analysis accessible to PI or those that don't understand code

* Learning goals:
  * Primary: Science is an iterative process, were reproducibility is only the
    starting point to moving the field forward
  * Secondary: Understand how to use technology to engage in peer review of
    computational analysis
  * Topic/technology: GitHub. It's free, popular, has a lot of features, for
    academic users their repositories can be made public

* Learning outcomes:
  * Appreciate the value of different platforms for archiving raw data
  * Experience forking, modifying, and submitting/receiving pull requests
  * Articulate the strengths and weaknesses of different open source licenses

* Activities:
  * Case study 1: A research group has their paper accepted at NatureScienceCell
    and another researcher that is perceived as being a competitor reaches out
    to them to get access to their raw data and data analysis pipeline. What
    would you suggest? How would you argue?
  * Presentation: Open science - licensing, open vs. closed source code
  * Discussion: Does your laboratory have a consistent practice on whether to
    make repositories public or private during development? What license does
    your lab prefer? Why?
  * Go explore: Journals vary in their requirements for making data accessible
    and methods transparent. Go to the websites for your five favorite journals
    and describe their policies. Which of the journals seems the most "open"?
  * Case study 2: Congratulations, you just published a paper with reproducible
    analyses! What hurdles remain to being fully reproducible? Making the data
    and source code accessible. Where to make the data/source code available
    what are the strengths and weaknesses of each?
  * Presentation: Overview of storage possibilities including personal lab
    servers, public databases, and commercial options (e.g. DataDrayd, FigShare,
    Amazon, GitHub)
  * Go explore: Look at your five favorite papers. How accessible are the
    original raw data? Are there metadata about the data? Is the analysis
    pipeline available?
  * Demonstration: submitting data to a commercial repository
  * Activity: submit a data file to DataDryad and automate the retrieval of that
    file
  * Demonstration: creating a presence on GitHub; pull/push workflow
  * Activity: post repository to GitHub
  * Demonstration: forking/pull requests, code review
  * Activity: collaborative coding, code review
  * Extend: post your repository to GitHub, pick a license, and privacy setting.
  * Extend: engage your PI or labmates in conducting code review of each other's
    code

* Assessment:
  * Time spent on case studies and presentations
  * Go explore results
  * How well results match what we're looking for in the canned activities
  * Demonstration that they got data in and out of DataDryad
  * Have they setup their repository?
  * How many repositories in their account after 30, 50, 100 days?
  * Number and frequency of forks and pull requests in the "Extend" activities
  * Indication from future publications that automated analyses are being
    published? ($$$)


Alternative topics
* Blogging
* Presentations
* LaTex




## Evaluation Plan
Applications must include a plan for evaluating the activities supported by the
award in terms of their frequency of use and their usefulness. The application
must specify baseline metrics (e.g., numbers, educational levels, and
demographic characteristics of participants), as well as measures to gauge the
short or long-term success of the research education award in achieving its
objectives. Wherever appropriate, applicants are encouraged to obtain feedback
from participants to help identify weaknesses and to provide suggestions for
improvements.


## Dissemination Plan
We hope that this project will be a seed to engage other developers and the
microbiome community, in general, improve the reproducibility of microbiome
research. All instructional materials will be made freely available through a
website at www.retromonas.org. To disseminate these materials we will several
avenues. We will:  

* Utilize social media (e.g. Twitter and blogs) to promote a reproducible
microbiome research initiative. This will create enthusiasm in the microbiome
community and foster their interest in developing and improving the modules.
* Publish at least two manuscripts describing the issue of
reproducibility in microbiome research and the development of our teaching
modules.
* Exploit several microbiome-based e-mailing lists that Schloss (PI) is part of
including the extensive mothur mailing list (N=XXXX users) and the Human
Microbiome Project XXXXX mailing list (N=XXXX users).
* Network with other microbiome researchers (see letters of support) to
facilitate workshops at 3 universities each of the two years of  the project.
This will serve ot help us develop the modules as well as  disseminate the
modules.
* Utilize our connections within the American Society for Microbiology
to advertise advertise the module through *Microbe* magazine and in workshop
offerings at the society's General Meetings in 2016 and 2017 (see letter of
support from ASM).


In addition to a website that hosts information about the instructional
materials, we intend to continue to develop instructional materials and best
practices beyond the funded period of this project to foster greater
reproducibility in microbiome research. Once funding for this project has been
exhausted, the project should be able to continue on as a democratic, open
source, community-supported endeavor. To support this all materials related
to the project will be maintained as a public GitHub project repository
(http://www.github/retromonas). In fact, the development of this proposal is
available at http://www.github/retromonas/reproduciblity_R25.


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
informatics*. The latter is a course that is designed to teach microbiology MS
and PhD students and postdocs to use R. This semester, in preparation for this
proposal, Schloss successfully experimented with using knitr-based documents and
GitHub repositories to submit assignments. In addition, all of his course
materials have been made available through the course's GitHub site including
the lecture slides that were prepared using the R slidify package that is based
on the knitr package (microbialinformatics.github.io). Although this course
touches on the content of the proposed teaching mateirals, it focused on
developing R skills rather than laboratory practices. This couse and Schloss's
willingness to experiment with the content is indicative of his innovative
approach to teaching. Finally, over the past 7 years, Schloss has offered 4-5
workshops describing how microbiologists can use mothur and R to analyze data
from microbiome research projects. This experience has given him a unique
perspective into the needs and competencies of the microbiome resarch community.
Together, these data and experiences indicate Schloss is "actively engaged in
research in an area related to the mission of NIH, and can organize, administer,
monitor, and evaluate the research education program."


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
to microbiome research and have limited computational skills. For this audience,
we will have an entry level stage where they would go through all of the
modules. An innovative component of our project will provide training materials
for those leading research groups to help them understand how to interact with
those researchers that they supervise. Two significant problems with a lack of
reproducibility include the inability of supervisors to adequately vet a
trainees methods and the inability of supervisors to fully engage with the
trainee in develop the methods. By including participants from across multiple
levels we will be able to take a more holistic approach to the problem of
reproducible research within the microbiome research area.

We pride ourselves on recruiting diverse cohorts of researchers to the workshops
we hold to instruct people on best practices for using mothur to analyze 16S
rRNA gene sequences. It is common for the number of women to outnumber men and
to have 4-5 African American and Hispanic American researchers attend workshop
with 30 participants. This level of diversity is uncommon in computational
workshops. Our strategy is to place a very low bar for admission to the
workshops, requiring that the researcher merely email us to register. We have
identified a number of research groups led by diverse investigators that we will
use to help develop and refine our materials prior to final dissemination.
Included in these is the research group of Dr. Courtney Robinson, an Assistant
Professor at Howard University, which is a Historically Black University. For
all of our assessments we will keep track of the researchers' gender, race,
ethnicity, and academic rank to understand whether there are individual groups
that we are not accessing or that may be having greater difficulties with some
materials than other groups. Finally, because the materials will be made freely
available to anyone that wants to participate in the modules, there should be
little difficulty in maintaining a high level of diversity among the
participants. Regardless, we will continue to monitor the demographic
distribution of the participants on the pre-test. We are committed to making
our materials accessible to anyone wanting to engage them. Our track record with
previous training efforts indicates that our approach does an exceptional job of
engaging a diverse cross section of microbiologists.

We take seriously our commitment to maintaining a low barrier to participation
in our training modules. This includes insuring that the proposed training
modules are compliant with section 508 of the Rehabilitation Act (29 U.S.C. '794
d), as amended by the Workforce Investment Act of 1998 (P.L. 105–220). To
achieve this, we will follow the recommendations provided at the "GSA 508
Tutorials, Guidance, Checklists" website
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

* Improved reproducibility of microbiome analyses
* Improved computational skills
* Greater collaboration
* Increased re-use of data and code
* Motivation to develop additional modules to improve reproducibility and data
  analysis skills




## Potential Problems & Alternative Strategies





## Future Directions

* Establish an evolving resource for describing tools and practices for
  further development of these materials and practices (e.g. make, authoring
  papers, etc)





## Timeline
Provide a timeline for module development, piloting and refinement,
dissemination, evaluation, and maintenance.  This timeline must propose making
the training publicly available within two years of the award date
