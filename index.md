## About

This is a series of seminars organized, ideated and attended by PhD Students in Computer Science (and possibly faculty members) at UniPI.
This seminar series will consist (ideally) of 16+ seminars where students can discuss open problems in CS, present their recent results and
create connections and opportunities for collaborations among them and faculty members.

If you're interested in giving a seminar, you can reach out to me at *danilo [dot] numeroso [at] phd [dot] unipi [dot] it* or to Laura Bussi
at *laura [dot] bussi [at] phd [dot] unipi [dot] it*.

## Attendance Report
<iframe src="https://docs.google.com/spreadsheets/d/14bbEs3nreK_MI-J0mvm6d4IezieCn8R43yEobAGIJNA/edit?usp=sharing" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="400px" width="100%" allowfullscreen=""></iframe>

## Schedule

**1- Combinatorial properties of degree sequences of 3-uniform hypergraphs arising from saind arrays** ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/palma-hypergraphs.pdf))

*Giulia Palma, 15/01/2021, 15:00-16:00*

The characterization of *k*-uniform hypergraphs by their degree sequences, say *k*-sequences, has been a longstanding open problem for *k>2*. Very recently its decision version was proved to be NP-complete by Deza et al. Formally, the decision version of the problem is: Given *π=(d<sub>1</sub>,d<sub>2</sub>,...,d<sub>n</sub>)* a non increasing sequence of positive integers, is *π* the degree sequence of a *k*-uniform simple hypergraph? The *NP*-completeness reduction uses, in an intermediate step, a subclass of 3-uniform hypergraphs whose incidence matrices are computed starting from a sequence of integer numbers. In general, the complexity of the reconstruction of the elements of such a subclass is unknown.

In this talk, we consider saind arrays *S<sub>n</sub>* of length *n*, i.e. arrays whose entries are the integers from *n* to *2-2n* in decreasing order, and we compute the related 3-uniform hypergraphs incidence matrices *M<sub>n</sub>*. The arrays of vertical projections, *V_n* of each *M<sub>n</sub>* turns out to be its degree sequences. We show that, for a generic *n ≥ 2*, *V<sub>n</sub>* and *V<sub>n+1</sub>* share the same entries starting from an index on. Furthermore, increasing *n*, these common entries converge to the integer sequence *A002620* in The Online Encyclopaedia of Integer Sequences.

This sequence is known to enumerate several combinatorial structures such as symmetric Dyck paths with three peaks, some families of integers partitions in two parts, bracelets with beads in three colours satisfying certain constraints and special kind of genotype frequency vectors.

We define bijections between the *V<sub>n</sub>* arrays and the above mentioned combinatorial families, thus showing an innovative approach to the study of 3-sequences which should provide subclasses of 3-uniform hypergraphs polynomially reconstructable.


**2- Techniques for query verification** ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/loporchio-query-verification.pdf))

*Matteo Loporchio, 22/01/2021, 15:00-16:00*

In recent years, many companies and private users have taken advantage of cloud services to store large collections of data, with a huge saving on infrastructure and maintenance costs. Therefore, each time a user wants to retrieve information from the cloud it needs to issue a query and contact the cloud provider, which manages the data collectionon behalf of the owner. In this scenario, however, nothing prevents the provider from sending back tampered or incomplete results. As a consequence,all users must be able to detect any inconsistency in what they receive. This problem is known in the literature as authenticated query processing and its solution hinges on the design of efficient algorithms and cryptographic protocols for data retrieval and authentication. In this talk we will explore some state-of-the-art techniques to address it and discuss some of the challenges we must face when dealing with query processing in the context of blockchain environments.

**3- Computational design of metamaterials for achieving desired mechanical properties in digitally-fabricated shapes** ([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/manolas-metamaterials.pdf))

*Iason Manolas, 29/01/2021, 15:00-16:00*

The ability to manufacture objects was a turning point in human history. Nowadays digital fabrication provides new means for the realization of highly complex shapes.
When constructing a physical object, besides manufacturing a specific shape, users often want to achieve specific mechanical properties such as rigidity, weight, deformation behavior and so on.
A way for achieving desired effective properties, is by computationally designing mechanical metamaterials. Metamaterials are artificial structures with mechanical properties determined by their structure rather than their composition. Designing such metamaterial structures by hand quickly becomes infeasible as the size and complexity of the shape increases. Thus, such materials are accompanied by the need for computational methods that can generate them.
In this talk we discuss the development of a computational framework able to design metamaterials for achieving desired mechanical properties in digitally-fabricated objects.


**4- Neural Patient: A neural approach to multimodal patient data representation** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/sansone-neural-patient.pdf))

*Francesco Sansone, 05/02/2021, 15:00-16:00*

The recent and continuous technological improvement has led to the rising development of applications enabling deep exploration of biology and human health. In this view, recently, great attention has been placed on omic sciences and their role in the study and characterization of complex biological mechanisms and interactions. Omic sciences include several different fields, such as genomics, proteomics, transcriptomics, metabolomics, and many others. From a technical point of view, each of these fields needs the implementation of bioinformatic algorithms and data science methods characterized by an increasing level of innovation.
In particular, precision medicine represents a special opportunity for omic sciences, since it allows their integration with much other information produced from different sources, such as data coming from imaging techniques, information acquired with biomedical sensors, and data collected in medical histories within hospitals.
The integration of this kind of data becomes particularly useful if applied to an information systems dedicated to patients’ health and care. This combined use allows the correlation between omic data and information related to treatments, interventions and laboratory tests patient’s.
The big amount of data produced by omics science, merged together with the use of informative systems devoted to patients’ health and care, is leading the approach to the patients from a merely physician-based framework towards a pathway where decision and diagnostic support systems are frequently used, taking advantage of Machine and Deep Learning techniques.
In this framework, it is evident that, in order to build and train an expert system, is more and more necessary to represent the patient in a domain-free mode, without the need for requiring external efforts and being usable independently from the type of application where it is used.

**5- Quantum Computing: From Zero to Classification** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/berti-quantum-computing.pdf))

*Alessandro Berti, 12/02/2021, 15:00-16:00*

Quantum Computing is the use of quantum phenomena such as superposition and entanglement to perform computation.

But what actually is it? What are these quantum phenomena exploited to do this kind of computation? And, last but not least, is it really going to be a disruptive technology?

In this seminar, you will get an answer to these questions and, also, will be shown a “Quantum Distance-based Classifier”, a simple example of classification in the quantum world.

**6- Locality Filtering for Efficient Ride Sharing Platforms** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/tosoni-locality-filtering.pdf))

*Francesco Tosoni, 19/02/2021, 15:00-16:00*

Ride sharing has been recently shown to have a tremendous potential to reduce the number of vehicles needed to serve a certain mobility demand, such as one based on taxis. However, although car pooling services have developed in recent years and are now widely available worldwide (e.g. Uber, Didi, Lyft, Via), ride sharing techniques still suffer severe scalability limitations, especially if the goal is combining multiple on-demand ride requests into a single trip in a large urban area.

As a result, any on-demand mobility system needs eventually to design and implement an efficient procedure that avoids comparing all the mobility requests (with their GPS coordinates and time constraints) against each other.
Indeed, brute force approaches based on considering all possible combinations of request endpoints and vehicles are not scalable for real-time computations. Therefore, when constructing shared trip trajectories, it is essential to design a procedure which extracts just a small and accurate subset of candidate request pairs from the exhaustive set of all request combinations.

We hence present a novel locality filtering approach that, combined with a scalable ride sharing algorithm based on shareability networks, is able to substantially speed up known approaches while only minimally impacting the quality of the computed ride sharing solution.

**7- Theory of Mind for Deep Reinforcement Learning in Hanabi** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/fuchs-hanabi.pdf))

*Andrew Fuchs, 26/02/2021, 15:00-16:00*

The partially observable card game Hanabi was proposed in 2019 as a challenge problem for AI. The relevance of Hanabicomes from its dependence on implicit communication conventions as well as its apparent necessity of theory of mind reasoning for efficient gameplay. In our work, we proposed a mechanism for imbuing Reinforcement Learning agents with a theory of mind to estimate the mental state of players and discover efficient cooperative strategies in Hanabi. Our work provided several contributions. First, a formal definition of a computationally tractable mechanism for computing hand probabilities in Hanabi. Second, anextension to conventional Deep Reinforcement Learning that introduced reasoning over finitely nested theory of mind belief hierarchies. Finally, an intrinsic reward mechanism enabled by theory of mind that incentivized agents to share strategically relevant private knowledge with their teammates. We demonstrated the utility of our algorithm against Rainbow, a state-of-the-art Reinforcement Learning agent. In my current research, I strive to develop a framework for effectively modeling human-AI interactions. The goal is to utilize the model to optimize the behavior of the AI system in anticipation and response to the human’s behavior. Therefore, I present my work on the Hanabi challenge problem as it serves at minimum as an inspiration for possible future directions for my PhD research.

**8- Distributed and cyber-physical systems: formal tools and research challenges** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/bussi-distributed.pdf))

*Laura Bussi, 05/03/2021, 15:00-16:00*

Nowadays, distributed and cyberphysical systems are used by millions of people. As such systems are becoming widespread, there is a growing need for techniques to ensure their trustworthiness. Properties like safety, security, integrity and availability are crucial in this kind of systems and, for the time being, there is still a lack of formal tools for their specification and verification.

In this seminar, we will take a glance at the main challenges that must be taken into account when designing specification and verification tools for such systems. We will then give an overview of existing formal tools and possible research directions.

**9- Explainable and Trustworthy Deep Learning** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/numeroso-xai.pdf))

*Danilo Numeroso, 12/03/2021, 15:00-16:00*

Deep learning models learn to map a set of features into a class or a set of properties. However, the logic behind why a given deep neural model makes certain prediction is unknown. This lack of transparency may become a problem, especially when considering well-known ethical issues (i.e, bias in the data) or safety-critical issues (i.e, drug design, self-driving cars). Hence, being able to assess the quality of model predictions is important and may enable deep learning to be adopted in an increasing number of scenarios.

This talk will serve as introduction to the problem of interpretability
of deep neural networks, with an emphasis on deep learning for structured
data. The seminar also overviews some related work in the field to date.

**10- Drug repurposing for COVID-19 through Deep Graph Networks** ([presentation](null))

*Alessio Gravina, 19/03/2021, 15:00-16:00*

The COVID-19 pandemic is one of the biggest in recent human history. The timeline of the virus has urged scientists from all over the world to seek effective treatments. With this objective, we attempted to address the problem of drug repurposing from the point of view of deep learning for graphs, developing an architecture that exploits both structural and biological information to propose a reduced list of drugs that may be effective against an unknown disease. Our approach has shown excellent performances, and we assessed its practical use on COVID-19.

**11- Computational Methods for Improving Manufacturing Processes** ([presentation](https://github.com/danilonumeroso/pesaresi-seminar-series/slides/alderighi-computationalfab.pdf))

*Thomas Alderighi, 26/03/2021, 15:00-16:00*

The recent developments and economic growth related to digital fabrication techniques and machinery created a strong need for robust computational tools and methods that allow users to fully harness the capabilities and potential offered by these technologies.

This demand led to the birth of a novel research domain called Computational Fabrication, where knowledge and results from different research fields like Numerical Optimization, Geometry Processing and Simulation, are applied to improve the scope of digital fabrication.

In this talk we will present some recent contributions in this field related to the automatic generation of soft silicone molds for objects of complex free-form geometry. Molding is an ancient and well known fabrication technique, where a hollowed block, whose cavity has the shape of the desired object, is filled using some liquid material like plastic or metals. Despite its ancient origins, generating effective molds for non trivial shapes remains a hard task, often requiring a high level of expertise and manual work and design.

We will present how digital fabrication machinery and a geometry processing based approach can help us to improve the scope of molding as a fabrication technique and to strongly reduce the expertise required to the user.

**12- A mechanistic approach to modelling spatial, temporal and social aspects of human mobility**

*Giuliano Cornacchia, 09/04/2021, 15:00-16:00*

Modelling human mobility is crucial in several areas, from urban planning to epidemic modeling, traffic forecasting, and what-if analysis.
Existing generative models focus mainly on reproducing the spatial and temporal dimensions of human mobility, while the social aspect, though it influences human movements significantly, is often neglected.
Those models that capture some social perspectives of human mobility utilize trivial and unrealistic spatial and temporal mechanisms.
In this paper, we propose STS-EPR, a modeling framework that embeds mechanisms to capture the spatial, temporal, and social aspects together.
We compare the trajectories produced by STS-EPR whit respect to real trajectories and synthetic trajectories generated by two state-of-the-art generative models on a set of standard mobility measures.
Our experiments conducted on an open dataset show that STS-EPR, overall, outperforms existing spatial-temporal or social models demonstrate the importance of modeling properly sociality to capture precisely all the other dimensions of human mobility.
We further investigate the impact of tile shape and granularity of the spatial tessellation on the performance of our model.
STS-EPR, which is open-source and tested on open data, represents a step towards the design of a mechanistic model that can capture all the aspects of human mobility comprehensively.

**13- Compressing and indexing using a learned approach**([presentation](null))

*Antonio Boffa, 16/04/2021, 15:00-16:00*

The growth rate of the data has already surpassed Moore’s law in areas like bioinformatics and astrology. Succinct data structures are fundamentals to store the data in almost optimal space, and still to efficiently solve queries. Very recently, the unexpected combination of succinct data structures and machine learning has led to the development of learned data structures.

In this seminar, we address the problem of designing, implementing and experimenting with succinct data structures over a dictionary of integers. We shine a new light on this classical problem by showing a surprising connection between the input integers and the geometry of a set of points in a Cartesian plane suitably derived from them. We then build upon some results in computational geometry to introduce the first compressed rank/select dictionary based on the idea of "learning" the distribution of such points via proper linear approximations. We prove time and space complexities in several scenarios: in the worst case and the case of input distributions with finite mean and variance.

We corroborate our theoretical results with a large set of experiments over datasets originating from a variety of applications (Web search, DNA sequencing, information retrieval and natural language processing). Our approach provides new interesting space-time trade-offs with respect to several well-established implementations.

**14- Compositional Linear Programming**([presentation](https://danilonumeroso.github.io/pesaresi-seminar-series/slides/Comp-linear-programming.pdf))

*Alessandro Di Giorgio, 16/04/2021, 15:00-16:00*

A complex structure or system is said to be compositionalwhenever its behaviour is entirelydetermined by the behaviour of its simpler parts andthe way they are composed. Thisproperty is clearly essential when the system underanalysis is big enough to make theanalysis itself impracticable. Moreover, from thepoint of view of optimization, the ability toforget unneeded parts of the system is crucial.The theory IH of interacting Hopf Algebras is a compositionalcharacterization of linearrelations (subspaces) over an arbitrary field. Thetheory has an intuitive representation as alanguage of string diagrams, hiding the categoricalfoundation behind it.We present AIH+, an extension of IH which turns outto be sound and complete for wellknown geometrical objects, namely polyhedra. Thisclass of objects is ubiquitous in linearprogramming, where it is employed to represent (setsof constraints of) linear programs.Within  AIH+we aim to give an axiomatic and diagrammaticperspective on well-knownresults from the theory of linear programming suchas the Farkas Lemma. We also present adenotational way of characterizing equivalent flownetworks and, more generally, linearprograms.

**15- Community Detection in Large Graphs**([link](https://teams.microsoft.com/l/meetup-join/19%3aa288a69763dd4ec6a0bbb344bfb6f107%40thread.tacv2/1617122930578?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d))

*Davide Rucci, 07/05/2021, 15:00-16:00*

The concept of network is fundamental in computer science and its popularity has been ever increasing thanks to its many different application fields.
Since real-world networks do not appear to be random, i.e. they cannot be modeled with an Erdos-Renyi graph, one is interested in finding the substructures that compose them. We focus here on communities: groups of nodes sharing many links "inside" and significantly less links with the rest of the graph. An immediate formalization of this idea is that of cliques.
Enumerating all cliques in a graph is a well-known NP-hard problem and has seen extensive study.
The first recursive algorithm was proposed by Bron and Kerbosch and it was recently improved by Tomita et al. and Eppstein et al. The latter version is fixed-parameter tractable, but not
all of its properties, such as if it is output sensitive are known yet.
We then move to graphlets, discussing a novel technique called push-out amortization that is rising nowadays in the enumeration field, and that will lead to the improvement of current state-of-the-art algorithms.

**16- Structuring Neural Representations with the Entity-Relation Meta-Prior**([link](https://teams.microsoft.com/l/meetup-join/19%3a9b56de2ce723496b96a6a21e223b7d0c%40thread.tacv2/1617124068873?context=%7b%22Tid%22%3a%22c7456b31-a220-47f5-be52-473828670aa1%22%2c%22Oid%22%3a%22f2fd2449-3fe1-4a22-92e3-32757a6b4104%22%7d))

*Andrea Valenti, 14/05/2021, 15:00-16:00*

I will present the main ideas behind my research, showing how meta-priors could be used to improve the neural representations learned by machine learning models.

**17- Michele Resta 21/05/2021**

**18- Domenico Tortorella 28/05/2021**

**19- Andrea Pedrotti 04/06/2021**

**20- Valerio De Caro 11/06/2021**

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
