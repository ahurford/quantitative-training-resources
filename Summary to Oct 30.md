These are my _prelimary_ ideas as of Oct 30, 2019, but I have not consulted widely enough to be confidence in these recommendations at this point. As such, I welcome feedback. My current thoughts are shaped by Hampton et al. 2017, which I highly recommend (https://academic.oup.com/bioscience/article/67/6/546/3784601).

The revision of the biology curiculuum with respect to quantitative training should have two objectives:
1. Prepare biology majors for quantitative skills that are expected in 3000 and 4000 courses in their choosen stream; and
2. Upon completing our BSc program (or potentially only specific streams of our program), if a student were given data and some context, the student can apply their biological knowledge to form a hypothesis, and make some progress on assessing whether the data support their hypothesis using statistics and/or data visualization.

## BIOL 1001/1002
Biology 1001 and 1002 lectures seems tightly focused around Campbell Biology, and as such, there is limited opportunity to deviate from the textbook.

## BIOL 1001/1002 Labs
### Revise lab manual text to give an updated description of what biologists do
The lab manual needs to be edited to communicate current practices for researchers. Particularly, in Appendix II, beginning on p118, comments around 'The Scientific Method', 'How Researchers communicate their findings', and 'Graphs and Tables' need to be revised. In addition, the roles of statistics in biology and modelling as an approach to doing science needs to be communicated.

### Tables
Data archiving standards for professional biologists have now moved beyond writing results in a notebook, and we need to give the students exposure to these expectations. We should ask first year students to archive data in an electronic format and submit to a github repository. This requirement needs to be supported by readings/text that explain that this is the current standard for professional biologists. We might also discuss what is metadata and Ecological Metadata Language (https://joss.theoj.org/papers/10.21105/joss.01276). We need to provide training/documentation for lab instructors and TAs on github. 

### Graphs
Similarly, professional biologists have moved beyond making graphs using pencil and paper! Perhaps this isn't the place to introduce R, and we could accept graphs made in a variety of softwares, while also have developed resources for R, RStudio, and ggplot. Expectations around figure captions should be revised.

### Statistics
Having not yet required STAT 2550, BIOL 1001/1002 is not the place to start in on statistics, but it is the place to better prepare students for (1) the importance of statistics in biology; and (2) key concepts in statistics.

(1) will be address by revisions to the lab manual.

Regarding (2), (and these recommendations are made primarily from my conversations with DS):

1. Currently, first year students are taught to write a hypothesis and a prediction. We need to add: sketch a graph of the results if your hypothesis was supported; draw a graph if your hypothesis is not supported; and write the equations that correspond to each of your graphs. To teach this we need to say, 'if you think _y_ increases with _x_, but you're not quite sure exactly how, the default assumption, given that _x_ is a continous variable, is that there is a linear relationship, _y=mx+c_. In writing the equations, students get to choose their notation. This is powerful, because biology involves a lot of non-conventional notation, for example, dN/dt = r N (exponential growth), if dN/dt is plotted on the y-axis, and N is plotted on the x-axis, is a straight line with a zero y-intercept and a slope of r, but the notation is a barrier because it isn't in the form _y = mx_.

1. We need to expect that some indication of spread is reported, i.e. error bars on bar plots where the error bars represent the range (i.e. from the min to the max observation) and the figure caption is required to specify what the error bars show.

### Add/Remove labs
We should add labs to introduce students to data science by removing some of the labs that are focused more specifically around knowledge reinforcement from lecture. At least one lab needs to be added to prepare students for our new expectations on data archiving and graphs.

### Publically available as an ebook
The BIOL 1001 and 1002 lab manuals will be available as ebooks as well as hardcopies. The transfer to an ebook will be completed in the winter and summer of 2020 using the bookdown package for R and will be completed by the TA hired to work with AH on our quantitative program.

## A 2000-level "Datacarpentary in Biology"
I recommend introducing a required second your course that is "Datacarpentary in Biology" or "Introduction to data science for biologists". The course could draw on materials from here: https://datacarpentry.org/semester-biology/schedule/

## Recommendations for BIOL 2000-level courses and beyond
We will maintain resources and guidelines to help with quantitative content in 2000- and above courses. Some recommendations are:

1. Discuss Type I and Type II errors (Type I: alarm, no fire; Type II: fire, no alarm). The statement from American Statistical Association advocating the downfall of alpha = 0.05, if I understand DS correctly, should now be replaced with a discussion of the types of questions where lower or higher acceptable Type II errors are appropriate, for example, a fire with no alarm is a life and death matter; if my oven timer doesn't go off, then dinner will get burnt which is much less serious and as such a higher Type II error is acceptible for the latter. (I need to read and consult further on this point).

1. All graphs should be accompanied by their formulas and in non-conventional notation, if appropriate, to encourage better familiarity with the shapes of functions and non-conventional notational. 

1. To build confidence with writing equations, we might also talk about units (really the only way an equation can go wrong) and give guidelines for notation choices (see links.md for recent paper on this).

1. We need to be consistently reporting the spread of data and discussing overlap with respect to Type II error.

1. ggplot and RStudio. Personally, don't use ggplot, but https://stat545.com/index.html makes a compelling argument for it.

## Recommendations for each year
With the BIOL 1001/1002 lab manuals now available as ebooks (and publically available), instructors in upper level courses should be knowledgeable of what is taught in first year and be knowledgable as to if what they are recommending conflicts. We should set specific goals for expectations at the end of second, third and fourth years. Competency E1 on p22 of Scientific Foundations for Future Physicians (https://store.aamc.org/scientific-foundations-for-future-physicians-pdf.html) has some good comments.

## STAT 2550

Hampton et al. (https://academic.oup.com/bioscience/article/67/6/546/3784601) states that "we recommend a computational approach to statistics training". Therefore, we need to consult with the Statistics department to determine if STAT 2550 is meeting our needs and to facilitate better integration STAT 2550 and our program.

It is also important to touch on 1) the statement from that ASA about alpha = 0.05; and 2) data visualization as discussed here (https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128).


## BIOL 4605 and graduate courses
This course from UBC seems very good: https://stat545.com/index.html

## The curriculuum
To introduce a new second year course that is required we will need to elimate at least one required second year course. However, we need to reduce our required courseload further than this, and, ideally, to the extent that double majors with geogaraphy, math, stats, and computer science could be possible.

## Making resources publically available
A key aspect of making progress is continuity across courses within the major including STAT 2550 (Vision and Change can be cited regarding the importance of this point). What we are teaching about 'how to make a graph in R' in first or second year needs to flow up to third and fourth year. To this extent, we need to maintain public (github) and private (brightspace) repositories of our teaching materials.

## Computing and software requirements
We should develop a policy on our expectations (i.e., are undergrads expected to have access to a personal computer) and quantify demand for departmental computing resources.

## Teaching communication and collaboration
Both Vision and Change and Hampton et al. 2017, highlight communication skills as a key aspect of data science training. YW has mentioned an interest in this area. To my understanding, the references are not so much referring to social media or giving talks, but how to communicate to participate in interdisciplinary collaborations.

## Streams
We need to work on tightening up our streams as recommended in the AUP, including the Quantitative/field stream.

## Modelling
Vision and Change highlights the importance of modelling. So far, my recommendations focus mainly around stats and data science.
