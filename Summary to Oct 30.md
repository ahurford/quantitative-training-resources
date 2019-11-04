These are my _prelimary_ ideas as of Oct 30, 2019, but I have not consulted widely enough to be confidence in these recommendations at this point. As such, I welcome feedback.

The revision of the biology curiculuum with respect to quantitative training should have two objectives:
1. Prepare biology majors for quantitative skills that are expected in 3000 and 4000 courses in their choosen stream; and
2. Upon completing our BSc program (or potentially only specific streams of our program), if a student were given data and some context, the student can apply their biological knowledge to form a hypothesis, and make some progress on assessing whether the data support their hypothesis using statistics and/or data visualization.

Objective 1. will be addressed by surveying the faculty to identify what skills are considered necessary. Potentially, 1. may be entirely subsumed under 2.

## BIOL 1001/1002
Biology 1001 and 1002 lectures seems tightly focused around Campbell Biology, and as such, there is limited opportunity to deviate from the textbook.

## BIOL 1001/1002 Labs
We should use the labs to introduce students to data science, removing some of the labs that are focused more specifically around knowledge reinforcement from Lecture, instead focusing on giving the students exposure to how biologists, collect, archive, and report data. In addition, the lab manual needs to be edited to communicate current practices for researchers. Particularly, in Appendix II, beginning on p118, comments around 'The Scientific Method', 'How Researchers communicate their findings', and 'Graphs and Tables' need to be revised. In addition, the roles of statistics in biology and modelling as an approach to doing science needs to be communicated.

### Recommendations around making tables
Data archiving standards for professional biologists have now moved beyond writing results in a notebook and we need to give the students exposure to these expectations. We should ask first year students to archive data in an electronic format and submit to a github repository. This requirement needs to be supported by readings/text that explain that this is the current recommendation. We might also discuss what is metadata and Ecological Metadata Language.

### Recommendations around making graphs
Similarly, professional biologists have moved beyond making graphs using pencil and paper! Perhaps this isn't the place to introduce R, and we could accept graphs made in a variety of softwares, while also have developed resources for R, RStudio, and ggplot. Expectations around figure captions should be revised.

### Recommendations around statistics
Having not yet required STAT 2550, BIOL 1001/1002 is not the place to start in on statistics, but it is the place to better prepare students for (1) the importance of statistics in biology; and (2) key concepts in statistics.

(1) will be address by revisions to the lab manual.

Regarding (2), (and these recommendations are made primarily from my conversations with DS):

1. Currently, first year students are taught to write a hypothesis and a prediction. We need to add: sketch a graph of the results if your hypothesis was supported; draw a graph if your hypothesis is not supported; and write the equations that correspond to each of your graphs. To teach this we need to say, 'if you think _y_ increases with _x_, but you're not quite sure exactly how, the default assumption, given that _x_ is a continous variable, is that there is a linear relationship, _y=mx+c_. In writing the equations, students get to choose their notation. This is powerful, because biology involves a lot of non-conventional notation, for example, dN/dt = r N (exponential growth), if dN/dt is plotted on the y-axis, and N is plotted on the x-axis, is a straight line with a zero y-intercept and a slope of r, but the notation is a barrier because it isn't in the form _y = mx_.

1. We need to expect that some indication of spread is reported, i.e. error bars on bar plots where the error bars represent the range (i.e. from the min to the max observation) and the figure caption is required to specify what the error bars show.

### Recommendations on the lab manual
The BIOL 1001 and 1002 lab manuals will be available as ebooks as well as hardcopies. The transfer to an ebook will be completed in the winter and summer of 2020 using the bookdown package for R and will be completed by the TA hired to work with AH on our quantitative program.

## Recommendations for statistics in 2000-level courses and beyond

1. Discuss Type I and Type II errors (Type I: alarm, no fire; Type II: fire, no alarm). The statement from American Statistical Association advocating the downfall of alpha = 0.05, if I understand DS correctly, should now be replaced with a discussion of the types of questions where lower or higher acceptable Type II errors are appropriate, for example, a fire with no alarm is a life and death matter; if my oven timer doesn't go off, then dinner will get burnt which is much less serious and as such a higher Type II error is acceptible for the latter. (I need to read and consult further on this point).

1. All graphs should be accompanied by their formulas and in non-conventional notation, if appropriate, to encourage better familiarity with the shapes of functions and non-conventional notational. 

1. To build confidence with writing equations, we might also talk about units (really the only way an equation can go wrong) and give guidelines for notation choices (see links.md for recent paper on this).

1. We need to be consistently reporting the spread of data and discussing overlap with respect to Type II error.

## STAT 2550

Hampton et al. (https://academic.oup.com/bioscience/article/67/6/546/3784601) states that "we recommend a computational approach to statistics training. Whereas calculus and a basic statistics course might have been sufficient background for classical ecological statistics, some basic computational training is essential to understand today's algorithms (Wilson 2006)". Therefore, we need to consult with the Statistics department to determine with STAT 2550 is meeting our needs and to facilitate better integration STAT 2550 and our program.

It is also important to touch on 1) the statement from that ASA about alpha = 0.05; and 2) data visualization as discussed here (https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128).


## BIOL 4605 and graduate courses
This course from UBC seems very good: https://stat545.com/index.html

# Recommendations for data science
I recommend introducing a required second your course that is "Data carpentary in Biology" or "An introduction to data science for biologists". The course could draw on materials from here: https://datacarpentry.org/semester-biology/schedule/

# The curriculuum
To introduce a new second year course that is required we will need to elimate at least one required second year course. We need to reduce our required course load, and, ideally, to the extent that double majors with geogaraphy, math, stats, and computer science could be possible.

## General comments
A key aspect of making progress is continuity across courses within the major including STAT 2550 (Vision and Change can be cited regarding the importance of this point). What we are teaching about 'how to make a graph in R' in first or second year needs to flow up to third and fourth year. To this extent, we need to maintain public (github) and private (brightspace) repositories of our teaching materials. I will hire a TA whose job will be to assemble documentation on how to do particular R tasks, which will be maintained as a bookdown file. As such, it will be available in pdf and ebook. I will consult with Lourdes for this, but ideally this task is a matter of finding links to existing good explanations, for example, the relevant sections of the Pirates Guide to R.

I am leaning towards not getting too far into this in the first year, since the 1001 and 1002 follows closely off of Campbell's Canadian Biology. This book does have some great exercises about reading graphs, but a treatment of statistics is lacking. In addition, 1001 and 1002 are serving non-biology majors. If we were to adopt measures in 1001 and 1002 labs, we should introduce the expectations that all graphs are made in R (or at least on a computer) and that data tables are achived electronically to a github repository. We need to find a reference for best practices in data archiving and build our expectations from here (perhaps this? https://joss.theoj.org/papers/10.21105/joss.01276). If we expect graphs in R, we may need to add a 'how to make graphs in R' lab, or at least a component of a lab. Data from 1001 and 1002 could also be analyzed in R and this could be a separate lab towards the end of the semester, perhaps just covering 'how to do a linear regression in R'. I suspect that we have sufficient computing resources to achieve all this, but that needs to be flushed out.

I've been trying to figure out 'what are quantitative skills'. Vision and Change wasn't especially helpful, but Competency E1 on p22 of Scientific Foundations for Future Physicians (https://store.aamc.org/scientific-foundations-for-future-physicians-pdf.html) has some good comments. My favorite reference to date is Hampton et al. 2017 https://academic.oup.com/bioscience/article/67/6/546/3784601

Vision and change mentions communication as the other aspect (in addition to quantitative skills), that is undervalued in the biology curriculum, and Yolanda had mentioned this too.
