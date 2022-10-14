# Bias-and-Reproducibility-Poster: Bias and reproducibility in a computational neurobiology PhD's journey. 

This was a poster created for the [COMBINE](https://combine-org.github.io/events/) and [ICSB](https://www.icsb2022.berlin/home) 2022 conferences. 

### What do I do?
-	Computer modelling
-	Look at synaptic molecules
-	Try to understand learning and memory
- Make this research as ethical and accessible as possible as I go along

### Where am I coming from? 
I wanted to look at biases in the research that I do and this brought me to the realization that in order to remove them and/or make them more clear I had to make my research also more reproducible and accessible. The original bias is that we think “there is no bias in my research”. 

My PhD and any research endeavour is a journey. A journey which can generally be divided into different milestones. And in each step of the way we can carry some type of biased information as well as tools to overcome them or at least point them out. At the same time, in order to make my PhD research more ethical, reproducibility and accessibility are key.

So, I divided some of the questions I have been asking myself into different sections of the research journey.

I briefly describe each section, then offer references and resources to look at bias and how to make research more reproducible at each stage of a research journey; I have sorted them out through the 4 different steps:

1. Design
2. Data Collection
3. Data Analysis
4. Reporting.

*Note: there's lots of references to the Turing Way Booklet since it is quite an extensive, easy to follow, resource. Please follow up on this and continue your own research on anything you find interesting/agree/disagree with.

## 1. Design

###  1.1. What's the Bias here?:
This part of the project is key to lay out initial biases and prevent further bias feedback. We can ask questions like: 

- Who is my data including/excluding? 
- What am I assuming?
- How much am I simplifying?

I look at data that comes from non-human animals. We generally make assumptions that because we did an experiment on a mouse, this is likely to be similar in humans. But we ought to recognise these are just assumptions. 
Other assumptions in my research can be the fact that I explain memory and learning in very simplified, reduced ways, usually using specific molecules to describe a process that is extremely complex and that we don’t fully understand all the caveats of. 

### 1.2. Tools for reproducibility:
Planning for reproducibility from the beginning is key.
Version control, code literacy and planning where I will keep and share my data from the beginning have been a livesaviour. See below some good places to get you started, I have learnt lots from these sites:

-  [Guide for Project Design](https://the-turing-way.netlify.app/project-design/project-design.html?highlight=design)
-  [(re)Learn how to Version Control on Git](https://carpentries-incubator.github.io/git-novice-branch-pr/)
-  [The Good Research Code Handbook](https://goodresearch.dev/)
-  [Defining Reproducibility/Replicability/Robustness/Generalisability](https://the-turing-way.netlify.app/reproducible-research/overview/overview-definitions.html)
-  [Zenodo](https://about.zenodo.org/)
-  [OSF: Open Sciences Framework](https://help.osf.io/article/342-getting-started-on-the-osf)

## 2. Data Collection
### 2.1. What's the Bias here?
- Where is my data coming from when I collect it? data are not just numbers. They come from living beings that likely gave their lives for our own benefit. There is an ethical bias here. 
- What resources am I using to collect data, and likewise what resources were used to create the data I am now currently collecting? Supercomputers? Maths? 

### 2.2. Tools for reproducibility:
Plan for reproducibility at each stage:
It's helpful to think where you are keeping the data, and how will you share it later on.

- [Data Management Plans](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-dmp.html?highlight=data%20management%20plans) are good practice. 
- [Keep data FAIR](https://www.go-fair.org/fair-principles/): be transparent with each data point you are talking about.

## 3. Data Analysis
### 3.1. What's the Bias here?
Who is your research serving? Am I continuing an ableist bias to “fix” individuals? Racist bias? Sexist bias? The list is quite endless.
There is a historical bias in how science has been made. This affects the present of how science is still being done. There is a need to deconolize science. 
- [Good book on historical bias of Mental Health Sciences/Neuroscience](https://pmpress.org.uk/product/warp-weft/)
- [Who makes science?: Identity and positionality](https://the-turing-way.netlify.app/ethical-research/self-reflection/sr-positionality.html?highlight=bias)

Again, how much am I simplifying an explanation into molecules when in reality a holistic explanation might be best? E.g. CaMKII has been linked with Alzheimers disease, but by offering mechanisms of understanding this does not directly help those who might be most impacted by their social-economical status, what they might need is social and economical support. Not a cure for Alzheimers. 

### 3.2. Tools for reproducibility
- [Scientific Data Analysis Pipelines and Reproducibility](https://towardsdatascience.com/scientific-data-analysis-pipelines-and-reproducibility-75ff9df5b4c5)
- [Data Hazards](https://datahazards.com/index.html)
- [Researchers Degrees of Freedom](https://www.frontiersin.org/articles/10.3389/fpsyg.2016.01832/full)

## 4. Reporting
### 4.1. What's the Bias here?
"Everything is in the paper; anyone can reproduce this from there!"

This is one of the most common misconceptions when reporting. Even having an extremely detailed description of the methods and workflows employed to reach the final result will not be sufficient in most cases to reproduce it. This can be due to several aspects, including different computational environments, differences in the software versions, implicit biases that were not clearly stated, etc.

It can be useful to think:
- How will my research be used in the future?
- Am I feeding into positive results publishing? [Good article to read and think](https://psycnet.apa.org/fulltext/2014-20922-001.html)
- Slow science manifesto - there are many, but [here's](https://acofacien.org/images/files/BIBLIOTECA/Poliiticas_educacion_superior/SLOW%20SCIENCE%20MANIFESTO.pdf) an example.

### 4.2. Tools for reproducibility
- [Jupyter notebooks](https://escholarship.org/content/qt5w52878j/qt5w52878j_noSplash_bd899b661901fae486923c953fbcb877.pdf), [Open Lab Notebooks](https://the-turing-way.netlify.app/reproducible-research/open/open-notebooks.html?highlight=open%20lab%20notebooks)
- Share and licence your research. 
- Suitable data repositories by subject, content type or location can be found at:
    - [re3data.org](https://www.re3data.org/)
- You can also see which standards (metadata and identifier) the repositories implement and which journal/publisher recommend them, through:
    - [fairsharing.org](https://fairsharing.org/search?fairsharingRegistry=Database)

### Acknowledgements:
This poster has bloomed in response to many discussions and credit should be given to [David C Sterratt](https://github.com/davidcsterratt), [Melanie Stefan](https://github.com/MelanieIStefan), [Nicola Romano](https://github.com/nicolaromano), [Malvika Sharan](https://github.com/malvikasharan) and Claudia Fischer.
