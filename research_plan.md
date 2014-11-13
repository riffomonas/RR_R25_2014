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
**Proposed modules**
---

### Modules will provide
* instruction on the importance of computational notebooks
* templates for setting up and maintaining a blog-based notebook
* best practices for using version control software (e.g. git and GitHub)
* discussion of code review as an mechanism for mentor-mentee interaction
* best practices for using literate programming tools for fostering reproducible
  research



The length of the proposed training module should be explained in terms
of scope and depth of coverage of the subject matter and how the research
education will be utilized by trainees, for example, a module on how to avoid
confirmation bias to be taken by all beginning laboratory workers at the
graduate student, postdoctoral fellow and beginning investigator level, or a
module on appropriate design of animal studies to be taken immediately prior to
beginning such work.

Describe the plans for piloting the training module.






### Plan

Core components of a teachable unit
* Learning goals: what will students know, understand, and be able to do?
* Intended learning outcomes: what performances or behaviors will indicate
  whether students have met the learning goals?
* Assessment activities: What activities will give students and instructors
  regular feedback about learning?
* Classroom activities: What activities will engage a diversity of students in
  learning?

Themes of a teachable unit
* Active learning
* Assessment
* Diversity - use male/female names in case studies; select papers from diverse
  environments; make sure papers that participants read are open
* Scientific teaching  


Bloom hierarchy
* Evaluation
* Synthesis
* Analysis
* Application
* Understanding
* Knowledge


Backward design
1. Identify desired results
2. Determine evidence for learning
3. Plan learning experiences and instruction (activities)
4. Align goals, activities, and assessments


Filter for learning goals
* Primary conceptual goals (these are *essential* to understand)
* Secondary conceptual goals (these are *important* to understand)
* Specific topics (these *illustrate* what is to be understood or present
  *interesting* examples with which students should be familiar)

Consider what students already know and target the difficult concepts
* What prior knowledge, previously held ideas, or misconceptions might students
  have?
* What are the conceptually challenging aspects of this material?
* What experiences will encourage students to share their misconceptions so they
  can be addressed?


* For each module, develop open source templates and example workflows

* Topic material:
   - Cookbook w/ predefined project
   - Generic w/ predefined project
   - Generic w/ their project

### Autotutorials
1. The importance of reproducible research and its relevance to studying the
   human microbiome

* Incomming:
  * Knowledge: At least a general familiarity with scientific method and
    microbiome research
  * Held ideas: Data and methods should be shrouded to protect research group
    from competitors
  * Misconceptions: A lack of reproduciblity indicates bad science or fraud

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

* Activities:
  * Case study 1: PI publishes a paper and gets innundated by emails asking
    about the nitty gritty of the methods
  * Case study 2: Student finds Meadows et al. IPython notebook and wants to do
    a secondary analysis
  * Presentation: describe of the recent history highlighting problems in
    reproducibility across science and in the microbiome literature (20 min).
  * Read: Wommack and Ravel editorial from Microbiome
  * Think-pair-share: what are the areas of microbiome research that are most
    prone to limit reproduciblity?
  * Read and analyze a recent microbiome paper to identify where there are
    possible limitations to reproducibility
  * Presentation: identify areas that are the most prone to limiting
    reproducibility and provide a technology overview that links technologies
    to specific hurdles in terms of insuring reproducibiltiy (20 min).
  * Go and do: create accounts at GitHub, FigShare, and DataDryad
  * Extend: go through an audit of your research group's five most recent
    publications and score them for their reproducibility using a checklist

* Assessment:
  * Take in responses to think-pair-share activity
  * Matching task linking reproducibility fail to a practice/technology that can
    help
  * Evidence that they created the GitHub, FigShare, and DataDryad accounts
  * Time spent on case studies and presentations
  * Indication from future publications that practices have changed? ($$$)



1. Development of electronic notebook using a blog
  - markdown
  - knitr
1. Maintaining blog and documentation using git and GitHub
  - version control
  - case studies w/ varying levels of documentation
1. How to collaborate
  - pull requests
  - code review
  - blog comments
1. Licensing
  - privacy
  - open science
1. Advanced topics
  - publishing
  - LaTex
  - slidify




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






## Potential Problems & Alternative Strategies





## Future Directions

* Establish an evolving resource for describing tools and practices for
  further development of these materials and practices (e.g. make, authoring
  papers, etc)





## Timeline
Provide a timeline for module development, piloting and refinement,
dissemination, evaluation, and maintenance.  This timeline must propose making
the training publicly available within two years of the award date
