---
layout: page
title: Overview 
permalink: /
---

* TOC
{:toc}

## Overall Reproducibility Objectives

Why considering reproducibility? 
Reproducibility of scientific results is at the core of the Scientific Method. 
The reason why we do research is to create new knowledge. 
This knowledge is built up over time by research findings that are confirmed because they are reproducible by the research community.

> An experimental result is not fully established unless it can be independently reproduced. ACM DL. [Read it here](https://tinyurl.com/ycw6zd7j).

The long-term objective of ACM Multimedia Retrieval Reproducibility is to promote a common research culture where sharing the full set of products of multimedia research (e.g., not just the algorithm description, but also the data, the code, the plots) is the norm rather than an exception. The main challenge we face is promoting research reproducibility both efficiently and effectively. To tackle this challenge, we must build technical expertise that can support repeatable and shareable research. 

The [ACM Multimedia Retrieval Reproducibility Committee]() is here to help you with this.

Overall, our objectives are to:
* Promote reproducibility as a strong foundation for scientific productivity and progress in the multimedia community,
* Increase the impact of multimedia research by accelerating the dissemination and uptake of multimedia research results,
* Establish a common understanding among researchers about the reproducibility of scientific results in order to communicate clearly and visibly the effort that authors have invested in ensuring that their findings can be recreated,
* Support easier dissemination of code, data sets, experimental frameworks and other products of multimedia research.

We aim at reaching that goal through the use of a series of instruments deployed by the ACM and that specifically address the reproducibility of scientific results.

This page describes these instruments and then their implementation at ACM Multimedia Retrieval. It also discusses best practices and points to example of contribution promoting reproducibility.

Please visit the following page for specific information about the [ACM ICMR 2021]() call for reproducibility papers.

## ACM Reproducibility Badges

Reproducibility at ACM takes the concrete form of a _reproducibility badges_ that is given to papers whose authors have invested effort to describe their algorithms and experiments in detail.

ACM defines several reproducibility badges, spanning several levels of reproducibility engagements, from light to strong, and you can find the list of ACM badges [here](https://tinyurl.com/ycw6zd7j).

Some reproducibility badges involve developing and releasing research artifacts. Quoting ACM:
> By &#8220;artifact&#8221; we mean a digital object that was either created by the authors to be used as part of the study or generated by the experiment itself. For example, artifacts can be software systems, scripts used to run experiments, input datasets, raw data collected in the experiment, or scripts used to analyze results. ACM DL. [Read it here](https://tinyurl.com/ycw6zd7j)


Reproducibility badges are awarded to scientific contributions that have successfully passed a formal reproducibility reviewing phase. 
Contributions that have passed get embedded in their .pdf a reproducibility badge, which is also prominently displayed in the ACM Digital Library.

Having a reproducibility badge awarded to your contribution promotes the dissemination and uptake of your work. 
When they see the badge, other researchers will understand it is possible to build on your contribution and whether there are resources available that will allow them to adopt or extend your approach. 
The result is that your work receives wider recognition and is positioned to make higher impact.

---

## Reproducibility Badging at ACM ICMR 
Only authors that already have a paper accepted at ACM ICMR (as a regular long/short paper or a special session paper) can participate in the reproducibility review process.

Such authors are invited to prepare and submit a _reproducibility paper_. The reproducibility paper is a _companion paper_ that is distinct from the main paper. 
It is this companion paper which is formally reviewed by the [ACM Multimedia Retrieval Reproducibility Committee](). 
If this paper pass the review process with success, then both the companion paper and the corresponding main paper are awarded with reproducibility badges that are embedded in their .pdf. 
These two badged papers appear in the ACM Digital Library, and the companion paper is linked to the original ACM Multimedia paper.

Furthermore, the authors of an accepted reproducibility paper present their work as part of a specific reproducibility poster session at ACM ICMR.

---

## Reproducibility Review Process at ACM ICMR 
Submitted reproducibility companion papers are reviewed by a collaborative reproducibility review process, which is distinct from the main conference paper reviewing process. 
It is the [ACM Multimedia Retrieval Reproducibility Committee]() that is carrying out the review process, determining whether or not a paper will receive a badge. 
The committee assigns two reviewers to each reproducibility companion paper submission.

During the process of assessing the submission and possibly the artifacts, the reviewers interact with the submitting authors in order to work through any technical issues or gaps in the documentation that they find. 
The review process is fully open: the reviewers know the authors; the authors know the reviewers. 
If it is possible to address all the issues, then the reviewers document the review process in a description which is added as a section to the reproducibility companion paper that is under review.

Because the reviewers interact with the authors, devote a large amount of time and effort to assess your submission, and because they write a section in the final reproducibility companion paper, the reviewers become co-authors of the final reproducibility companion paper.

If the reviewers find that the technical issues or problems with the documentation cannot be resolved, then the reproducibility companion paper is rejected. 
If, during the evaluation, a serious flaw invalidating the scientific results published in the original contribution is discovered, then the companion paper is rejected, and the reproducibility reviewers will encourage the original authors to publish an errata.

Note that the collaborative review process requires substantial efforts, and for this reason the reproducibility companion paper is not published in the same ACM ICMR proceedings as the original paper, but rather appears in the next year’s proceedings. 
This provides authors with the opportunity to present their work twice at an ACM Multimedia Retrieval conference: The original paper is presented first, and the next year the reproducibility companion paper is presented as a poster. 
In this way, the work of authors’ who devote attention to reproducibility receives additional visibility at the conference.

This companion paper in the ACM DL and its exposure during the conference are fabulous incentives for both authors and reviewers.

---

## ACM ICMR 2021: Call for Reproducibility Papers
Detailed instructions about the ACM Multimedia Retrieval 2021 call for reproducibility papers are provided in the [Call for Papers]({{site.baseurl}}/cfp2021).

You will find there the general submission guidelines for 2021, the timeline, the one badge that we consider in 2021, namely the **Results Replicated** badge, the description of what the companion paper typically contains when submitting for this specific badge, the description of what the artifacts associated to this companion paper typically contain as well as a few packaging guidelines facilitating the preparation of the artifacts.

If you have questions, if you are unsure about what to submit, then please contact the [chairs](mailto:maau@itu.dk,bjth@itu.dk?subject=%5BICMR2021%20Reproducibility%5AD).

---
## Best Practices

Best practices in reproducibility are a set of actions and principles that you can take in order to ensure that your work is reproducible. 
Best practices should not be considered a single, static recipe, but rather they are a flexible knowledge of processes and strategies that evolve overtime.

To get started understanding best practices, we suggest that you take a look at the ACM Digital Library’s webpage entitled [Software and Data Artifacts in the ACM Digital Library](https://www.acm.org/publications/artifacts), which provides information on motivations for reproducibility and a look into how reproducibility is supported and continues to evolve in the ACM Digital library. 
From that page you can get more information on badges.

Researchers in the area of databases started explicitly emphasizing reproducibility early on. 
Much of what we propose to implement for ACM Multimedia Retrieval is inspired from their _DOs_ and _DON'Ts_. 
We suggest that you take a look at material on reproducibility that has been published in the database community and consider how their best practices transfer to your work.

A good source of information can be found in the [ICDE 2008 tutorial by Ioana Manolescu and Stefan Manegold](http://pages.saclay.inria.fr/ioana.manolescu/SLIDES/ManolescuManegoldICDE2008.pdf). The tutorial includes a road-map of tips and tricks on how to organize and present code that performs experiments, so that an outsider can repeat them.

A discussion about reproducibility in research including guidelines and a review of existing tools can be found in the [SIGMOD 2012 tutorial by Juliana Freire, Philippe Bonnet, and Dennis Shasha](http://dl.acm.org/citation.cfm?id=2213908). 

Closer to multimedia retrieval, ACM MMSys and ACM MM has lead the multimedia research community in explicitly emphasizing reproducibility and Gwendal Simon chaired the reproducibility track at MMSys 2019. Emailing Gwendal or reading what he wrote about reproducibility [in his blog](http://peerdal.blogspot.com/2017/05/reproducibility-in-acm-mmsys-conference.html) can be helpful. Take also a look at ACM MM's reproducibility efforts that are documented [here](https://project.inria.fr/acmmmreproducibility). Our approach follows very much the principles brought forward for ACM MM.

---

## Examples of Badged Papers

Here are a few links to papers with badges inside the ACM DL. They have been picked because they nicely illustrate what is described in this page, not due to their scientific value. They come from multiple domains, giving you a broad view of what colleagues have done. 

The first two papers from ACM MM 2019 comply with guidelines specified in this page. The latter two do not necessarily comply with our rules. For example, sometimes there is no companion paper, sometimes the companion paper is not always a 2-4 pages paper, ACM style. Furthermore, papers may target other types of badges that are about the availability of the artifacts, not solely about replicability or reproducibility of results.

* **Reproducible Experiments on Adaptive Discriminative Region Discovery for Scene Recognition**, Z. Zhao, Z. Liu, M. Larson, A. Iscen, N. Nitta. _ACM MM 2019_. ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/results_replicated-150x150.jpg){:height="30px"}. [Paper's DOI](https://dl.acm.org/citation.cfm?id=3351169). The artifacts are on [GitHub](https://github.com/ZhengyuZhao/Adi-Red-Scene).
* **Companion Paper for “MiniView Layout for Bandwidth-Efficient 360-Degree Video”**, M. Xiao, S. Wang, C. Zhou, L. Liu, Z. Li, Y. Liu, S. Chen, L. Sassatelli, G. Simon. _ACM MM 2019_. ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/results_replicated-150x150.jpg){:height="30px"}. [Paper&#8217;s DOI](https://dl.acm.org/citation.cfm?doid=3343031.3351168). The artifacts are on [GitHub](https://github.com/bingsyslab/mm19-artifact).
* **Generating Preview Tables for Entity Graphs**, N. Yan, S. Hasani, A. Asudeh and C. Li. _Winner of the 2017 most reproducible papers from SIGMOD 2016_. ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/artifacts_available-150x150.jpg){:height="30px"}![](https://project.inria.fr/acmmmreproducibility/files/2018/09/results_replicated-150x150.jpg){:height="30px"}. [Paper&#8217;s DOI](https://doi.org/10.1145/2882903.2915221).
* **Cicada: Dependably Fast Multi-Core In-Memory Transactions**, H. Lim, M. Kaminsky, D. G. Andersen. _ACM SIGMOD 2017 Reproducible Paper_. ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/artifacts_evaluated_reusable-150x150.jpg){:height="30px"} ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/artifacts_available-150x150.jpg){:height="30px"} ![](https://project.inria.fr/acmmmreproducibility/files/2018/09/results_replicated-150x150.jpg){:height="30px"}. [Paper&#8217;s DOI](https://doi.org/10.1145/3035918.3064015). The artifacts are on [GitHub](https://github.com/efficient/cicada).

---

## Reproducibility Committee
The committee is chaired by two chairpersons who each serve for two years. At the end of each year, one chair is replaced and the other continues. This system ensures a one year overlap, which helps the committee to maintain freshness while also facilitating the transmission of the gradually improved expertise in managing reproducibility.

The two chairpersons nominate the members of the committee that are enrolled for at least one year. Chairs can also take part in the evaluation. There is a strict conflict of interest policy: the chairs cannot submit a reproducibility paper while they hold their positions.

The committee in charge of reproducibility at the 2021 edition of ACM ICMR is provided at the bottom of [ACM ICMR 2021 — Call for Reproducibility papers]({{site.baseurl}}/cfp2021).

---

## Credits

The process described in these pages was originally designed and implemented by Laurent Amsaleg, General Chair and Reproducibility Chair of ACM Multimedia 2019, with inputs from co-chairs Martha Larson, Benoit Huet and Björn Þór Jónsson. The text here originates from the Web page for [ACM MM Reproducibility](https://project.inria.fr/acmmmreproducibility)and was used with the authorisation of the original authors. Naturally, however, that text was adapted when necessary. Also see the credits on <https://project.inria.fr/acmmmreproducibility>.
