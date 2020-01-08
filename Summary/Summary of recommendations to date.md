This summary covers activities through the end of the Jan 8, 2019.

During this time I have had meetings with BUGS (2), Dave Schniedier, Danielle Quinn, an EcoEvo meeting open to all members of the department, Ed Whalen, Yolanda, Eric, Shawn, as well as email exchanges or brief communication with Dawn Bignell, Kapil Tahlan, Andrew Lang, Lourdes Pena-Castillo, Piotr Trela, Margret Caldwell, Sally Goodard, Hope Bennett, Valerie Power, and Fiona Cuthbert.

My initial thoughts are shaped by Hampton et al. 2017, which I highly recommend (https://academic.oup.com/bioscience/article/67/6/546/3784601).

The revision of the biology curiculuum with respect to quantitative training should have three objectives:
1. Give biology majors training in the quantitative skills that are necessary for successful completion of 3000 and 4000 courses in their choosen stream (these skills should include those listed in Table 2 of Hampton et al. 2017);
2. Foster quantitative literacy. In additon to basic numeracy, quantitative literacy implies that students will graduate with the skills to critically assess and evaluate formal presentations of data and quantiative analyses (e.g., in a report, journal article). Not all students will graduate to be coders or statistical wizards, but all of our students should be comfortable reading and evaluating papers with quantitaitve methods appropriate to their steam/specialization (for example, statistical analyses, mathematical models, large data sets, graphs, computer code). 
3. Develop students' confidence in handling and interpreting data. At minimmum, upon completing our BSc program (or potentially only specific streams of our program), if a student were given data and some context, the student can apply their biological knowledge to form a hypothesis, and make some progress on assessing whether the data support their hypothesis using statistics and/or data visualization.

See document: "Draft quantiative learning goals" for detailed learning goals and objectives at each level (document in progress): https://github.com/ahurford/quantitative-training-resources/blob/master/Documents%20in%20progress/Draft%20Quantitative%20Learning%20Goals.pdf. This document requires restructuring and further work.

In addition, I emailed Carissa Brown to request a copy of geography's quantitative training document at the request of Eric Vanderwal, but have not received a reply.

### Publically available as an ebook
A Quantitative training in biology manual will be developed and available as an online resource that is publically available and hosted on Gitlab. Courses can provide the link to the ebook on brightspace. It is essential that the quant materials are available digitially so that we can link to existing online resources such as the carpentaries and ebooks, or where to download R.

Existing lab manuals will be retained in their current form, but will be edited to reference links to the labs which are from the quantitative training manual.

## BIOL 1001/1002
Biology 1001 and 1002 lectures seems tightly focused around Campbell Biology, and as such, there is limited opportunity to deviate from the textbook. This was the feedback given from Sally, Piotr, and Margaret. We note that there are nice quantiative exercises contained within Campbell Biology.

## BIOL 1001/1002 Labs
### Revise lab manual text to give an updated description of what biologists do
The lab manual needs to be edited to communicate current practices for researchers. Particularly, in Appendix II, beginning on p118, comments around 'The Scientific Method', 'How Researchers communicate their findings', and 'Graphs and Tables' need to be revised. In addition, the roles of statistics in biology and modelling as an approach to doing science needs to be communicated. The role of traditional ecological knowledge and non-western approaches should be mentioned. Basic terminology around statistics and data science should be introduced.

### Tables
Data archiving standards for professional biologists have now moved beyond writing results in a notebook, and we need to give the students exposure to these expectations. These expectations should be a streamlined version of Week 1 https://datacarpentry.org/semester-biology/schedule/ and Emilie and Danielle may also have relevant materials. Specifically, Q.2 of the assignment for week 1 https://datacarpentry.org/semester-biology/assignments/sql-data/ reflects similar expectations as to what we should have for first year biology. We might also discuss what is metadata and Ecological Metadata Language (https://joss.theoj.org/papers/10.21105/joss.01276). In the 

Ideally, we will ask first year students to archive data in an electronic format and submit to a github/gitlab repository. We would require the students to consent to having their data be publically availabile and perhaps anonymize the names. This would also require that the students create a free github/gitlab account, which may be problematic for the university. This would also require some training of staff to understand how to manage the data repository that we've created.  We need to provide training/documentation for lab instructors and TAs on github, both for help the students to submit their data, but also on merging the pull requests from the submitted data.

### Graphs
Similarly, professional biologists have moved beyond making graphs using pencil and paper. Perhaps we could accept graphs made in a variety of softwares, while also have developed resources for R, RStudio, and ggplot. Again, this should be a streamlined version of Week 5 from https://datacarpentry.org/semester-biology/schedule/, but may require some time as plotting requires some preliminary comments on built-in functions, loading packages, getting help, common errors, reading in data, etc. Expectations around figure captions should be revised. 

### Statistics
_AH: These are some very specific suggestions that we need to integrate into https://github.com/ahurford/quantitative-training-resources/blob/master/Documents%20in%20progress/Draft%20Quantitative%20Learning%20Goals.pdf and eventually remove from here_

Having not yet required STAT 2550, BIOL 1001/1002 is not the place to start in on statistics, but it is the place to better prepare students for (1) the importance of statistics in biology; and (2) key concepts in statistics.

(1) will be addressed by revisions to the lab manual.

Regarding (2), (and these recommendations are made primarily from my conversations with DS):

1. Currently, first year students are taught to write a hypothesis and a prediction. We need to add: sketch a graph of the results if your hypothesis was supported; draw a graph if your hypothesis is not supported; and write the equations that correspond to each of your graphs. To teach this we need to say, 'if you think _y_ increases with _x_, but you're not quite sure exactly how, the default assumption, given that _x_ is a continous variable, is that there is a linear relationship, _y=mx+c_. In writing the equations, students get to choose their notation. This is powerful, because biology involves a lot of non-conventional notation, for example, dN/dt = r N (exponential growth), if dN/dt is plotted on the y-axis, and N is plotted on the x-axis, is a straight line with a zero y-intercept and a slope of r, but the notation is a barrier because it isn't in the form _y = mx_.

2. We need to expect that some indication of spread is reported, i.e. error bars on bar plots where the error bars represent the range (i.e. from the min to the max observation) and the figure caption is required to specify what the error bars show.

### Add/Remove/Revise 1001/1002 labs
At least one lab needs to be added to prepare students for our new expectations on data archiving and graphs. This lab will also cover data vizualization and choosing what type of graph to use. We may need to remove 1 existing lab to do this. We may need to lighten the content for some labs that we will now be requiring electronic data entry and graphs.

## A 2000-level "Datacarpentary in Biology"
Initially, I had wanted to recommend a new second year course: "Datacarpentary in Biology", "Handling biological data","Tools and techniques in biology" or "Concepts and Principles in Biology". The course could draw on materials from here: https://datacarpentry.org/semester-biology/schedule/ (which has a github repository and I emailed Ethan White and he is more than okay with use borrow and modifying his materials). The linked course is a graduate-level course and so the idea is to spread the content across 13 weeks to resuls in a course appropriate for the 2000-level. A course proposal was drafted here: https://github.com/ahurford/quantitative-training-resources/blob/master/Documents%20in%20progress/2020%20%20New%20Course%20Proposal%20Biol%202XXX%20Data%20skills%20for%20Biologists.docx

Each week the documentataion and exercises could be based around a different second year required course, i.e. Week 1: Data entry and storage use examples from Cell Biology; Week 2 Intro to R uses examples based from Ecology; and so forth for Genetics, Evolution and Physiology. This would also open up the possibility to pilot these labs at the second year level if instructors are willing and while the proposed course is undergoing university approval.

The idea to propose a basic R programming and quantitative literacy course for biologists at the second year was shelved following the meeting with Yolanda, Eric, and Shawn on December 17 for the following reasons:

- I am concerned that Lourdes feels that we should instead require a CS course on general programming. I see Lourdes as a key component of our quantitative training going forward.

- The Dean of Science does not want courses that duplicate resources

- Teaching faculty are a scarce resource: whoever teaches this second year course then becomes unavailable at the third and fourth year level

- 2000- is the appropriate level for such a course, and the course it needed, but currently the second year course requirements for the biology major are very heavy, and so it is not possible to add this course (or any course) without a broader discussion of our curiculuum.

Having shelfed this idea, currently we plan to develop labs for second year to develop related skills. It should be noted that we are having to work within a constrained space (limited instructor availability and a heavy load of required courses) and these constraints reduce our ability effect change in the area of quantitative training. In addition, if we are to work within the scope of existing courses, there needs to be support from leadership in the department, both in terms of identifying quantitative training as a priority for our department (so that individual instructors know to support the quantitative training initiative), and providing the resources to effect change (i.e., currently we have a TA to help us with this for 3 semesters, and this TA is the main avenue through which we can affect change).

## Recommendations for BIOL 2000-level courses and beyond
We will maintain resources and guidelines to help with quantitative content in 2000- and above courses. Resources could include ready-made activities and exercises for use in lecture and/or lab, as well as training/workshops for faculty and lab instructors/TAs. 

Some recommendations for learning outcomes are (need to revise https://github.com/ahurford/quantitative-training-resources/blob/master/Draft%20Quantitative%20Learning%20Goals.pdf to cover these):

1. Discuss Type I and Type II errors (Type I: alarm, no fire; Type II: fire, no alarm). The statement from American Statistical Association advocating the downfall of alpha = 0.05, if I understand DS correctly, should now be replaced with a discussion of the types of questions where lower or higher acceptable Type II errors are appropriate, for example, a fire with no alarm is a life and death matter; if my oven timer doesn't go off, then dinner will get burnt which is much less serious and as such a higher Type II error is acceptible for the latter. (I need to read and consult further on this point).

1. Increase awareness about the importance of sampling design and the implications of different sampling approaches (random, haphazarad, stratified random) on analyses and inference. This could be done in lectures through illustrating concepts with figure and images from real-world reserarch papers (if your own, even better) and through simple lab exericses that have students sample from a population and analyse the data. 

1. Increase awareness about the imporance of experimental design and how decisions about experimental design affect which statistical tests are appropriate. Some of this may overlap concepts taughts in STAT 2550 (AH edit: I'm not sure this is covered here), but illustrting these with Biology examples will increase undertanding. Key concepts related to experimental design that students should be comfortable with at the end of the 2000-level courses include: treatment/control, sampling replicates vs. experimental replicate (some areas of biology term these technical replicate vs. biological replication), pseudoreplication, block design, randomized block design.

1. All graphs should be accompanied by their formulas and in non-conventional notation, if appropriate, to encourage better familiarity with the shapes of functions and non-conventional notational. 

1. To build confidence with writing equations, we might also talk about units (really the only way an equation can go wrong) and give guidelines for notation choices (see links.md for recent paper on this).

1. We need to be consistently reporting the spread of data and discussing overlap with respect to Type II error.

1. ggplot and RStudio. Personally, I don't use ggplot, but https://stat545.com/index.html makes a compelling argument for it and all the software/data carpentries and other prepackaged materials are in ggplot and dplyr.

## Recommendations for each year
With the BIOL 1001/1002 lab manuals now available as ebooks (and publically available), instructors in upper level courses should be knowledgeable of what is taught in first year and be knowledgable as to if what they are recommending conflicts. We should set specific goals for expectations at the end of second, third and fourth years. Competency E1 on p22 of Scientific Foundations for Future Physicians (https://store.aamc.org/scientific-foundations-for-future-physicians-pdf.html) has some good comments.

## STAT 2550

Hampton et al. (https://academic.oup.com/bioscience/article/67/6/546/3784601) states that "we recommend a computational approach to statistics training". Therefore, we need to consult with the Statistics department to determine if STAT 2550 is meeting our needs and to facilitate better integration STAT 2550 and our program. At BUGS, there was support for replacing STAT 2550 with an in-house version, but this would present staffing challenges. It was noted that psychology does not require STAT 2550 and instead teaches their own course. Might we consider requiring that pyschology course instead of STAT 2550?

It is also important to touch on 1) the statement from that ASA about alpha = 0.05; and 2) data visualization as discussed here (https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128).

## BIOL 4605 and graduate courses
This course from UBC seems very good: https://stat545.com/index.html. Amy has also archieved all of Dave Schneiders BIOL 4605 materials from Fall 2019.

## The curriculuum
To introduce a new second year course that is required we will need to elimate at least one required second year course. However, we need to reduce our required courseload further than this, and, ideally, to the extent that double majors with geogaraphy, math, stats, and computer science could be possible. This was a topic of discussion at BUGS. The current required courses are (see https://www.mun.ca/regoff/calendar/sectionNo=SCI-0736):

BIOC 2201 Intro to Biochemistry

BIOC 3206 Metabolism

CHEM 1050 General Chemistry 1 (3h lab/wk)

CHEM 1051 General Chemistry 2 (3h lab/wk)

CHEM 2400 Organic Chemistry 1 (3h lab/wk)

CHEM 2401 Organic Chemistry 2 (3h lab/week)

Six (6) credit hours in Critical Reading and Writing (CRW) courses, including at least 3 credit hours in English courses.

MATH 1000 Calculus 1

PHYS 1020 Intro physics 1 (6 x 3hr lab/semester)

PHYS 1021 (or 1050 and 1051) Intro physics 2 (6 x 3hr lab/semester)

STAT 2550 Statistics for Science Students (90 min lab/wk)

BIOL 1001 Principles of Biology I (3h lab/week)

BIOL 1002 Principles of Biology II (3h lab/week)

BIOL 2060 Prinicples of Cell Biology (3h lab/week)

BIOL 2250 Principles of Genetics (3h lab/week)

BIOL 2600 Prinicples of Ecology (3h lab/week)

BIOL 2900 Principles of Evolution and Systematics (3h lab/week)

one of BIOL 3401 Comparative Animal Physiology, 3402 Plant physiology, 4245 Biophysics and 4404 Microbial physiology. (3h lab/week)

If the faculty divide into two groups, I'd expect that the courses each group would fight for are:

Cell and Molecular: BIOL 2060, physiology, 2 organic chemistries, 2 biochemistries (6 total courses + 4 labs = 30 hr/wk)

Ecology and Evolution: BIOL 2600, 2900, MATH 1001, STAT 2550 (4 total courses + 2.5 labs = 19.5 hr/wk)

The remaining reqirements are probably supported by all.

Leading suggestions are eliminating the requirement of Organic Chem 2 and making the course requirments stream specific (As discussed at the Sept. 20 and Nov 7, 2019 BUGS meetings). 

I choose three other Canadian universities for a quick comparison:

- Dalhousie BSc in Biology: lighter load of required courses by requiring only 2 semesters of CHEM, no BIOCHEM, and no PHYS: https://www.dal.ca/faculty/science/biology/undergraduate/majors-and-minors/major-in-biology.html

- Simon Fraser BSc in Biology: appears to have a similar load of required courses as compared to us  http://www.sfu.ca/students/calendar/2020/spring/programs/biological-sciences/major/bachelor-of-science.html

- University of Alberta: Difficult to compare as Cell and Molecular Biology appears to be separated from Ecology, Evolution and Environmental Scinece.

## Making resources publically available
A key aspect of making progress is continuity across courses within the major including STAT 2550 (Vision and Change can be cited regarding the importance of this point). What we are teaching about 'how to make a graph in R' in first or second year needs to flow up to third and fourth year. To this extent, we need to maintain public (github) and private (brightspace) repositories of our teaching materials.

## Computing and software requirements
We should develop a policy on our expectations (i.e., are undergrads expected to have access to a personal computer, and if so, what minimum specs) and quantify demand for departmental computing resources. See https://github.com/ahurford/quantitative-training-resources/blob/master/Computer%20policies.md

## Teaching communication and collaboration
Both Vision and Change and Hampton et al. 2017, highlight communication skills as a key aspect of data science training. YW has mentioned an interest in this area. To my understanding, the references are not so much referring to social media or giving talks, but how to communicate to participate in interdisciplinary collaborations. (YW: My communications module in BIOL 4651 (6-9 hours of the semester) focuses on general principles of good communication and practical examples of to effectively communicate science to different audiences (e.g., government/decision makers, fellow scientists, K-12 students, general public) and with different formats (written, oral, visual). This could be modified to focus explicitly on communicating quantiative material to diverse audiences). 

## Streams
We need to work on tightening up our streams as recommended in the AUP, including the Quantitative/field stream.

## Modelling
Vision and Change highlights the importance of modelling. So far, my recommendations focus mainly around stats and data science.
