## About

This is a series of seminars organized, ideated and attended by PhD Students in Computer Science (and possibly faculty members) at UniPI.
This seminar series will consist (ideally) of 16+ seminars where students can discuss open problems in CS, present their recent results and
create connections and opportunities for collaborations among them and faculty members.

If you're interested in giving a seminar, you can reach out to me at *danilo [dot] numeroso [at] phd [dot] unipi [dot] it* or to Laura Bussi
at *laura [dot] bussi [at] phd [dot] unipi [dot] it*.

## Attendance Report
<iframe src="https://docs.google.com/spreadsheets/d/14bbEs3nreK_MI-J0mvm6d4IezieCn8R43yEobAGIJNA/edit?usp=sharing" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="400px" width="100%" allowfullscreen=""></iframe>

## Schedule

**1- Combinatorial properties of degree sequences of 3-uniform hypergraphs arising from saind arrays** ([link](https://teams.microsoft.com/l/meetup-join/19%3a9507f4382f764a568f38dc256aaa8b80%40thread.tacv2/1610014746395?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d)) ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/palma-hypergraphs.pdf))

*Giulia Palma, 15/01/2021, 15:00-16:00*

The characterization of *k*-uniform hypergraphs by their degree sequences, say *k*-sequences, has been a longstanding open problem for *k>2*. Very recently its decision version was proved to be NP-complete by Deza et al. Formally, the decision version of the problem is: Given *π=(d<sub>1</sub>,d<sub>2</sub>,...,d<sub>n</sub>)* a non increasing sequence of positive integers, is *π* the degree sequence of a *k*-uniform simple hypergraph? The *NP*-completeness reduction uses, in an intermediate step, a subclass of 3-uniform hypergraphs whose incidence matrices are computed starting from a sequence of integer numbers. In general, the complexity of the reconstruction of the elements of such a subclass is unknown.

In this talk, we consider saind arrays *S<sub>n</sub>* of length *n*, i.e. arrays whose entries are the integers from *n* to *2-2n* in decreasing order, and we compute the related 3-uniform hypergraphs incidence matrices *M<sub>n</sub>*. The arrays of vertical projections, *V_n* of each *M<sub>n</sub>* turns out to be its degree sequences. We show that, for a generic *n ≥ 2*, *V<sub>n</sub>* and *V<sub>n+1</sub>* share the same entries starting from an index on. Furthermore, increasing *n*, these common entries converge to the integer sequence *A002620* in The Online Encyclopaedia of Integer Sequences.

This sequence is known to enumerate several combinatorial structures such as symmetric Dyck paths with three peaks, some families of integers partitions in two parts, bracelets with beads in three colours satisfying certain constraints and special kind of genotype frequency vectors.

We define bijections between the *V<sub>n</sub>* arrays and the above mentioned combinatorial families, thus showing an innovative approach to the study of 3-sequences which should provide subclasses of 3-uniform hypergraphs polynomially reconstructable.


**2- Techniques for query verification** ([link](https://teams.microsoft.com/l/meetup-join/19%3a2e55862b55f74ef9a9d4a36a59d5775e%40thread.tacv2/1610016452373?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d)) ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/loporchio-query-verification.pdf))

*Matteo Loporchio, 22/01/2021, 15:00-16:00*

In recent years, many companies and private users have taken advantage of cloud services to store large collections of data, with a huge saving on infrastructure and maintenance costs. Therefore, each time a user wants to retrieve information from the cloud it needs to issue a query and contact the cloud provider, which manages the data collectionon behalf of the owner. In this scenario, however, nothing prevents the provider from sending back tampered or incomplete results. As a consequence,all users must be able to detect any inconsistency in what they receive. This problem is known in the literature as authenticated query processing and its solution hinges on the design of efficient algorithms and cryptographic protocols for data retrieval and authentication. In this talk we will explore some state-of-the-art techniques to address it and discuss some of the challenges we must face when dealing with query processing in the context of blockchain environments.

**3- Computational design of metamaterials for achieving desired mechanical properties in digitally-fabricated shapes** ([link](https://teams.microsoft.com/l/meetup-join/19%3a0b2efda5150a4a2a862bdf970b314927%40thread.tacv2/1610016516396?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d)) ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/manolas-metamaterials.pdf))

*Iason Manolas, 29/01/2021, 15:00-16:00*

The ability to manufacture objects was a turning point in human history. Nowadays digital fabrication provides new means for the realization of highly complex shapes.
When constructing a physical object, besides manufacturing a specific shape, users often want to achieve specific mechanical properties such as rigidity, weight, deformation behavior and so on.
A way for achieving desired effective properties, is by computationally designing mechanical metamaterials. Metamaterials are artificial structures with mechanical properties determined by their structure rather than their composition. Designing such metamaterial structures by hand quickly becomes infeasible as the size and complexity of the shape increases. Thus, such materials are accompanied by the need for computational methods that can generate them.
In this talk we discuss the development of a computational framework able to design metamaterials for achieving desired mechanical properties in digitally-fabricated objects.


**4- Neural Patient: A neural approach to multimodal patient data representation** ([link](https://teams.microsoft.com/l/meetup-join/19%3a2cb0306256f649c887c4ac983ccdb4c5%40thread.tacv2/1610117051535?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d))([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/blob/gh-pages/slides/Sansone_NeuralPatient.pdf))

*Francesco Sansone, 05/02/2021, 15:00-16:00*

The recent and continuous technological improvement has led to the rising development of applications enabling deep exploration of biology and human health. In this view, recently, great attention has been placed on omic sciences and their role in the study and characterization of complex biological mechanisms and interactions. Omic sciences include several different fields, such as genomics, proteomics, transcriptomics, metabolomics, and many others. From a technical point of view, each of these fields needs the implementation of bioinformatic algorithms and data science methods characterized by an increasing level of innovation.
In particular, precision medicine represents a special opportunity for omic sciences, since it allows their integration with much other information produced from different sources, such as data coming from imaging techniques, information acquired with biomedical sensors, and data collected in medical histories within hospitals.
The integration of this kind of data becomes particularly useful if applied to an information systems dedicated to patients’ health and care. This combined use allows the correlation between omic data and information related to treatments, interventions and laboratory tests patient’s.
The big amount of data produced by omics science, merged together with the use of informative systems devoted to patients’ health and care, is leading the approach to the patients from a merely physician-based framework towards a pathway where decision and diagnostic support systems are frequently used, taking advantage of Machine and Deep Learning techniques.
In this framework, it is evident that, in order to build and train an expert system, is more and more necessary to represent the patient in a domain-free mode, without the need for requiring external efforts and being usable independently from the type of application where it is used.

**5- Quantum Computing: From Zero to Classification** ([link](https://teams.microsoft.com/dl/launcher/launcher.html?url=%2F_%23%2Fl%2Fmeetup-join%2F19%3A0ecebe659e1f4bb68fdf80e469a032e8%40thread.tacv2%2F1613136446236%3Fcontext%3D%257b%2522Tid%2522%253a%2522c7456b31-a220-47f5-be52-473828670aa1%2522%252c%2522Oid%2522%253a%252274e788f6-b61a-4a90-bfd2-3b962fca24ae%2522%257d%26anon%3Dtrue&type=meetup-join&deeplinkId=dd4febb1-86d0-4ac3-b9f7-2a729fa71069&directDl=true&msLaunch=true&enableMobilePage=true&suppressPrompt=true))([presentation](https://docs.google.com/presentation/d/1a_bZXdusPEec2jJTgHzugIS6H6-EiwW5eAmmZp8JPWY/edit#slide=id.g796ec1f13b_0_241))

*Alessandro Berti, 12/02/2021, 15:00-16:00*

Quantum Computing is the use of quantum phenomena such as superposition and entanglement to perform computation.

But what actually is it? What are these quantum phenomena exploited to do this kind of computation? And, last but not least, is it really going to be a disruptive technology?

In this seminar, you will get an answer to these questions and, also, will be shown a “Quantum Distance-based Classifier”, a simple example of classification in the quantum world.

**6- Locality Filtering for Efficient Ride Sharing Platforms** ([link](https://teams.microsoft.com/l/meetup-join/19%3addec64efedad4f40a91a856d49a9adcb%40thread.tacv2/1610117204840?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d))([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/blob/gh-pages/slides/tosoni-locality-filtering.pdf))

*Francesco Tosoni, 19/02/2021, 15:00-16:00*

Ride sharing has been recently shown to have a tremendous potential to reduce the number of vehicles needed to serve a certain mobility demand, such as one based on taxis. However, although car pooling services have developed in recent years and are now widely available worldwide (e.g. Uber, Didi, Lyft, Via), ride sharing techniques still suffer severe scalability limitations, especially if the goal is combining multiple on-demand ride requests into a single trip in a large urban area.

As a result, any on-demand mobility system needs eventually to design and implement an efficient procedure that avoids comparing all the mobility requests (with their GPS coordinates and time constraints) against each other.
Indeed, brute force approaches based on considering all possible combinations of request endpoints and vehicles are not scalable for real-time computations. Therefore, when constructing shared trip trajectories, it is essential to design a procedure which extracts just a small and accurate subset of candidate request pairs from the exhaustive set of all request combinations.

We hence present a novel locality filtering approach that, combined with a scalable ride sharing algorithm based on shareability networks, is able to substantially speed up known approaches while only minimally impacting the quality of the computed ride sharing solution.

**7- 26/02/2021**

**8- 05/03/2021**

**9- 12/03/2021**

**10- 19/03/2021**

**11- 26/03/2021**

**12- 09/04/2021**

**13- 16/04/2021**

**14- 23/04/2021**

**15- Valerio Decaro 30/04/2021**

**16- 07/05/2021**

## FAQ
- **How long do the seminars last?**
Seminars will be 1-hour long. Speakers are warmly invited to conclude their presentations in 40-45 minutes, in order to leave
enough time for questions and discussions.

- **How can I get credits for this seminar series?**
In order to get credits, students need to attend at least 80% of the seminars as well as give one of them.

- **I am a 2+ year PhD student in CS, can I give a seminar?**
Yes, you can.

## Organizers
Laura Bussi, Danilo Numeroso
