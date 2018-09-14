---

title: "Steps to Reproducible Research"
teaching: 30
exercises: 10
questions:
- "What is reproducibility?"
- "Why should I take reproducibility in mind for my research?"
- "How can I make my research reproducible?"
objectives:
- understand what it means to have a reproducible research
- understand the steps to create a reproducible research
keypoints:
- reproducibility is the ability to exactly re-create an earlier research/analysis given the same data
- the less time it takes to get the same result you did with the resources provided, the more "reproducible" your research/analysis are
- in research, experiments/results are not trusted unless
    
    - The experimental setup is tested
    
    - The method is well-documented
    
    - We can demonstrate that our results are reproducible and reliable

- simple steps to reproducible research are
    
    - record the project's provenance
    
    - data and metadata curation
    
    - establish a testing/analysis workflow
    
    - test, document, and publish your code
    
    - share it!

---

# What is Reproducibility?

In a single sentence, **reproducibility** is the ability to exactly **re-create** an earlier **research/analysis** given the **same data**. Meaning that if I hand of a piece of journal that describe my method for a research, and the input data, another person can make the exact findings.

<img src="../assets/img/reproducibility/spectrum.png" alt="Reproducibility Spectrum" style="width:800px;height:auto;">

The image above is the reproducibility spectrum showing the range from research that are described in publications, all the way through full replication, which are research with publication, executable code, and linked data, like *having a frozen machine on the cloud, that can be executed to run your whole research*. We don't want both extremes, but rather in the middle depending on your field, data, and your research.

> ## Reproducibility Discussion
>
> What measures do you take to ensure your analyses are:
> - reproducible,
> - replicable,
> - robust?
>
> [https://etherpad.wikimedia.org/p/ghw2018-reproducible-discussion](https://etherpad.wikimedia.org/p/ghw2018-reproducible-discussion)
>
{: .challenge}

PS: shameless copied from the awesome slides available at: [https://github.com/oceanhackweek/ohw2018_tutorials/blob/master/day5/reproducible_research_and_tools/](https://github.com/oceanhackweek/ohw2018_tutorials/blob/master/day5/reproducible_research_and_tools/).

## Simple steps to reproducible research

- record the project's provenance
- data and metadata curation
- establish a testing/analysis workflow
- test, document, and publish your code
- share it!

For this tutorial I'm going to cover **test, document, and publish your code** part.

In research, experiments/results are not trusted unless:

- The experimental setup is tested
- The method is well-documented
- We can demonstrate that our results are reproducible and reliable

*So why would scientific software be any different?*

## Clear code is paramount!

![Non-clean code](https://raw.githubusercontent.com/oceanhackweek/ohw2018_tutorials/master/day5/reproducible_research_and_tools/images/code_quality_2.png)

## Good practices for the scientific env creation is also important!

![Confusing science env creation](https://raw.githubusercontent.com/oceanhackweek/ohw2018_tutorials/master/day5/reproducible_research_and_tools/images/universal_install_script.png)

## Let me introduce you

The code test-document-publish cookie cutter!

(Yep! Another cookie cutter for Scientific Python package!)

![Standard proliferation](https://raw.githubusercontent.com/oceanhackweek/ohw2018_tutorials/master/day5/reproducible_research_and_tools/images/standards.png)

Example: [https://nsls-ii.github.io/scientific-python-cookiecutter](https://nsls-ii.github.io/scientific-python-cookiecutter)

## What We will need

- [https://github.com/lsetiawan/rppc](https://github.com/lsetiawan/rppc)
- GitHub account
- Travis-CI account

> ## Hack session
>
> 1. create python package
> 2. choose a license
> 3. write doctest
> 4. bug? fix test / re-run
> 5. setup Travis-CI / CircleCI
> 6. setup AppVeyor
> 7. upload source dist and docs
> 8. create doi ![DOI](https://zenodo.org/badge/104919828.svg)
>
{: .challenge}
